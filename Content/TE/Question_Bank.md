# 🛣️ Transportation Engineering Lab — Viva Question Bank

> **How to Use:** Each experiment follows the pattern — Principle → Procedure-based Q&A → Conceptual → Tricky Examiner Questions → Typical Values → Code Reference. Study the *tricky questions* section carefully — these are most commonly asked in external viva.

## Table of Contents

| # | Experiment | Key Code |
|---|-----------|----------|
| 1 | California Bearing Ratio (CBR) Test | IS 2720 (Part 16), IRC:37-2018 |
| 2 | Aggregate Crushing Value (ACV) | IS 2386 (Part IV) |
| 3 | Aggregate Impact Value (AIV) | IS 2386 (Part IV) |
| 4 | Los Angeles Abrasion Test | IS 2386 (Part IV) |
| 5 | Flakiness & Elongation Index | IS 2386 (Part I) |
| 6 | Penetration Test (Bitumen) | IS 1203, IS 73:2013 |
| 7 | Ductility Test (Bitumen) | IS 1208, IS 73:2013 |
| 8 | Softening Point Test (Bitumen) | IS 1205, IS 73:2013 |
| 9 | Flash and Fire Point Test | IS 1209, IS 73:2013 |
| 10 | Bitumen Extraction Test | IS 2172 |
| 11 | Benkelman Beam Deflection Test | IRC:81, IRC:37-2018 |
| 12 | High-Level Examiner Questions | — |
| 13 | Quick Revision Tables | — |

---

## 1. California Bearing Ratio (CBR) Test

**Principle:** The resistance of a soil sample to penetration by a standard plunger, compared to the resistance of a standard crushed stone material, expressed as a percentage.

**Code Reference:**
- `IS 2720 (Part 16) : 1987` — Laboratory Determination of CBR *(Reaffirmed 2021)*
- `IRC:37-2018` — Guidelines for Design of Flexible Pavements (4th Revision)

---

### 📋 Basic / Procedure-Based Questions

**Q1. Define CBR. Write the formula.**
> CBR (%) = (Test Load / Standard Load) × 100
> Standard loads: 13.44 kN at 2.5 mm and 20.16 kN at 5.0 mm penetration.

**Q2. What are the standard penetration depths in CBR test?**
> 2.5 mm and 5.0 mm. The higher of the two CBR values is adopted for design.

**Q3. Why is the surcharge weight placed on the sample during CBR test?**
> To simulate the overburden pressure of pavement layers above the subgrade.

**Q4. What is the rate of penetration applied during the test?**
> 1.25 mm/min (standard rate as per IS 2720 Part 16).

**Q5. What is soaking period in CBR test and why is it done?**
> 4 days (96 hours). To simulate worst-case field moisture conditions (post-monsoon subgrade).

**Q6. How is CBR value selected if 5 mm value exceeds 2.5 mm value?**
> The test is repeated. If the 5 mm value still governs, it is used for design.

---

### 🧠 Conceptual Questions

**Q7. Why is CBR test still widely used in India despite being empirical?**
> It is simple, economical, and well-correlated with field pavement performance. IRC:37-2018 still uses design CBR as a primary input parameter.

**Q8. Can two soils with the same CBR value behave differently in the field?**
> Yes. Differences in drainage condition, plasticity index, moisture sensitivity, and swell potential cause different field performance even at equal CBR.

**Q9. What is the difference between soaked and unsoaked CBR?**
> Soaked CBR represents wet subgrade (critical condition); unsoaked CBR is used only for arid/semi-arid regions where saturation is unlikely.

**Q10. How does CBR relate to pavement thickness design in IRC:37-2018?**
> IRC:37-2018 uses the mechanistic-empirical (M-E) approach. CBR is used to compute the resilient modulus (Mr) of the subgrade: `Mr (MPa) = 10 × CBR` (for CBR ≤ 5%) or as per regression equations.

---

### ❗ Tricky Examiner Questions

**Q11. Why is CBR a ratio and not an absolute strength value?**
> Because it benchmarks soil performance against a reference standard material. Absolute load values vary with sample size and test conditions, but the ratio remains comparable.

**Q12. If a soil gives CBR = 8% at 2.5 mm and CBR = 10% at 5.0 mm, which value is used and why?**
> The 5 mm value (10%) is used — but only after repeating the test to confirm. If 5 mm consistently governs, it indicates the load-deformation curve is unusual (no peak at 2.5 mm), which itself is a red flag for the soil type.

**Q13. Why does soaking reduce CBR?**
> Moisture weakens inter-particle bonds in cohesive soils, reduces effective stress, and causes swelling — all of which reduce the soil's resistance to penetration.

---

### 📊 Typical CBR Values

| Subgrade Category | CBR Range | Pavement Suitability |
|---|---|---|
| Very Poor | < 2% | Not suitable without stabilization |
| Poor | 2% – 5% | Requires thick pavement |
| Fair | 5% – 10% | Moderate pavement |
| Good | 10% – 20% | Thinner pavement possible |
| Very Good | > 20% | Granular subbase may be reduced |

---

## 2. Aggregate Crushing Value (ACV) Test

**Principle:** The ACV measures the resistance of aggregates to gradual compressive loading. A lower ACV indicates stronger aggregates.

**Code Reference:**
- `IS 2386 (Part IV) : 1963` — Mechanical Properties of Aggregates *(Reaffirmed 2020)*
- `MoRTH Specifications for Road and Bridge Works (5th Revision)`

---

### 📋 Basic / Procedure-Based Questions

**Q1. What does ACV indicate?**
> Resistance of aggregate to slow, progressive compressive loading. Expressed as percentage of fines (< 2.36 mm) generated after crushing.

**Q2. What size of aggregate is used in ACV test?**
> Aggregates passing 12.5 mm sieve and retained on 10 mm sieve.

**Q3. What load is applied and at what rate in ACV test?**
> 400 kN applied gradually over 10 minutes.

**Q4. How is ACV calculated?**
> ACV (%) = (Weight of fines passing 2.36 mm sieve / Total weight of sample) × 100

---

### 🧠 Conceptual Questions

**Q5. Why must ACV be low for aggregates used in wearing course?**
> Wearing course bears direct wheel load. High ACV means aggregates crush easily → ravelling, deformation, and early pavement failure.

**Q6. What is the difference between ACV and 10% Fines Value (TFV)?**
> ACV applies a fixed load (400 kN) and measures fines generated. TFV measures the load required to produce exactly 10% fines — a more precise measure of aggregate strength.

**Q7. Why are angular aggregates preferred over rounded ones in base courses?**
> Angular aggregates have better interlocking, higher shear strength, and lower ACV due to point-to-point stress distribution rather than surface sliding.

---

### ❗ Tricky Examiner Questions

**Q8. If ACV is high, does it mean aggregate is weak or strong?**
> Weak. High ACV = more fines generated = aggregate crushes easily.

**Q9. Can aggregate pass ACV but fail in the field under repeated loading?**
> Yes. ACV is a single-application static test. Repeated dynamic traffic loads cause progressive degradation (fatigue), which ACV does not capture. That is why AIV is complementarily tested.

---

### 📊 Typical ACV Limits (MoRTH / IS)

| Application | Maximum ACV |
|---|---|
| Wearing / Surface Course | ≤ 30% |
| Base Course (WBM/WMM) | ≤ 40% |
| Sub-base Course | ≤ 50% |

---

## 3. Aggregate Impact Value (AIV) Test

**Principle:** AIV measures the toughness (resistance to sudden impact / shock loading) of aggregates, simulating the effect of dynamic traffic loads, especially in wearing and base courses.

**Code Reference:**
- `IS 2386 (Part IV) : 1963` *(Reaffirmed 2020)*
- `MoRTH Specifications (5th Revision)`

---

### 📋 Basic / Procedure-Based Questions

**Q1. What is the height of drop of hammer in AIV test?**
> 380 mm (±5 mm). The hammer weighs 13.5–14 kg and is dropped 15 times.

**Q2. What sieve size is used to separate fines after impact?**
> 2.36 mm sieve (same as ACV).

**Q3. How is AIV calculated?**
> AIV (%) = (Weight of fines / Total weight of sample) × 100

---

### 🧠 Conceptual Questions

**Q4. Why is impact test conducted separately when crushing test already exists?**
> Traffic loads are dynamic, not static. Sudden braking, potholes, and vehicle impacts create shock loading. ACV uses slow progressive load; AIV simulates sudden impact — both are needed.

**Q5. Which test is more critical for surface course — ACV or AIV?**
> AIV, because surface course is subjected to sudden dynamic loads from vehicle tyres, especially at intersections, speed breakers, and heavy vehicle passages.

**Q6. Is there a numerical relationship between AIV and ACV?**
> Approximately: `AIV ≈ ACV − 2 to 5%`. Both are generally in the same range for a given aggregate, but AIV is usually slightly higher (more fines under dynamic load).

---

### ❗ Tricky Examiner Questions

**Q7. An aggregate has ACV = 28% but AIV = 38%. Is this possible? What does it indicate?**
> Yes, it is possible. It indicates the aggregate is brittle — it withstands slow compression but fractures easily under sudden impact. Such aggregate should not be used in wearing course despite passing ACV.

---

### 📊 Typical AIV Limits

| Application | Maximum AIV |
|---|---|
| Wearing Course | ≤ 30% |
| Bituminous Macadam / Base | ≤ 35% |
| Water Bound Macadam (WBM) | ≤ 40% |

---

## 4. Los Angeles Abrasion Test

**Principle:** Measures resistance of aggregates to abrasion, impact, and grinding — simulating wear caused by traffic friction on the pavement surface. Uses steel balls as abrasive charge inside a rotating drum.

**Code Reference:**
- `IS 2386 (Part IV) : 1963` *(Reaffirmed 2020)*
- `ASTM C131 / C535` (for reference comparison)
- `MoRTH Specifications (5th Revision)`

---

### 📋 Basic / Procedure-Based Questions

**Q1. What is the principle of LA Abrasion test?**
> Aggregates and steel balls are rotated in a drum (500 revolutions for Grading A/B; 1000 for C/D). Impact and abrasion action of balls degrades the aggregate. Percentage fines generated = LA value.

**Q2. What sieve is used to separate fines after LA test?**
> 1.70 mm IS sieve.

**Q3. What are the grading categories in LA test?**
> Gradings A, B, C, D — selected based on aggregate particle size range.

**Q4. How is LA value calculated?**
> LA (%) = [(Original weight − Retained weight on 1.70 mm) / Original weight] × 100

---

### 🧠 Conceptual Questions

**Q5. How is LA Abrasion test different from AIV?**
> LA combines both abrasion and impact simultaneously over many cycles, simulating cumulative wear. AIV is a single sudden impact. LA is better for assessing long-term wear resistance.

**Q6. Why is low LA value critical for surface course aggregates?**
> Surface course is directly exposed to tyre friction. High abrasion loss → surface smoothening → reduced skid resistance → accident risk.

---

### ❗ Tricky Examiner Questions

**Q7. A road has good ACV and AIV but high LA value — will it perform well?**
> No. High LA value means aggregates will abrade quickly under tyre friction. The road may show good initial strength but will develop surface wear, loss of texture, and skid hazard under traffic.

---

### 📊 Typical LA Abrasion Value Limits

| Application | Maximum LA Value |
|---|---|
| Wearing / Bituminous Surface Course | ≤ 30% |
| Bituminous Macadam (Base) | ≤ 35–40% |
| Water Bound Macadam | ≤ 40–50% |

---

## 5. Flakiness Index (FI) and Elongation Index (EI) Test

**Principle:** Shape of aggregates significantly influences packing, voids, and strength of pavement layers. This test quantifies the proportion of flaky (thin) and elongated (long) particles using a thickness gauge and a length gauge respectively.

**Code Reference:**
- `IS 2386 (Part I) : 1963` — Particle Size and Shape *(Reaffirmed 2021)*
- `MoRTH Specifications (5th Revision)`

---

### 📋 Basic / Procedure-Based Questions

**Q1. Define Flakiness Index.**
> Percentage by weight of aggregate particles whose least dimension (thickness) < 0.6 × mean sieve size. Determined using a metal thickness gauge.

**Q2. Define Elongation Index.**
> Percentage by weight of aggregate particles whose greatest dimension (length) > 1.8 × mean sieve size. Determined using a metal length gauge.

**Q3. What is the combined Flakiness and Elongation Index limit as per MoRTH?**
> Maximum FI + EI combined ≤ 35% for bituminous courses.

**Q4. Which sieve sizes are typically used for FI testing?**
> Aggregates are sieved on paired sieves: 63/50, 50/40, 40/25, 25/20, 20/16, 16/12.5, 12.5/10, 10/6.3 mm.

---

### 🧠 Conceptual Questions

**Q5. Why are flaky aggregates undesirable in pavement construction?**
> - Flaky particles orient flat under compaction, creating planes of weakness
> - Increase void content → reduce density
> - Break easily under load → generate fines → loss of interlock

**Q6. Why do elongated aggregates cause problems?**
> They project beyond the surface texture, are prone to breakage under wheel load, and create uneven surface with reduced skid resistance.

**Q7. Can crushed aggregates have high FI even if they are strong?**
> Yes. Quarry stone shape depends on blasting and crushing process. A strong but platy rock (like slate or phyllite) will produce flaky aggregates regardless of strength.

---

### ❗ Tricky Examiner Questions

**Q8. If FI = 20% and EI = 18%, is the aggregate acceptable for bituminous surface course?**
> Combined FI + EI = 38% > 35% (MoRTH limit). **Not acceptable.** The contractor must improve the crushing process to produce more cubical aggregates.

---

### 📊 Typical FI & EI Limits

| Parameter | Limit (MoRTH) |
|---|---|
| Flakiness Index | ≤ 25% |
| Elongation Index | ≤ 25% |
| Combined FI + EI | ≤ 35% |

---

## 6. Penetration Test (Bitumen)

**Principle:** Measures the consistency/hardness of bitumen by quantifying the depth (in 0.1 mm units) to which a standard needle penetrates a sample of bitumen under a standard load (100 g), at 25°C, for 5 seconds.

**Code Reference:**
- `IS 1203 : 1978` — Determination of Penetration *(Reaffirmed 2022)*
- `IS 73 : 2013` — Specification for Paving Bitumen *(This replaces the old IS 73:1992)*

---

### 📋 Basic / Procedure-Based Questions

**Q1. What does a higher penetration value indicate?**
> Softer bitumen. Higher penetration = less viscous at 25°C = suitable for colder climates.

**Q2. What are the standard test conditions for penetration test?**
> Load = 100 g | Temperature = 25°C | Time = 5 seconds | Needle = standard tapered steel

**Q3. What is the unit of penetration value?**
> 0.1 mm (i.e., penetration value of 60 means needle penetrated 6.0 mm).

**Q4. How many readings are taken and how is the final value reported?**
> Minimum 3 readings at different points (≥ 10 mm apart). Average of 3 readings within acceptable tolerance is reported.

---

### 🧠 Conceptual Questions

**Q5. Why is VG-30 preferred over 60/70 bitumen in the current Indian scenario?**
> IS 73:2013 replaced old penetration-grade specifications with Viscosity Grade (VG) bitumen. VG-30 is performance-specified by viscosity (not penetration), making it more suitable for high-temperature, heavy-traffic Indian conditions.

**Q6. What happens if overly soft bitumen is used in a hot region like Punjab?**
> Bitumen loses stiffness → bleeding → rutting → loss of surface texture → hazardous for vehicles.

**Q7. What happens if too hard (low penetration) bitumen is used in a cold region?**
> Bitumen becomes brittle at low temperature → thermal cracking → pavement fails under frost action.

---

### ❗ Tricky Examiner Questions

**Q8. The penetration value of a bitumen sample is 35. To which VG grade does this approximately correspond?**
> VG-40 (harder grade). VG grades in IS 73:2013: VG-10, VG-20, VG-30, VG-40. VG-40 has lowest penetration (hardest). Old 30/40 penetration grade ≈ VG-40; 60/70 ≈ VG-30.

**Q9. If penetration is measured at 30°C instead of 25°C, will the value increase or decrease?**
> Increase. Higher temperature = softer bitumen = deeper needle penetration. Always maintain 25°C as per standard; variation affects result significantly.

---

### 📊 Typical Bitumen Grades and Penetration Values

| IS 73:2013 VG Grade | Approx. Penetration Range | Application |
|---|---|---|
| VG-10 | > 80 | Cold regions, spray applications |
| VG-20 | 60–80 | Moderate traffic, cold/hilly areas |
| VG-30 | 50–70 | Standard paving grade — most of India |
| VG-40 | 30–50 | Hot climate, heavy traffic, intersections |

---

## 7. Ductility Test (Bitumen)

**Principle:** Measures the ability of bitumen to stretch (deform plastically) without rupture, simulating its capacity to accommodate minor deformations in the pavement without cracking.

**Code Reference:**
- `IS 1208 : 1978` — Determination of Ductility *(Reaffirmed 2022)*
- `IS 73 : 2013` — Paving Bitumen Specification

---

### 📋 Basic / Procedure-Based Questions

**Q1. What are the standard test conditions for ductility test?**
> Temperature = 27°C | Rate of pull = 50 mm/min | Water bath ensures uniform temperature.

**Q2. How is ductility value reported?**
> Distance in cm at which the bitumen thread breaks (minimum of 3 readings).

**Q3. What is the minimum ductility value specified for paving bitumen?**
> 75 cm minimum (as per IS 73:2013 for VG-30 and VG-40).

---

### 🧠 Conceptual Questions

**Q4. What does low ductility indicate about bitumen behaviour?**
> Low ductility = brittle bitumen → unable to accommodate thermal movement → susceptible to longitudinal and transverse cracking, especially in winter.

**Q5. Why is ductility test conducted at 27°C in India (not 25°C as in some international standards)?**
> Reflects Indian field conditions more accurately; 27°C is closer to mean annual temperature in most Indian states.

---

### ❗ Tricky Examiner Questions

**Q6. A bitumen sample has high penetration but low ductility. Is it suitable for paving?**
> No. High penetration (soft) + low ductility (brittle) is a contradictory combination indicating degraded or adulterated bitumen. Both properties must meet minimum specifications simultaneously.

---

### 📊 Ductility Requirements (IS 73:2013)

| VG Grade | Minimum Ductility |
|---|---|
| VG-10 | 75 cm |
| VG-20 | 75 cm |
| VG-30 | 75 cm |
| VG-40 | 40 cm |

---

## 8. Softening Point Test (Ring and Ball Method)

**Principle:** The temperature at which bitumen softens and flows under a standard steel ball load, indicating the upper service temperature limit of bitumen — critical for hot-climate performance.

**Code Reference:**
- `IS 1205 : 1978` — Determination of Softening Point *(Reaffirmed 2022)*
- `IS 73 : 2013`

---

### 📋 Basic / Procedure-Based Questions

**Q1. What is the standard apparatus and procedure?**
> Two brass rings filled with bitumen, two 3.5 g steel balls, heated in water/glycerine bath at 5°C/min. Softening point = temperature when balls drop 25.4 mm.

**Q2. Why is the rate of heating kept constant at 5°C/min?**
> Uniform heating ensures reproducible results; faster heating would raise the apparent softening point.

**Q3. When is glycerine used instead of water as the heating medium?**
> When expected softening point > 80°C (glycerine has higher boiling point than water).

---

### 🧠 Conceptual Questions

**Q4. Why is softening point critical for bitumen used in Punjab/Rajasthan?**
> Pavement surface temperatures can exceed 60–70°C in summer. Bitumen with low softening point will flow, causing rutting and bleeding.

**Q5. What is the relationship between softening point and penetration grade?**
> Inverse relationship: harder bitumen (low penetration = VG-40) has higher softening point; softer bitumen (high penetration = VG-10) has lower softening point.

---

### ❗ Tricky Examiner Questions

**Q6. Can two bitumens have the same softening point but different penetration values?**
> Yes. Softening point and penetration measure different aspects of consistency at different temperatures. A bitumen modified with polymers may have elevated softening point without proportional change in penetration.

---

### 📊 Typical Softening Point Values (IS 73:2013)

| VG Grade | Min. Softening Point |
|---|---|
| VG-10 | 40°C |
| VG-20 | 45°C |
| VG-30 | 47°C |
| VG-40 | 50°C |

---

## 9. Flash Point and Fire Point Test

**Principle:** Flash point is the lowest temperature at which vapours above heated bitumen momentarily ignite (flash) with an external flame. Fire point is the temperature at which sustained burning occurs for at least 5 seconds — critical for safe laboratory handling and field mixing.

**Code Reference:**
- `IS 1209 : 1978` — Determination of Flash and Fire Point *(Reaffirmed 2022)*
- `IS 73 : 2013`

---

### 📋 Basic / Procedure-Based Questions

**Q1. What apparatus is used for flash and fire point test of bitumen?**
> Cleveland Open Cup (COC) apparatus — standard for bitumen.

**Q2. At what rate is the temperature raised during the test?**
> 5–6°C/min up to 56°C below expected flash point; then at 2°C/min near the flash point.

**Q3. What is the difference between flash point and fire point?**
> - **Flash point:** Temperature at which vapour momentarily ignites (brief flash) — does NOT sustain burning
> - **Fire point:** Temperature at which vapour ignites AND burns continuously for ≥ 5 seconds (usually 5–15°C higher than flash point)

---

### 🧠 Conceptual Questions

**Q4. Why is flash point important in pavement construction?**
> Bitumen is heated during mixing (140–160°C). If flash point is too low → fire hazard at hot mix plant or during paver laying. Minimum flash point ensures safe heating margin.

**Q5. How does water contamination affect flash point?**
> Water in bitumen causes sudden boiling and frothing when heated, artificially lowering the apparent flash point and creating explosion/spatter hazard.

---

### ❗ Tricky Examiner Questions

**Q6. Mixing temperature of bitumen is ~150°C. Flash point is 220°C. Is there a safety concern?**
> Technically safe, but a 70°C margin exists. In practice, overheating due to faulty plant equipment or operator error can narrow this margin. Always maintain bitumen well below flash point during operations.

---

### 📊 Flash and Fire Point Requirements

| Bitumen Grade | Min. Flash Point (COC) |
|---|---|
| VG-10 | 220°C |
| VG-20 | 220°C |
| VG-30 | 220°C |
| VG-40 | 220°C |

---

## 10. Bitumen Extraction Test (Binder Content Test)

**Principle:** Determines the bitumen (binder) content in a compacted or loose asphalt mix by dissolving the bitumen using a solvent (trichloroethylene or benzene) in a centrifuge extractor, separating it from aggregates.

**Code Reference:**
- `IS 2172 : 1983` — Determination of Binder Content *(Reaffirmed 2020)*
- `MoRTH Specifications (5th Revision)` — for permissible limits

---

### 📋 Basic / Procedure-Based Questions

**Q1. What solvent is used in extraction test and why?**
> Trichloroethylene (or benzene as alternative). These solvents dissolve bitumen without attacking aggregate minerals.

**Q2. What equipment is used for bitumen extraction?**
> Centrifuge extractor — spins the solvent-bitumen-aggregate mixture; centrifugal force separates solvent+bitumen from aggregate.

**Q3. How is binder content calculated?**
> Binder Content (%) = [(Weight of mix − Weight of extracted aggregate) / Weight of mix] × 100

**Q4. What additional test can be done on extracted aggregate?**
> Sieve analysis (grading) to check if aggregate gradation in the laid mix matches the design mix gradation.

---

### 🧠 Conceptual Questions

**Q5. What happens if binder content is more than specified?**
> - Bleeding (free bitumen rises to surface)
> - Reduced skid resistance (slippery road)
> - Rutting under heavy traffic (loss of stiffness)

**Q6. What happens if binder content is less than specified?**
> - Ravelling (aggregate particles dislodge from surface)
> - Premature cracking and disintegration
> - Reduced impermeability → water ingress → pothole formation

**Q7. Why is extraction test done during quality control of road construction?**
> To verify that the hot mix plant is delivering the correct binder content as per the approved Job Mix Formula (JMF). A deviation of even ±0.3% can significantly affect pavement life.

---

### ❗ Tricky Examiner Questions

**Q8. If the extraction test shows correct binder content but the road still shows bleeding — what could be the reason?**
> Possible causes: higher-than-designed voids (VMA issue), poor mix design, incorrect aggregate gradation (excess fines), or high ambient temperature combined with heavy slow-moving traffic (trucks).

---

### 📊 Typical Binder Content (as per MoRTH/JMF)

| Mix Type | Approximate Binder Content |
|---|---|
| Dense Bituminous Macadam (DBM) | 3.5% – 4.5% |
| Bituminous Concrete (BC) | 5.0% – 6.0% |
| Semi-Dense Bituminous Concrete (SDBC) | 4.5% – 5.5% |

---

## 11. Benkelman Beam Deflection (BBD) Test

**Principle:** Measures the vertical elastic deflection of a flexible pavement under a standard dual-wheel load (8170 kg per axle = 80 kN), using a lever-arm device (Benkelman Beam). Deflection indicates structural adequacy of the existing pavement and is used for overlay design.

**Code Reference:**
- `IRC:81 : 1997` — Guidelines for Strengthening of Flexible Road Pavements Using Benkelman Beam Deflection Technique
- `IRC:37 : 2018` — References BBD method for rehabilitation design

---

### 📋 Basic / Procedure-Based Questions

**Q1. What is the standard test truck configuration for BBD test?**
> Rear axle load = 8170 kg (80 kN); dual tyres inflated to 5.6 kg/cm² (80 psi); standard dual wheel spacing = 310 mm.

**Q2. What is the beam ratio (lever arm ratio) of Benkelman Beam?**
> 2:1 (rear arm : front arm). Dial gauge reading must be multiplied by 2 to get actual deflection.

**Q3. When is the rebound deflection measured vs. total deflection?**
> **Total deflection:** Truck moves from start to measure max. deflection.
> **Rebound deflection:** Used in IRC:81 — difference between initial and final dial gauge readings as truck moves forward.

**Q4. At what intervals are BBD readings taken along a road?**
> Every 50 m in each wheel track (or closer where distress is visible).

---

### 🧠 Conceptual Questions

**Q5. Why is deflection a good indicator of pavement structural condition?**
> Deflection represents the combined response of all pavement layers and subgrade to load. High deflection = inadequate stiffness in one or more layers = pavement fatigue likely.

**Q6. What factors affect pavement deflection?**
> - Subgrade strength (CBR / resilient modulus)
> - Pavement layer thickness and material quality
> - Moisture content (deflection increases post-monsoon)
> - Temperature (bituminous layer stiffness drops in summer → higher deflection)
> - Traffic loading

**Q7. How is BBD test data used in overlay design?**
> IRC:81 uses characteristic deflection (90th percentile of measured deflections) to determine the required bituminous overlay thickness to restore structural adequacy.

---

### ❗ Tricky Examiner Questions

**Q8. BBD test is done in summer. Will the deflection be higher or lower than in winter? Which is used for design?**
> Higher in summer (bitumen is softer → more flexible pavement response). Design should use critical (worst-case) deflection — typically measured in post-monsoon season when subgrade moisture is maximum and bitumen temperature is high.

**Q9. What is the advantage of FWD (Falling Weight Deflectometer) over Benkelman Beam?**
> FWD is faster, generates a deflection basin (multiple sensors), allows back-calculation of layer moduli, and is non-contact. BBD is slower, manual, but simpler and still widely used in Indian highway projects due to lower equipment cost.

---

### 📊 Pavement Condition Based on Deflection (IRC:81)

| Characteristic Deflection (mm) | Pavement Condition |
|---|---|
| < 1.0 mm | Good — no overlay needed |
| 1.0 – 2.0 mm | Fair — thin overlay recommended |
| 2.0 – 3.0 mm | Poor — moderate overlay required |
| > 3.0 mm | Very Poor — structural rehabilitation |

---

## 12. ⚠️ High-Level Examiner Questions (External Viva Critical)

These are integrative and WHY-based questions commonly asked by external examiners. Know these thoroughly.

---

**Q1. Why do pavements fail in field even when all laboratory test results are within acceptable limits?**
> Lab tests evaluate individual materials in isolation under controlled conditions. Field failures arise from: (a) poor drainage design, (b) inadequate compaction during construction, (c) workmanship defects at joints, (d) unexpected traffic overloading, (e) material variability from different batches, and (f) combined effects of moisture, temperature, and fatigue not captured in individual lab tests.

**Q2. IRC:37-2018 uses mechanistic-empirical (M-E) approach. How is it different from the old CBR-based empirical method?**
> Old IRC:37 (pre-2012): Used CBR to directly read pavement thickness from design charts — purely empirical. New IRC:37-2018: Uses CBR to compute subgrade resilient modulus (Mr), then applies IITPAVE software to compute stresses and strains at critical layers, verifying against fatigue and rutting failure criteria — this is the M-E approach.

**Q3. Why is IRC preferred over IS codes for highway pavement work?**
> IS codes give material testing methods and specifications. IRC codes provide design-oriented guidelines specific to pavement engineering — layer thickness design, overlay, geometric design, safety — aligned with Indian traffic and climatic conditions. For field decisions, IRC takes precedence.

**Q4. A road contractor argues that using softer bitumen (VG-10 instead of VG-30) will save cost. What are the technical implications?**
> VG-10: lower viscosity, lower softening point → higher susceptibility to rutting in hot Indian summers → bleeding → loss of skid resistance. While it reduces fatigue cracking risk (more flexible), the overall performance in hot-dry regions like Punjab deteriorates rapidly. Not recommended as a cost-saving measure.

**Q5. Can aggregate shape affect pavement fatigue life? How?**
> Yes. Flaky/elongated aggregates → poor interlock → higher void content → lower stiffness modulus of bituminous mix → faster fatigue under repeated loading. Cubical aggregates → better particle contact → higher mix stiffness → longer fatigue life. Shape affects not just strength but also durability under cyclic traffic.

**Q6. What is the difference between structural failure and functional failure of a pavement?**
> - **Structural failure:** Loss of load-carrying capacity (e.g., deep rutting, cracking, base failure)
> - **Functional failure:** Loss of riding quality/safety without structural collapse (e.g., surface roughness, skid resistance loss, noise)
> A pavement can fail functionally (IRI too high) but remain structurally sound — requiring resurfacing not rehabilitation.

**Q7. Why does pavement deflection increase during monsoon season?**
> Subgrade absorbs moisture → pore water pressure increases → effective stress decreases → subgrade shear strength and stiffness drop → pavement deflects more under same load. This is why BBD test and pavement condition surveys are done post-monsoon for worst-case assessment.

---

## 13. 📊 Quick Revision Tables

### Table A — Experiment Summary

| Experiment | Property Measured | Key Formula | IS/IRC Code |
|---|---|---|---|
| CBR Test | Subgrade strength | (Test Load / Std. Load) × 100 | IS 2720 (Pt.16), IRC:37-2018 |
| ACV Test | Crushing resistance | (Fines / Total) × 100 | IS 2386 (Pt.IV) |
| AIV Test | Impact toughness | (Fines / Total) × 100 | IS 2386 (Pt.IV) |
| LA Abrasion | Wear resistance | (Loss / Original) × 100 | IS 2386 (Pt.IV) |
| FI / EI Test | Aggregate shape | Weight % of flaky/elongated | IS 2386 (Pt.I) |
| Penetration Test | Bitumen hardness | Depth in 0.1 mm | IS 1203, IS 73:2013 |
| Ductility Test | Bitumen flexibility | Length in cm at break | IS 1208, IS 73:2013 |
| Softening Point | Temp. stability | Ring & Ball temp (°C) | IS 1205, IS 73:2013 |
| Flash & Fire Point | Fire safety | Ignition temperature (°C) | IS 1209, IS 73:2013 |
| Extraction Test | Binder content | (Bitumen wt. / Mix wt.) × 100 | IS 2172 |
| Benkelman Beam | Pavement deflection | Rebound deflection (mm) | IRC:81, IRC:37-2018 |

---

### Table B — Critical Limiting Values at a Glance

| Test | Wearing Course | Base Course | Sub-base |
|---|---|---|---|
| ACV | ≤ 30% | ≤ 40% | ≤ 50% |
| AIV | ≤ 30% | ≤ 35% | ≤ 40% |
| LA Abrasion | ≤ 30% | ≤ 35–40% | ≤ 40–50% |
| FI + EI Combined | ≤ 35% | ≤ 35% | ≤ 45% |
| CBR (Subgrade) | Poor < 5% | Fair 5–10% | Good > 10% |

---

### Table C — Bitumen Test Quick Reference (IS 73:2013 — VG Grades)

| Property | VG-10 | VG-20 | VG-30 | VG-40 |
|---|---|---|---|---|
| Min. Softening Point | 40°C | 45°C | 47°C | 50°C |
| Min. Ductility (27°C) | 75 cm | 75 cm | 75 cm | 40 cm |
| Min. Flash Point | 220°C | 220°C | 220°C | 220°C |
| Typical Use | Cold regions / spray | Hilly/moderate | Standard India | Hot climate / HVR |

---

### Table D — Code Reference Master List

| Code | Title | Relevance |
|---|---|---|
| IS 2720 (Pt.16) : 1987 | Laboratory Determination of CBR | CBR test procedure |
| IS 2386 (Pt.I) : 1963 | Particle Size and Shape | FI, EI tests |
| IS 2386 (Pt.IV) : 1963 | Mechanical Properties | ACV, AIV, LA Abrasion |
| IS 2172 : 1983 | Determination of Binder Content | Extraction test |
| IS 1203 : 1978 | Determination of Penetration | Bitumen penetration |
| IS 1205 : 1978 | Determination of Softening Point | Ring & Ball test |
| IS 1208 : 1978 | Determination of Ductility | Ductility test |
| IS 1209 : 1978 | Flash and Fire Point | Fire safety test |
| **IS 73 : 2013** | **Paving Bitumen Specification** | **Replaces IS 73:1992 — use this** |
| IRC:37 : 2018 | Guidelines for Flexible Pavement Design (4th Rev.) | Pavement thickness design |
| IRC:81 : 1997 | BBD Technique for Overlay Design | Benkelman Beam, overlay |
| MoRTH Specs (5th Rev.) | Specifications for Road and Bridge Works | Material acceptance criteria |

> ⚠️ **Note:** IS 73:2013 (Viscosity Grade Bitumen) has **replaced** IS 73:1992 (Penetration Grade). Always cite IS 73:2013 in viva and reports. Old grades like 60/70 and 80/100 are now referred to as VG-30 and VG-10 respectively.

---
