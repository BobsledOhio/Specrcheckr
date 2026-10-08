# Plumbing Fixture Cutsheet Cross-Check vs. Division 22 (v17)

Project: Eureka Apostolic Christian Home, New AL / MC Facility (RDFA 25059 / pH7 2025-11)
Date: October 8, 2026

## Sources compared

| Source | What was used |
|---|---|
| Division 22 spec | `2026_10_5_Apostolic_Div_22_check_QC_redline_v17.pdf`, Section 22 40 00 (PDF pp.217-229), plus fixture references in 22 07 00, 22 11 19 and 22 13 00 |
| Drawings | P801 Plumbing Fixture Schedule, 9/28/26 permit set (`P Sheets.pdf` on OneDrive). The spec defers to this schedule for design-base models (22 40 00 1.2.B, 2.1.A-B). |
| Cutsheets | `2026_10_8_Apostolic_Plumbing_Fixture_Check.pdf`, 41 pages, all read. Cutsheet page numbers below are PDF pages of this package. |

Limits of this review:
- It is a document cross-check. Product data was read from the cutsheets as printed. Nothing was verified against manufacturer websites, and no hydraulic or code calculation was run.
- Code editions are not verified. Illinois adoption records are still open (see CD-Spec-003).
- IDs continue the audit log numbering (P-Spec-026 and up). Recommended edits need EOR disposition before they go into the spec or schedule.
- Severity follows the audit log: Major means a material coordination or verification gap, Minor means editorial.

## A. Fixture-by-fixture result

Status: OK = submitted product matches schedule and spec. DIFF = differs from schedule or spec. VERIFY = cutsheet does not show enough to confirm.

| Tag | Submitted (cutsheet pp.) | Status | Notes (finding IDs below) |
|---|---|---|---|
| WC-1 | American Standard Compact Cadet 3, 2403.128 (p.1) | DIFF / VERIFY | P-Spec-026, -027, -028 |
| LAV-1 | American Standard Studio 0614 (pp.2-3) | OK, minor | P-Spec-029 |
| LAV-1 faucet | Delta 562-MPU-DST (p.4) | OK | 1.2 gpm matches schedule |
| SHR-1 / 1A | Oasis SHFW-6235 ADA roll-in (pp.5-6) | DIFF | P-Spec-030, -031 |
| SHR-1/1A trim | Delta 51913 hand shower (p.7), T14062 valve trim (p.8) | OK, minor | P-Spec-032 |
| SINK-1 | Elkay LR2222 (pp.9-10) | DIFF | P-Spec-033 |
| SINK-1A | Elkay LRAD222255 (pp.11-12) | DIFF | P-Spec-033 |
| SINK-1/1A faucet | Delta 19867LF (p.13) | OK | 1.8 gpm matches |
| SINK-2 | Elkay LR1919 (pp.14-15) | DIFF | P-Spec-034 |
| SINK-2 faucet | Chicago 895-GN6AE36XK317AB (pp.16-17) | OK | 1.5 gpm, 4 in. centers match |
| SINK-2S faucet | Delta 14882LF bar and prep (p.18) | DIFF | P-Spec-035 |
| SINK-3 | Elkay EFRU311610TC (pp.19-20) | OK, minor | P-Spec-036 |
| SINK-3/5 faucet | Delta 19831Z-SPSD-DST (p.21) | OK | 1.8 gpm, soap dispenser match |
| SINK-4 | Deleted (p.22) | DIFF | P-Spec-037 |
| SINK-5 | Elkay ELUH1316 (pp.23-24) | OK | Matches schedule |
| SINK-6 | Deleted (p.25) | DIFF | P-Spec-037 |
| SINK-7 | Fiat PA11 (pp.26-27) | DIFF | P-Spec-038 |
| SINK-7 faucet | Chicago 201-A1000ABCP (pp.28-29) | OK, minor | P-Spec-038, -041 |
| SINK-8 | American Standard 9512999.020 (p.30) | DIFF | P-Spec-039 |
| SINK-8 flush valve | Delta 81TBP100 (p.31) | DIFF | P-Spec-039 |
| SINK-9 | Kaemark Reflections RP-CB1013-BKBK-903B (pp.32-36) | VERIFY | P-Spec-040 |
| MSB-1 | Zurn Z1996-24 (p.37) | VERIFY | P-Spec-041 |
| MSB-1 faucet | Chicago 897-RCF (pp.38-39) | OK | Mounting height 36 in. matches |
| TUB-1 | Penner TheraSpa (pp.40-41) | VERIFY | P-Spec-042 (supports P-Spec-024) |

## B. Findings: cutsheet vs. schedule vs. spec

| ID | Severity | Fixture | Where | Issue | Recommendation |
|---|---|---|---|---|---|
| P-Spec-026 | Major | WC-1 | P801 WC-1; cutsheet p.1; 22 40 00 2.2.B, PDF p.220 | Schedule lists only 2403.128 but calls for "L HAND / R HAND" handle. The cutsheet shows 2403.128 has the trip lever on the left. A right-hand lever needs 2403.813. Spec 2.2.B says left-handed unless right-handed is needed for ADA. Schedule says handle on the approach side. | Schedule both models (2403.128 and 2403.813) and tie each to the room's approach side. Align the spec wording with the schedule. |
| P-Spec-027 | Major | WC-1 | Cutsheet p.1; P801; 22 40 00 3.3.A, PDF p.225 | Cutsheet gives rim height 16-1/2 in. Spec 3.3.A requires 17 to 19 in. to top of seat for ADA water closets. Schedule says "17+ in. with seat". Seat thickness is not on the cutsheet. | Verify top-of-seat height with the supplied seat (range 17-19 in.). Show the verified value on the shop drawing. |
| P-Spec-028 | Minor | WC-1 | P801; cutsheet p.1; 22 40 00 2.2.A, D.2 (PDF p.220) | Schedule cites ASME A112.18.1 (faucet standard). Cutsheet lists ASME A112.19.2 / CSA B45.1 and WaterSense HET. Spec caps at 1.6 gpf while WC-1 is 1.28 gpf. The included American Standard seat is not on the spec's seat manufacturer list. Model number has no color suffix. | Correct the standard to A112.19.2. Decide whether the spec cap should match the scheduled 1.28 gpf. Add American Standard to the seat list or schedule the seat separately. Add the white color suffix to the schedule model (as .020 on 9512999.020). |
| P-Spec-029 | Minor | LAV-1 | Cutsheet pp.2-3; 22 40 00 3.4.C, PDF p.226 | Spec ADA lavatory height reads "29 in. to bottom of apron". LAV-1 is an undermount with no apron. Cutsheet gives 34 in. to finished floor and 27 in. knee clearance with the sink at least 4 in. from the counter edge. | Add the undermount ADA mounting criteria to 3.4.C. Coordinate the countertop edge with casework. |
| P-Spec-030 | Major | SHR-1 / 1A | P801; cutsheet pp.5-6; 22 40 00 2.1.A and 2.6.B.1, PDF pp.220, 222 | Schedule design base is Freedom Showers APC6236BF1PT. Submitted unit is Oasis SHFW-6235. Oasis is not on the spec's acceptable fiberglass shower manufacturer list (Freedom, American Standard, Aqua Bath, Aqua Glass, Aquarius, Dura Glass, Fiat, Fibersheen, Kohler, National). | Reject as submitted, or add Oasis through an approved equal. EOR to confirm. |
| P-Spec-031 | Major | SHR-1 / 1A | P801 SHR-1 and SHR-1A; cutsheet p.5-6 | The Oasis package shown (ADA/TL-RS) includes a folding seat and two straight bars (36 in. back, 26 in. side). That matches SHR-1A only for the seat. SHR-1 has no seat, and both schedule lines call for an "L" grab bar (APCGB3037SSFI). Oasis exterior is 62 x 36-1/4 in. (schedule 62 x 36). Interior is 60 x 34 in. (schedule 60 x 33-3/4). | If Oasis is accepted, require a no-seat package for SHR-1 and confirm the grab bar arrangement. Otherwise submit the Freedom unit. |
| P-Spec-032 | Minor | SHR-1 / 1A | P801; cutsheet pp.7-8; 22 40 00 3.7.B-C, PDF p.228 | Schedule rough valve reads "R1000". Cutsheet p.8 says R10000 series. T14062 is a pressure-balance trim. Spec 3.7.C says to adjust "mixing valves" to 105 F maximum, and 22 11 19 (PDF pp.155-156) lists single-fixture TMVs at 109 F. Delta hand shower is 1.75 gpm at 80 psi (spec limit 2.5 gpm). | Correct the rough valve number. Align the 105 F and 109 F setpoints with the final temperature sequence (see P-Spec-021). Confirm the slide bar is not being used as a grab bar (Delta notes it is not). |
| P-Spec-033 | Major | SINK-1 / 1A | P801 SINK-1, SINK-1A; cutsheet pp.9-12 | Schedule: LRAD221910, 22 x 19-1/2 x 10 in. deep (SINK-1), and LRAD221905, 22 x 19-1/2 x 5-1/2 in. deep (SINK-1A), both with centerset drain. Submitted: LR2222, 22 x 22 x 7-5/8 in., and LRAD222255, 22 x 22 x 5-1/2 in. Size, depth and drain location (rear center on the ADA model) differ. Faucet hole configuration is not selected on either sheet. Schedule strainer LK35 is not shown in the accessory lists (LK99 and LKAD35 are). | Reconcile the schedule and the submitted models. Specify the hole configuration (single hole). Confirm the strainer. Check casework cutout (21-3/8 in. square for both submitted sinks). |
| P-Spec-034 | Major | SINK-2 / 2S | P801; cutsheet pp.14-15 | Schedule: LRQ1918, 19 x 18 x 7-5/8 in. Submitted: LR1919, 19-1/2 x 19 x 7-1/2 in. SINK-2 needs two holes on 4 in. centers (Chicago 895) and SINK-2S needs a single hole. One sheet covers both with no configuration selected. | Reconcile model and size with the schedule. Submit separate configurations for SINK-2 and SINK-2S. |
| P-Spec-035 | Major | SINK-2S | P801 SINK-2S; cutsheet p.18 | Schedule faucet is Delta Nicoli 19867LF-SS, a pull-down at 1.8 gpm. Submitted is Delta 14882LF bar and prep faucet at 1.5 gpm. | Match the faucet to the schedule, or revise the schedule. Confirm the intended spray function for the salon sink. |
| P-Spec-036 | Minor | SINK-3 | P801; cutsheet pp.19-20 | Schedule strainer is LK35. The Elkay kit includes the LKDD deep strainer basket and bottom grid (schedule remarks already call for a deep strainer and grid). Minimum cabinet is 36 in. | Delete LK35 for SINK-3. Confirm the base cabinet width with casework. |
| P-Spec-037 | Major | SINK-4, SINK-6 | Cutsheet pp.22, 25 (annotated "deleted"); P801; P902/P903 | Cutsheet annotations say SINK-4 (breakroom) is deleted and the breakroom now has SINK-1, and SINK-6 (B215 laundry) is deleted and now has SINK-7. P801 still schedules both, and the stack diagrams still show SINK-4 and SINK-6. | Revise P801 and the stacks, and remove the deleted tags from the spec references. Confirm B215 and breakroom B123 vent and waste sizes after the swap. |
| P-Spec-038 | Major | SINK-7 | P801 SINK-7; cutsheet pp.26-29; 22 40 00 2.9 | Schedule says basin is "field drilled three hole on 4 in. centers" but the faucet is Chicago 201-A1000ABCP on 8 in. centers. Fiat PA11 comes with its own A1 chrome faucet (4 in. centerset) and P-trap, so the specified Chicago faucet would duplicate it. P1 is the model sold without faucet. | Specify P1 (no faucet) with the Chicago faucet and 8 in. drilling, or use PA11 as sold. Fix the schedule text. |
| P-Spec-039 | Major | SINK-8 | P801 SINK-8; cutsheet pp.30-31; 22 40 00 2.2.D.3, 2.10.A.2, PDF pp.220, 223 | Schedule says 1.6 gpf. The clinic sink cutsheet states 6.5 gpf flush volume, 25 psi flowing and 25 gpm. The Delta/Teck 81TBP100 flush valve is factory-set at 1.6 gpf (adjustable 1.1 to 6.6) and is not on the spec's flush valve list (Coyne and Delany, Sloan Regal XL, Zurn Aqua Flush; American Standard also on 2.2). The cutsheet page is labelled "SINK-8 FAUCET" but it is a flush valve. | Correct the scheduled flush volume to the sink's rated value, with the valve adjusted to suit. Add Delta/Teck to 2.10.A.2 or substitute a listed valve. Confirm minimum flow and pressure at the supply. |
| P-Spec-040 | Major | SINK-9 | P801 SINK-9; cutsheet pp.32-36; 22 40 00 3.9, PDF p.228 | Cutsheet shows the specified SKU (RP-CB1013-BKBK-903B). The handling and plumbing instruction pages (pp.33-36) cover RP-370-S, RP-370-B and RP-235 models, not the Reflections cabinet. No faucet flow rate or ASME A112.18.1 data is shown, and the sheets refer to UPC, not the Illinois requirements. Spec 3.9.A-B is written for countertop shampoo bowls (templates, countertop cutout) but this is a freestanding cabinet. | Obtain installation data for the specified cabinet. Confirm the backflow device on the spray hose. Rewrite 3.9 for a cabinet-type unit. |
| P-Spec-041 | Major | MSB-1 | P801 MSB-1; cutsheet pp.37-39; 22 40 00 3.5.G, PDF p.227; 22 13 00 mop hanger | Schedule calls for a white basin. Zurn Z1996-24 needs the -AW suffix for white, and the other options (bumper guard, mop hanger, hose bracket) are unchecked. Spec requires a mop hanger at 4 ft-0 in. (3.5.G.4) while 22 13 00 (PDF p.175) names Fiat 889-CC, and Zurn offers -MH. Chicago 897-RCF matches the schedule. Drain body is PVC with a 3 in. gasketed outlet. | Add the -AW suffix and select the options. Choose one mop hanger. Confirm the drain connection (PVC and the -NHG gasket for no-hub). |
| P-Spec-042 | Major | TUB-1 | P801 TUB-1; cutsheet pp.40-41; 22 40 00 2.5, 3.6 (PDF pp.222, 227-228) | Cutsheet carries a "review and confirm or submit different model" note. Drawing shows a 2 in. drain and 52 x 32 x 40 in. unit. Schedule says 3 in. waste, 1 in. cold and hot, 1-1/2 in. vent. No fill valve, faucet, flow rate, electrical or pump data, or ASME / ADA listing is shown. Spec 3.6 requires a thermostatic mixing valve at 105 F maximum. | Supports P-Spec-024. Obtain the missing product data before the EOR accepts the model, and reconcile the drain and supply sizes. |

## C. Specification text issues found during the cross-check

| ID | Severity | Spec location | Issue | Recommendation |
|---|---|---|---|---|
| P-Spec-043 | Minor | 22 40 00 1.2.E, PDF p.218 | Faucet cartridge alternatives are unresolved: "(renewable seats) (ceramic disc) (cam-activated diaphragm)". Submitted faucets are ceramic disc (Delta) and quarter-turn (Chicago 895, 897). Chicago 201-A1000ABCP is described as a rebuildable compression cartridge. | Select one wording that covers the scheduled faucets. |
| P-Spec-044 | Minor | 22 40 00 3.4.D, PDF p.226 | Self-closing lavatory faucet closing time "(8) seconds" has no matching scheduled faucet. | Delete unless a metering faucet is added. |
| P-Spec-045 | Minor | 22 40 00 3.4, PDF p.226 | Two paragraphs are lettered "A". 3.2.L keeps "(Lead Contractor shall caulk) (Caulk)". | Renumber 3.4 and resolve the alternative. |
| P-Spec-046 | Minor | 22 40 00 1.4, PDF p.219 | Shop drawing submittals need model, color, rough-in and flow data. Several sheets in the package have unchecked selections (color, hole drilling, options) and no flow rate (MSB-1 faucet, SINK-9 faucet, TUB-1). 1.4.C still carries "[3]" color options. | Mark up each sheet with the selected model and options. Resolve the bracket. |
| P-Spec-047 | Minor | 22 40 00 1.3, PDF pp.218-219 | Accessibility standards are listed without editions (ADA, ABA, ICC A117.1). Cutsheets cite ICC A117.1 (2009 and 2017 editions appear on the Oasis sheet) and ADA 2010. Illinois accessibility requirements are in IAC Title 71 on the same list. | State the governing editions after the Illinois adoption record is verified (CD-Spec-003). |

## D. Observations (no new finding)

- WC-1 (1.28 gpf), LAV-1 faucet (1.2 gpm), SINK-2 faucet (1.5 gpm), SINK-1 / SINK-3 faucets (1.8 gpm), SINK-7 faucet (2.2 gpm) and the shower hand shower (1.75 gpm) all report flow rates on the cutsheets. This satisfies 22 40 00 1.4.D for those items.
- Chicago 895, 201 and 897 faucets are rated 40 to 140 F. P701 shows 140 F domestic hot water and 160 F heater leaving temperature. This depends on the temperature sequence under P-Spec-021.
- The Elkay EFRU311610TC sheet notes Reserve Selection products are sold only through authorized wholesalers. Check lead time.

## E. Not checked

- Fixture rough-in locations on the drawings, carriers, and toilet room layouts (not in the supplied sheets).
- Spec 22 05 00.33 submittal log rows against the cutsheet package.
- Casework coordination (cutouts, cabinet widths).
