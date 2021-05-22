# Yocto_Configuration
modify local.conf

------------------------------------------------------------------------
# Uncomment and set to allow bitbake to execute multiple tasks at once.
# For a quadcore, BB_NUMBER_THREADS = "4", PARALLEL_MAKE = "-j 4" would
# be appropriate.
 BB_NUMBER_THREADS = "6"
# Also, make can be passed flags so it run parallel threads e.g.:
 PARALLEL_MAKE = "-j 6"
------------------------------------------------------------------------



