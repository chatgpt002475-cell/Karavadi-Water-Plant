# HYDROGEOLOGICAL TESTING REPORT: Gundlakamma Right Bank Main Canal
**Report Code:** GW_13  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Location:** Gundlakamma Right Bank Main Canal (15.5610 N, 80.0820 E) | **Surface Elevation:** 16.2 m MSL  
**Assessment Standard:** Central Ground Water Board (CGWB) & Bureau of Indian Standards IS 14543:2016  

---

## 1. WELL CONSTRUCTION & STRATIGRAPHIC LITHOLOGY

```
Depth (m)   Lithological Stratum                         Casing & Screen Configuration
 0.0 - 2.5m  Topsoil, dark silty clay                    [ 175mm (7") MS Surface Protective Casing ]
 2.5 - 12.0m Medium-to-coarse alluvial sand & gravel    [ Solid 150mm (6") Heavy Duty PVC Casing ]
12.0 - 28.0m Highly weathered granite gneiss (saprolite) [ Slotted PVC Strainer (0.75mm slot width) ]
28.0 - 30m Fractured hornblende-biotite gneiss bedrock [ Open Bore in Hard Rock (150mm dia) ]
```

- **Total Drilled Depth:** 30 m (98 feet)
- **Static Water Level (SWL):** 4.1 m below ground level (bgl)
- **Pumping Water Level (PWL at 16,000 LPH):** 9.60 m bgl
- **Net Observed Drawdown ($s$):** 5.5 m
- **Pump Setting Depth:** 18 m bgl (Continuous Submersible 5.0 HP)

---

## 2. 8-HOUR CONTINUOUS PUMPING TEST & HYDRODYNAMIC EQUATIONS

### 2.1 Pumping Test Time-Drawdown Observations
| Elapsed Time ($t$, min) | Discharge Rate ($Q$, LPH) | Pumping Level (m bgl) | Drawdown ($s$, m) | Specific Capacity ($S_c$, LPH/m) |
| :--- | :--- | :--- | :--- | :--- |
| **0** (Static) | 0 | 4.10 | 0.00 | — |
| **15** | 16,000 | 6.57 | 2.48 | 6464.6 |
| **30** | 16,000 | 7.67 | 3.58 | 4475.5 |
| **60** | 16,000 | 8.50 | 4.40 | 3636.4 |
| **120** | 16,000 | 9.05 | 4.95 | 3232.3 |
| **240** | 16,000 | 9.38 | 5.28 | 3030.3 |
| **360** | 16,000 | 9.54 | 5.45 | 2938.5 |
| **480** (Equilibrium)| 16,000 | 9.60 | 5.50 | **2909.1 LPH/m** |

### 2.2 Hydrodynamic Formulations
1. **Cooper-Jacob Drawdown Equation:**
   $$s = \frac{2.303 Q}{4 \pi T} \log_{10}\left(\frac{2.25 T t}{r^2 S}\right)$$
   Where:
   - $Q = 16,000\text{ LPH} = 0.004444\text{ m}^3/\text{s}$
   - Aquifer Transmissivity $T \approx 280.0\text{ m}^2/\text{day} = 0.003241\text{ m}^2/\text{s}$
   - Storage Coefficient $S = 0.00045$ (Semi-confined fractured rock aquifer)
   - Casing radius $r = 0.0762\text{ m}$ (6-inch bore)
   - Continuous pumping duration $t = 28,800\text{ s}$ (8 hours)

2. **Specific Capacity ($S_c$):**
   $$S_c = \frac{Q}{s} = \frac{16,000}{5.5} = \mathbf{2909.1\text{ Litres/Hour per metre of drawdown}}$$

---

## 3. LABORATORY PHYSICO-CHEMICAL & MICROBIOLOGICAL WATER ANALYSIS

| Tested Parameter | Observed Value | BIS IS 14543 Permissible Limit | Analytical Method Reference | Compliance Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **Appearance / Odour** | Clear / Unobjectionable | Clear / Agreeable | Organoleptic | Compliant |
| **pH at 25°C** | **7.7** | 6.50 – 8.50 | IS 3025 (Part 11) | Compliant |
| **Total Dissolved Solids (TDS)** | **680 mg/L** | 75 – 500 mg/L | IS 3025 (Part 16) | Requires RO Desalination |
| **Total Hardness (as $CaCO_3$)** | **280 mg/L** | Max 200 mg/L | IS 3025 (Part 21) | Requires Antiscalant |
| **Chlorides (as $Cl^-$)** | **190 mg/L** | Max 200 mg/L | IS 3025 (Part 32) | Requires RO Permeation |
| **Iron (as $Fe$)** | **0.15 mg/L** | Max 0.10 mg/L | IS 3025 (Part 53) | Requires Sand Filtration |
| **Reactive Silica (as $SiO_2$)** | **13.2 mg/L** | Max trace / guideline | Molybdate Blue Method | Compliant (<25 mg/L) |
| **Turbidity** | 1.8 NTU | Max 2.0 NTU | IS 3025 (Part 10) | Compliant |
| **Total Coliform Bacteria** | **65 CFU/100ml** | 0 CFU / 250 ml | IS 15185 Membrane Filter | Contaminated - Pre-Chlorination Required |
| **E. coli & Faecal Strep** | Absent | Absent / 250 ml | IS 15185 / IS 15186 | Compliant |

---

## 4. RO PROCESS ENGINEERING & CHEMICAL TREATMENT DESIGN

```
Feed Water (16,000 LPH, TDS: 680 mg/L)
   │
   ▼
[Sodium Hypochlorite Dosing: 1.5 ppm]
   │
   ▼
[Dual Media Sand Filter (MGF) + Activated Carbon (ACF)]
   │
   ▼
[Antiscalant Dosing Skid: 2.2 mg/L Phosphonate SHMP]
   │
   ▼
[High-Pressure RO Skid: Coagulant Dosing + Sand Filter]
   │
   ├───► Permeate Stream (2000 LPH, TDS: 110-130 mg/L) ──► Ozone + UV Disinfection
   │
   └───► Reject Stream (14,000 LPH, TDS: 1224 mg/L) ──► Can Washing / Re-use
```

- **Langelier Saturation Index (LSI at 28°C concentrate):** $+1.15$ (Super-saturated)
- **Required Antiscalant Dosing:** **2.2 mg/L** (Prevents gypsum and calcium carbonate crystal nucleation)
- **Suitability Assessment for Karavadi Plant:** **Canal Recharge Driven / Seasonal Turbidity Swing**
