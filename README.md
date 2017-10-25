# lingo
## Acronyms for random things

When auditing a codebase, I tend to come across acronyms and then forget them years later.  This repo is to store some of them.

- qcacld
  - **Q**ual**C**omm **A**theroc **C**hipset **L**an (?) **D**river
- scm
  - **S**ecure **C**hannel **M**anager (Qualcomm) [link][scm]
  - **S**ource **C**ontrol **M**anagement (git, svn)
- scr
  - **S**ecure **C**onfiguration **R**egister (determines ARM EL and Normal/Secure)
- smc
  - **S**ecure **M**onitor **C**all (ARM instruction used by SCM)
- qseecom
  - **Q**ualcomm **S**ecure **E**xecution **E**nvironment **Com**munication
- xbl
  - e**X**tensible **B**oot**L**oader (Qualcomm) [link][xbl]
- pbl
  - **P**rimary **B**oot**L**oader (Qualcomm) [link][xbl], in ROM
- sbl
  - **S**econdary **B**oot**L**oader (Qualcomm) [link][xbl]  
- lk
  - **L**ittle **K**ernel, used for some Qualcomm bootloaders [link][lk]
- avc
  - **A**ccess **V**ector **C**ache (SELinux)
- edl
  - **E**mergency **D**ownload **M**ode (Qualcomm, protocol is Sahara)
- qdm
  - **Q**ualcomm **D**iagnostic **M**onitor (`/dev/diag`?)
- qxdm
  - **Q**ualcomm e**X**tensible **D**iagnostic **M**onitor

[xbl]: https://www.qualcomm.com/media/documents/files/secure-boot-and-image-authentication-technical-overview.pdf
[lk]: https://developer.qualcomm.com/qfile/28821/lm80-p0436-1_little_kernel_boot_loader_overview.pdf
[scm]: https://patchwork.kernel.org/patch/415041/


## TEE

- tcb
  - **T**rusted **C**computing **B**ase
- tcg
  - **T**rusted **C**computing **G**roup
- pcr
  - **P**latform **C**onfiguration **R**egisters
- rtm
  - **R**oot of **T**rust for **M**easurements
- drtm
  - **D**ynamic RTM
- rts
  - **R**oot of **T**rust for **S**torage
- rtr
  - **R**oot of **T**rust for **R**eporting
- ek
  - **E**ndorsement **K**ey
- aik
  - **A**ttestation **I**dentity **K**ey
- srk
  - **S**torage **R**oot **K**ey
- txt
  - **T**rusted **E**xecution **T**echnology (Intel)
- svm
  - **S**ecure **V**irtual **M**achine (AMD)
- mle
  - **M**easured **L**aunch **E**nvironment
- acm
  - **A**uthenticated **C**ode **M**etrics
- sgx
  - **S**oftware **G**uard e**X**tensions
- epc
  - **E**nclave **P**age **C**ache
- ssa
  - **S**ave **S**tate **A**rea
- aex
  - **A**synchronous **E**nclave **E**xit
- trts
  - **T**rusted **R**un **T**ime **S**ystem
- urts
  - **U**ntrusted **R**un **T**ime **S**ystem
- le
  - **L**aunch **E**nclave
- pe
  - **P**rovisioning **E**nclave
- qe
  - **Q**uoting **E**nclave
- sme
  - **S**ecure **M**emory **E**ncryption
- tsme
  - **T**ransparent **SME**
- sev
  - **S**ecure **E**ncrypted **V**irtualization
- asid
  - **A**dress **S**pace **ID**
- pek
  - **P**latform **E**ndorsement **K**ey
- cek
  - **C**hip **E**ndorsement **K**ey
- pdh
  - **P**latform **D**iffie **H**ellman **K**ey
