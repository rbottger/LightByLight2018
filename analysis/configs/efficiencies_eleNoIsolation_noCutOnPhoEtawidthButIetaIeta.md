##  Efficiencies config

### Verbosity level (0: critical errors only, 1: errors and warnings, 2: full debug log):
verbosityLevel: 0

### Select which efficiencies should be calculated:
doRecoEfficiency:      0 
doTriggerEfficiency:   0 
doHFvetoEfficiency:   1
doCHEefficiency:       1 
doNEEefficiency:        1
doElectronRecoEfficiency: 0

### Max number of events to analyze
maxEvents: 9999999
# maxEvents: 50000

### Criteria to match calo tower with photon SC for neutral exclusivity
maxDeltaEtaEB:  0.15
maxDeltaPhiEB:  0.7
maxDeltaEtaEE:  0.15
maxDeltaPhiEE:  0.4

### Charged exclusivity cuts (GeV)
maxNtracks:                             0
trackMinPt:                               0.8 
trackMaxEta:                            2.1
trackMaxDxy:                           999999
trackMaxXYdistanceFromBS:  999999
trackMaxDxyOverSigma:         999999
trackMaxDz:                             999999
trackMaxZdistanceFromBS:    999999
trackMaxDzOverSigma:           999999
trackMinNvalidHits:                  4
trackMaxChi2:                          999999

### Pixel cuts
maxNpixelRecHits:                  999999

### Pixel track cuts
maxNpixelTracks:                    0
pixelTrackMinPt:                      0.05
pixelTrackMaxEta:                   2.1
pixelTrackMinNvalidHits:         3
pixelTrackMaxChi2:                 999999

### ZDC cuts
maxZDCenergy:                       999999
maxTotalZDCenergy:                999999
maxTotalZDCenergyPerSide:    10000

### Max ΔR for matching for reco+ID efficiency
maxDeltaR:              0.3

### Photon ID cuts:
photonMinEt:                            2.0
photonMaxEta:                         2.1
photonMaxHoverEbarrel:          0.04596
photonMaxHoverEendcap:       0.0590
photonMaxEtaWidthBarrel:      99999 
photonMaxEtaWidthEndcap:    99999
photonMaxSigmaEta2012Barrel:     0.02
photonMaxSigmaEta2012Endcap:  0.06
photonMinSwissCross:             0.0
diphotonMaxPt:                        1.0
diphotonMaxRapidity:               9999999
diphotonMinMass:                    5.0
diphotonMaxAco:                      0.01
photonRejectConverted:           1

### Electron ID cuts:
electronMinPt:                            2.0
electronMaxEta:                         2.1
electronMaxNmissingHits:         1
electronMaxHoverE_Barrel:         0.005
electronMaxHoverE_Endcap:      0.005
electronMaxDetaSeedBarrel:      0.1
electronMaxDetaSeedEndcap:   0.1
electronMaxChargedIsoBarrel:   999 
electronMaxChargedIsoEndcap: 999 
electronMaxPhotonIsoBarrel:     999 
electronMaxPhotonIsoEndcap:   999 
electronMaxNeutralIsoBarrel:      999
electronMaxNeutralIsoEndcap:   999 
dielectronMaxPt:                        1.0
dielectronMinMass:                    5.0
dielectronMaxRapidity:               2.4

### Exclude transition region between calo barrel and endcap
ecalCrackMin: 1.4442
ecalCrackMax: 1.566

### Exclude hole in ECal (HEM issue, only in negative part of EE)
ecalHEMmaxEta:  -1.39
ecalHEMminPhi:  -1.6
ecalHEMmaxPhi: -0.9

### Don't look at towers that are in very noisy region of EE
maxEtaEEtower:      2.4

### Calorimeter noise thresolds (GeV)
noiseThresholdEB:        0.7
noiseThresholdEE:        7.5
noiseThresholdHB:        2.8
noiseThresholdHE:        2.4
noiseThresholdHFp:      7.2
noiseThresholdHFm:     7.5


### eta dependant EE noise thresholds (GeV)
doNoiseEEetaDependant:    0
noiseEEetaStep: 0.1
noiseEEetaMin: 1.5
noiseEEetaMax: 3.0

noiseThresholdEE_1.5:   9.61
noiseThresholdEE_1.6:   1.5
noiseThresholdEE_1.7:   1.2
noiseThresholdEE_1.8:   1.5
noiseThresholdEE_1.9:   1.5
noiseThresholdEE_2.0:   1.8
noiseThresholdEE_2.1:   2.11
noiseThresholdEE_2.2:   4.41
noiseThresholdEE_2.3:   7.91
noiseThresholdEE_2.4:   9.21
noiseThresholdEE_2.5:   9.71
noiseThresholdEE_2.6:   9.91
noiseThresholdEE_2.7:   10.01
noiseThresholdEE_2.8:   10.01
noiseThresholdEE_2.9:   10.01
noiseThresholdEE_3.0:   10.01
