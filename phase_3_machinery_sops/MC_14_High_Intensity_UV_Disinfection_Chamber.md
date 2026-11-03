# MACHINERY OPERATIONAL & CALIBRATION PROCEDURE: High-Intensity UV-C In-Line Sterilizer
**Equipment Code:** MC_14  
**Facility Tracking:** Karavadi Pure Waters Pvt. Ltd. (KPW)  
**Rated Capacity:** 6.0 m³/hr (Dosage >40 mJ/cm²) | **Metallurgy:** SS316 Electro-polished Chamber  
**Target Operating Setpoint:** 254 nm Wavelength, Quartz sleeve clean  
**Governing Standard:** BIS IS 14543:2016 & Machinery Manufacturer Manual  

---

## 1. TECHNICAL SPECIFICATIONS & P&ID CONNECTION

```
+-------------------------------------------------------------------------+
| [EQUIPMENT TAG: MC_14] - HIGH-INTENSITY UV-C IN-LINE STERILIZER
| Capacity: 6.0 m³/hr (Dosage >40 mJ/cm²)
+-------------------------------------------------------------------------+
    Inflow Stream ---> [ MC_14 UNIT ] ---> Outflow Process Stream
                             |
                      Control Panel / Sensors
                   (4-20mA Output to PLC/SCADA)
```

- **Mechanical Construction:** SS316 Electro-polished Chamber
- **Electrical Motor Rating:** Commercial 3-Phase 415V, 50 Hz, IP55 protection
- **Operational Setpoints:** 254 nm Wavelength, Quartz sleeve clean
- **Fail-Safe Safety Interlocks:** Integrated with high/low pressure trip switches and dry-run float sensor.

---

## 2. STANDARD OPERATING PROCEDURE (STEP-BY-STEP)

### 2.1 Pre-Start Inspection Checklist
1. Verify liquid levels in upstream buffer tanks.
2. Confirm electrical voltage is within $415	ext{V} \pm 6\%$.
3. Check all isolation butterfly valves and sample cocks are set in normal flow positions.
4. Confirm zero leaks at tri-clamp gaskets and mechanical pump seals.

### 2.2 Startup & Normal Operation
1. Switch panel selector switch from `OFF` to `AUTO`.
2. Allow soft-starter or VFD to ramp up operating RPM over 10 seconds.
3. Observe delivery pressure gauge and digital flow meter. Ensure reading stabilizes at **254 nm Wavelength, Quartz sleeve clean**.
4. Log operating parameters in Form **OP-MC_14** every 60 minutes.

### 2.3 Controlled Shutdown Sequence
1. Press stop pushbutton on remote control panel.
2. Allow line pressure to decay gradually.
3. Close isolation valves if maintenance or cleaning-in-place (CIP) is scheduled.

---

## 3. CALIBRATION & MAINTENANCE PROTOCOL

### 3.1 Maintenance Schedule
- **Cadence:** Quarterly quartz sleeve wipe, replace lamp at 9,000 hours.
- **Vibration & Bearing Check:** Vibration threshold $<2.8\text{ mm/s RMS}$; greasing every 1,000 running hours.
- **Wear Components:** Seals, O-rings, and impellers replaced annually during plant overhaul.

### 3.2 Calibration Workflow
1. Isolate the primary instrument using double block-and-bleed valves.
2. Connect certified master gauge or reference standard.
3. Apply 5-point test points ($0\%, 25\%, 50\%, 75\%, 100\%$ of span).
4. Verify linearity within $\pm 1.0\%$. If error exceeds threshold, adjust span potentiometer.
5. Affix dated calibration sticker signed by Approved QC Engineer.
