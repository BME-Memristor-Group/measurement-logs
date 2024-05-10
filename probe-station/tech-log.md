# Probe Station Logs

---------------------------------------------
## 2024.05.10. Julich samples, Nth measurement - Matteo
### MT1 E08p20
#### IV

- First we conducted the F08p50, which was success in IV6. We tried to contact F08p20 but it probably died. (very low resistance)
- Success in IV36. IV38 switch, 39-40 also. Switching stability Iv41-42 3V 1s 10.
- HRS Stab in IV49 1V 1s 10. LRS IV44 1V 1s 10. Switching stab in IV 50-54 3V 1s 10. IV56 1e7 gain, LRS 1V 10 1s. IV58 wrong gain. IV57 switch 1. IV59 1e7 HRS 1V 10 1s.
#### Noise
- offset comp: card: -0.0827379 mV, agilent: -0.537584 mV
- HRS in ser01 
- 5e7 gain offsets
- card : -0.30796 mV, agilent: -0.741139 mV
- it went overload, tried to measure LRS (ser02) with the normal gain amplifier, but the resistance levels were not correct.

## 2024.05.03. Julich samples, Nth measurement - Matteo
### MT1 F08p50
#### IV 
- successful init in IV1-4. start noise in LRS

#### Noise
- offset comp: card: -0.122523 mV, agilent: -0.427412 mV
- LRS in ser03. on the first try I missed to switch the capacitance, so I restarted the measurement. HRS in ser04.

### MT1 F08p100
#### IV 
- IV 12-14 very strange, inverted IV. success if IV17. 3V ,0.1s in IV21. 3.2V 10 0.1s in IV22-23. LRS -2.5e-5 A at -1V. 3.2V 10 1s in IV26. HRS is -5e-6 A at -1V. Start Noise in LRS.



## 2024.04.26. Julich samples, Nth measurement - Matteo
### MT1 F08p50
#### IV
- successful init. IV6, full in iv11, bad gain. at 64 we realised that the gain's offset was huge. we terrorised the sample a bit, and then it chaged the states to -2e-6A, and -6e-6 A.

#### Noise
- offset comp: card offset -0.0970116 mV, Agilent offset 0.194962 mV
- LRS in ser01, HRS in ser02.
## 2024.03.20. Julich samples, Nth measurement - Matteo

### MT M03p50

#### Noise

- Card: -0.00611255 mV, Agilent: -0.140019 mV,
- The measurement's purpose was to detect how much the current is drifting if we apply higher and higher currents.
- In LRS I see that it drifts at around 600-700 mV. Asthe current is increasing the slope of the average current is also. At highest it's 8.62%. The drifting is the same like in the nonlinear measurements.
-There is a strange flick at the start of the measurements over 500.

## 2024.03.19. Julich samples, Nth measurement - Matteo

### MT M03p50 again

#### Noise again

- Card (5e7 gain) : -0.0692141 mV, Agilent : -0.137436 mV, Card (changeable gain): 0.0273034 mV,
- to 500 mV, 1000 mV , 1500 mV with 100 steps(20s, and 2s for the biggers). The condensator of the current gain broke down.
- We see that the sample is switching on higher currents over time.

## 2024.03.18. Julich samples, Nth measurement - Matteo

### MT M03p50

#### IV

- IV 15 Stability HRS, IV 18 stab in LRS. IVs in 19.

#### Noise

- Card: -0.283573 mV, Agilent : 0.0356573
- Did noise with many setup. Tomorrow will do the eval.

## 2024.03.14. Julich samples, Nth measurement - Matteo

### MT1 N03p50

#### IV measurements

- the plan is to make stabilty measurements on the sample. Starting with around 30-40. FULL IV.
- IV14 Contact. IV19 stab in LRS. 6e-6 is with 1V, 1s. Probably killed N03p50 with 5V. Switching

### MT1 P03p50

#### IV measurements

- IV 43 contact, Full. Switch stab in IV58, LRS IV59, HRS IV61. -1,5e-6 A is HRS, LRS is -5e-6 A. 30 Full in IV64. Switching to noise

#### Noise

- Card : -0.083298 mV, Agilent 0.198055 mV
- Everything is good. LRS HRS LRS HRS. WEnt expectred

#### Doing nonlinear measurements

- IV Setup, test time stability,IV69
- Wont copntinue nonblinear measurements. Successfull, 1.5V made it switch.

## 2024.03.12. Julich samples, Nth measurement - Matteo

### MT1

#### Noise

- Setup. Card offset : -0.0987745 mV, Agilent 0.258328 mV,
- Measuring without any switching, default should be HRS.
- Measured the following chips with zero switching in HRS.
N03p100, O03p100, P03p100, P03p50, O03p50, N03p50
All was successful. N03p100 was weird, and the results on P03p100 was also weird. Measured in 1e4 gain all p100, while 1e6 gain all the p50s.

### MT1 N03p50

#### Noise

- After the zero shot measurement, I made two Full switches and measured noise in LRS twice. The second two Fulls were in 1e4 gain while I set 1e3 in the program.

## 2024.03.01. Julich samples, Nth measurement - Matteo

### MT1 K09p100

#### IV

- Success conduct. (IV4). Stability in HRS IV18. IV 16-17 RESET-ing. After measuring it with neg voltage many times, the Normal measurements(1V, 1s, full) bottom left (2.5e-5 A) has rised to a more stable state. LRS is -2.5e-5 A. Hrs's lowest state is (what i could achieve) -8e-6 A. Full cycle is stable, starting the noise in LRS. The on off ratio is roughy 2-2.5-3. IV27-33.

#### Noise

- Setup Card offset: -0.097008 mV, Agilent offset: -0.143239 mV
- LRS was stable in the device (ser01) after resetting I lost contact, tried to move the contacts 3 times, no result.

### MT1 K09p20

#### IV

- LRS -8e-7 A,  HRS = -4 e-7 A., on/off is roughly 2.

#### Noise

- Start in LRS (ser01). Died after LRS.

### MT1 J08p100

#### IV

-// Success conduct. (IV4). Stability in HRS IV18. IV 16-17 RESET-ing. After measuring it with neg voltage many times, the Normal measurements(1V, 1s, full) bottom left (2.5e-5 A) has rised to a more stable state. LRS is -2.5e-5 A. Hrs's lowest state is (what i could achieve) -8e-6 A. Full cycle is stable, starting the noise in LRS. The on off ratio is roughy 2-2.5-3. IV27-33.// NOT TRUE
- IV25-55. around 10 switch.

#### Noise

- HRS noise in (ser01,ser03). LRS noise in (ser02,ser04). I think that the connection between the gain and the probe station was the leaky, and didnt after changed it to a normal bnc cable, it worked.

### MT1 J08p50

#### IV

- Success conduct. (IV111). HRS/LRS -2.5e-6, -4e-6 (A). on off roughly 2.

#### Noise

- LRS noise in (ser01). HRS noise in (ser02).

### MT1 K09p50

#### IV

- LRS -4e-6 A,  HRS = -2 e-6 A., on/off is roughly 2. Stab in 128. RESET 129, stab in HRS 130, SET 131, stab in LRS 132

#### Noise

- Start in LRS (ser01). Next in HRS (ser02), the filter wasn't turned on

### MT1 J09p20

#### IV

- First I catched the p50 sample, but then I could catch the p20. The switching was nice and stable, I_LRS(@-1V)=-1e6, I_HRS(@-1V)=-2e7.

#### Noise

- Start in LRS (ser01). The noise seems very low :( I fitted the PDSs, but they are rather theoretical fits, because I used only the few first points. After ser01 I made 2-3 full cycle and a reset. They were nice and then I started a noise measurement in HRS with higher gain (1e7). The noise was measurable and I could fit the PSDs. I switched back to LRS, the IVs are nice. I tried a new noise measurement (ser03) with the LCA amplifier. I didn't make a proper offset compensation, but checked it and the offset wasn't bad. The noise was higher than before, it is closer to the trend, but still below it.

## 2024.02.29. Julich samples, Nth measurement - Matteo

### MT1

- Test IV on 100s.

### K08p100

- IV_02 successfull contacting. LRS = -8E-9, HRS = -4E-9, On/Off Ratio = rouhgly 2, Switching voltage = +-3V, 1s. Stable. Stability check from IV19-23.
- Switching to noise setup.

#### Noise

- Card offset : -0.117204 mV, Agilent offset : -0.248276 mV,
- Starting in HRS state (ser01). The first HRS in (ser01) is without the +-500mV in the end. The second is longer and contains it.
- Switching to LRS. Couldnt set it with -3V. Switching to IV setup.
- After some measurements the LRS/HRS switched to  LRS = -20E-6, HRS = -8E-6. The (ser02)'s measurements are unknown whether they are LRS or HRS.
- The first (ser01) measurement was in 1e6 gain, and it went to overload, which made the position weird on the map.

## 2024.02.07. Julich samples, Nth measurement - Matteo

### MT1

- calib. card : -0.0707422 mV,  agilent offset : -0.0608005 mV

### K08p50

- Starting to measure K08p50. couldnt contact. Going back to it after consulting with Zoltan, had the contact and starting measuring it. LRS, HRS is 2e-6A, 4e-6 A, the same around 2 ratio like the previouses. LRS is in (ser01), HRS is in (ser02).
- Done fitting for all the prev measurements. L10p50ser01 fitting is bad really, need to check it with Zoli.

## 2024.02.06. Julich samples, Nth measurement - Matteo

### MT1

- card -0.0967912 mV, agilent is essentially 0.

### L09p50

- Accidentally, I did the first measurements with open cab, and lights on. DELETED it.
- Had some very strange noise measurements. LRS is in (ser02)
- HRS is around 4e-6A, LRS is around 8e-6 A. After noise HRS/LRS moved to 3e-6, 4e-6 A. Moving to another 50 sample.

### L10p50

- L10p50 LRS state is 4e-6 A, HRS is 2e-6 A. Ratio is around 2., did the hrs and lrs noise measurement. The eval comparing to the others is left.
- HRS is in (ser01), LRS is in (ser02)

## 2024.02.05. Julich samples, Nth measurement - Matteo

### MT1

- Card Offset : -0.045904 Mv, Agilent Offset : 0.13 mV
- the plan is to search for contact on a 20 and 100 sample ({\mu }m)
- Just found out that the norma setup's cable is sending the same voltage after the measurement has stopped.c

### L08p100

- Couldn't contact 20, L08p100 is successfully contacted. 460 resistance, (sweep 0.5V, 0.1s Min: -8*e-4 A, Max: 1e-3 A)
- base measurement(5 sweep) is looking stable
- switching on pos 0.5V (RESET), HRS state is -3.5e-5 A Min (0.5V, 0.1s) IV_26

### L09p100

- probably killed the sample with -1.5V. Go to L09p100. Contact success. IV37. Base 5 looking stable, -1.5e-5 A on 0.5V sweep, RESET on 1.5V pos, -2.5e-5 A on min, stable
- SET on -2V.
- after some steps it went out from e-5 A to e-6 A. IV68 Going to a "known" 50 {\mu}m. L09p50 conduct success IV79

### L09p50

- +3V is RESET, -3V is SET, 1s, Base state is SET which is HRS. HRS is -2.25e-6 A - -2.7e-6 A min. LRS is -4e-6 A - (-5e-6 A). The HRS/LRS is around 2. Both state look stable.
- Setting up the noise measurement. The agilent has a lower step of 0.5 mV, and a 0.10-0.15mV minimum agilent error. It's okay if you measure it back.
- Starting with IV, base was LRS state. measured is -4e-6 A. RESETing device.
- When formatting, I need to watch out to change the amplifier. Failed the first reset, second was good. Failed the amplifier constant change in the measurement program. Doing HRS again. Switching was good. Recreating the measurement file for noise, because we change from 0-1v-0-(-1v)-0 to 0-500mV-0-(-500mV)-0 . I forget to change filter when doing IV.
- The sample again moved from 2e-6A to 3e-6A while doing measurement, even though We lowered to 500mV.
- Went off for two hours. The HRS is -3e-6 A, while the LRS is -6e-6 A. Zoltan created a switch for the easy change of the amplifier's state, and it sent the amplifier to overload. Now it makes sense why the other sample went off a couple days ago. Changed it, and now the Non-Conducting state is actually grounded. After the overload I measured a change in the LRS, HRS that is described above.

## 2024.02.01. Julich samples, third measurement - Matteo, Zoli

### Recreate the measurement made yesterday

- IV_Block 5 looking stable, higher current amplifier makes less noise on the stable measurements., IV6 is with higher 1e6 current amplifier.
Noise:
- Card offset -0.090654 mV , Agilent offset:0.269617 mV
- Start measuring with an IV. Noise, IV, SET, IV Noise, IV RESET.
- IV is looking good. Start noise measurement in HRS (ser03), then LRS meas (still in ser03), but it was bad. Restart because didnt switched the capacitor. the first HRS iv's bottom is around -2e-6 A, and the LRS is around -4e-6 A at 1 V. The HRS after the noise is slightly higher at -3e-6 A. Noise on LRS (ser04), the HRS meas in this folder is also bad. Restart because didnt switched the capacitor.
- From the evaluatioin we see that 1V is making the sample switch. Next time will measre with fix LCA.

## 2024.01.31. PCMO samples from Julich, second measurement

Start with MT1, test IV.

### L06p50

#### IV

Test IV is good on 0.5 V.
Cannot switch, at -3V the resistance is good according to the reference measurement, at +3V it’s half of it.
Characteristics is similar on the IV to the reference measurement. Top electrode is the ground (4), bias is the bottom electrode. Positive voltage RESET, Negative is SET (3V, 1s). HRS/LRS is around 2.5. Similar to the ref. measurement. Starting from (IV_35) in HRS. IV_36 SET, IV_39 RESET, others are stability measurements. States (HRS/LRS) are looking stable on low bias measurements (0.1s, 1V, 5 times).
Switching to noise measurement.

#### Noise

Measure offsets. Card offset: -0.0901297 mV, Agilent offset:0.419638 mV
Noise measurement in HRS (ser01), nice noise results. Continous IV measurement with the noise setup, overload when SET state.
After changing gain, we measured no contact. Anomaly accoured, no contact on the sample, anomaly in the measurement setup also, last measurement was good when measuring back the measurement setup.
TBC. 5hr passed.
Continuing measurement on MT1L06p50. Anomaly solved by experiencing that the chairs in the new lab are charging us. The sample died in ESD.

### L07p50

#### Noise

We made the following procedure. While always wearing the blue hand band. With the noise setup we did the following.
IV, Noise, IV, SET, IV Noise, IV, RESET, IV
We used the IVs to see that we are on the right switch .( referencing the normal conducting setup).
The noise on the L07p50 had a small 50Hz due to our system, we didnt experienced that in the L06p50 previously today. When changing IV and Noise, we need to change the filter also.
First noise measurement in LRS (ser01), then continous IVs (in LRS/HRS and reset, folder is still ser01). Noise meas in HRS (ser02).

## 2024.01.24. Első mérés az új PCMO mintákon

Chipek elnevezése MT1; MT1p5; MT2, rendre 1nm, 1.5nm és 2nm vastagságú rétegeket jelölik
Measuring MT1p5.

### H06p100

#### IV

Nagy kezdeti ellenállás, ez megfelel a várakozásoknak. Mérhető IV görbék (IV_69,70). Megpróbálunk még az érintetlen állapoton zajt mérni.
A zajmérés után megpróbáltuk a kapcsolást, felső tű a + elektróda, az oldalához nyomott tű a föld (-).
!!!!Igaz de fordított, mint az utánna valók!!!
 Ebben az elrendezésben azt tapasztaltuk, hogy pozitív irányban kapcsol be, negatív irányban pedig ki. 2.5-3.5V amplitúdóknál látszott kapcsoló jelleg, de nem volt túl nagy az ON/OFF arány. Kb 2-es faktor lehetett és nem volt szimmetrikus OFF-ON irányba nagyobbat kapcsolt. A rendszer viszont kevésbé tűnt volatile-nak.
Sajnos elfogyott az idő, így itt befejeztük, de ígéretesnek tűnik.

#### Zaj

Offset kompenzálás még az előző mintán történt, ezt használjuk. Card_offset=-0.0727059mV, Agilent_offset=0.57777mV.
Cél sima hosszú platós zaj 100-200-500-1000mV fel-le +- irányba nagy szűrővel (20s görbék).
Első zajmérés (ser01) sikeres, de nagyon nagy volt az 50Hz., ezért nem értékeltük ki. A problémát a probe station elmozgatása megoldotta és a második (ser02) mérésnél nagyon szép lett az alapzaj, kb 50Hz mentes. Ezt kiértékeltük, kicsi volt a zaj, de mérhető. A 100-200mV-os görbéket nem fitteltük, mert közel voltak az alapzajhoz, 500-1000mV került mentésre. Ezek ígéretes eredményt adtak, a zaj kisebbnek tűnik, mint a régi PCMO-nál.

-------------------------------------

# Old

## 2024.01.24. Mérés Matteoval betanítás céljából Régi PCMO-n

### D06p100

Van mérhető ellenállás, de elég kicsi, 25Ohm. Megpróbáljuk az inicializálást, de túl kicsi az ellenállás, telítésbe viszi az erősítőt 1e3-ban is, így inkább másik mintára megyünk át.
Megj.: elképzelhető, hogy meg lett terrorizálva a tűvel

### C07p100

Szintén kicsi ellenállás ~36Ohm, inkább másikat keresünk. Közben láttuk meg, hogy ez már pirossal van jelölve

### E06p100

Ennek is ~35Ohm az ellenállása, ez sem annyira ígéretes, de azért megpróbálok kiadni egy 2.5V IV-t. Nem sikerül, másik minta jön.

### G07p100

Túl kicsi ellenállás

### F07p50

Túl kicsi ellenállás

### E06p50

kezdeti ellenállás 65 Ohm, init test
Init sikerült , 2.5V 1s beállítással (IV_12)
Telítésbe ment 0.1 mp-n, viszont 1 s-en sikerült.. Ellenállás 500mV-nál 2.5MOhm

### IV

Kapcsolás próba 0.01s hosszú -3/2.2V jellel (IV_25). 1e6-ban telítésbe megy, így levesszük 1e5-be. Még mindig telítésbe megy a negatív oldalon (IV_26). Mutat valamennyi kapcsolást, stabilnak is túnik. 5 görbés IV (IV_28). LEvettük a negatív amplitúdót 2.7V-ra, így már nincs telítés (IV_29). Szép görbék. Stabilnak tűnik 5 görbe egymás után (IV_33). Az IV görbéken látszik némi kapcsolás/hiszterézis, de kis feszültségnél nem válnak szét, illetve nem tűnik igazi kapcsolásnak (steady state ellenállás mintha nem változna).

### Zaj

Sajnos nem sikerült, mert közben meghalt (kis ellenállásba ment) a minta

2022.10.07. Teszt zajmérések 1MOhm-mal a probe stationben
Áthoztam a zajmérő setuphoz a Botilaborba a probe station. Boti (nagyfrekis setuphoz készített) régi nyákjára  forrasztottam rá egy SMD 1 MOhm ellenállást, aminek egyik vége kontaktálva van SMA-csatlakozóhoz, és a másik végét kell tűvel kikontaktálni.
Offsetelést elhanyagoltam.
Irtó zajos.
2022.10.18. Teszt zajmérések 1MOhm-mal a probe stationben
Árnyékolással probálkozom: probe station fakeretes “doboza“ köré alufóliát tekerek, és azt teszem rá a setupra. Kb. semmit nem javított a külső árnyékolás.
Ha ellenállásdobozban lévő 1MOhm ellenállást sorba kapcsolok, a tűket összeérintem, akkor szép, külső zajoktól (50Hz-től) mentes PSD-ket tudok mérni. Ha az SMD 1MOhm-ot kontaktálom ki a tűkkkel, akkor rendkívül zajos a mérés.
2022.10.20./24./25. Tesztmérések
Probe stationben irtó zajos, nem nagyon tudom átalakítás nélkül eliminálni. Tesztmérés a Maciban: SMD 1MOhm-ot egyik oldalról tűvel, másik oldalról a nyákra forrasztott BNC-vel kontakálok ki. Ezzel az elrendezéssel elérhető a termikus szint, de mind az alacsony, mind a magas frekvenciákon megjelenik zaj.
2022.11.16. Tesztmérések a probe station árnyékolásával
Műhelyben készítettünk egy alumíniumdobozt Faraday-kalitkának, itt-ott vannak rajta lyukak. A lyukak maximum a magas frekvenciákon számítanak (hullámhosszal jobban összemérhető). Alacsony frekin van a gond, durván erős az 50 Hz. Ennek árnyékolása már nem magától értetődő, skin-mélység, EM hullám mágneses komponensének árnyékolása is megfontolandó.
Néhány mérés ellenállásdobozzal sokkal jobbnak tűnik, de Zoli szerint túl nagy az 50 Hz így is, ezért lehet, hogy a setuppal van inkább a gond, ami ilyen ellenállás-tartományban jobban zavaró, mint a “hétköznapi“ memrisztorainknál.
2022.11.21. Tesztmérések ellenállásdobozzal, a setup variálásával
Különböző ellenállásdobozoknál az 50 Hz is más mértékben tűnik megjelenni (100 kOhm-os ellenállás mérésekor). 1MOhm-os ellenállást mérek, a setup minden elemét (kivéve adatgyűjtőkártya) egyenként kicserélgettem, nagy hatást nem értem el vele. Nem tűnik sem az Agilent, sem az adatkártya hibásnak. Úgy néz ki, hogy az egyetlen tényező, ami számíthat, az a kábelek hossza és elhelyezkedése.
2022.11.22. Kábelek szerepe
Tesztelés egy Hammond-dobozba forrasztott 10 MOhm ellenállással, GAIN=1e8. A teljes rendszerben csak az kábel hossza számít, ami a mintáról megy a Femtóba. Amikor az közvetlenül BNC-toldóval megy, akkor eltűnik az 50 Hz.
BNC-toldós setup tesztelése különböző dobozú 100kOhm ellenállásokkal. Úgy néz ki, nem mindegy a doboz sem, de nagy különbség nincsen. Nagyon rossz, amikor az ellenállásdoboz küldeje nincs összeföldelve a BNC földjével, hanem lebeg.
Probe station tesztmérések az előző mérésekből tanult infók alapján. 50 Hz nem tűnik el, a doboz valószínűleg nem árnyékol kellőképpen.
Maci tesztmérések a Femto-val, hogy javítana-e, ha betennénk a Femtót a setupba, és a lehető legrövidebb úton jutna a jel a mintáról a Femtóra. Amikor a Maci környékén mérek, nem olyan csúnyáka mérések. Egy nagyságrenddel kisebb az 50 Hz-es csúcsom most, pedig a Femtóra menő kábel irtó hosszú, és az asztalon kóvályog.
Probe stationt az asztaltól messzebb, a földre tettem, ott kisebb az 50 Hz. Sok tesztmérés volt, nem teljesen konztisztensek. Érthetetlen módon olykor szinte teljesen eltűnt az 50 Hz, de semmilyen módon nem sikerült reprodukálóan előidézni ezt. Volt, hogy ez a Faraday-kalitka nyitott állapotában történt, ezért én arra gyanakszom, hogy a környezeti 50 Hz változott meg esetleg. Estétől reggelig 8 mérést indítottam el a setuphoz való nyúlkálás nélkül, ezekben viszont nem látszott semmiféle változás.
A zaj az eredeti állapothoz képest azért sokat javult, az 50Hz már nem olyan magas, ezért ha a minta zaja kiemelkedik az alapzajból, akkor ez működőképes dolog lehet.
2022.11.23. Első mérések a BSC6 mintával: A01, B01, C01 100umx100um
D:\Data\Memristor\22_11_23
Kontaktálás probe stationben, asztaltól távolabb. A negatív pólus kell legyen a Pt elektróda, ami a minta szélén van. Először a két tűt erre a felületre tettem, hogy megbizonyosodjak róla, hogy jól kontaktálok. Aztán a pozitív pólust áttettem a legnagyobb padre, 100x100 mikron. Figyeltem live módon az ellenállását a programban, hogy mikor lesz értelmes. Közben mikroszkópot is néztem. Az értelmetlen ellenállásból egyszer hirtelen egy nagyon kis ellenállás lett. 100 Ohm-os nagyságrendben. Aztán kipróbáltam azt, hogy a Femtót a legnagyobb erősítésbe tettem, és figyeltem, hogy mikor megy telítésbe.1e9-ben ez 100 mV-os biasszel 10 MOhm alatt történik meg.  A mikroszkópot itt csak addig néztem, amíg közelítettem, utána ki is húztam az erős 50 Hz-es zaja különben telítésbe vinné az erősítőt.  A lehető legközelebb vittem mikroszkóp alatt, ahol még szakadás volt, és nem kapcsolható semennyire sem. Aztán a legnagyobb óvatossággal közelítettem, lassan a tűt, és amin elkezdett jelezni a Femtó, megálltam. Itt is ez volt az eredmény, hogy 100 Ohm-os nagyságrendbe ugrott egyből.
Az ellenállás amúgy erősen driftel, anélkül, hogy bármit tennék. Ezen felül mechanikailag is elég érzékeny, már néha arra is óriásit változik, hogy megérintem a mikromanipulátor tekerőjét...
Ebben a 100 Ohm-os nagyságrendben amúgy valamiféle egyedi kapcsolásokat tudok csinálni, de nem reprodukál és nem konzisztens.
2022.12.01. Kontaktálás más tűkkel, H01.100
D:\Data\Memristor\22_11_23
100 um-os Au-vezeték végét ollóval ferdén megvágtam, azt tettem be a volfram tűk helyett. Ugyanazt tapasztaltam, mint korábban, szakadásból hirtelen 100 Ohm alatt.
!! Kipróbáltam, hogy mi történik, ha a mintákon kívülre teszem a negatív tűt, de nem a minta legszélére a vonalon túl, ahogy eddig. Ezen a területen eddig azért nem dolgoztam, mert ha ez lenne a Pt elektróda, akkor kettő tű rajta rövidzárba benne, és ezt nem teszi.
Viszont eközött, és a minta teteje között mérve valamiféle viszonylag nagy, de mérhető ellenállás van, mintha talán kapcsolásféleséget is produkálna. Erősen látszik egy mechanikai instabilitás. Ezt két másik mintán nem sikerült reprodukálni.
2022.12.06. AFM-kompatibilis mintatartó és első mérések AFM-mel (F08.100)
Probe station talán túl durván kontaktál, eért próbáljuk meg a coductive AFM-mel. Tervezés, bondolás a laborfüzetemben.
100x100 padek.
Hasonló ellenállástartomány közvetlenül a kontaktálás után.
Instabilitás itt is jelentős.
Topográfia mérések alapján próbáltuk összerakni a pontos mintafelépítést. minta padek alatt van az Al, és a PCMO közös.
0.3-0.4 N/m-es tűvel kontaktáltunk, ez sem segít a stabilitáson
Beállított: 40 N/m rugóállandóval, 20-60 nN-os approach. (Ennél két nagyságrenddel kisebb volt a valós erő.) Ez irtó pici.
Németeknek írt e-mail -> nem biztos, hogy rossz tartományban vagyunk a ~100 Ohm-okkal, innen is akár lehet kapcsolni. Könnyebb a kisebb padet kapcsolni. Meg használt a chip, előfordulhat hibás/elhasznált minta.
2022.12.13. AFM-mérések 2.0
C4 cantilever: adatlap: 0.4 N/m, ~30kHz
J11.100 setpoint: 5 nN, no resistance measured
F08.100 (last time this sample was measured), setpoint: 1nN
no resistance reached
A bondvezeték jónak tűnik, talán a cantilevernél van esetleg valami kontakhiba. Ezért tesztelünk egyet a minta szélén soros ellenállással.
Gyanús, hogy a hiba a mintától független, az AFM-fejben van, de a cantilever chip és a kábel vége összesípol.
SMD-ellenállásokkal teli tesztmintán sem sikerült kontaktálni. Setpoint maximum 100 nN volt.
Kantilevercsere
C3: 0.36 N/m, programban 0.4 beírható
SMD-tesztmintát tisztítottuk és utána új mérés. Olykor-olykor felvillan az ellenállás scan közben. Néha hosszan stabil. Úgy tűnik, elég fontos, hogy ki legyen szintezve és jól legyenek beállítva a PI-paraméterek. De nem tökéletes. setpoint: 30-150 nN
Aranylapkás tesztmintán + Rserial hasonló módon nem egyértelmű, hogy elértük a felületet. Egyáltalán nem is láttunk közel Rs értéket, csak a szakadás. A minta elég ferde, ez esetleg okozhat nehézséget, de legrosszabb esetben arra számítanánk, hogy belenyomjuk a tűt, és akkor a pásztázás nem működne jól, de a az ellenállásban kéne ezt látni.
2022.12.14. AFM-megbeszélés Semilabosokkal
Szénszálas minta Semilabból, azzal sem látunk semmit. A kantilevert gyanúsítjuk, lekopott a vezető réteg?
2022.12.15. Last hope
Dec. 6-ai mérést minden szempontból reprodukálni szeretnék:
program: 40 N/m, setpoint: 60 nN
soros ellenállás: 100 Ohm (erre nem emlékszem)
Tű: C7 (friss), ESD-védelemmel szerelve
H08.100
200 Ohm-os kezdeti ellenállás, néhány IV, majd szakadás 1.7 V-os meghajtással. Talán csak nagyobb ellenállásba kapcsolt, ami az 1e3-ban nem látszott. Nem tudtuk visszanyerni az ellenállást.
H08.50 és H07.100 közelítésekor ugyanígy nem működött.
H betűnél szkenneléskor olykor felvillan az Overload. Hasonlóan, mint korábban, mintha mikor oldalról nekiütközne a lépcsőnek.
Instabil ellenállás, hasonlóan a dec. 6-i méréshez.
Hangszigetelős fakeretet rátettük az AFM-re.
Bizonyos helyzetekben látunk ellenállást akár percekig, de stabilizálás nem sikerül. Erőt 120 nN-ig felnyomtuk, nem javította meg.
I08.100, semmi
Tűcsere, C8
I08.100, 200 Ohm elsőre, és talán még sosem volt ilyen stabil
Nagy k-jú tűt kéne mindenképp.
2022.12.16. Reprodukálás, new hope
I08.100
SAM szoftverrel közelítés, k=40 N/m
60 nN: után ingadozó ellenállás, hol van, hol nincs. De ez lehet stabilitási probléma.
80 nN: semmi
másik pozícióban 80 nN: gyenge, de néha van kontakt
ScanTool szoftverrel, Andris egyik régi mérése alapján: szénszálas kalibrációs minta
k=1N/m, setpoint:2nN
bias: 50 mV, mért max áram 20 nA (lehet skálázási hiba itt)
BSC6 mintára, I08.100-ra közelítés: k=1N/m, setpoint:1nN majd 2 és 3 nN, eleinte néhány pont, majd semmi
error signal zajos, felülettartással is lehet gond, zajos a bending jel
4nN: eleinte látunk valamit, aztán semmi, majd később magától beáll 250 Ohm környékére
erő növelésével növekvő áramjelet látunk, instabil. Talán a minta felülete nem elég tiszta.
cél: felületszkennelés párhuzamos áramméréssel, 100 mV szénszálas mintán
nincs kontraszt a szénszál vs szigetelő felület között. Gyanús, hogy a tű elromlott, túl nagy erővel nyomtuk a felületnek. A topográfiai kép sem olyan szép, az is magyaráható lenne ezzel.
Ha így van, akkor a tű még az eddigi feltételezéseinkhez képest is érzékenyebb.
Teszt a BSC6 mintán, hogy ott sem működik, így akkor nagyon valószínű, hogy a tű meghalt.
2022.12.19. No feedback AFM stability, BSC6
AFM közelítés után lekapcsoljuk a feedbacket, és stabilabbnak látjuk mind a bending jelet, mind az ellenállást. Ezen kívül nem pásztázunk a tű megkímélése érdekében.
Scantool szoftver: 1 N/m, setpoint néhány nN-nál.
I08.100
IV-mérés. Reset 2.2V meghajtásnál, utána nagy ellenállást látunk, valami kapcsol. Erősítésnövelés, majd újraközelítés. Nem látunk semmit.
Növelés az IV amplitúdóban, a bending jelben egyértelműen látszik.
I09.100, valami megaOhm környéke látszik, fura kapcsolás is?
I10.100, semmi
Konklúziók:
AFM stabilabb lehet feedback nélkül. Feedback mellett erősen PI-paraméterek függvénye.
Tűt koptatja a szkennelés, ezt ma egyáltalán nem csináltuk.
IV-méréseknél, a ending jel -0.2 V környékéről indultunk. Minden IV után akár 20-40 mV-ot is csökkent. (Ezt a feedback valószínűleg állandóan visszahúzta volna, ami nem biztos, hogy jó/rossz?) Erő is párhuzamos növekedett, végül már -0.6 V körüli bending jelnél voltunk.
A cikkben olvasott RESET fesz kb. felénél láttunk egy nagy kapcsolást. Előfordulhat, hogy a tűt gyilkoltuk le. A kapcsolás kb. 5 mA körüli áramnál történt.
Összegzés eddigi IV adatok alapján (2023.01.03.)
Minden “hasznos“ adatot tartalmazó IGOR fájl: kockagép "D:\Data\Memristor\22_12_19\Experiment.pxp" és "D:\Data\Memristor\22_12_19\BSC6_first_switchings.pptx"
2022.11.23.
probe station
A01.100, B01.100, C01.100
kis nemlinearitás, nem konzisztens kapcsolások, IVB_118 nagy kikapcs.
2022.12.01.
probe station
I01.100, J01.100
apró kapcsolások, telítlés
2022.12.06.
AFM
F08.100
nagyon durva zaj, látszik valami alatta, de használhatatlan
2022.12.15.
AFM
H08.100, H08.50, H07.100, I08.100
nagy kikapcs: IVBlock_5 és 60
2022.12.19.
AFM
I08.100, I09.100, I10.100
IVB_20-46 növelgetett IV, majd nagy kikapcs.
2023.01.31. BSC6 IV switching
C07.100, D07.100, F08.100
Baromi lineráis IV kb 80-100 Ohmnál, változóan instabil, nem sikerült kapcsolni.
R12.100
Minimális eltérések a linearitástól, de nem elég a feszültség, amit a Femto telítése miatt megengedhetünk magunknak.
R12.50
Kapcsol!
Konklúziók:
Probe stationnel nem kell annyira félteni a mintát, nem olyan könnyű átszúrni. Viszont az erősebb kontakt segít a stabilitáson (cserébe az ellenállás is erősen csökken). A tű belenyomásakor nem csak erősebben nyomjuk a mintát, hanem meg is csúszik a tű, de ez optikai mikroszkóp alatt nem hagy látható sérülésnyomot-
Az AFM-nél is 100 Ohm-os nagyságrendet láttunk, ezért most már abból indulunk ki, hogy ez normális, és inizializálni kell csak a mintát. A németektől megtudtam, hogy a 100-as pad-en ez nem mindig működik könnyen technikailag (túl nagy áram kéne már neki).
Az 50-es padet könnyebben ki tudtam kontaktálni úgy, hogy nem féltettem annyira a mintát.
kapcsolást tudtam 1e4-es erősítésben csinálni a cikkben szereplő -3 / 2.2 V sweeppel. Idővel még lehet játszani, mintha lenne hatása. Az ON és OFF ellenállások 1e7-esben nézegettem meg: 2-2.5 MOhm / 4-6 MOhm, -500 mV-on (pozitív irányban nem volt ennyire eltérő, ami megfelel a cikkben leírtaknak).
2023.02.01. BSC6 noise, R12.50
Átvittem a teljes setupot az optikai asztalra, de elsősorban az 50 Hz kiküszöbölése miatt, mert a mechanikai instabilitást az erősebben belenyomott tű megoldotta.
Nem ofszeteltem
Agilenttel néhány IV.
Optikai asztalt földeltem, de bénán, majd meg kell csinálni jól. Zajmérés 1e6-ban -500 mV-on (ON-ban).
2023.02.02. IV-k különböző időkkel és zajmérések, Q12.100
Ofszetkompenzáció, 1e6, szűrő nélkül:
Card: -0.535121 mV, Agilent: 2.2 (2.249) mV
R12.50-et nem sikerült újra kikontaktálni. A Q12.100-at viszont igen, és méghozzá sikerült inicializálni is. Láthatóan kisebb ellenállása van, mint a tegnap R12.50-nek, ami a felületarányosságból logikus.
IV-mérés: 100us, 1s, 10s, 100s. Egyre kisebb kapcsolás a növelt idővel, majd visszafele, csökkentve az időt ez nem fordult vissza. Mintha fáradna a kapcsolás, nem igazán lehet visszahozni stabilna a régi kapcsolást.
IV_noise mérés, kis szűrővel 1500 mV-os amplitúdóval, 1e6-ban.
2023.02.07. zajmérések, Q12p50
Ofszetkompenzáció, 1e6, szűrő nélkül:
Card: -0.520177 mV, Agilent: 3.1 (3.13041) mV
Q12p100
Nagyon magas ellenálláson van. Lehet, hogy degradálódott?
Megfigyeltük, hogy ez a minta is negatív feszültségen inicializálódott, talán ez összefügghet a romló kapcsolással.
Q12p50
Inicializálás 0.01s-os, 2.5 V-os háromszögjellel. Egyből ezzel a feszültséggel, mert eddig lassanként növelgettem az amplitúdót, és akár ennek is lehetett köze a negítav inicializációhoz.
Elsőre működött: 400 Ohm-ból (-500mV-on mért) 6-700 kOhm -ba kapcsolunk. Utána 10 IV, megint nem olyan stabil, de inkább mérek zajt, aztán játszom az IV-vel.
ser01
Kettő kis IV, abból látszik, hogy nincs kapcsolás, se telítés 500 mV-ig, majd kettő 100 mV-os lépésközzel IVnoise, platónként 10s, nagy szűrővel mértem.  Átkapcsolás OFF-ba, félIV negatív irányba 10us-os teljes IV-hosszal.
MAPPA
MÉRÉSEK
SZŰRŐ
ERŐSÍTÉS
1_ON
2x IV, 2x IVnoise 500 mV
VAN!
1e6
2_RESET
RESET félIV
nincs
1e3
3_OFF
2x IV, 2x IVnoise 500 mV
VAN!
1e6
4_SET
SET félIV
nincs
1e3
5_ON
2x IV, 2x IVnoise 500 mV
VAN!
1e6
6_FULL
3x fullIV 10us
nincs
1e3
Elrontottam, mert az átkapcsolásoknál nem váltottam erősítést…1e6-ban mértem, és hamar telítésbe ment. Így is volt valamiféle kapcsolás, de nem jó…
ser02
Előzőek ismétlése (kis IV-k nélkül), és jó erősítéssel + kezdeti full IV-méréssel (0_FULL)
Full IV-k végein furaság van. De ezen a ponton már nem volt erőm debuggolni, inkább végigmértem az egészet.
2023.02.08. IV-mérések, Q12p50
Cél az ellenállás hangolása, meg a stabil kapcsolási paraméterek megtalálása.
Konklúzió: a cikkbeli -3/2.2 V nem feltétlenül stabil, egyre nagyobb ellenállás felé vándorol. Ezért  csak a negatív oldalt, a SET-et növelem meg, és úgy sikerül találni -3.5/2.2 V-on stabil kapcsolást.
Elképzelhető, hogy a cikkben differenciális ellenállást adnak meg, és lévén, hogy erősen nemlineáris az IV, ez nagy különbséget jelenthet a sima U/I ellenálláshoz képest.
Ma megint látok egy furcsa dolgot, ami múltkor is megjelent. Kapcsolgatok, minden rendben, majd egyszer az egyik SET-nél az ellenállás irtóra lecsökken, 80 Ohmra. Az inicializálás előtti ellenállás ennél nagyobb volt, ez inkább a 100-as pad kiinduló ellenállására emlékeztet, de a tű továbbra is jó helyen van. A múltkorihoz hasonlóan úgy oldom meg, hogy felemelem a tűt és újraközelítem, oldalazok is kicsit, és így végül megint a nagy ellenállásban vagyunk.
2023.02.09. IV, ON & OFF zaj
Ofszetkompenzáció, 1e4, szűrő nélkül:
Card: -0.482831 mV, Agilent: 2.9 mV
Sok minta nem inicializálható: T03.100, T03.50, U03.100, U03.50, U05.100, U06.100, kezdeti ellenállások 50-70 Ohm
U03.20
Kontaktálási módszer: tűt merőlegesen húztam a padekre, hogy az ellenállásban egyértelműen látszódjon, hogy mikor vagyok paden, és mikor szigetelőn. A harmadik pad a 20-as kell legyen, a kezdeti ellenállás néhány száz Ohm volt.
Sikeres inicialziálás, de nagy ellenállásban vagyunk.
Megint hibás az Agilenttel mért IV (nem meglepő, mert múltkor nem oldottam meg…). Kapacitásra utaló jel van, a mérési idő megnövelésével lecsökken az effekt.
A tesztelés után megint elvesztettem a kontaktot, leesett az ellenállás. Egy inicializálást próbáltam, de tovább esett tőle az ellenállás. Megint azt látom, hogy ilyenkor instabilabb mechanikailag is. Megigazgatom a tűt, ellenállás 600 Ohm fele megy fel, inicializálás működik.Vajon még mindig a 20-as padon vagyok? Szerintem igen.
Egy furcsa kapcsolás, amúgy kapcsol megint. Aztán amikor erősítést váltanék elveszett a kontakt, 50 Ohm.  Inkább másik mintával érdemes próbálkozni, ez túl kicsi a tűnek... Azt is biztosan látom már, hogy elég gyakoriak a problémák, amikor az erősítőt lehúzom a váltás miatt.
U05.50
Negatív oldalon inicializálás. Utána nehezen találok stabil kapcsolási paramétereket. -3.8/2.2 V, 0.01 s egész jónak tűnik. De játszok vele sokat, és el akarom érni, hogy 1 s-mal is találjak jó értékeket. Növelem a negatív amplitúdót, míg -4.5 V-os meghajtásnál átszakítom (??) a kontaktot, az ellenállás 50 Ohm-os értékhez esik.
(Mentségemre szóljon 1s-ot a zajmérés miatt akartam beállítani, mert IV-t mérni nem sikerült szépen eddig 1 Hz felett, van valami vagy kapacitív, vagy valószínűbb módon időzítési probléma.)
U06.50
Nem stabil semmilyen probált amplitúdónál. Inkább mérek zajt, mielőtt tönkremegy. A 0207-ei séma alapján mérek, de csak egyszer-egyszer állapotonként 500-1000 mV-ig és kisIV-k nélkül. IV-k nem lesznek jók az említett időzítési hiba miatt!
MAPPA
MÉRÉSEK
SZŰRŐ
ERŐSÍTÉS
0_FULL
1x fullIV 10us
nincs
1e4!! elrontottam!
1_ON
IVnoise 500 mV, IVnoise 1000 mV
VAN!
1e6
2_RESET
RESET félIV
nincs
1e3
3_OFF
IVnoise 500 mV, IVnoise 1000 mV
VAN!
1e6
4_SET
SET félIV
nincs
1e3
5_ON
IVnoise 500 mV, IVnoise 1000 mV
VAN!
1e6
6_FULL
1x fullIV 10us
nincs
1e3
Kiértékelés után látszik, hogy nem elkülöníthető az ON állapot zajmérése az OFF-tól, pedig az IV-ben az volt. Ötlet, hogy esetleg relaxál az ON állapot, vagy talán mivel pozitív irányba kezdjük a sweepet és hosszú a mérés, már átkapcsol valami egy OFF-ba.
2023.02.14. IV, ON & OFF zaj, troubleshooting
Ofszetkompenzáció, 1e4, szűrő nélkül:
Card:  mV, Agilent:  mV (nem írtam fel…)
no init: S02.100 (35 Ohm), S02.50 (45 Ohm)
S02.20
Kezdeti 85 Ohm. Néhány IV, majd zajmérésre átdugáskor 30 Ohmra csökkent
no init S01.100, S01.50: 25 Ohm körül
W09.100
Kezdeti 85 Ohm, szépen inicializálódott.
ser01
Mátéval első bemutató mérések.
2023.02.15. Troubleshooting
Időzítési hibák. Új verzió: Scope_unlimited_final_230215.vi
Észlelt problémák:
Agilent már a trigger előtt kiadja a jelet, kb 20-30 ms-ig, változó hosszal.
A kiadott jel végén az első adatponttal megegyező feszültséget hagy a kimenete (ezt már ismertük eddig is, és a loop végén, két cycle között lenulláztuk az Outputot. Most Boti egy, a mérés végéhez közelebbi pontra tette át ezt a lehúzást, ezzel kb ~100 ms helyett ~10 ms ideig adja csak ki a végén a feszültséget.
kb. 30 us-nyi adatsor van a mért áram elején, ami még a kiadott jel előtt van mérve. Ez kb 14-15 pont 5e5 Hz-es BW-vel. Ezt lehet korrigálni, amennyiben töröljük az áram elejét és a feszültség végén ugyanannyi pontot, de ezt nem implementáljuk, legyen inkább mindig manuális, mert nem kizárható, hogy ez a 30 us változhat más paraméterekre.
teljes ideje a mérésnek kevesebb, mint aminek kéne lennie. Van egy default time delay 0.02s-mal, amivel több ideig mérünk, minthogy szoftveresen azt mondanánk, hogy végeztünk. Hibát találtunk a LabVIEW-ban, ahol a bináris fájl végét számolja, mert nem kalkulál a header méretével.
2023.02.21. noise U05.20
ofszetelés
Card: 0.357503
Agilent: 2.2
U05-ös mintán mértünk, .100 és .50 nem inicializálódott, .20-nak nagy volt az ellenállása de sikeres volt az inicializálás. Zaj, IV mérve.
LCA erősítőt használtuk, 5e7 V/A erősítés
2023.02.22.
Offsetelés, mindkét Femto erősítő offsetjét meghatározom:
Femto DLPCA-S Low Noise beállításban (1e5 erősítés):
Card offset: -0.447251
Agilent offset: 1.5 (1M Ohm) 1.8 (10k Ohm)
1-5 adatsorok
Femto LCA-100K-50M erősítő (5e7 erősítés):
Card offset: -0.587725
Agilent offset: 2.3 (1M Ohm) 1.2 (10k Ohm)
6-11 adatsorok
Az LCA-s értékeknél maradunk, mert azzal fogunk kis fesz. zajt mérni. A különbséget a két erősítő különböző bemeneti feszültségofszetje adhatja az Agilent offsetben, és az áramoffszet (amit multiméterrel is ki lehet mérni) a Card offsetben.
W09.100
Múltkor mért mintán akartunk mérni, de mikroszkóppal látszik, hogy maszatos lett. A minta jobb alsó sarkán mintha több kosz lenne, mint eddig.
V09.50
Volt egy teljes IV mérés, aminek megnyitásakor mindig lefagyott a gép… Ezért két fél IV-ével lett lemérve, azonban rossz erősítés érték mellett. Beállítva 10e4 volt, a valódi erősítés azonban 5e7 volt. Notepad++-ban korrigáltuk a hexeditor nézetben a második sor első négy elempárját.
2023.02.23.  
Megpróbálom kikontaktálni a tegnapi mintát (V09.50), majd megfelelő lépésekben egészen 1V-ig mérni a zajt.
Offsetelés:
Femto LCA-100K-50M erősítő (5e7 erősítés):
Card offset: -0.365766
Agilent offset: 2.8
Most megpróbálom kikontaktálni a tegnap már használt V09.50-es mintát, és újra mérni a zajt.
V09.50 igen alacsony ellenállást mutatott. Rossz mérés.
U09.100 inicializálása sikertelen.
U09.50 esetén sikeres inicializálás. Zajmérés 100 mV és 1000 mV-os IVnoise. Sajnos 1e3 volt az erősítés, így nagyon alacsony a jel, mert az ellenállás MOhm tartományban van. Az 1000 mV-os mérés egy része használható.
2023.03.09. Delta meghajtással inicializálás
Kisebb ellenállású pontokat szeretnénk, de az a nagyobb padeken elérhetőek inkább, amiket viszont nem tudunk inicializálni a Femto telítése és a NI kártya max kimeneti árama miatt. Ezért meghajtásnak használjuk a Deltát, ami 15x erősítéssel adja ki a ráadott feszültséget. A programban soros ellenállásra 0 Ohm-ot és Gainra 1-et állítunk be. Az összeállított áramkörben soros ellenállás 100 Ohm, és minta 50 Ohm-mal van lezárva. Így a program által kimentett Udrive és I=Umért adatokból az ellenállás így számolható:
R_M = (Umért/Udrive*(100+50)-50) / (1-Umért/Udrive)
Korábban felírt néhány nem inicializálható minta: T03.100, U03.100, U03.50. Most sem sikerült őket formázni, mikor már >4V esett rajtuk, akkor sem.
2023.03.10. Folytatás Deltával + nagy felbontású IV
Tegnapi mérési elrendezéssel további próbálkozás. 50 Ohm-os zárás helyett rövidzárral.
Ma 28 mV-os ofszet az NI kártya kiadott feszültségén.
R_M = (Umért/Udrive*100 / (1-Umért/Udrive)
K03.100, K03.50, K04.50 nem sikeres formázás
Fontosnak tűnő megfigyelés, hogy a K04.50 és a tegnapi U03.50 mintáknál mintha elkezdődne a formázás, aztán alacsony ellenállásba ugrik vissza, valószínűleg átszakad a minta. A soros 100 Ohm helyett érdemes lehet jóval kisebb ellenállást betenni, mert a mostani elrendezésben a formázódás után hirtelen óriási feszültséget kap a minta, ami miatt tönkre tud menni.
Másik mintákon meg olyan, mintha a formázási lépés meg sem indulna, csak alacsony ellenállásba vált. Ezeknél valószínűleg nem az eszközök limitjei a problémák, hanem valamiért előbb szakad át, minthogy formázódni tudna.
K05.50 sikeres formázás, utána viszont eltűnt, újraközelítettem, egész jónak tűnt. Egy kis piszkálás után viszont leesett az ellenállás, valószínűleg átszakadt.
Nagy felbontással IV-t szeretnék mérni. Ehhez első körben végigpróbálok néhány korábban működő mintát.
Q12.50 működik még. ezen fogok mérni IV-t és zajt is!
5e7-es erősítésben az LCA-val ofszetelek. Card: -0.119581 mV, Agilent: 2 mV
1e8-as erősítésben az DLPCA-val ofszetelek. Card: -0.485409 mV, Agilent: 1.3 mV
IV_Agilent
IV-hez mindkét erősítőt használtam, de a kis fesz.tartományon a DLPCA-t. Lineáris tartomány talán 50 mV-ig van.
Előkészítettem minden zajmérést, átdugtam az LCA-t, és amikor mértem egyet, telítésbe ment azonnal. Átdugtam a main_autosave-re, és 8kOhm-nál van az ellenállás, lineáris IV-vel.
noise
LCA-val 5e7-ben mérek a nagyobb sávszélesség miatt, ennek megfelelő ofszetek használok.
/ser01_shortIVnoise
kis feszültségfüggés, kis szűrővel
-> Ez elég zajos PSD-ket adott, a kis átlagolás miatt, nem optimális, nem is értékeltem ki, de ha szükség lesz fesz.függésre, akkor lehet belőle valami.
/ser02_longconst
25-0-50-0-75-0-100-0 mV lépcsők. Minden (nem nulla) lépcső 20s és 20 szakaszra van felbontva, hogy időfüggést lássunk esetleg, hogy a Lorentzek megjelennek-e. Nagy szűrővel (és először véletlenül kis szűrővel mértem)
- mivel annyira alcsony a jel, mértem nagy szűrővel a DLPCA-val 1e9-es és 1e8-as erősítésben (viszont nyilván irtó kis sávszélességgel)
-> a nagy szűrő miatti minden plató első 5s-nyi mérését manuálisan töröltem (segments: 21-25,42-46,63-67)
-> 0 mV-ok (segments 20,41,63,83) 5s-ig vannak mérve, ami egy hiba volt, mert a szűrő miatt annyi kéne levágni... Emiatt 4s-ot vágok le.
->nem látok időfüggést, Lorentzesedést
->kiértékelésnél az első 0 mV-os platót (segm.20) használom, és 25/50/75/100 mV-ra a méréssorozat utolsó szegmenseit 19/40/61/82
->1e8 és 1e9-es mérések konklúziója: az 1e8-as 7 kHz-nél vág le, kb ott, ahol megindulnak a probe station-ös zajok. Nem nyerünk viszont nagyon sokat vele. Az 1e9 1kHz-nél meg egyérteéműen túl hamar vág le.
2023.03.13. Korábbi minták + 20-as pad
Offsetelés 5e7 erősítésben 100k Ohmos ellenállással:
card offset: -0.163847  mV
Agilent offset: 2.7 mV

1.

Korábbi mintákat ellenőrizzük újra és mérjük 50 és 100 mV-on.
R12.50, U09.50, U06.50 is működik
Úgy néz ki, hogy a néhány mintán kívül, ami már ránézésre is koszolódott, a legtöbb régi minta még mindig működőképes.
2.
20-as padeket akarok mérni, hogy nagyobb ellenállás fele menjünk.
W01.20
3 szériát mértem, mert az első kettő után eltűnt a kapcsolás, és újra közelítettem, és még újra is kellett inicializálni. Valószínűleg nem az 50-es mértem véletlenül, mert a mérés végén az 50-es még inicializálatlan volt. Ellenállás kb. 50 MOhm.
W02.20
Furcsa, hogy a platók végét is le kellett vágni, mert már változott az áram. Mintha rosszul lenne szeletelve a jel. Amúgy ellenállás 10 MOhm körül, ami nem magasabb, mitn az 50-es padé.
L01.20 irtó instabil, inicializálás nem siker, kapcsolgat valamit néhány száz Ohmon.
2023.03.14. 20-as pad zajmérések lineáris tartomány
Minták összegző táblázata: <http://ssplab.phy.bme.hu:5055/oo/r/741013124299137051#tid=1>
No init: A04.20, A03.20, C04.20, E03.20
E10.20
Tegnapi ofszetekkel mértem. Az első 0 mV erősen 1/f-es, ezért a középsőt használom. 10 MOhm.
Ofszetelés, LCA 5e7 V/A
Card: -0.273002 mV, Agilent: 2.2 mV
R08.20
ser01: Első mérés megint 10 MOhm
pozitív félIV-kkel hangoltam
ser02: 300 MOhm
ser03: 100 MOhm
Ofszetelés, DLPCA 1e3 V/A
Card: -0.0277722 mV, Agilent: 2.3 mV
IV mérés a DLPCA-val, Agilenttel. Kapcsolás közben elromlott valami, 10 kOhm-ra kapcsolt a minta, onnan meg már csak csökkent az ellenállás.  Nem inicializálható újra. Lehet, hogy időközben elmozdult a tű, mert elég sokáig volt magára hagyva, míg kiértékeltem.
R08.100 nem inicializálható
R08.50
Cél: ellenállás hangolása több lépésben mindkét irányban + zajmérések
zajmérés: LCA ofszet, nagy szűrő
IV és hangolás: DLPCA ofszet, nincs szűrő
ser01: 10MOhm
ser02_IV: 3db IV, 1e3-as erősítés (lehetett volna 1e4…)
ser03: változatlan ellenállás
ser04_IV:  3db IV, 1e4-es erősítésben !!!!1e3 van a programba írva!!!!!!!!
ser05_tuning: halfIV 2500mV, 5ms
ser06: kicsit megnőtt ellenállás 12 MOhm
ser07_tuning:  halfIV 3000mV, 5ms
ser08: 15 MOhm
ser09_tuning: 3x halfIV 3000mV, 5ms
ser10: változatlan ellenállás
ser11_tuning: halfIV -2500mV, 5ms
ser12: ?? MOhm, 5e7-es erősítésben !!!!1e7 van a programba írva!!!!!!!! JAVÍTVA
ser13_tuning: halfIV -3000mV, 5ms
ser14: 25 MOhm
ser15_tuning: 3x halfIV -3000mV, 5ms
ser16: 20 MOhm
ser17_IV: 3db IV
S08.20
zaj és IV
történt valami mérés közben, valószínűleg kuka a mérés
2023.03.17. 100-as pad zajmérések lineáris tartomány
Megpróbálok találni egy inicializálható 100-as padet. Deltával inicializáljuk azt, ami nem ment alapból.
No init hagyományosan: O09.100 - tól  (ABC sorrendben) - U09.100-ig. Majd Deltával két magasabb (>70 Ohm) kezdeti ellenállású mintán sikerült inicializálni. Annyit változtattunk a kapcsoláson, hogy a soros ellenállás 33 Ohm, és a minta rövidzárral van le zárva. A programban a beállítások: Rser=0, Gain=1, így a kiadott feszültség eleinte még megoszlik a soroson és a mintán, majd utána nagyrészt a mintán esik, ahogy annak óriási lesz az ellenállása. Van egy kis lag, ezért a viszzamért görbék sem valami értelmesek, de az alakjukon látszik, ogyha történt inicializálás. A bevált init feszültség olyan 0.18 V x 15 -> 2.7 V.
Function DeltaInitCalc(Rserial,Vdrive_mV,Vmeas_mV)
Variable Rserial, Vdrive_mV, Vmeas_mV
 print Vmeas_mV/(Vdrive_mV-Vmeas_mV)*Rserial
End
Ofszetelés, LCA
Card: 0.151401 mV, Agilent: 2.8 mV
Ofszetelés, DLPCA 1e3 V/A
Card: 0.0256048 mV, Agilent: 3 mV
U09.100
ser01: 2 MOhm
ser02_IV: 3 db teljes IV
ser03: 1-1,5 MOhm (ugrás ellenállásban 100 mV-on)
ser04: 1 MOhm, erősen Lorentzes
ser05_IV: 22 db IV, egyre nőnek az ellenállások
ser06: 1.5 MOhm
S09.100
ser01: 1.5 MOhm
ser02_IV: 22 db IV
ser03: 3 MOhm
ser04_tuning: -3000mV_5ms halfIV, de a jel eleje hibás
ser05: 3 MOhm, egy kisebb ugrás 100 mV-on
Szakadást látszik a mérésben, de utána ránéztem a másik programban, ott minden ok. Úgyhogy ismétlem a zajmérést, talán valami kontakthiba volt.
ser06_tuning: 2200 mV 5ms halfIV
Ezután szakadás látszott, aztán sok átdugdosás után az ellenállás leesett 110 Ohmra.  Másik pozicióban tettem vissza a tűt, ahol 1k-t látunk, de nem incializál újra.
2023.03.20.
IV-beli hiszterézis tűnt fel, pl. U09p100 mért IV-n. Ezzel még lehetne foglalkozni, ma nem jutottunk konklúzióra. Régebbi méréseknél ez nem mindig volt látható, furcsa.
2023.03.23.
Döntött elrendezést próbálunk ki, így a kisebb padek kontaktálást megkönnyítjük valószínűleg azzal, hogy oldalról nézünk rá.
B06p20 (valószínűleg… ??)
/Agilent_IV: 10 db IV-mérés, ofszetelés nélkül
/offset:
Card offset: -0.178171
Agilent offset kimérésénél problémák voltak, végül nem sikerült, 0-nak hagytuk.
/noise:  sikeres zajmérés, az ellenállás viszonylag kicsi ~3-4MOhm, a zaj viszont nagy volt, utána újabb zajmérés (ser02), de ott történt valami baj és bár vannak PSD-k, nem értékeltem ki. Agilenttel megpróbáltam IV-ket mérni, az első 20-asnál (ser03) volt valami elugrás, utána a második 20-as (ser04) adag már kis ellenállásban volt. Visszaraktam az IV mérős rendszerre, ott ~50Ohm-ot mértem… Lehet, hogy átszakadt. Ránézek egy másik mintára.
Jobbra mentem, jó kérdés melyik minta, talán B07, ha jól látom
B07p20
kb 320Ohm-ot mutat a rátevéskor, megpróbálom inicializálni. SIKERÜLT és jó IV-ket mutat -> zajmérés
/noise/ser01: 20 db IV mérés (ser01), ezek értelmesnek tűntek
/ser02: zajmérés a szokásos módon, 50MOhm és a zaj sem brutálisan nagy, meglátjuk… NEM LEHETETT ÉRTELMESEN FITTELNI! Meg kell majd nézni újra, mert “megtörős” görbék vannak. A zaj pontok viszont egész jó helyre kerültek
/ser03: kiértékelés közben futott egy újabb zajmérés, a fittelés itt sem az igazi
/ser04: 20db IV agilenttel, újra történt valami, az utolsó IV-ken van ugrás +1 IV mérés, az értelmesnek tűnik, ezért mérek még egy zajt
/ser05: zajmérés újra a szokásos módon, kicsit nagyobb ellenállása lett
/ser06: ismétlő mérés (zaj)
/ser07: befejező 20db IV Agilenttel, normálisnak tűnnek az IV-k
2023.03.24.
Újabb próbálkozás a döntött mintával, L07-esre úgy tűnik, hogy sikerült letenni a tűt és ~1.3-1.5kOhm stabil ellenállást látok. Megpróbálom inicializálni
L07p20
működő minta, mértem rajta az IV-s programmal vagy 40-50IV-t, aztán zajmérés
/IV_agilent: ser01- zajmérés előtt 20 IV agilenttel 1e5-ös erősítésben, nincs semmi offset kompenzálva!. Elsőre valamiért nem mért a rendszer (mintha szakadás lett volna), de csekkoltam a másik program és él a minta, ezért újra IV-ket mértem (20db). A korábbi rossz adatokat ki is töröltem. Most működött a mérés, nem túl nagy az ON-OFF arány, de kb a szokásos IV-ket látom. OFFSET-elés, aztán zaj!
/Offset_LCA: kicsit bénáztam az offsetelésnél, de végül sikerült :) Elég korrekt lett, a szűrőt egy csavarhúzóval kisütöttem a mérések között, bár erre nem biztos, hogy feltétlenül szükség volt
card offset: -0.253278, femto offset: 2.05mV
/noise: ser02 - végre zajmérés… “check” néven egy ellenőrzés, sajnos az első mérés valamiért szakadást mutatott, majd a második szintén :( nem jó jel, megnézem a másik programmal. Sajnos ott sem mutat semmit… Visszamenni a mintára a tűvel kb esélytelen, kicsit próbálkoztam, de sikertelen volt.
Undefined
Újabb próbálkozás, egy random mintára mentem rá. Mármint azért random, mert nem tudtam leolvasni a betűt és a számot. Az L sor melletti sor, “lefelé” (amerre lejt a tartó), és talán 7-8-9 közül valamelyik. Kezdeti ellenállás ~680Ohm volt, sikerült inicializálni, majd mértem rajta IV-ket. Átkötöttem a zaj rendszerre és ott is sikerült IV-t mérni, de ugyanakkor (a zajmérés előtt, amikor az LCA-t bekötöttem) megint végtelen lett az ellenállása. Mindkét esetben nagy volt a laborban a forgalom, először Dani és Sebastian jött meg, majd a második mintánál Timi és később Laci (igen nagy lendülettel) vette birtokba a probe station környékét. Nem mondom, hogy ezért szállt el a mérés, de erős a korreláció. Vagy szisztematikusan én rontottam el valamit…
Sajnos újabb zajmérés nem történt, de 2db 20-as mintán vannak új IV-k, amiket érdemes lenne kiértékelni majd. Továbbra az az érdekesség, hogy ezen minták ellenállása is viszonylag nagy volt. AFM? Hmm.
2023.03.27.
További próbálkozás a döntött mintával, D06-ra sikerült rámenni, elég valószínű, hogy a 20-as pad, de viszonylag közel van az 50-es.
D06p20
Kb 200Ohm volt a kezdeti ellenállása, a szokásos inicializálás működött és IV-t is mértem rajta, működik bár nem túl jó az ON/OFF arány.
/IV_agilent:
ser01- zajmérés előtt 20 IV agilenttel 1e5-ös erősítésben, nincs semmi offset kompenzálva! Volt egy lyukrafutás, valamiért nem mért semmit először, de utáűna jó volt. Az ON/OFF arány csapnivaló.
ser05 - IV-k zajmérés után, sajnos úgy tűnik kis ellenállásba ment, így átszereltem a másik rendszerre
/Offset_LCA: az első zajmérés után kompenzáltam. A feszültség offset-et szokásos módon 1MOhm-on néztem. Egész jól sikerült kioffsetelni.
card offset: -0.282221, femto offset: 2.25mV
/noise:
ser02 - zajmérés, kezdésként egy ellenőrzés “check”’ néven, ami végre mutat ellenállást (bár nem túl szép a zaj). Ezután a szokásos zajmérés. FONTOS, hogy itt még nem kompenzáltam az offset-et!!! Sikeres volt a mérés, így kompenzálok és új mérést futtatok. Rettenetesen Lorentzes… Sajnos a háttérben éppen elveszik a levágási frekvencia, így nem lehet illeszteni. Azért kiértékelem, hogy látszódjon kb hol van a CNR, de ez nem sokat ér így. :(
ser03 - újabb zajmérés, akartam, de elfelejtettem ellenőrzést csinálni, így rögtön a hosszú méréssel kezdtem… Persze szerencsétlen voltam és sikeresen lemértem az 1MOhm-ot. Ezért nem szabad kapkodni és ezért kell ellenőrző mérést csinálni. Szerencsére még él a minta, így jöhet a rendes zajmérés. Közben kiértékelés. Itt kicsit értelmesebb PSD-ket látok, de ezt is nehéz fittelni
ser04 - kiértékelés alatt egy újabb mérés, az elsőhöz képest egész értelmes PSD-k
E07p20
Szintén kb 200Ohm volt a kezdeti ellenállása, a szokásos inicializálás működött és IV-t is mértem rajta, működik és egész korrektnek tűnik az ON/OFF arány
OFFSET az előző mérésből
/IV_agilent:
ser01- zajmérés előtt 20 IV agilenttel 1e5-ös erősítésben, nincs semmi offset kompenzálva!
ser04 - zajmérés után 20 IV, FIGYELEM, ITT VETTEM ÉSZRE, HOGY VALAMIKOR 1e6-ba RAKTAM AZ ERŐSÍTŐT, ÍGY AZ IV MÉRÉSEKNÉL LEHET, HOGY ROSSZ AZ  ERŐSÍTÉS! Egyébként az IV mérés sikerült
/noise:
ser02 - zajmérés, kezdésként egy ellenőrzés “check”’ néven, ezen egy elég nagy lorentz jelent meg, de sebaj. Jöhet a rendes mérés. Értelmes PSD-k jöttek, persze tele van Lorentzel, de legalább ment a mérés
ser03 - kiértékelés alatt újabb zajmérés, ez is működött
