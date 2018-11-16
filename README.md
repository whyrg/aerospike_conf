Aerospike's shipped config file is bare bones and requires referencing the
online documentation to fully understand what parameters are available and
what each parameter does.


This repo's content adds **every, single** parameter into the conf file,
along with corresponding comments to give a brief overview of what each
does.

Also specifically denotes which parameters are not dynamic (cannot be changed
by info commands), which must be unanimous (must be same across entire cluster)
and which are locked behind feature keys.
