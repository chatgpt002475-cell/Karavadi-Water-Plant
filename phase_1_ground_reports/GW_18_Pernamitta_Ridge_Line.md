# HYDROGEOLOGICAL TESTING REPORT: Pernamitta Uplands Structural Zone
**Report Code:** GW_18  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Pernamitta Uplands Structural Zone (15.4910 N, 80.0120 E) | **Surface Elevation:** 28.0 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 115m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 115 m (377 feet)
- **Static Water Level (SWL):** 18.2 m below ground level (bgl)
- **Pumping Water Level (PWL at 4,900 LPH):** 49.20 m bgl
- **Net Observed Drawdown ($s$):** 31.0 m
- **Pump Setting Depth:** 103 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 18.20 | 0.00 | — |
| **15** | 4,900 | 32.15 | 13.95 | 351.3 |
| **30** | 4,900 | 38.35 | 20.15 | 243.2 |
| **60** | 4,900 | 43.00 | 24.80 | 197.6 |
| **120** | 4,900 | 46.10 | 27.90 | 175.6 |
| **240** | 4,900 | 47.96 | 29.76 | 164.7 |
| **360** | 4,900 | 48.89 | 30.69 | 159.7 |
| **480** (Equilibrium)| 4,900 | 49.20 | 31.00 | **158.1 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 4,900\text{ LPH} = 0.001361\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 169.0\text{ m}^2/\text{day} = 0.001956\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{4,900}{31.0} = \mathbf{158.1\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.1** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **1980 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **780 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **760 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.21 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Requires Sand Filtration |
| **Reactive Silica (as $SiO_2$)** | **25.0 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **0 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Sterile |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (4,900 LPH, TDS: 1980 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 0.8 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 6.0 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: High Pressure Multi-Stage]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (2,900 LPH, TDS: 3564 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **6.0 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Low Transmissivity / High Pumping Head Required**
