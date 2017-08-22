HIGGS COMBINED LIMIT TOOL
=========================

```
# The official documentation can be found at
https://twiki.cern.ch/twiki/bin/viewauth/CMS/SWGuideHiggsAnalysisCombinedLimit

# And the official repo can be cloned using
git clone https://github.com/cms-analysis/HiggsAnalysis-CombinedLimit.git HiggsAnalysis/CombinedLimit

# However we have maintained a copy of this with the necessary modifications for the aTGC limit calculation, since many files e.g.
-HWWLVJRooPdfs.cxx, PdfDiagonalizer.cc, hyperg_2F1.cc (and headers)
# have to be modified from the official tool (copied from our repo's PDFs) and some files in the official repo which were giving compile time errors are not needed. So for convenience, we just clone the repo from here.

# Also CombinedLimit/python contains ACModel.py which has to be copied to ../CombinedEWKAnalysis/CommonTools/python/

