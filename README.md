# Shadow Short Rate

Originally by (Leo Krippner) [webpage](http://www.rbnz.govt.nz/research_and_publications/research_programme/additional_research/5655249.html) in MATLAB. Translated into Python 2 by (Amandeep Singh)(https://github.com/as4456) and translated here into Python 3. 

## Instructions for generating the results
*	Run "python data\_read.py"   This generates yield curve data.   The script generates the spliced yield curve dataset (Govt. data spliced with the OIS data after a specific date) for a respective country (Line 61 in the code) in monthly, weekly and daily csv formats.
*	Run "python AAA\_RUN\_KANSM2\_Est\_LB.py"  This generates the shadow rate and other results.  The script generates the results in a csv format as in the “Comparison of international monetary policy measures” for a respective country (Line 27) in the desired frequency (Line 28).