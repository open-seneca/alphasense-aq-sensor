# This code is for the Raspberry Pi Zero based air quality sensor board piloted in March 2019 by open-seneca in Nairobi, Kenya.

It is based on scs_dfe_edu by [South Coast Science](https://github.com/south-coast-science)

Environmental sampling abstractions for the South Coast Science educational board.

_Contains library classes only._

Sampling operations are performed using command line utilities found in the 
[scs_dev](https://github.com/south-coast-science/scs_dev/wiki) package. System configuration is performed using 
utilities found in the [scs_mfr](https://github.com/south-coast-science/scs_mfr/wiki) package.


**Required libraries:** 

* Third party: tzlocal
* SCS root: scs_core
* SCS host: scs_host_rpi


**Branches:**

The stable branch of this repository is master. For deployment purposes, use:
```
git clone --branch=master https://github.com/south-coast-science/scs_dfe_edu.git
```
