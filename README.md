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
  - **E**mergency **D**ownload **M**ode (Qualcomm)
    - Sahara and DLOAD and DM / QCDM protocols
- qdm
  - **Q**ualcomm **D**iagnostic **M**onitor (`/dev/diag`?)
- qcdm
  - Same as **QDM**
- qxdm
  - **Q**ualcomm e**X**tensible **D**iagnostic **M**onitor
- laf
  - **L**G **A**dvanced **F**lasher
- qfprom
  - **Q**ualcomm **F**use **P**rogrammable **ROM**
- gdsc
  - **G**lobal **D**istributed **S**witch **C**ontrollers (Qualcomm)
- msm
  - **M**obile **S**tation **M**odem (Qualcomm)
- qsd
  - **Q**ualcomm **S**nap**D**ragon
- sdm
  - **S**nap**D**ragon **M**obile (Qualcomm)
- spm
  - **S**ubsystem **P**ower **M**anagement (Qualcomm)
- wcnss
  - **W**ireless **C**ontrol **N**etwork **S**ub**S**ystem (Qualcomm) [link][wcnss]
- smem
  - **S**hared **Mem**ory (Qualcomm)
- smemsm, smsm
  - **SMEM** **S**tate **M**achine (Qualcomm) [link][smemsm] [link2][smemsm_lwn]
- smp2p
  - **S**hared **M**emory **P**oint-to-**P**oint (Qualcomm) [link][smp2p]
- gsbi
  - **G**eneral **S**erial **B**us **I**nterface (Qualcomm)
- qup
  - **Q**ualcomm **U**niversal **P**eripheral Engine [link][qup]
- spi
  - **S**erial **P**eripheral **I**nterface
- smd, qsmd
  - **Q**ualcomm **S**hared **M**emory **D**river
- bam
  - **B**us **A**ccess **M**anager / **M**odule (Qualcomm] [link][bam]
- blsp
  - **B**AM **L**ow **S**peed **P**eripheral (Qualcomm) [link][blsp]
- caf
  - **C**ode **A**urora **F**orums (Qualcomm FOSS)
- sps
  - **S**mart **P**eripheral **S**system (Qualcomm) [link][sps]

[xbl]: https://www.qualcomm.com/media/documents/files/secure-boot-and-image-authentication-technical-overview.pdf
[lk]: https://developer.qualcomm.com/qfile/28821/lm80-p0436-1_little_kernel_boot_loader_overview.pdf
[scm]: https://patchwork.kernel.org/patch/415041/
[wcnss]: https://www.kernel.org/doc/Documentation/devicetree/bindings/soc/qcom/qcom,wcnss.txt
[smemsm]: https://www.kernel.org/doc/Documentation/devicetree/bindings/soc/qcom/qcom%2Csmsm.txt
[smemsm_lwn]: https://lwn.net/Articles/655874/
[smp2p]: http://elixir.free-electrons.com/linux/v4.7/source/drivers/soc/qcom/smp2p.c
[qup]: https://developer.qualcomm.com/qfile/28819/lm80-p0436-5_peripherals_programming_guide.pdf
[blsp]: https://www.inforcecomputing.com/public_docs/BLSPs_on_Inforce_6540_6501_Snapdragon_805.pdf
[bam]: https://lwn.net/Articles/582840/
[sps]: http://thread.gmane.org/gmane.linux.ports.arm.msm/543

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
