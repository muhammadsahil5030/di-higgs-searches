# di-higgs-searches
This analysis uses the MadGraph5_aMC@NLO version2.9.15
Signal generation:
>import model loop_sm
>generate p p > h h [QCD]
>output
>launch
>madspin=none
1) run_card.dat:
lhapdf used 230000
factorization and renormalization constant = 1/2(mass higgs)
add line (decay h > b b~) to madspin
