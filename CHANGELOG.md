# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0](https://github.com/lotusnoir/ansible-apps_consul_agent/compare/3.0.0...3.1.0) - 2024-03-13

### Commits

- update pre-commit and lint fix [`1e9a12d`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/1e9a12dc720b7b44b82319a55f6a49d8299523fa)
- condition on handler if no binary installed [`7a8fe34`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/7a8fe3427c3927df9be2dc7c40ad93e77c3c2faa)
- split dir create in order to create consul.d separatelly [`7e14796`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/7e14796dcc08f0839ed73e6ff5ad8ab85b3fb287)
- add variables to split install tasks [`1336956`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/13369563212286635d84b4f1c1920c3dce789079)
- update version and add skip install variable [`eb0bf9a`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/eb0bf9ac18471781d4cd24159add53df9adb40a2)
- remove support for rhel7 and docker dind on gitlab [`8a2e5da`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/8a2e5dac94d6831d654e8878e704dbfe28ca604a)
- remove unsupported rhel7 [`8def026`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/8def0268eb3b466b135aa87427d47b0a29b0913f)
- add retries on packages install, to avoid error if temp pkg lock [`585510e`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/585510eb1b4e16b769dc98c3966527c6e2bef396)
- change facts var to be able to surcharge them on a pre_tasks [`b4fd7d9`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/b4fd7d9945244352b94525fd26adffdbd19e6245)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_consul_agent/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`75329d3`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/75329d353695522d41d0342a5e98172cadfe18e5)
- fix missing vars for rhel8 [`2d58584`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/2d58584357cb7ca8b56b4b5f2a438809a093a979)
- change import tasks to include in order to support facts on name [`bb8f7f5`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/bb8f7f54d760e8d6d4d1cb9bdccb4aabbc19e170)
- prevent install folder to have the right change [`58b102d`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/58b102d2e6fedd77d11972311f6711e151502563)
- fix lint [`378e18a`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/378e18ab6c3929ea512f7605510911758fc500cc)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_consul_agent/compare/0.1.0...1.0.0) - 2023-04-07

### Commits

- add  config_d management [`b18ccfb`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/b18ccfbfb248e30b7e29f7295aaa45db785283d0)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`62585ef`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/62585ef440303f10439f8c80673b9590801c733a)
- add precommit for lint [`14c5464`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/14c546438621ffbf87264d9fe1086611921cfcc2)
- change default [`055950d`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/055950d942b5f926eaf666e2a408ad3253bdbfcc)
- fix checks [`592c501`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/592c501aaa084fd48bf7fba9c786312139409459)
- add new molecule all scenario [`6db3daf`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/6db3daf9b0f10472645d8fc20a2630de809cef57)
- fix molecule failure [`5eb77b2`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/5eb77b2092bc03adb4e52cad1e792110d5d3c2bb)
- update readme [`753a101`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/753a1010a348cc41e5dcd29b3887093115a9b6d6)
- change vars and just install by default [`5a4b360`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/5a4b360ccdaf25ee59a5ef96059260016d643a91)
- split distro for molecule tests on ci [`dff123d`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/dff123d8663b4784e15e83ee73045005d8a3b1bc)
- test [`0135152`](https://github.com/lotusnoir/ansible-apps_consul_agent/commit/0135152f810b423394b61c6a9feeca034d630104)
