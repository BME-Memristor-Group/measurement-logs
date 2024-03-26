# AFM as Probe Station Logs

---------------------------------------------
## 2024.03.26. Julich samples, Nth measurement - Matteo - /w AFM

### MT1 G08p50
#### Conductive AFM measurements
- cantilever C14. ForceSetpoint 5nN. 0.1V 0.1s no contact yet. Contact with C14, HRS state at -1V, -1.5e6 IV12. Using 1e5 gain. 10 1V 1s in IV13. IV16 100 1V 1s. Stable. IV17 2s 1V, IV18 5s 1V, IV19 10 5s 1V. IV20 10s 1V. IV21 5 10s 1V. IV22 1s 1.2V. IV27 0.1s 1.5V. Max Current 1.8e-5. IV30 1s 1.5V. IV33 5s 1.5V. IV35 10s 1.5V. IV37 0.1s 2V. 5e-5 max current. IV39 1s 2V. IV41 5s 2V. IV44 10s 2V. IV47 0.1s 2.5V. Reaching the maximum of the current gain. IV52 1s 2.5V. IV55 5s 2.5V. IV57 10s 2.5V. Iv58 1s 2.5V gain and resistance is wrong. IV59 1s 2.5V. IV60 1s 2.8V. IV64 only -, 1s 3V. IV66 pos 1s 3V. IV72 1s 3.2V. Parked the measurement. 
### MT1 G08p10 
- IV78 10 mu_m cample has been conducted for the first time. 1V -1.4e-7 is min, 6e-8A is max. Resistance is around 120 MOhm in HRS. IV89, IV90 2V. IV92 3V 1s, IV95 neg 3V 1s. IV97 +3V,1s. +-2e-7 is LRS at 1V. -3V neg half cycle. HRS  is 1.4e-7A at 1V,1s. HRS looks stable, after many -3V half cycle it didnt go lower than 1.25e-7A. +3V half cycle IV105. Stable at -2e-7A in IV106. IV130 is after many +3V formatting. -2.5e-7 A is the lowest we could achieve.
- Switching to HRS. IV141 3.3V 1s two times. IV145 AFM drifted apart to the right. 2.5e-7A  is the max LRS. 170-182 Offset compensation . Switched to 1e4 gain.
- The states changed to 5e-8 A in HRS to 1.5e-7 A at -1V. IV228-230 10 3V 1s. 
- Offsets -14.08X, -4.369Y. IV233 before, IV234 after.
### MT1 F08p10 
#### Conductive AFM measurements
- Did a topography measurement with AFM. IV235 stablity in HRS 10 1s 1V. IV236 -3V 1s Probably HRS and LRS are switched for us. IV247 10 1s 3V. 10 1s 1V. -1V -6e-8 HRS. Around 2 on-off ratio. -1.5e-7 is LRS. This could be achieved when doing many Pos Cycles in LRS. 10 Full 3V. HRS stay stable. Switching. LRS is stable. Changed the position on the sample. We are looking for the same data. IV282 10 Full 3V 1s. It stayed the same. It seems like after moving it is a bit relaxed to -1.2e-7 A. IV305 from HRS 3V 1s. 
- Made a topography measurmeent on the same area. We can see the places where we made the measurements.



## 2024.03.22. Julich samples, Nth measurement - Matteo - /w AFM
### Conductive AFM setup.
- tried measurement with C40.4, which worked for 10-20 measurements. IV1-8. AFter that we tried to format it with 1.5V, when the current amplifier went overload. Switched to 1e4 from 1e6 and no further measurements were possible. Tried to get contact while measureing the surface. It went to error after 1/4 of the 20x20 micrometer part. The error was Tip Guard Decel. Probably killed the cantilever. Sending it to diagnostics with Gergő. Changeing to C40.5.
- Successful contact on P08p50 with C.AFM. IV 28-29. Stbility of 1V 10s, at IV 30. Lost contact at 1V 10s. Switched gain from 1e6 to 1e4. 40-41-42 is getting the signal back. The noise is more. The signal died again. Tried to raise the Force Setpoint to 100 and 150 from 50.
- Change C40.5 (probably died) to C12. Switched from PCMO MT1 to golden sheet. C12 didnt went overload on 1V 10s. Switched to C13. No contact. After investigation the plate, we see that it could move. We fixed it. The bnc cables inner wire was not maintained, so we pulled out the wire by hand. The conducting was semi-success. The conducted state is not stable, and low chance that we can see the linear curve. Otherwise it's not conducted. We shouldnt press the cantilever with higher Force Setpoint. It was good and stable at 1 nN.
