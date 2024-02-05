# Probe Station Logs

## 2024.02.01. Julich smaples, third measurement - Matteo, Zoli

### Recreate the measurement made yesterday.
- IV_Block 5 looking stable, higher current amplifier makes less noise on the stable measurements., IV6 is with higher 1e6 current amplifier. 
Noise:
- Card offset -0.090654 mV , Agilent offset:0.269617 mV
- Start measuring with an IV. Noise, IV, SET, IV Noise, IV RESET.
- IV is looking good. Start Noise. Restart because didnt switched the capacitor. the first HRS iv's bottom is around -2e-6 A, and the LRS is around -4e-6 A at 1 V. The HRS after the noise is slightly higher at -3e-6 A. Noise on LRS. Restart because didnt switched the capacitor.
- From the evaluatioin we see that 1V is making the sample switch. Next time will measre with fix LCA.

## 2024.02.05. Julich smaples, Nth measurement - Matteo

### MT1
- Card Offset : -0.045904 Mv, Agilent Offset : 0.13 mV
- the plan is to search for contact on a 20 and 100 sample ({\mu }m)
- Just found out that the norma setup's cable is sending the same voltage after the measurement has stopped.c
- Couldn't contact 20, L08p100 is successfully contacted. 460 resistance, (sweep 0.5V, 0.1s Min: -8*e-4 A, Max: 1e-3 A)
- base measurement(5 sweep) is looking stable
- switching on pos 0.5V (RESET), HRS state is -3.5e-5 A Min (0.5V, 0.1s) IV_26
- probably killed the sample with -1.5V. Go to L09p100. Contact success. IV37. Base 5 looking stable, -1.5e-5 A on 0.5V sweep, RESET on 1.5V pos, -2.5e-5 A on min, stable
- SET on -2V. 
- after some steps it went out from e-5 A to e-6 A. IV68 Going to a "known" 50 {\mu}m. L09p50 conduct success IV79
- +3V is RESET, -3V is SET, 1s, Base state is SET which is HRS. HRS is -2.25e-6 A - -2.7e-6 A min. LRS is -4e-6 A - (-5e-6 A). The HRS/LRS is around 2. Both state look stable.
- Setting up the noise measurement. The agilent has a lower step of 0.5 mV, and a 0.10-0.15mV minimum agilent error. It's okay if you measure it back.
- Starting with IV, base was LRS state. measured is -4e-6 A. RESETing device.
- When formatting, I need to watch out to change the amplifier. Failed the first reset, second was good. Failed the amplifier constant change in the measurement program. Doing HRS again. Switching was good. Recreating the measurement file for noise, because we change from 0-1v-0-(-1v)-0 to 0-500mV-0-(-500mV)-0 . I forget to change filter when doing IV.
- The sample again moved from 2e-6A to 3e-6A while doing measurement, even though We lowered to 500mV.
- Went off for two hours. The HRS is -3e-6 A, while the LRS is -6e-6 A. Zoltan created a switch for the easy change of the amplifier's state, and it sent the amplifier to overload. Now it makes sense why the other sample went off a couple days ago. Changed it, and now the Non-Conducting state is actually grounded. After the overload I measured a change in the LRS, HRS that is described above. 





