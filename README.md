# macros_HiggsAnalysis-HiggsToZZ4LeptonsMiniAOD
cmsrel CMSSW_8_0_24

cd CMSSW_8_0_24/src

cmsenv

git clone https://github.com/ndefilip/cmssw -b HiggsAnalysis_CMSSW_8_0_x_miniAOD_2016 ${PWD}

cd /path/of/condor_macros

source compilereference.sh 4e

source loopcheck_signal_new.sh FNAL NO Spring16 4e


Rootuples should be written in /eos/uscms/store/user/your_username
