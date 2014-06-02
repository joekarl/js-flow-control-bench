js-flow-control-bench
=====================

Various benchmarks of js flow control libraries

Shamelessly borrowed from https://github.com/petkaantonov/bluebird

##Run benchmarks
There are 3 benchmarks:

* `./bench parallel` - contrived simple loop benchmark
* `./bench doxbee` - Run simulated mixed task flow benchmark
* `./bench doxbee-errors` - Run simulated mixed task flow benchmark with 10% errors

##Native promise support
Run with node 0.11.13+ to benchmark native promises and some experimental
stuff from bluebird.
