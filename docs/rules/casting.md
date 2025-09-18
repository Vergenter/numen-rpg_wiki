# Casting (Material-Magic Operation)

- [ ] Set safe per-turn body draw (erg/turn)
- [ ] Define nośnik (carrier) break probability curve

??? info "Layers"
    **📜 Lore** — early eras mistook "will" for control; in fact, materials govern magic.  
    **🧪 Reconstruction** — operations require configured minerals; thought alone does nothing.  
    **⚙️ Mechanics** — costs, tests, failures.

## ⚙️ Mechanics

### Methods
- **Direct (body):** `SelfDamage = max(0, ModulationCost_erg − BodyResilience_erg)`.
- **Carrier (mineral):** `Excess = max(0, ModulationCost_erg − CarrierCapacity_erg)`  
  `P(break) = clamp(p0 + k·Excess, 0, 0.95)` with defaults `p0=0.1, k=0.05`.

### Fuel
- Vis never creates energy; bring **fuel** (oil/heat/electricity) or couple to **Tain** sources.

### Tests
- Operation check: `Test(Engineering + Kunszt + situational)`; complications on failure draw from the **Tain Noise** table.

**Tags:** `#rules` `#casting`
