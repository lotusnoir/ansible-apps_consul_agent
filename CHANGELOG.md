# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v4.0.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/3.3.0...v4.0.0) - 2025-10-09

### Commits

- update gitlab-ci [`f4e6372`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/f4e637244325f8e8a803d3cf983e58ef429a20ef)
- update gitlab-ci [`5116638`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/51166385b8a956a5826d3ec5dba82c979aac5423)
- fix systemd path [`61c9fa8`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/61c9fa8dcf3306ccdb1668e0ff661c3fe856b53e)
- change role_path and scenario on molecule [`cef00be`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/cef00be9e8928d093954125e66549e28ad0710f1)
- add latest feature for version [`5e3c322`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5e3c3220e618eafb4b5edc285b91a58c1aaa6dd4)
- add verify.yml [`e100720`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/e100720cb79e80d4e2b7da9fcbbeecb8e414e2ef)
- add molecule tune + small fixes [`04e79d6`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/04e79d68433b7bf838971da8737e434d9b7f0996)
- create new vars and rename some tasks [`d51b0ef`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/d51b0ef330738538058eade10a3c237889f8caf9)
- add redhat repo install [`7706d42`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7706d42e78256b28c26cd98b3dcb063b20f4a2d1)
- rebuild role with multiple install possibilities + benchmark [`8ac75a1`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/8ac75a1ec831b88f3028becf5fea3e046647943b)
- change molecule output [`c292b64`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/c292b64a25ed8669178516ba51a22a7da9954c74)
- rebuild install [`ba1b896`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/ba1b8966881b560d87d70ab2fedf1432bc3539d3)
- fix lint [`cbca97f`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/cbca97f31c9745bd63038c0b0679e885b204405f)
- fix molecule paralelism and little updates [`0a701a0`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/0a701a0644ff6d0a136b345c47f517a7c6e793d4)
- fix unavailable package on redhat [`750344c`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/750344c16cb487425a559df0154fa65704572384)
- update and remove unsupported ubuntu18 [`0e842d6`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/0e842d6b54008750c52a61fbd5e9b75a338cf80f)
- fix [`9d8791d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/9d8791d70984ea9e5377b9e195404e235ef78276)
- add support for ubuntu24 [`48c2cc4`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/48c2cc40360cb75a97f22a4ae966acf55982d254)
- add version on molecule play image to maintain support on old release [`3525b04`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/3525b04d34b92e358368550e732d58737aede5e8)
- remove support for debian10 / ubuntu18 / redhat8 [`7fa09e7`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7fa09e781d002f98a85265f692b2209044edfe67)
- update molecule [`a1b9e56`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/a1b9e56d2fe247f9a02ee1d2b06c0602e6cc1a7f)
- add redhat 9 to default supported distrib [`bdfc6fd`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/bdfc6fd07572deebc254cb47af4415735dc64476)
- fix requirement packages fore redhat [`6962336`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/69623364680db5248b68f78419e542cf51ddc340)
- remove redhat molecule checks [`525c00d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/525c00db2f25a23870018c235f735b04ea0d1298)
- add redhat 8 to default supported distrib [`42dda55`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/42dda550835c16fc6730693288f87d6c6f3f30e3)
- sort testing distrib to avoid random changes [`0a3ef4e`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/0a3ef4e7da66a7fa707246c9fab4e3aa32288d2a)
- update pre-commit and lint fix [`603a577`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/603a577e1bc6036a77b4e593d7e3f4ea8eebf590)
- condition on handler if no binary installed [`2fa5853`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/2fa5853ad2fc6f6ea448129527b8b77aafc13e5e)
- split dir create in order to create consul.d separatelly [`aaa82b6`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/aaa82b6e167b253545f141810321d33b2cadaf08)
- add variables to split install tasks [`4af20d5`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/4af20d5f9bebf03b8b8238957a51c01b72908cad)
- update version and add skip install variable [`d27ec29`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/d27ec2956762b849658b3ffd99629ea7b9f7be48)
- remove support for rhel7 and docker dind on gitlab [`fc0aae9`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/fc0aae921ea3ed32bbfbe02690e21bf4b7e5e474)
- remove unsupported rhel7 [`d4a0972`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/d4a09725ab7838433bbf81096dda9c3c4b00d120)
- remove lint from pipeline [`12a6539`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/12a653930cac36c0c43dc4fa1d84d352c3da21ff)
- remove pipelines tests, moved in precommits [`74c80b3`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/74c80b39058ae859dd3a83571f89b23b989554cd)
- add retries on packages install, to avoid error if temp pkg lock [`1c1a7c0`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/1c1a7c06b190d2d60e75a5f2f348fcabd3a4753d)
- change facts var to be able to surcharge them on a pre_tasks [`60af073`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/60af0733001bc7f8b68106777c46e20fa4cee773)
- update vars [`9a735f2`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/9a735f29039d1a5626d78bc69e8dc2fe54b348c2)
- fix missing vars for rhel8 [`ee96e3c`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/ee96e3c6259299dfda694d059fbc61c6bff625a0)
- fix bad comments on json file [`c745109`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/c7451097c140b10919b2472b5b09a2f48e3a7ac3)
- update readme + precommit + include vars [`5fab44a`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5fab44adc898b44d2b2ba0dae4003933e98d8afb)
- add ansible comment on template files [`5012d03`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5012d0354125bb49ab43f8525e1797c71b6d39af)
- change import tasks to include in order to support facts on name [`7a32bb2`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7a32bb2f16d8ef8f8a865d0af05613a9609d7c2d)
- prevent install folder to have the right change [`03d95b7`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/03d95b7438f502868402b019a427c4da09ab07fb)
- fix lint [`a72b030`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/a72b030c97a62ec187e8bb7cb0d420f40bdb1715)
- Revert "add comment on templates" [`5a85a52`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5a85a52b13e3d8835420fdf40ab5e8d617499dc7)
- add comment on templates [`32e3cac`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/32e3cac4a26fcb7a28ab25cde6bf7262ac08b1ee)
- add  config_d management [`7bfde24`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7bfde240d32f6867fe8a250e27b704f775b170b3)
- add code of conduc and small changes [`225ff26`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/225ff26a16e9bc1af8072b444b4ed0ddb8e2d6d3)
- add precommit for lint [`f68a241`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/f68a241427516033798a2df01389e32e1b30495e)

## [3.2.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/3.1.0...3.2.0) - 2025-10-09

### Commits

- fix unavailable package on redhat [`2ca6572`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/2ca6572181ec86598c12ac1a97c39145e4fe0545)
- fix [`882b917`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/882b917b80b3fe51c768618a6040ce5f2be4f53d)
- add support for ubuntu24 [`a85f7d4`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/a85f7d44017bba89f67232090becf555dc03c165)
- add version on molecule play image to maintain support on old release [`9c352a8`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/9c352a8a11438609574251132923a9cf62dda8c3)
- remove support for debian10 / ubuntu18 / redhat8 [`0aeee3d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/0aeee3d11a417ad9d0cda1ec2a449756645ddde0)
- update molecule [`8bca1f5`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/8bca1f5b0cf9fb1a0865dd9739aaf045eb78ba61)
- add redhat 9 to default supported distrib [`56d85f3`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/56d85f3a05fcdd6f49e1139436a801eaaaa4752a)
- fix requirement packages fore redhat [`6223d23`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/6223d232aee0a484965de23f53df7a1b41081987)
- remove redhat molecule checks [`604676d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/604676de209d2cb2e98acfb4b8d03aff2e741d91)
- sort testing distrib to avoid random changes [`d48bbb0`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/d48bbb048f5923942d01c4a34962074ab5641932)
- doc: update changelog [`c7a3749`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/c7a374972aeef73fd92e34f63f1ed29b3d9dd992)

## [3.1.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/3.0.0...3.1.0) - 2025-10-09

### Commits

- update pre-commit and lint fix [`1e9a12d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/1e9a12dc720b7b44b82319a55f6a49d8299523fa)
- condition on handler if no binary installed [`7a8fe34`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7a8fe3427c3927df9be2dc7c40ad93e77c3c2faa)
- split dir create in order to create consul.d separatelly [`7e14796`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/7e14796dcc08f0839ed73e6ff5ad8ab85b3fb287)
- add variables to split install tasks [`1336956`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/13369563212286635d84b4f1c1920c3dce789079)
- update version and add skip install variable [`eb0bf9a`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/eb0bf9ac18471781d4cd24159add53df9adb40a2)
- remove support for rhel7 and docker dind on gitlab [`8a2e5da`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/8a2e5dac94d6831d654e8878e704dbfe28ca604a)
- remove unsupported rhel7 [`8def026`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/8def0268eb3b466b135aa87427d47b0a29b0913f)
- add retries on packages install, to avoid error if temp pkg lock [`585510e`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/585510eb1b4e16b769dc98c3966527c6e2bef396)
- change facts var to be able to surcharge them on a pre_tasks [`b4fd7d9`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/b4fd7d9945244352b94525fd26adffdbd19e6245)

## [3.0.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/2.0.0...3.0.0) - 2025-10-09

### Commits

- doc: update changelog [`281b585`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/281b585972797664c51a72e21d31037f2dcd7f43)

## [2.0.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/1.1.0...2.0.0) - 2025-10-09

### Commits

- update vars [`75329d3`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/75329d353695522d41d0342a5e98172cadfe18e5)
- fix missing vars for rhel8 [`2d58584`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/2d58584357cb7ca8b56b4b5f2a438809a093a979)
- change import tasks to include in order to support facts on name [`bb8f7f5`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/bb8f7f54d760e8d6d4d1cb9bdccb4aabbc19e170)
- prevent install folder to have the right change [`58b102d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/58b102d2e6fedd77d11972311f6711e151502563)
- fix lint [`378e18a`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/378e18ab6c3929ea512f7605510911758fc500cc)
- doc: update changelog [`9983071`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/99830716137bdf94f9de06f4c00df4e1c7acedd4)

## [1.0.0](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/compare/0.1.0...1.0.0) - 2025-10-09

### Commits

- add  config_d management [`b18ccfb`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/b18ccfbfb248e30b7e29f7295aaa45db785283d0)
- doc: update changelog [`95f6ef5`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/95f6ef5cb9b29b270965bddec2570d2993a14bfd)

## 0.1.0 - 2025-10-09

### Commits

- add code of conduc and small changes [`62585ef`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/62585ef440303f10439f8c80673b9590801c733a)
- add precommit for lint [`14c5464`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/14c546438621ffbf87264d9fe1086611921cfcc2)
- change default [`055950d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/055950d942b5f926eaf666e2a408ad3253bdbfcc)
- fix checks [`592c501`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/592c501aaa084fd48bf7fba9c786312139409459)
- add new molecule all scenario [`6db3daf`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/6db3daf9b0f10472645d8fc20a2630de809cef57)
- fix molecule failure [`5eb77b2`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5eb77b2092bc03adb4e52cad1e792110d5d3c2bb)
- update readme [`753a101`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/753a1010a348cc41e5dcd29b3887093115a9b6d6)
- change vars and just install by default [`5a4b360`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5a4b360ccdaf25ee59a5ef96059260016d643a91)
- split distro for molecule tests on ci [`dff123d`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/dff123d8663b4784e15e83ee73045005d8a3b1bc)
- test [`0135152`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/0135152f810b423394b61c6a9feeca034d630104)
- update checks and Readme [`4a25e47`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/4a25e47fdb0caf09ccb1abccecb2664a31572472)
- add molecule fix for ora9 [`a2ff7ef`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/a2ff7ef885b7afbf880dc5db4d3d16f6331d08e2)
- add ora9 support [`a7364a9`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/a7364a933a911ed84529615c364dbe2144274fb7)
- lint [`bf51ae2`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/bf51ae2ee20a68349898124c0024ecd48fcde666)
- update version [`abdd1e5`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/abdd1e58372d7290047fbb697fd36c1501a4c418)
- test epel repo present [`14fc262`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/14fc262fd255e3ac386edec94a44b25b6cee79ce)
- fix checks [`57f600e`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/57f600e23fb3dec713e17dd565179b23f4c7dd7b)
- lint: fix trailing space [`ad88a14`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/ad88a14f5439e98cfa622aed7c6eba58a3876ce9)
- remove apt cache / idempotence fail [`3508bb8`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/3508bb836082ef2197ba4cf543fe4a8067de350d)
- initial commit [`5e8778c`](https://gitlab.pleal.ovh/ansible-roles_base/ansible-apps_consul_agent/commit/5e8778c692aef706158a9b2c1f26d5920632fd9f)
