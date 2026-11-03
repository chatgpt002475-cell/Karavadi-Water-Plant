# HYDROGEOLOGICAL TESTING REPORT: Karavadi Plant Site (Bore 1 - Primary Production)
**Report Code:** GW_01  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Karavadi Plant Site (Bore 1 - Primary Production) (15.5421 N, 80.0845 E) | **Surface Elevation:** 18.2 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 79m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 79 m (260 feet)
- **Static Water Level (SWL):** 9.2 m below ground level (bgl)
- **Pumping Water Level (PWL at 11,800 LPH):** 23.70 m bgl
- **Net Observed Drawdown ($s$):** 14.5 m
- **Pump Setting Depth:** 67 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 9.20 | 0.00 | — |
| **15** | 11,800 | 15.72 | 6.53 | 1808.4 |
| **30** | 11,800 | 18.62 | 9.43 | 1252.0 |
| **60** | 11,800 | 20.80 | 11.60 | 1017.2 |
| **120** | 11,800 | 22.25 | 13.05 | 904.2 |
| **240** | 11,800 | 23.12 | 13.92 | 847.7 |
| **360** | 11,800 | 23.55 | 14.36 | 822.0 |
| **480** (Equilibrium)| 11,800 | 23.70 | 14.50 | **813.8 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 11,800\text{ LPH} = 0.003278\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 238.0\text{ m}^2/\text{day} = 0.002755\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{11,800}{14.5} = \mathbf{813.8\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.42** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **1120 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **410 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **380 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.08 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Compliant |
| **Reactive Silica (as $SiO_2$)** | **18.2 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **0 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Sterile |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (11,800 LPH, TDS: 1120 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 0.8 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 3.8 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Brackish Water BW30-4040 x4]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (9,800 LPH, TDS: 2016 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **3.8 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Optimal Primary Source for 2000 LPH RO**
