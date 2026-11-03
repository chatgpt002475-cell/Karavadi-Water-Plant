# HYDROGEOLOGICAL TESTING REPORT: Alluru Road Rural Cluster
**Report Code:** GW_14  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Alluru Road Rural Cluster (15.5310 N, 80.0980 E) | **Surface Elevation:** 18.0 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 82m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 82 m (270 feet)
- **Static Water Level (SWL):** 10.5 m below ground level (bgl)
- **Pumping Water Level (PWL at 10,100 LPH):** 26.70 m bgl
- **Net Observed Drawdown ($s$):** 16.2 m
- **Pump Setting Depth:** 70 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 10.50 | 0.00 | — |
| **15** | 10,100 | 17.79 | 7.29 | 1385.5 |
| **30** | 10,100 | 21.03 | 10.53 | 959.2 |
| **60** | 10,100 | 23.46 | 12.96 | 779.3 |
| **120** | 10,100 | 25.08 | 14.58 | 692.7 |
| **240** | 10,100 | 26.05 | 15.55 | 649.4 |
| **360** | 10,100 | 26.54 | 16.04 | 629.8 |
| **480** (Equilibrium)| 10,100 | 26.70 | 16.20 | **623.5 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 10,100\text{ LPH} = 0.002806\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 221.0\text{ m}^2/\text{day} = 0.002558\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{10,100}{16.2} = \mathbf{623.5\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.34** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **1320 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **480 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **450 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.07 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Compliant |
| **Reactive Silica (as $SiO_2$)** | **18.9 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **0 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Sterile |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (10,100 LPH, TDS: 1320 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 0.8 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 4.1 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Brackish Water 8040 Skid]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (8,100 LPH, TDS: 2376 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **4.1 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Standard Crystalline Fractured Gneiss**
