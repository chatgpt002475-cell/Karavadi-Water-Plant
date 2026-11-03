# HYDROGEOLOGICAL TESTING REPORT: North Gundlakamma River Alluvial Fringe
**Report Code:** GW_03  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** North Gundlakamma River Alluvial Fringe (15.5510 N, 80.0892 E) | **Surface Elevation:** 16.5 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 64m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 64 m (210 feet)
- **Static Water Level (SWL):** 6.1 m below ground level (bgl)
- **Pumping Water Level (PWL at 14,200 LPH):** 14.50 m bgl
- **Net Observed Drawdown ($s$):** 8.4 m
- **Pump Setting Depth:** 52 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 6.10 | 0.00 | — |
| **15** | 14,200 | 9.88 | 3.78 | 3756.6 |
| **30** | 14,200 | 11.56 | 5.46 | 2600.7 |
| **60** | 14,200 | 12.82 | 6.72 | 2113.1 |
| **120** | 14,200 | 13.66 | 7.56 | 1878.3 |
| **240** | 14,200 | 14.16 | 8.06 | 1760.9 |
| **360** | 14,200 | 14.42 | 8.32 | 1707.6 |
| **480** (Equilibrium)| 14,200 | 14.50 | 8.40 | **1690.5 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 14,200\text{ LPH} = 0.003944\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 262.0\text{ m}^2/\text{day} = 0.003032\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{14,200}{8.4} = \mathbf{1690.5\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.65** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **780 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **320 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **220 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.12 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Requires Sand Filtration |
| **Reactive Silica (as $SiO_2$)** | **14.5 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **14 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Contaminated - Pre-Chlorination Required |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (14,200 LPH, TDS: 780 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 1.5 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 2.5 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Standard Low Energy LE-4040]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (12,200 LPH, TDS: 1404 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **2.5 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **High Yield Alluvial Aquifer / Requires Biological Filter**
