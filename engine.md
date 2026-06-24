# Engine — Volvo Penta MD11C

## Specs

| Spec | Value |
|------|-------|
| Model | Volvo Penta MD11C |
| Type | Naturally aspirated marine diesel |
| Configuration | 2-cylinder, 4-stroke |
| Horsepower | 17 kW (23 HP) at 2,500 RPM |
| Cooling | Raw-water cooled — sea water pump with neoprene impeller, driven via rubber flange from camshaft |
| Reverse gear | Volvo Penta MSB (Mono Shift), ratio 1.91:1 |
| Drive | Walter V-drive |
| Fuel | Diesel (quality "Autodiesel") |
| Injection pump | Bosch PRF 2K 75A 407/11 |
| Injector | Bosch KBL 87S78/4, nozzle DLLA 150S720 |
| Pre-injection angle | 23°–26° B.T.D.C. |
| Max operating speed | 2,500 RPM (41.7 r/s) |
| Idle speed | 650–780 RPM (11–13 r/s) |
| Compression ratio | 17.5:1 |
| Compression pressure | 284–355 psi (2–2.5 MPa) at starter motor speed |
| Thermostat opens | 60°C (140°F); fully open at 75°C (168°F) |
| Battery | 12V, max 150 Ah |
| Alternator | 35A / 420W |

### Oil Specs

| System | Oil grade | Capacity |
|--------|-----------|----------|
| Engine (excl. filter) | API CD diesel, SAE 20W above 50°F / SAE 10W below 50°F — modern 15W-40 CJ-4 is fine | 2.6 liters (~2.75 qt) |
| Engine (incl. filter) | Same | 2.9 liters (~3.0 qt) |
| Reverse gear MSB | Same oil as engine | 0.60 liters (~⅝ qt) |

**Order 4 quarts total to cover both engine and reverse gear fills.**

### Valve Clearance (engine warm)

| Valve | Clearance |
|-------|-----------|
| Inlet | 0.30 mm (0.012") |
| Exhaust | 0.35 mm (0.014") |

### Key Torques

| Fastener | Torque |
|----------|--------|
| Cylinder head bolts (19mm wrench) | 11.0 kpm / 79 lbf·ft |
| Cylinder head bolts (15mm wrench) | 4.5 kpm / 32 lbf·ft |
| Connecting rod bolts | 6.5 kpm / 46 lbf·ft |
| Crankshaft centre bearing | 8.0 kpm / 58 lbf·ft |
| Injector nuts | 2.0 kpm / 14 lbf·ft |

## Access

Primary access through cockpit lockers and companionway. Tight working space. Most maintenance items (impeller, alternator, starter, injectors, stop linkage) are done in this confined area.

## Known Issues / Active Work

### Mechanical Stop Cable

The mechanical stop mechanism has been repaired. The cable still needs to be physically reconnected to the injection pump fuel shutoff lever and adjusted.

- **Status:** Mechanism fixed — cable reconnection and adjustment pending
- **Fix:** Reconnect cable end to injection pump shutoff lever; adjust tension so the lever moves fully to stop position

### Battery Wiring

Battery wiring work in progress. See `electrical.md` for details.

### Shore Power

Shore power assessment in progress during recommissioning.

### Freshwater System

Freshwater system assessment in progress during recommissioning.

## Recommissioning Checklist (After Winter Storage)

- [ ] Reconnect and adjust mechanical stop cable
- [ ] Raw water impeller — inspect/replace (replace annually or if any doubt)
- [ ] Engine oil — change
- [ ] Fuel filter — replace
- [ ] Belts — inspect tension and condition
- [ ] Zincs — inspect/replace
- [ ] Alternator — inspect belts and output voltage
- [ ] Starter — verify operation
- [ ] Injectors — inspect; note any smoke or hard starts
- [ ] Raw water strainer — clean
- [ ] Coolant hoses — inspect for cracking or soft spots
- [ ] Exhaust system — inspect wet exhaust for blockage or wear

## Start / Stop Procedure (from Instruction Book)

### Starting
1. Switch on the main switch
2. Open the cooling water sea cock
3. Push the **stop control IN** — you cannot start with it pulled out
4. Turn key one stage right — oil pressure and battery charging warning lamps should light
5. **Cold start (MD11C only):** push cold start button DOWN — it returns automatically after engine starts
6. Turn key further right to crank; release when engine fires
7. Check immediately that warning lamps go out — if either stays lit, stop engine immediately
8. Run at idle until warm; check that cooling water flows from exhaust

### Stopping
1. Reduce to idle; let run a few minutes
2. **Pull stop control** while at idle
3. Turn key back to initial position
4. **Switch off main switch ONLY AFTER engine has stopped** — switching it off while running destroys the charging regulator
5. Close fuel cock and cooling water cock if not sailing soon; check for leaks before leaving boat

### Fuel System Venting (required after sitting, fuel filter change, or tank ran dry)
1. Open fuel filter vent screw ~4 turns; pump hand primer until bubble-free fuel flows; close screw
2. Open injection pump vent screw ~2 turns; pump until bubble-free; close
3. Loosen injector delivery pipe nut; push stop control IN; press cold start button; crank with starter until fuel flows from delivery pipe; retighten nut; start engine

## Fault Diagnosis (Instruction Book page 26)

| Symptom | Most Likely Causes (check in order) |
|---------|--------------------------------------|
| Won't start | Stop control not pushed in → main switch off → flat battery → blown fuse → empty tank → closed fuel cock → blocked filter → water/air in fuel |
| Runs then stops | Empty tank, closed fuel cock, blocked filter, water in fuel |
| Won't reach full RPM | Defective injector, blocked air filter, fouling on hull, damaged propeller |
| Overheating | Blocked cooling water intake → defective impeller → faulty thermostat |

## Stop Device Location

The stop device (Item 1 in the MD11C Component Guide) is on the starboard/forward face of the engine, above and near the injection pump. The air bleed screw for the injection pump is immediately adjacent (Item 2). The cable end reconnects to the fuel shutoff lever on the injection pump body.

## Key Behaviors to Know

- **Short beep on key-on:** Normal. This is the low oil pressure / charging warning alarm that sounds before the engine starts and clears once it's running.
- **V-drive:** The Walter V-drive means the engine faces aft and the prop shaft exits forward — opposite of a standard straight-drive installation. Normal for this model.
- **Reverse gear oil is separate:** The MSB reverse gear has its own dipstick and oil level — check every 14 days. Same oil spec as the engine. Same fill interval (every 50 hours).
- **Belt tension spec:** Belt should deflect no more than 5mm (3/16") pressed midway between pulleys with the thumb.
- **Main switch rule:** Never switch the main switch off while the engine is running. This will destroy the voltage regulator on the alternator.

## Future

Long-term consideration: electric propulsion conversion. Document current diesel condition thoroughly before any conversion work so the scope is fully understood.
