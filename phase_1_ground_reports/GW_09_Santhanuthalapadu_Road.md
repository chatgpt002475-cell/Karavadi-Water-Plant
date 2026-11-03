# HYDROGEOLOGICAL TESTING REPORT: Santhanuthalapadu Junction Corridor
**Report Code:** GW_09  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Santhanuthalapadu Junction Corridor (15.5450 N, 80.0420 E) | **Surface Elevation:** 20.1 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 70m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 70 m (230 feet)
- **Static Water Level (SWL):** 8.8 m below ground level (bgl)
- **Pumping Water Level (PWL at 10,500 LPH):** 20.90 m bgl
- **Net Observed Drawdown ($s$):** 12.1 m
- **Pump Setting Depth:** 58 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 8.80 | 0.00 | — |
| **15** | 10,500 | 14.25 | 5.45 | 1928.4 |
| **30** | 10,500 | 16.66 | 7.87 | 1335.0 |
| **60** | 10,500 | 18.48 | 9.68 | 1084.7 |
| **120** | 10,500 | 19.69 | 10.89 | 964.2 |
| **240** | 10,500 | 20.42 | 11.62 | 903.9 |
| **360** | 10,500 | 20.78 | 11.98 | 876.5 |
| **480** (Equilibrium)| 10,500 | 20.90 | 12.10 | **867.8 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 10,500\text{ LPH} = 0.002917\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 225.0\text{ m}^2/\text{day} = 0.002604\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{10,500}{12.1} = \mathbf{867.8\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.35** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **1240 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **460 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **420 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.1 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Compliant |
| **Reactive Silica (as $SiO_2$)** | **17.6 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **0 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Sterile |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (10,500 LPH, TDS: 1240 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 0.8 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 3.9 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Standard Brackish Water 8040]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (8,500 LPH, TDS: 2232 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **3.9 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Stable Confined Aquifer / Excellent RO Feed**
