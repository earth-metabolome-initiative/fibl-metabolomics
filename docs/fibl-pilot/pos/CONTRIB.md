

tmux ls
tmux a

### Login

sirius login --user-env SIRIUS_USERNAME --password-env SIRIUS_PASSWORD


### Run sirius

(from the source of this repo)

sirius -i ./docs/fibl-pilot/pos/results/mzmine/fibl_pilot_pos_sirius.mgf --output ./docs/fibl-pilot/pos/results/sirius/fibl-pilot-pos --maxmz 2500 config --IsotopeSettings.filter=true --FormulaSearchDB=BIO --Timeout.secondsPerTree=0 --FormulaSettings.enforced=HCNOP --Timeout.secondsPerInstance=0 --AdductSettings.detectable=[[M+H3N+H]+,[M+Na]+,[M-H4O2+H]+,[M+K]+,[M-H2O+H]+,[M+H]+] --UseHeuristic.mzToUseHeuristicOnly=650 --AlgorithmProfile=orbitrap --IsotopeMs2Settings=IGNORE --MS2MassDeviation.allowedMassDeviation=5.0ppm --NumberOfCandidatesPerIon=1 --UseHeuristic.mzToUseHeuristic=300 --FormulaSettings.detectable=Cl,Br,S --NumberOfCandidates=10 --ZodiacNumberOfConsideredCandidatesAt300Mz=10 --ZodiacRunInTwoSteps=true --ZodiacEdgeFilterThresholds.minLocalConnections=10 --ZodiacEdgeFilterThresholds.thresholdFilter=0.95 --ZodiacEpochs.burnInPeriod=2000 --ZodiacEpochs.numberOfMarkovChains=10 --ZodiacNumberOfConsideredCandidatesAt800Mz=50 --ZodiacEpochs.iterations=20000 --AdductSettings.enforced=, --AdductSettings.fallback=[[M+Na]+,[M+K]+,[M-H2O+H]+,[M+H]+] --FormulaResultThreshold=true --InjectElGordoCompounds=true --StructureSearchDB=BIO --RecomputeResults=false formula zodiac fingerprint structure canopus write-summaries

### Rerun sirius

sirius -i ./docs/fibl-pilot/pos/results/sirius/fibl-pilot-pos --output ./docs/fibl-pilot/pos/results/sirius/fibl-pilot-pos --maxmz 2500 config --IsotopeSettings.filter=true --FormulaSearchDB=BIO --Timeout.secondsPerTree=0 --FormulaSettings.enforced=HCNOP --Timeout.secondsPerInstance=0 --AdductSettings.detectable=[[M+H3N+H]+,[M+Na]+,[M-H4O2+H]+,[M+K]+,[M-H2O+H]+,[M+H]+] --UseHeuristic.mzToUseHeuristicOnly=650 --AlgorithmProfile=orbitrap --IsotopeMs2Settings=IGNORE --MS2MassDeviation.allowedMassDeviation=5.0ppm --NumberOfCandidatesPerIon=1 --UseHeuristic.mzToUseHeuristic=300 --FormulaSettings.detectable=Cl,Br,S --NumberOfCandidates=10 --ZodiacNumberOfConsideredCandidatesAt300Mz=10 --ZodiacRunInTwoSteps=true --ZodiacEdgeFilterThresholds.minLocalConnections=10 --ZodiacEdgeFilterThresholds.thresholdFilter=0.95 --ZodiacEpochs.burnInPeriod=2000 --ZodiacEpochs.numberOfMarkovChains=10 --ZodiacNumberOfConsideredCandidatesAt800Mz=50 --ZodiacEpochs.iterations=20000 --AdductSettings.enforced=, --AdductSettings.fallback=[[M+Na]+,[M+K]+,[M-H2O+H]+,[M+H]+] --FormulaResultThreshold=true --InjectElGordoCompounds=true --StructureSearchDB=BIO --RecomputeResults=false formula zodiac fingerprint structure canopus write-summaries