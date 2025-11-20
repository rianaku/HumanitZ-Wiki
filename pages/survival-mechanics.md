# <span style="color:#E79543;">🍖 Survival Mechanics</span>
> How the game tries to kill you even when no zeek is in sight.

---

## <span style="color:#E79543;">🩸 Core Status Systems (Overview)</span>

<div style="background:#111; padding:16px; border:1px solid #333; border-radius:8px;">

Typical survival stats (names may differ in-game):

- **Health** – how close you are to death.
- **Stamina** – sprinting, melee, and other actions.
- **Hunger** – impacts regeneration and maximum stamina/performance.
- **Thirst** – impacts performance; can become lethal.
- **Temperature / Weather Exposure** – cold, rain, possibly heat.
- **Infection / Disease** – consequences of bites, injuries, or bad events.

Document exact values and thresholds as they become known.

</div>

---

## <span style="color:#E79543;">🥩 Hunger & Food</span>

<details>
<summary><strong style="color:#E79543;">How Hunger Typically Works</strong></summary>

- Hunger slowly increases over time.
- Being very hungry may:
  - Reduce stamina regen.
  - Reduce max stamina or movement speed.
  - Block health regeneration (if it exists).
- Food quality may influence:
  - How fast hunger recovers.
  - Risk of sickness (e.g. raw or spoiled food).

Add concrete, data-backed details here once tested.

</details>

---

## <span style="color:#E79543;">💧 Thirst & Fluids</span>

<details>
<summary><strong style="color:#E79543;">Managing Thirst</strong></summary>

- Thirst increases faster than hunger in many survival games.
- Severe dehydration can quickly become lethal.
- Water sources:
  - Found bottles and drinks
  - Potentially wells, taps, lakes (depending on mechanics)
- Risk: contaminated water → sickness/infection.

List exact items and their thirst values later.

</details>

---

## <span style="color:#E79543;">🌡️ Weather, Temperature & Exposure</span>

<div style="background:#0F0F0F; padding:16px; border:1px solid #333; border-radius:8px;">

Weather and time of day change how safe the world is:

- Cold or wet conditions can drain stamina, increase exposure risk.
- Night reduces visibility, making scouting and combat harder.
- Certain enemies or behaviours might change at night or in storms.

Track specific weather effects here as they’re confirmed.

</div>

---

## <span style="color:#E79543;">🧟 Infection & Injury</span>

<details>
<summary><strong style="color:#E79543;">Infection System (placeholder – fill as confirmed)</strong></summary>

Potential sources:

- Zeek bites or hits.
- Leaving wounds untreated.
- Using dirty water or bad food.

Potential outcomes:

- Gradual debuff escalation (movement, vision, stamina).
- Eventual death if untreated.
- Requirement for specific meds or crafted cures.

</details>

<details>
<summary><strong style="color:#E79543;">Injuries & Trauma</strong></summary>

- Cuts / bleeding → need bandages.
- Broken / sprained limbs → movement penalties.
- Pain → might affect aim or stamina.

Populate with specific statuses, icons, and treatment items as discovered.

</details>

---

## <span style="color:#E79543;">💀 Permadeath & Failure States</span>

<div style="background:#111; padding:16px; border:1px solid #333; border-radius:8px;">

**Permadeath enabled:**

- Death = full character loss (gear, progression, etc.).
- Designed for players wanting a high-stakes experience.

**Permadeath disabled:**

- Use this mode to learn systems and map layout.
- Still treat death as a learning opportunity: note what killed you.

</div>

---

## <span style="color:#E79543;">📈 Difficulty, Afflictions & Modifiers</span>

Use this section to record:

- Global difficulty settings (enemy health/damage, loot rarity, etc.).
- Optional afflictions / challenge modifiers:
  - Slower reloads
  - Lower carry weight
  - Reduced movement speed
  - Etc.

Explain recommended combinations for different playstyles later.

---

<p align="center" style="color:#555; font-size:13px;">
Next: <a href="Base-Building.md" style="color:#E79543;">🏠 Base Building</a> • or return <a href="README.md" style="color:#E79543;">🏠 Home</a>
</p>
