# TEE Basics & General

- Introduction to Trusted Execution Environment: ARM's TrustZone
	- https://blog.quarkslab.com/introduction-to-trusted-execution-environment-arms-trustzone.html

- Introduction to TEE (original title: TEEを中心とするCPUセキュリティ機能の動向 )
	- https://seminar-materials.iijlab.net/iijlab-seminar/iijlab-seminar-20181120.pdf

- Attacking the ARM's TrustZone
	- https://blog.quarkslab.com/attacking-the-arms-trustzone.html

- ARM TrustZone Security Whitepaper
	- http://infocenter.arm.com/help/topic/com.arm.doc.prd29-genc-009492c/PRD29-GENC-009492C_trustzone_security_whitepaper.pdf

- Web Site ARM TrustZone
	- https://developer.arm.com/ip-products/security-ip/trustzone

- TrustZone Explained: Architectural Features and Use Cases
	- http://sefcom.asu.edu/publications/trustzone-explained-cic2016.pdf

- Trustworthy Execution on Mobile Devices
	- https://netsec.ethz.ch/publications/papers/paper-hyperphone-TRUST-2012.pdf

- Demystifying ARM Trustzone : A Comprehensive Survey
	- https://www.researchgate.net/profile/Nuno_Santos9/publication/330696364_Demystifying_Arm_TrustZone_A_Comprehensive_Survey/links/5c6ff1a792851c6950379cdd/Demystifying-Arm-TrustZone-A-Comprehensive-Survey.pdf

- Understanding Trusted Execution Environments and Arm TrustZone (by Azeria)
	- https://azeria-labs.com/trusted-execution-environments-tee-and-trustzone/

- SoK: Understanding the Prevailing Security Vulnerabilities in TrustZone-assisted TEE Systems
	- https://www.cs.purdue.edu/homes/pfonseca/papers/sp2020-tees.pdf

- Giving Mobile Security the Boot (by Jonathan Levin)
	- https://papers.put.as/papers/ios/2016/TrustZone.pdf

- The ARMs race to TrustZone (by Jonathan Levin)
	- http://technologeeks.com/files/TZ.pdf

# TEE Exploits/Security Analysis

## HiSilicon/Huawei (TrustedCore)

- Exploiting Trustzone on Android (BH-US 2015) by Di Shen(@returnsme)
	- https://www.blackhat.com/docs/us-15/materials/us-15-Shen-Attacking-Your-Trusted-Core-Exploiting-Trustzone-On-Android-wp.pdf

- EL3 Tour : Get the Ultimate Privilege of Android Phone (Infiltrate19)
	- https://speakerdeck.com/hhj4ck/el3-tour-get-the-ultimate-privilege-of-android-phone
	- Paper : [infiltrate.pdf](https://github.com/enovella/TEE-reversing/blob/master/Papers/infiltrate.pdf)
	- video: https://vimeo.com/335948808

- Nailgun: Break the privilege isolation in ARM devices (PoC #2 only)
	- https://github.com/ningzhenyu/nailgun

- Nick Stephens : how does someone unlock your phone with nose. (give big picture of NWd <> SWd communications and exploits) GeekPwn 2016
	- https://fr.slideshare.net/GeekPwnKeen/nick-stephenshow-does-someone-unlock-your-phone-with-nose

## Qualcomm (QSEE)

- Reflections on Trusting TrustZone (2014)
	- https://www.blackhat.com/docs/us-14/materials/us-14-Rosenberg-Reflections-on-Trusting-TrustZone.pdf

- Getting arbitrary code execution in TrustZone's kernel from any context (28/03/2015)
	- http://bits-please.blogspot.com/2015/03/getting-arbitrary-code-execution-in.html

- Exploring Qualcomm's TrustZone implementation (04/08/2015)
	- http://bits-please.blogspot.com/2015/08/exploring-qualcomms-trustzone.html

- Full TrustZone exploit for MSM8974 (10/08/2015)
	- http://bits-please.blogspot.com/2015/08/full-trustzone-exploit-for-msm8974.html

- TrustZone Kernel Privilege Escalation (CVE-2016-2431)
	- http://bits-please.blogspot.com/2016/06/trustzone-kernel-privilege-escalation.html

- War of the Worlds - Hijacking the Linux Kernel from QSEE
	- http://bits-please.blogspot.com/2016/05/war-of-worlds-hijacking-linux-kernel.html

- QSEE privilege escalation vulnerability and exploit (CVE-2015-6639)
	- http://bits-please.blogspot.com/2016/05/qsee-privilege-escalation-vulnerability.html

- Exploring Qualcomm's Secure Execution Environment (26/04/2016)
	- http://bits-please.blogspot.com/2016/04/exploring-qualcomms-secure-execution.html

- Android privilege escalation to mediaserver from zero permissions (CVE-2014-7920 + CVE-2014-7921)
	- http://bits-please.blogspot.com/2016/01/android-privilege-escalation-to.html

- Trust Issues: Exploiting TrustZone TEEs (24 July 2017)
	- https://googleprojectzero.blogspot.com/2017/07/trust-issues-exploiting-trustzone-tees.html

- Breaking Bad. Reviewing Qualcomm ARM64 TZ and HW-enabled Secure Boot on Android (4-9.x)
	- https://github.com/bkerler/slides_and_papers/blob/master/QualcommCrypto.pdf

- Technical Advisory: Private Key Extraction from Qualcomm Hardware-backed Keystores CVE-2018-11976 (NCC)
	- https://www.nccgroup.trust/us/our-research/private-key-extraction-qualcomm-keystore/

- Qualcomm TrustZone Integer Signedness bug (12/2014)
	- https://fredericb.info/2014/12/qpsiir-80-qualcomm-trustzone-integer.html

- The road to Qualcomm TrustZone apps fuzzing (RECON Montreal 2019)
	- https://cfp.recon.cx/media/tz_apps_fuzz.pdf

- Downgrade Attack on TrustZone
	- http://ww2.cs.fsu.edu/~ychen/paper/downgradeTZ.pdf

### Motorola (Qualcomm SoC)

- Unlocking the Motorola Bootloader (10/02/2016)
	- http://bits-please.blogspot.com/2016/02/unlocking-motorola-bootloader.html

### HTC (Qualcomm SoC)

- Here Be Dragons: Vulnerabilities in TrustZone (14/08/2014)
	- https://atredispartners.blogspot.com/2014/08/here-be-dragons-vulnerabilities-in.html

## Trustonic (Kinibi & MobiCore)

- Unbox Your Phone: Parts I, II & III
	- https://medium.com/taszksec/unbox-your-phone-part-i-331bbf44c30c
	- https://medium.com/taszksec/unbox-your-phone-part-ii-ae66e779b1d6
	- https://medium.com/taszksec/unbox-your-phone-part-iii-7436ffaff7c7
	- https://github.com/puppykitten/tbase
	- https://github.com/puppykitten/tbase/blob/master/unboxyourphone_ekoparty.pdf

- KINIBI TEE: Trusted Application Exploitation (2018-12-10)
	- https://www.synacktiv.com/posts/exploit/kinibi-tee-trusted-application-exploitation.html

- TEE Exploitation on Samsung Exynos devices by Eloi Sanfelix: Parts I, II, III, IV
	- https://labs.bluefrostsecurity.de/blog/2019/05/27/tee-exploitation-on-samsung-exynos-devices-introduction/
	- https://labs.bluefrostsecurity.de/files/TEE.pdf
	- video: (Infiltrate 2019) https://vimeo.com/335947683

- Breaking Samsung's ARM TrustZone (BlackHat USA 2019)
	- slides: https://i.blackhat.com/USA-19/Thursday/us-19-Peterlin-Breaking-Samsungs-ARM-TrustZone.pdf
	- video: https://www.youtube.com/watch?v=uXH5LJGRwXI&list=PLH15HpR5qRsWrfkjwFSI256x1u2Zy49VI&index=30

- Launching feedback-driven fuzzing on TrustZone TEE (HITBGSEC2019)
	- https://gsec.hitb.org/materials/sg2019/D2%20-%20Launching%20Feedback-Driven%20Fuzzing%20on%20TrustZone%20TEE%20-%20Andrey%20Akimov.pdf

- A Deep Dive into Samsung's trustzone
	- (Part 1 - intro) https://blog.quarkslab.com/a-deep-dive-into-samsungs-trustzone-part-1.html
	- (Part 2 - fuzzing TAs) https://blog.quarkslab.com/a-deep-dive-into-samsungs-trustzone-part-2.html
	- (Part 3 - exploiting EL3) https://blog.quarkslab.com/a-deep-dive-into-samsungs-trustzone-part-3.html

## Samsung (TEEGRIS)

- Breaking TEE Security :
	- (Part 1 - Intro) https://www.riscure.com/blog/tee-security-samsung-teegris-part-1
	- (Part 2 - Exploiting TAs) https://www.riscure.com/blog/tee-security-samsung-teegris-part-2
	- (Part 3 - EoP TAs > TOS) https://www.riscure.com/blog/tee-security-samsung-teegris-part-3

- Reverse-engineering Samsung Exynos 9820 bootloader and TZ by @astarasikov
	- http://allsoftwaresucks.blogspot.com/2019/05/reverse-engineering-samsung-exynos-9820.html

- Bug Hunting S21’s 10ADAB1E FW (OffensiveCon 2022)
	- https://www.dropbox.com/s/2f14ga52jguu5cy/OffensiveCon%202022%20-%20Bug%20Hunting%20S21s%2010ADAB1E%20FW.pdf?dl=0

## Apple (Secure Enclave)

- Demystifying the Secure Enclave Processor by Tarjei Mandt, Mathew Solnik, and David Wang
	- http://mista.nu/research/sep-paper.pdf
	- *slides* https://www.blackhat.com/docs/us-16/materials/us-16-Mandt-Demystifying-The-Secure-Enclave-Processor.pdf

## Intel (Intel SGX)

- Intel SGX Explained by Victor Costan and Srinivas Devadas
	- https://css.csail.mit.edu/6.858/2017/readings/costan-sgx.pdf


# TEE Fuzzing

- PARTEMU: Enabling Dynamic Analysis of Real-World TrustZone Software Using Emulation
	- https://people.eecs.berkeley.edu/~rohanpadhye/files/partemu-usenixsec20.pdf

- The Road to Qualcomm TrustZone Apps Fuzzing
	- https://research.checkpoint.com/the-road-to-qualcomm-trustzone-apps-fuzzing/
	- https://cfp.recon.cx/media/tz_apps_fuzz.pdf

- Launching feedback-driven fuzzing on TrustZone TEE (HITB GSEC 2019 Singapore)
	- slides: https://gsec.hitb.org/materials/sg2019/D2%20-%20Launching%20Feedback-Driven%20Fuzzing%20on%20TrustZone%20TEE%20-%20Andrey%20Akimov.pdf
	- video: https://www.youtube.com/watch?v=yb7KGznzczs

- Fuzzing Embedded (Trusted) Operating Systems Using AFL (Martijn Bogaard | nullcon Goa 2019) OP-TEE
	- slides: https://nullcon.net/website/archives/pdf/bangalore-2019/fuzzing-embedded-(trusted)-operating-systems%20using-AFL.pdf
	- video: https://www.youtube.com/watch?v=AZhxZlwZ160
	- webinar: https://www.youtube.com/watch?time_continue=12&v=ROyD9RTMePA

- SAN19-225 Fuzzing embedded (trusted) operating systems using AFL (Martijn Bogaard) OP-TEE
	- video: https://www.youtube.com/watch?v=7bYAwaJ7WZw


# TEE Secure Boot

- Reverse Engineering Samsung S6 SBOOT - Part I & II
	- https://blog.quarkslab.com/reverse-engineering-samsung-s6-sboot-part-i.html
	- https://blog.quarkslab.com/reverse-engineering-samsung-s6-sboot-part-ii.html

- Secure initialization of TEEs: when secure boot falls short (EuskalHack 2017)
	- https://www.riscure.com/uploads/2017/08/euskalhack_2017_-_secure_initialization_of_tees_when_secure_boot_falls_short.pdf

- Amlogic S905 SoC: bypassing the (not so) Secure Boot to dump the BootROM
	- https://fredericb.info/2016/10/amlogic-s905-soc-bypassing-not-so.html#amlogic-s905-soc-bypassing-not-so

- Qualcomm Secure Boot and Image Authentication Technical Overview
	- https://www.qualcomm.com/documents/secure-boot-and-image-authentication-technical-overview-v20

- Breaking Samsung's Root of Trust - Exploiting Samsung Secure Boot (BlackHat 2020)
	- https://teamt5.org/en/posts/blackhat-s-talk-breaking-samsung-s-root-of-trust-exploiting-samsung-secure-boot/

- Overview of Secure Boot state in the ARM-based SoCs (Hardware-Aided Trusted Computing devroom - Maciej Pijanowski- FOSDEM 2021)
	- https://archive.fosdem.org/2021/schedule/event/tee_arm_secboot/attachments/paper/4635/export/events/attachments/tee_arm_secboot/paper/4635/Overview_of_Secure_Boot_in_Arm_based_SoCs.pdf

- Dive-Into-Android-TA-BugHunting-And-Fuzzing (Kanxue SDC 2023)
        - https://github.com/guluisacat/MySlides/blob/main/KanxueSDC2023/%E3%80%90%E8%AE%AE%E9%A2%98%E3%80%91%E6%B7%B1%E5%85%A5Android%E5%8F%AF%E4%BF%A1%E5%BA%94%E7%94%A8%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98.pdf

# TEE Videos

- Ekoparty-13 (2017) Daniel Komaromy - Unbox Your Phone - Exploring and Breaking Samsung's TrustZone SandBoxes
	- video: https://www.youtube.com/watch?v=L2Mo8WcmmZo
	- slides: https://github.com/puppykitten/tbase/blob/master/unboxyourphone_ekoparty.pdf

- Daniel Komaromy - Enter The Snapdragon (2014-10-11)
	- https://www.youtube.com/watch?v=2wJRnewVE-g

- BSides DC 2018 & DerbiCon VIII - On the nose: Bypassing Huaweis Fingerprint Authentication by Exploiting the TrustZone by Nick Stephens
	- https://www.youtube.com/watch?v=QFFhdqP7Dxg
	- https://www.youtube.com/watch?v=MdoGCXGHGnY

- An infestation of dragons: Exploring vulnerabilities in the ARM TrustZone architecture by Josh Thomas and Charles Holmes Android Security Symposium in Vienna, Austria, 9-11 September 2015
	- https://www.youtube.com/watch?v=vxNGgOR-iVM

- Android and trusted execution environments by Jan-Erik Ekberg (Trustonic) at the Android Security Symposium in Vienna, Austria, 9-11 September 2015
	- https://www.youtube.com/watch?v=5542lEk3OAM

- 34C3 2017 - Console Security - Switch by Plutoo, Derrek and Naehrwert
	- https://media.ccc.de/v/34c3-8941-console_security_-_switch

- 34C3 2017 - TrustZone is not enough by Pascal Cotret
	- https://media.ccc.de/v/34c3-8831-trustzone_is_not_enough

- RootedCON 2017 - What your mother never told you about Trusted Execution Environment... by José A. Rivas
	- *audio Spanish original* https://www.youtube.com/watch?v=lzrIzS84mdk
	- *English translation* https://www.youtube.com/watch?v=Lzb5OfE1M7s

- BH US 2015 - Fingerprints On Mobile Devices: Abusing And Leaking
	- https://www.youtube.com/watch?v=7NkojB9gLXM

- No ConName 2015 - (Un)Trusted Execution Environments by Pau Oliva
	- video: *audio Spanish only* https://vimeo.com/150787883
	- slides: https://t.co/vFATxEa7sy

- BH US 2014 - Reflections on Trusting TrustZone by Dan Rosenberg
	- https://www.youtube.com/watch?v=7w40mS5yLjc

- ARM TrustZone for dummies by Tim Hummels
	- https://www.youtube.com/watch?v=ecBByjwny3s

# Microarchitectural attacks applied to TEE

- ARMageddon: Cache attacks on mobile devices
    - [Paper] https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_lipp.pdf
    - [Related tool] https://github.com/IAIK/armageddon

- Cache storage channels: Alias-driven attacks and verified countermeasures.
    - https://www.kth.se/polopoly_fs/1.641701.1550155969!/R.Guanciale.pdf

- 34C3 - Microarchitectural Attacks on Trusted Execution Environments
    - https://media.ccc.de/v/34c3-8950-microarchitectural_attacks_on_trusted_execution_environments

- TruSpy: Cache side-channel information leakage from the secure world on ARM devices
    - https://eprint.iacr.org/2016/980.pdf


# Tools

## Emulate

- QEMU Support for Exynos9820 S-Boot
	- https://github.com/astarasikov/qemu

- Emulating Exynos 4210 BootROM in QEMU
	- https://fredericb.info/2018/03/emulating-exynos-4210-bootrom-in-qemu.html#emulating-exynos-4210-bootrom-in-qemu

## Reverse

- TZAR unpacker
	- https://gist.github.com/astarasikov/f47cb7f46b5193872f376fa0ea842e4b#file-unpack_startup_tzar-py

- IDA MCLF Loader
	- https://github.com/ghassani/mclf-ida-loader

- Ghidra MCLF Loader
	- https://github.com/NeatMonster/mclf-ghidra-loader

# Other useful resources

- ARM Trusted Firmware: reference implementation of secure world for Cortex A and Cortex M
	- https://www.trustedfirmware.org/

- OP-TEE: open source ARM TrusZone based TEE
	- https://www.op-tee.org/

- Trust Issues: Exploiting TrustZone TEEs by Project Zero Team
	- https://googleprojectzero.blogspot.com/2017/07/trust-issues-exploiting-trustzone-tees.html

- Boomerang: Exploiting the Semantic Gap in Trusted Execution Environments (A.Machiry) 2017
	- https://pdfs.semanticscholar.org/f62b/db9f1950329f59dc467238737d2de1a1bac4.pdf (slides)
	- http://sites.cs.ucsb.edu/~cspensky/pdfs/ndss17-final227.pdf (paper)
	- https://github.com/ucsb-seclab/boomerang (tool)

- TEE research (Some useful IDA and Ghidra plugins for TEE research)
	- https://github.com/bkerler/tee_research

