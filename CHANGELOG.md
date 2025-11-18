# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/3.0.1...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`3a34486`](https://github.com/lotusnoir/ansible-system_upgrade/commit/3a3448644900c2336ce0cc1326ceba04f50ed537)
- add oraclelinux10 support + lint and core fixes [`30e393b`](https://github.com/lotusnoir/ansible-system_upgrade/commit/30e393baa97a4c2bc269080e378a4ec79b4a45e9)

## [3.0.1](https://github.com/lotusnoir/ansible-system_upgrade/compare/3.0.0...3.0.1) - 2025-10-30

### Commits

- fix core lint [`b08603a`](https://github.com/lotusnoir/ansible-system_upgrade/commit/b08603a72e85471658cc86ed6f168d144513937e)

## [3.0.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`b24e320`](https://github.com/lotusnoir/ansible-system_upgrade/commit/b24e320a8045f3d015ed1032f9159c8da67f5a7a)
- update core, molecule + gitlab-ci [`1ff5e4c`](https://github.com/lotusnoir/ansible-system_upgrade/commit/1ff5e4c07b7c8322bad4f65b545095a1d9583623)
- print full to include the kept back that are in fact installed [`0e8aacc`](https://github.com/lotusnoir/ansible-system_upgrade/commit/0e8aacc3d93da932a9191445294bf35c325f44e6)
- fix lint [`4124599`](https://github.com/lotusnoir/ansible-system_upgrade/commit/412459991f7742292ba15da6861f9e1062f39b0c)
- fix molecule paralelism and little updates [`00d35ef`](https://github.com/lotusnoir/ansible-system_upgrade/commit/00d35efff1f29ae70d2a50347ca036b3a20b56ea)
- add support for ubuntu24 [`33cea00`](https://github.com/lotusnoir/ansible-system_upgrade/commit/33cea0006887e16b6ba9196c51b84689e1802202)
- fix module to avoid stuck on execution [`4ba8cc0`](https://github.com/lotusnoir/ansible-system_upgrade/commit/4ba8cc062bf0234d8e7cdc9790d38b450a99d2f0)
- add version on molecule play image to maintain support on old release [`3f76100`](https://github.com/lotusnoir/ansible-system_upgrade/commit/3f7610088972ff2e4a45bfebb3269506dff6d683)
- update molecule [`bf3aa2c`](https://github.com/lotusnoir/ansible-system_upgrade/commit/bf3aa2c3a2a7b61bf421d595017ecff0c4eb71c7)
- fix molecule tests [`e1806cc`](https://github.com/lotusnoir/ansible-system_upgrade/commit/e1806cc1f17f6293c8e46a1c2f37ac9d6c72bf44)

## [2.0.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`fa7359b`](https://github.com/lotusnoir/ansible-system_upgrade/commit/fa7359ba9b032f45ec26be9257fc81f21905832c)
- update readme + precommit + include vars [`089f0dc`](https://github.com/lotusnoir/ansible-system_upgrade/commit/089f0dc8764e994f52b7f863153d5d1c7b14c88b)
- change import tasks to include in order to support facts on name [`50f5b53`](https://github.com/lotusnoir/ansible-system_upgrade/commit/50f5b53f77ef1f090bed407e0d58243a02673dea)
- add option for kernel max keep on rehat [`b322be5`](https://github.com/lotusnoir/ansible-system_upgrade/commit/b322be51cba5daa9bd8a54609c4ae84a0313ea1e)
- remove too restricted clean condition for debian [`6b6a68d`](https://github.com/lotusnoir/ansible-system_upgrade/commit/6b6a68d25dd011040a8b897de5b631971b975377)

## [1.1.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`78adb6e`](https://github.com/lotusnoir/ansible-system_upgrade/commit/78adb6e000787cb128d65b222fb5141b12fec715)

## [1.0.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`0fd8c13`](https://github.com/lotusnoir/ansible-system_upgrade/commit/0fd8c13bc625715f23d4b49bbff08484f3c4c1f9)
- add precommit for lint [`c312562`](https://github.com/lotusnoir/ansible-system_upgrade/commit/c312562f9cb6047e57395d255952e719883bc91e)
- fix checks [`343e538`](https://github.com/lotusnoir/ansible-system_upgrade/commit/343e53817f6f379facdee74d9efa91307cc865da)
- add new molecule all scenario [`87fcefc`](https://github.com/lotusnoir/ansible-system_upgrade/commit/87fcefc9534a599b90f42c7fbc3abb1e3d107a9a)
- fix redhat [`5838e30`](https://github.com/lotusnoir/ansible-system_upgrade/commit/5838e30699732e5eb67b8b9367a24a74f18294c4)
- ignore command-instead-of-module ansible-lint [`8224b63`](https://github.com/lotusnoir/ansible-system_upgrade/commit/8224b6378159af5b3ef60b7a1b59de73fdbf972f)
- update checks [`a783f5b`](https://github.com/lotusnoir/ansible-system_upgrade/commit/a783f5b8bff59a6d40d32f22e645445a53c02198)
- fix test and pipeline [`ed6b995`](https://github.com/lotusnoir/ansible-system_upgrade/commit/ed6b9954411b47cf18cfb4855f3419e4b47b0341)
- changes on molecule [`f99ee2a`](https://github.com/lotusnoir/ansible-system_upgrade/commit/f99ee2a14be6740b5e12f58a14ef34ccaa27a8c0)
- fix: replace dnf by yum [`097854b`](https://github.com/lotusnoir/ansible-system_upgrade/commit/097854b9cd08164969eb01744b31d5d3c29c9293)

## [0.3.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`4855d44`](https://github.com/lotusnoir/ansible-system_upgrade/commit/4855d445cefde75b77a443931b2b8199d783d81f)
- minor: add oracleLinux support + little fixes [`083e695`](https://github.com/lotusnoir/ansible-system_upgrade/commit/083e6959a0ebf0a4497c544ed9fa3cd84b80501b)

## [0.2.0](https://github.com/lotusnoir/ansible-system_upgrade/compare/0.1.0...0.2.0) - 2022-06-01

### Commits

- add jammy release support + lint fix [`be3e338`](https://github.com/lotusnoir/ansible-system_upgrade/commit/be3e3385096ee2fa0b2cc9e68d0ec50cb314db5a)
- fix: remove unsupported centos8 + minor fixes [`a9561b7`](https://github.com/lotusnoir/ansible-system_upgrade/commit/a9561b7a6c1adb96b83cc0dbec945721488a1701)

## 0.1.0 - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`ef0eacd`](https://github.com/lotusnoir/ansible-system_upgrade/commit/ef0eacdff9616a9c2bb069de574d007ffc12bbbc)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`91eff97`](https://github.com/lotusnoir/ansible-system_upgrade/commit/91eff97c78e9eccbb43ff66f6580fe1ce4f02223)
- fix: licence type [`2fd07a9`](https://github.com/lotusnoir/ansible-system_upgrade/commit/2fd07a9441ca71eb5a5d1d543b137663eba554b5)
- initial commit [`b6d1bf2`](https://github.com/lotusnoir/ansible-system_upgrade/commit/b6d1bf245a1c1588999e1c0776fa174f7eea4ce5)
