# HYDROGEOLOGICAL TESTING REPORT: Ongole Northern Industrial Boundary
**Report Code:** GW_08  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Ongole Northern Industrial Boundary (15.5180 N, 80.0520 E) | **Surface Elevation:** 22.5 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 110m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 110 m (360 feet)
- **Static Water Level (SWL):** 15.6 m below ground level (bgl)
- **Pumping Water Level (PWL at 6,800 LPH):** 40.10 m bgl
- **Net Observed Drawdown ($s$):** 24.5 m
- **Pump Setting Depth:** 98 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 15.60 | 0.00 | — |
| **15** | 6,800 | 26.62 | 11.03 | 616.8 |
| **30** | 6,800 | 31.52 | 15.93 | 427.0 |
| **60** | 6,800 | 35.20 | 19.60 | 346.9 |
| **120** | 6,800 | 37.65 | 22.05 | 308.4 |
| **240** | 6,800 | 39.12 | 23.52 | 289.1 |
| **360** | 6,800 | 39.85 | 24.25 | 280.4 |
| **480** (Equilibrium)| 6,800 | 40.10 | 24.50 | **277.6 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 6,800\text{ LPH} = 0.001889\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 188.0\text{ m}^2/\text{day} = 0.002176\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{6,800}{24.5} = \mathbf{277.6\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **6.95** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **2150 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **820 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **810 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.28 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Requires Sand Filtration |
| **Reactive Silica (as $SiO_2$)** | **31.2 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **0 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Sterile |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (6,800 LPH, TDS: 2150 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 0.8 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 6.5 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Specialist Silica Antiscalant Required]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (4,800 LPH, TDS: 3870 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **6.5 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Severe Scaling Potential / High Silica (31 mg/L)**
