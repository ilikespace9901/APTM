This file contains all the reactions, theres some chance i forgot one though, temp is in K, *Italic* means its a catalyst and isnt consumed by the reaction, no reaction will be listed twice on 2 different elements
## CARB
- Pressure > 80 and temp > 1500 = PDMN with 0.5%\f
## NTRG
- NTRG and OXYG and temp > 1273.15 = NO2 with 5%\f
- NTRG and HYGN and *IRON* and pressure > 8 and temp > 723.15 = NH3 with 5%\f
## LN2
- Temp > 77.36 = NTRG
## BRON
- BRON and OXYG = B2O3
## B2O3
- B2O3 and WATR = BRAC
## SULF
- SULF and HYGN = H2S with 5%/f
- SULF and IRON = FES with 5%/f
- SULF and OXYG = SO2 with (temp / 400)^10 / 20)%/f
## FES
- FES and ACID = H2S with 100%/f
## H2S
- H2S and OXYG = SULF and H2O2 with 5%/f
## FLOR
- FLOR and any metal = FLOR and BRMT with 2%/f
- FLOR and TUNG = WF6 with 5%/f
## LF2
- LF2 and any metal = LF2 and BRMT with 2%/f
- LF2 and TUNG = WF6 with 5%/f
## ALNM
- ALNM and OXYG = ALMO with 10%/f and OXYG with 50%/f
## CHLR
- CHLR and any water = TCWR with 10%/f
- CHLR and SODI = SALT with 20%/f
- CHLR and HYGN = HCL with (temp/580)^21)%/f
## SODI
- SODI and any water = NAOH with 50%/f and HYGN with 90% or FIRE with 10% and +30K
## TCWR
- TCWR and PLNT = TCWR with 50%/f
## BRMN
- BRMN and SODI = NABR with 5%/f
- BRMN and any water = TCWR with 10%/f
## BRMV
- BRMV and any water = TCWR with 10%/f
## NABR
- NABR and CHLR = SALT and BRMN with 5%/f
## ZINC
- ZINC and an acid = HYGN with 4%/f or an acid with 50%
## COPR
- COPR and SULF = CUS with 5%/f
## CUS
- CUS and an acid = H2S and COPR with 5%/f
- CUS and temp > 493 = COPR and SULF and +1 pressure and +20K with (temp/1000)^5 * 50)%/f
## PDMN
- PDMN and temp > 5031 = BDMM
## NO2
- NO2 and WATR = HNO3 with 5%/f
## NH3
- NH3 and NO2 = NTRG and WATR with 5%/f
## HNO3
- HNO3 and any metal = BRMT with 5%/f
- HNO3 and NH3 = AMNI with 33%/f
## AMNI
- AMNI and temp > 443 = FIRE and WTRV and +1 pressure and +50K with ((temp - 400) / 500)^3 * 50)%/f
## SLVR
- SLVR and SULF = AG2S with ((temp / 1000)^4 * 10)%/f
- SLVR and H2S = AG2S with ((temp / 1000)^3 * 15)%/f
## AG2S
- AG2S and an acid = SLVR and H2S with 5%/f
## SO2
- SO2 and OXYG and *VANM* = SO3 with (temp - 673) / 50)^3 * 20)%/f
## SO3
- SO3 and any organics = SO3 and FIRE with 50%/f
- SO3 and any metal = SO3 and BRMT
- SO3 and any water = SLFA with 90% and ACID with 10% and +50K
## SLFA
- SLFA and any organics = SLFA and CARB and +50K with 50%/f
- SLFA and any metal = SLFA and BRMT
- SLFA and any water = +100K and WATR with 50%
- SLFA and temp > 611 = SFAV
## BRAC
- BRAC and temp > 373.15 = B2O3 and WTRV and +20K with ((temp/400)^8)%/f
- BRAC and any metal = BRAC and BRMT
## HCL
- HCL and any organics = HCL and CARB and +50K with 50%/f
- HCL and any metal = HCL and BRMT
- HCL and any water = DHCL
- HCL and OXYG and *COPR* = WTRV and CHLR with (temp/690.115)^99)%/f
## DHCL
- DHCL and any organics = DHCL and CARB and +50K with 50%/f
- DHCL and any metal = DHCL and BRMT
## NAOH
- NAOH and HCL = SALT and WATR with 5%/f
## H2O2
- H2O2 and any transition metal = WATR and OXYG and +30K with (15*log((temp-277.5)/2.6))%/f
- H2O2 and temp > 300.15 = WATR and OXYG and +30K with ((temp/308)^21)%/f
## N2H4
- N2H4 and IRID = NTRG and HYGN and NH3 with 5%/f
## SFAV
- SLFA and any organics = SFAV and CARB and +50K with 50%/f
- SFAV and any metal = SFAV and BRMT
- SFAV and any water = +100K and WATR with 50%
- SFAV and temp < 611 = SLFA
## NFPU
NFPU and temp > 7474.15 = PLUT
NFPU = URAN and NEUT at 0.005%/f
NFPU = +20K with 0.1%/f and temp < random int 1-1000
## YEST
YEST and 303 < temp < 317 = ETHN with 4%/f
YEST and 303 < temp < 317 = ETHN with 3.33%/f
