# Troble shoot

## eosiocpp command line dosen't work in current version 
#### 1.0.x branch is works well.



## EoS eos_build.sh need LLVM version 4.0
#### Modify Cmakefile from LLVM 6.0 to LLVM4.0 
#### Default llvm should be LLVM@4.0  -> modify $PATH:


## eosiocpp -n test  # skeleton path error 

#### Make symbolic link like below 
```
sudo ln -s /Users/k1rh4/GIT/EOS/EoS-project/eos/build/share/eosio/skeleton skeleton
error -> cp: /usr/local/eosio/share/eosio/skeleton/./skeleton: Too many levels of symbolic links
Remove /usr/local/eosio/share/eosio/skeleton/skeleton  <--- link
```
 
#### /Users/k1rh4/GIT/EOS/EoS-project/eos/build/share/eosio 
