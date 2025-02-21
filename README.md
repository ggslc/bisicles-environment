# bisicles-environment
Environment including BISICLES and Chombo 

## Building 

1. obtain the Chombo and BISICLES submodules (git submodule init, git submodule update)
2. install dependencies, hdf5 etc
3. create Chombo/lib/mk/Make.defs.local
4. create bisicles-uob/code/mk/Make.defs.<uname -n>
5. cd bisicles-uob/code
6. make all (+ options) 

