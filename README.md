px - Path Exchange
==================

px list

px set rakudo
px add ~/perl6/rakudo-star-2012.06/bin
px add ~/perl6/rakudo-star-2012.07/bin

px set perl5
px add ~/perl5/perl-5.16/bin
px add ~/perl5/perl-5.17/bin

px activate rakudo-star-2012.06
px activate rakudo-star-2012.07 # fail because one of items in rakudo set is already activaated
px deactivate rakudo-star-2012.06
px deactivate rakudo
px activate rakudo

px use rakudo-star-2012.08 # implies deactivate the currently activated item in rakudo set
px use rakudo-star-2012.07

px info
