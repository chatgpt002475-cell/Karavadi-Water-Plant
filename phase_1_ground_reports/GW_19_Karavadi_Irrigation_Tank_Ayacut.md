# HYDROGEOLOGICAL TESTING REPORT: Karavadi Tank Downstream Ayacut
**Report Code:** GW_19  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Karavadi Tank Downstream Ayacut (15.5460 N, 80.0880 E) | **Surface Elevation:** 16.8 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 40m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 40 m (131 feet)
- **Static Water Level (SWL):** 4.8 m below ground level (bgl)
- **Pumping Water Level (PWL at 13,500 LPH):** 12.00 m bgl
- **Net Observed Drawdown ($s$):** 7.2 m
- **Pump Setting Depth:** 28 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 4.80 | 0.00 | — |
| **15** | 13,500 | 8.04 | 3.24 | 4166.7 |
| **30** | 13,500 | 9.48 | 4.68 | 2884.6 |
| **60** | 13,500 | 10.56 | 5.76 | 2343.7 |
| **120** | 13,500 | 11.28 | 6.48 | 2083.3 |
| **240** | 13,500 | 11.71 | 6.91 | 1953.1 |
| **360** | 13,500 | 11.93 | 7.13 | 1893.9 |
| **480** (Equilibrium)| 13,500 | 12.00 | 7.20 | **1875.0 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 13,500\text{ LPH} = 0.003750\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 255.0\text{ m}^2/\text{day} = 0.002951\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{13,500}{7.2} = \mathbf{1875.0\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.58** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **840 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **340 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **260 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.25 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Requires Sand Filtration |
| **Reactive Silica (as $SiO_2$)** | **15.1 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **28 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Contaminated - Pre-Chlorination Required |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (13,500 LPH, TDS: 840 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 1.5 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 2.7 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Dual Media Filter + Pre-Chlorine]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (11,500 LPH, TDS: 1512 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **2.7 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Perched Phreatic Lens / Bio Burden Present**
