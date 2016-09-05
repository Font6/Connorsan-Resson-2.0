# Connorsan-Resson-2.0
Referencing and hashes

#!/usr/bin/perl

#!/usr/bin/perl

use strict;

use warnings;

my %hash = (
    city     => 'Corona',
    county      => 'Riverside',
    state    => 'California',
    nation => 'USA',
);

my $hashref = \%hash;

print $hashref->{state};
