## Purpose
Provides user spack config files for lumi-g, tested installing pytorch+rocm.

## Setup
### Clone spack-config in the location of your user-config
```
cd <where_you_want_your_spack_config_cache>
git clone --depth 1 -b lumi https://github.com/aurianer/spack-config.git spack-user-config
export SPACK_USER_CONFIG_PATH=<where_you_want_your_spack_config_cache>/spack-user-config
```
