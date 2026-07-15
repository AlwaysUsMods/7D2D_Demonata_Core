# Demonata Core — Player Patch Notes

## Update v1.2.0 (Compatible with 7 Days to Die Patch 2.5 **ONLY**)

**Summary:** This update addresses compatibility issues with 7 Days to Die Patch 2.5 and introduces a major overhaul to the Jar Economy and Workstations (Apiary/Dew Collector). These changes establish a resource "attrition" loop and standardize workstation mechanics.

### 2.5 Compatibility Fixes

* **HUD Transparency:** Fixed transparency issues introduced in game patch 2.5.
* **Particle Effects:** Fixed black particle smoke appearing when the player coughs (patch 2.5 bug).

### Workstation Overhaul (Apiary & Dew Collector)

* **Forge-Style Mechanics:** The **Apiary** and **Dew Collector** now function like a **Forge**.
  * You must learn them via **Forge Ahead Magazines**.
    * They now use an **input system** (requiring **Empty Jars** as an ingredient) rather than passive generation.
    * **Crafting Time:** Items take **2 hours real-time** to craft honey and **8 hours real-time** to craft water. These times keep the base game values intact. Changing the in-game 24-hour cycle speed **does not** speed this up.
    * **Crafting Time:** Items take **2 hours real-time** to craft honey and **8 hours real-time** to craft water.
      These times keep the base game values intact. Changing the in-game 24-hour cycle speed **does not** speed this up.

* **Apiary Changes:**
  * **Honey:** Now craftable via the Apiary using Empty Jars. There are **3 recipes**, one for each flower type.
  * **Tool Updates:**
    * **Brood Box:** Now reduces ingredient costs (flowers) by **50%**.
    * **Extractor:** Now reduces crafting time by **50%**.
  * **Smoker:** The Apiary Smoker is no longer required or functional (Bee Swarms no longer spawn from the Apiary).
* **Dew Collector Changes:**
  * Functions identically to the new Apiary logic (requires jars, 8 hours real-time) Additionally, you get 2 waters for 2 jars per crafting cycle.
  * All existing Dew Collector tools function as they did before, adapted to the new system.

### The Jar Economy & Attrition

* **Crafting Removal:** **Empty Jars** have been removed from the crafting system.
  * **Intent:** This introduces an "attrition system." Jars are a finite resource supplied only through looting.
  * **Settings Recommendation:** It is highly recommended to set **Jar Refund** (Advanced Tab) to **100%**.
    * *For Roleplay/Sim:* Set to **80–90%** to simulate occasional breakage.
    * *For Struggle:* Set to **40–60%**.
* **Food & Jar Returns:**
  * **Gumbo Stew:** Now returns an Empty Jar when eaten.
  * **Chili Dogs:** No longer return an Empty Jar.

### Consumables & Drops

* **Bees Wax:** Increased drop chance from tree stumps (now equals Honey probability).
  * Reading **Wasteland Treasures Vol 1** increases this further (book description updated).
* **Dysentery Risks:**
  * **Honey Glazed Sham** and **Fort Bites** now carry **Dysentery** risk. This aligns them with other rotten-flesh based foods.
* **Honey Nerfs (Infection):**
  * Infection cure reduced from **5% → 2.5%** for **Honey Glazed Sham**, **Honey Brisket**, and **Honey Tea**. This aligns them with previous nerfs to raw Honey.
  * Infection cure reduced from **5% → 2.5%** for **Honey Glazed Sham**, **Honey Brisket**, and **Honey Tea**.
    This aligns them with previous nerfs to raw Honey.

### Skills & Perks

* **Fortitude Tree:** **Well Insulated** has been added back to the Fortitude skill tree.
  * *UI Note:* The Fortitude tree is now **2 pages** long. Remember to flip the page to see all skills.

### Known issues

* Localizations have not been updated to include any of these new changes. This is still a WIP and will come in a later update.

---

## Demonata Core — Player Patch Notes (v1.0.0)

v1.0.0 Changelog

**Summary:** Demonata Core restores the sandbox, puts real weight behind progression, and rewards skillful play. Expect headshot-centric combat, smarter spawns, tougher choices, and quality-of-life fixes that cut grind without gutting survival.

---

## Highlights

* **Headshots Only (ranged, knives, spears):** Precision matters; spray-and-pray is dead. Shotguns are exempt.
* **Difficulty-aware balance:** Headshot damage and zombie HP scale by difficulty to keep TTK fair.
* **Sandbox restored:** The world, spawns, economy, and crafting tie back into meaningful choices.
* **QoL without shortcuts:** Annoyances trimmed (reach, pickups, stacks) while risk stays real.

---

## World & Biomes

* **Infection “Survival Ladder” (Tree Stumps):**

  * **Pine Forest:** spawn rate **0.000575** (≈ **+50%** vs vanilla).
  * **Burnt Forest:** **0.0001917** (≈ **–4%** vs vanilla; Pine ≈ **3×** Burnt).
  * **Snow:** **0.0001095** (≈ **–45%** vs vanilla; Burnt ≈ **1.75×**, Pine ≈ **5.25×** Snow).
  * **Honey drop per stump remains 20%** (vanilla).
  * **Impact:** Snow sick? Sprint to Burnt for faster odds, or push to Pine for best odds—your risk, your reward.
* **Mines added to all biomes.** Terrain is dangerous again; watch your step.
* **Wasteland ambience:** Increased gore decorations for a harsher vibe.
* **Fog tuning:** Adjusted across biomes/weather to raise tension while keeping visibility playable.
* **Gore hazards:** Gore blocks now have a **50%** chance to cause **Infection** on contact.

---

## Combat, AI & Enemies

* **Headshots Only (ranged, knives, spears):**

  * **Headshot damage modifiers by difficulty:**

    * Scavenger: **–50%**
    * Adventurer: **±0%**
    * Nomad: **+100%**
    * Warrior: **+200%**
    * Survivalist: **+300%**
    * Insane: **+400%**
* **Difficulty-based zombie health (preserves vanilla ±15% variance):**

  * Scavenger: **–25%** | Adventurer: **±0%** | Nomad: **+10%** | Warrior: **+20%** | Survivalist: **+30%** | Insane: **+40%**
  * **Intent:** Higher difficulties hit harder but don’t turn enemies into pure bullet sponges.
* **Zombie reach overhaul:** Calibrated around spear-length melee.

  * **Longer reach** retained for **Cops, Mutated, Frostclaw, Plague Spitters** to keep them scary.
* **Zombies no longer climb ladders.** (Lore/realism pass.)
  Re-think base paths—no more easy ladder baiting.

---

## Spawns, Hordes & Blood Moon

* **Custom entity groups:** Spawns now respect **biomes** and **RWG tile tags**, reinforcing theme and pacing.
* **Wandering hordes:** Composition and counts adjusted to sharpen difficulty and variety.
* **Blood Moon:** Now **lasts all night**. The final wave **loops** until dawn.
  *Note:* This is step one toward a larger future BM rework.

---

## Loot, Items & Medicine

* **Z-Paks:** **Now last 45 minutes.** Slightly increased drop chance.
* **Chickens:** Harvesting can yield **eggs** (because… chickens).
* **Compass cleanup:** **Removed red zombie dots**—use your eyes and ears.
* **Lanterns & traps pickup:**

  * **Writable storage containers** and **lanterns** can be picked up **when not inside a Land Claim** by **destroy/harvest**.
    *No material refunds* (balance).
  * **Mines, wooden/iron spikes, and barbed wire** can be picked up.
* **Honey nerf:** Cure strength **–50%** to offset increased stump access.

---

## Weapons & Gunplay

* **Crosshairs removed** from ranged weapons (**shotgun exempt**) and from **laser/scopes**.
* **Bullet spread reduced** to support headshot-only precision (**does not affect shotguns**).

---

## Crafting, Repairs & Economy

* **Repairs require parts:**

  * **Armor** repairs use **Armor Parts**.
  * **Tools & weapons** use their **respective parts**.
* **Nails economy:** Increased **nail** drop rates; many **wood items** now require nails.

  * **Frame Shapes (helper variant)** now require **nails** (nerf to easy nerd-poling).
* **Recipes tuned for scarcity & play:**

  * **Rotten meat** recipes cost **10** (it’s everywhere).
  * **Raw meat** recipes cost **8** (encourages hunting).
  * **Planted crops** (e.g., Corn) cost **4** per recipe (promotes real farming).
  * **Dynamite:** **2 per craft** (pack smarter).
* **Stack sizes:**

  * **Resources:** up to **12,000**
  * **Food/Drugs/Drinks:** **20** (Rotting Meat reduced **125 → 20**)
  * **Medical supplies:** **15**

---

## Food & Disease

* **Canned foods:**

  * **Tuna & Beef:** **30 food**
  * **Chicken:** **35 food**
  * **All others:** **20 food**
* **Dysentery realism:** Because of rotting meat,

  * **Hobo Stew**, **Sham Chowder**, **Canned Sham** have **12%** Dysentery chance.

---

## Progression & XP

* **XP sources trimmed:** Only **quests** and **zombie/animal kills** grant XP by default.
  *Intent:* Crafting/survival matter; kills and missions carry progression.
* **Curve rebalanced:**

  * Base **XP/level = 9,000** (vanilla: 3,000–10,000 by version)
  * **+4%** XP per level (vanilla **+5%**)
  * Clamp at **Level 50** (vanilla 60) with **\~61,500** per-level post-clamp (vanilla \~177,897)
  * **Attributes:** cost multiplier **+16%/level** (was 14%)
  * **Feel:** Faster midgame; roughly **\~47%** faster to midgame vs vanilla. Total XP to 300 **\~60–65% lower** (playstyle dependent).
* **Optional Module:** An **XP Tuning** add-on lives in the mod root so creators can adjust pacing for videos/streams.

---

## Traders & Economy Loop

* **Shops open 12 hours** with **staggered schedules** to nudge exploration:

  * **Joel:** 06:00–18:00
  * **Jen:** 09:00–21:00
  * **Bob:** 00:00–12:00
  * **Hugh:** 03:00–15:00
  * **Rekt:** 06:00–18:00

---

## UI, UX & Atmosphere

* **Lighting pass:** Interior/exterior lighting adjusted for mood and readability.
* **Fog pass:** (See World & Biomes) More tension without cheap blindness.
* **HUD tweaks:** **Food/Water** bars moved to **left**; **toolbelt** lowered slightly for clarity.

---

## Persistence & Death

* **Injuries and debuffs persist through death.** Death isn’t a full reset—plan accordingly.

---

## Notes for Players

* **Pickups by destroy/harvest** never refund mats—this is intentional.
* **Shotguns** ignore headshot-only rules (pellet identity).
* **New saves recommended** for best results due to broad spawn/progression changes.

---

If something doesn’t play like it reads here, tell me. I’ll investigate and tune. Now go make the apocalypse behave.

---

## Recommended Mods (Optional, but spicy)

> These pair well with Demonata Core’s “player agency + balanced realism” approach. None are required. If a mod uses Harmony/DLLs, check its page for EAC/server requirements.

## Biome Hazard Comfort (useful when **Biome Progression** is ON)

* **Screen Effects Be Gone** — Hides the harsh biome hazard screen overlays. Keeps visibility and readability high while you deal with the actual mechanics.
* **Sound Effects Be Gone** — Mutes the auto-played “pain/cold/heat” vocal stingers from biome hazard buffs. Less noise, same danger.

## World, POIs & Exploration

* **CompoPack Classic — All-in-One** — Big POI expansion across all biomes. Synergizes with Demonata’s exploration-first pacing.
* **Big Cities, Big Maps** *(Compo optional add-on)* — Restores **large city** generation to **Pine Forest**. Great for early-mid game route planning.
* **GNS — Beautiful Bases** — Lets you recover decorative items (posters, etc.) from POIs. More personality for player bases.
* **Stallionsden’s Lootable Objects** — Makes more world props lootable. Pairs with our scarcity/stack changes to reward thorough scavenging.

## Inventory, Crafting & Storage QoL

* **Asylum Smart Storage** — Auto-sorts into your containers. Cuts management time without handing you free power.
* **Craft From Containers Plus** — Crafting stations pull from nearby storage. Streamlines the loop while keeping material costs intact.

## Lighting & Visibility

* **OCB Light Enabler (POI)** — Lets you switch on POI lights. Demonata Core darkens interiors a bit; this helps non-torch enjoyers keep things visible.

## AI, Combat & Quests

* **Path Smoothing** — Cleans up zombie pathing so challenges come from encounters, not nav jank. Works well with our reach and headshot rules.
* **KhaineGB — Zombie Fall Damage** — Zombies actually take fall damage. Complements base designs without trivializing combat.
* **MultiQuest** — Hold multiple trader quests at once. Extra handy now that trader hours are staggered.

> If two mods touch the same XML areas, load the one you want to “win” **after** the other (prefix with `zzz_` if needed). When in doubt, start clean and add one at a time.

---

## Notes & Caveats

* **New World Recommended** for big POI packs and city-gen changes.
* **Overhauls:** Don’t stack other total overhauls that change core spawns/progression/gunplay—pick one philosophy (hint: ours 😇).
* **EAC/Servers:** Some of these may use Harmony; check each page and match client/server installs.
* **Performance:** Large POI packs and light toggling can increase CPU/GPU load in cities.

Short version: these mods keep Demonata Core’s intent intact—more agency, less busywork, smarter world—without sandblasting the balance. Use what fits your playstyle (or your video pacing) and leave the rest.
