
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

 .. NOTE! THIS FILE IS AUTOMATICALLY GENERATED AND WILL BE OVERWRITTEN!

 .. IF YOU WANT TO MODIFY THIS FILE, YOU SHOULD MODIFY THE TEMPLATE
    `PROVIDER_COMMITS_TEMPLATE.rst.jinja2` IN the `dev/breeze/src/airflow_breeze/templates` DIRECTORY

 .. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN!

Package apache-airflow-providers-asana
------------------------------------------------------

`Asana <https://asana.com/>`__


This is detailed commit list of changes for versions provider package: ``asana``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.9.1
.....

Latest change: 2025-03-05

==================================================================================================  ===========  =====================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =====================================================================
`e4002c3305 <https://github.com/apache/airflow/commit/e4002c3305a757f5926f96c996e701e8f998a042>`__  2025-03-05   ``Move tests_common package to devel-common project (#47281)``
`1addb55154 <https://github.com/apache/airflow/commit/1addb55154fbef31bfa021537cfbd4395696381c>`__  2025-02-28   ``Improve documentation for updating provider dependencies (#47203)``
`c6c4f95ed9 <https://github.com/apache/airflow/commit/c6c4f95ed9e3220133815b9126c135e805637022>`__  2025-02-25   ``Add legacy namespace packages to airflow.providers (#47064)``
`dbf8bb4092 <https://github.com/apache/airflow/commit/dbf8bb409223687c7d2ad10649a92d02c24bb3b4>`__  2025-02-24   ``Remove extra whitespace in provider readme template (#46975)``
`b28c336e8b <https://github.com/apache/airflow/commit/b28c336e8b7aa1d69c0f9520b182b1b661377337>`__  2025-02-21   ``Upgrade flit to 3.11.0 (#46938)``
==================================================================================================  ===========  =====================================================================

2.9.0
.....

Latest change: 2025-02-21

==================================================================================================  ===========  =========================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =========================================================================
`0653ffe78e <https://github.com/apache/airflow/commit/0653ffe78e4a0acaf70801a5ceef8dbabdac8b15>`__  2025-02-21   ``Prepare docs for Feb 1st wave of providers (fixed) (#46962)``
`5d87bddf0a <https://github.com/apache/airflow/commit/5d87bddf0aa5f485f3684c909fb95f461e5a2ab6>`__  2025-02-21   ``Prepare docs for Feb 1st wave of providers (#46893)``
`4d5846f58f <https://github.com/apache/airflow/commit/4d5846f58fe0de9b43358c0be75dd72e968dacc4>`__  2025-02-16   ``Move provider_tests to unit folder in provider tests (#46800)``
`e027457a24 <https://github.com/apache/airflow/commit/e027457a24d0c6235bfed9c2a8399f75342e82f1>`__  2025-02-15   ``Removed the unused provider's distribution (#46608)``
`344451b85a <https://github.com/apache/airflow/commit/344451b85a9ff44659630686dd991caf777f1ddd>`__  2025-02-07   ``Adapt Asana Provider to Asana Client >=5.0.0 (#46553)``
`ee6bd7ee16 <https://github.com/apache/airflow/commit/ee6bd7ee162ff295b86d86fdd1b356c51b9bba78>`__  2025-02-03   ``Fix doc issues found with recent moves (#46372)``
`b6e802eb01 <https://github.com/apache/airflow/commit/b6e802eb01f4aaf97cbb7fa5f5d05017d6d552ed>`__  2025-01-26   ``Move ASANA provider to new structure (#46081)``
`f616c62209 <https://github.com/apache/airflow/commit/f616c62209d6b51d293ecf6f5c900f89a7fdc3a3>`__  2025-01-15   ``AIP-72: Support better type-hinting for Context dict in SDK  (#45583)``
==================================================================================================  ===========  =========================================================================

2.7.0
.....

Latest change: 2024-12-20

==================================================================================================  ===========  ========================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ========================================================================================
`2723508345 <https://github.com/apache/airflow/commit/2723508345d5cf074aeb673955ce72996785f2bc>`__  2024-12-20   ``Prepare docs for Nov 1st wave of providers Dec 2024 (#45042)``
`35b927fe17 <https://github.com/apache/airflow/commit/35b927fe177065dad0e00c49d72b494e58b27ca8>`__  2024-12-19   ``Update path of example dags in docs (#45069)``
`4b38bed76c <https://github.com/apache/airflow/commit/4b38bed76c1ea5fe84a6bc678ce87e20d563adc0>`__  2024-12-16   ``Bump min version of Providers to 2.9 (#44956)``
`4dfae23532 <https://github.com/apache/airflow/commit/4dfae23532d26ed838069c49d48f28c185e954c6>`__  2024-11-15   ``Update DAG example links in multiple providers documents (#44034)``
`a53d9f6d25 <https://github.com/apache/airflow/commit/a53d9f6d257f193ea5026ba4cd007d5ddeab968f>`__  2024-11-14   ``Prepare docs for Nov 1st wave of providers (#44011)``
`857ca4c06c <https://github.com/apache/airflow/commit/857ca4c06c9008593674cabdd28d3c30e3e7f97b>`__  2024-10-09   ``Split providers out of the main "airflow/" tree into a UV workspace project (#42505)``
==================================================================================================  ===========  ========================================================================================

2.6.0
.....

Latest change: 2024-08-19

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`75fb7acbac <https://github.com/apache/airflow/commit/75fb7acbaca09a040067f0a5a37637ff44eb9e14>`__  2024-08-19   ``Prepare docs for Aug 2nd wave of providers (#41559)``
`fcbff15bda <https://github.com/apache/airflow/commit/fcbff15bda151f70db0ca13fdde015bace5527c4>`__  2024-08-12   ``Bump minimum Airflow version in providers to Airflow 2.8.0 (#41396)``
==================================================================================================  ===========  =======================================================================

2.5.1
.....

Latest change: 2024-05-26

==================================================================================================  ===========  ================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ================================================
`34500f3a2f <https://github.com/apache/airflow/commit/34500f3a2fa4652272bc831e3c18fd2a6a2da5ef>`__  2024-05-26   ``Prepare docs 3rd wave May 2024 (#39738)``
`2b1a2f8d56 <https://github.com/apache/airflow/commit/2b1a2f8d561e569df194c4ee0d3a18930738886e>`__  2024-05-11   ``Reapply templates for all providers (#39554)``
`2c05187b07 <https://github.com/apache/airflow/commit/2c05187b07baf7c41a32b18fabdbb3833acc08eb>`__  2024-05-10   ``Faster 'airflow_version' imports (#39552)``
`73918925ed <https://github.com/apache/airflow/commit/73918925edaf1c94790a6ad8bec01dec60accfa1>`__  2024-05-08   ``Simplify 'airflow_version' imports (#39497)``
==================================================================================================  ===========  ================================================

2.5.0
.....

Latest change: 2024-05-01

==================================================================================================  ===========  ============================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ============================================================================
`fe4605a10e <https://github.com/apache/airflow/commit/fe4605a10e26f1b8a180979ba5765d1cb7fb0111>`__  2024-05-01   ``Prepare docs 1st wave May 2024 (#39328)``
`ead9b00f7c <https://github.com/apache/airflow/commit/ead9b00f7cd5acecf9d575c459bb62633088436a>`__  2024-04-25   ``Bump minimum Airflow version in providers to Airflow 2.7.0 (#39240)``
`5fa80b6aea <https://github.com/apache/airflow/commit/5fa80b6aea60f93cdada66f160e2b54f723865ca>`__  2024-04-10   ``Prepare docs 1st wave (RC1) April 2024 (#38863)``
`0a74928894 <https://github.com/apache/airflow/commit/0a74928894fb57b0160208262ccacad12da23fc7>`__  2024-03-18   ``Bump ruff to 0.3.3 (#38240)``
`83316b8158 <https://github.com/apache/airflow/commit/83316b81584c9e516a8142778fc509f19d95cc3e>`__  2024-03-04   ``Prepare docs 1st wave (RC1) March 2024 (#37876)``
`5a0be392e6 <https://github.com/apache/airflow/commit/5a0be392e66f8e5426ba3478621115e92fcf245b>`__  2024-02-16   ``Add comment about versions updated by release manager (#37488)``
`bfb054e9e8 <https://github.com/apache/airflow/commit/bfb054e9e867b8b9a6a449e43bfba97f645e025e>`__  2024-02-12   ``Prepare docs 1st wave of Providers February 2024 (#37326)``
`cead3da4a6 <https://github.com/apache/airflow/commit/cead3da4a6f483fa626b81efd27a24dcb5a36ab0>`__  2024-01-26   ``Add docs for RC2 wave of providers for 2nd round of Jan 2024 (#37019)``
`2b4da0101f <https://github.com/apache/airflow/commit/2b4da0101f0314989d148c3c8a02c87e87048974>`__  2024-01-22   ``Prepare docs 2nd wave of Providers January 2024 (#36945)``
`19ebcac239 <https://github.com/apache/airflow/commit/19ebcac2395ef9a6b6ded3a2faa29dc960c1e635>`__  2024-01-07   ``Prepare docs 1st wave of Providers January 2024 (#36640)``
`6937ae7647 <https://github.com/apache/airflow/commit/6937ae76476b3bc869ef912d000bcc94ad642db1>`__  2023-12-30   ``Speed up autocompletion of Breeze by simplifying provider state (#36499)``
==================================================================================================  ===========  ============================================================================

2.4.1
.....

Latest change: 2023-12-23

==================================================================================================  ===========  ==================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ==================================================================================
`b15d5578da <https://github.com/apache/airflow/commit/b15d5578dac73c4c6a3ca94d90ab0dc9e9e74c9c>`__  2023-12-23   ``Re-apply updated version numbers to 2nd wave of providers in December (#36380)``
`f5883d6e7b <https://github.com/apache/airflow/commit/f5883d6e7be83f1ab9468e67164b7ac381fdb49f>`__  2023-12-23   ``Prepare 2nd wave of providers in December (#36373)``
`cd476acd8f <https://github.com/apache/airflow/commit/cd476acd8f1684f613c20dddaa9e988bcfb3ac1c>`__  2023-12-11   ``Follow BaseHook connection fields method signature in child classes (#36086)``
==================================================================================================  ===========  ==================================================================================

2.4.0
.....

Latest change: 2023-12-08

==================================================================================================  ===========  ========================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ========================================================================
`999b70178a <https://github.com/apache/airflow/commit/999b70178a1f5d891fd2c88af4831a4ba4c2cbc9>`__  2023-12-08   ``Prepare docs 1st wave of Providers December 2023 (#36112)``
`d0918d77ee <https://github.com/apache/airflow/commit/d0918d77ee05ab08c83af6956e38584a48574590>`__  2023-12-07   ``Bump minimum Airflow version in providers to Airflow 2.6.0 (#36017)``
`c905fe88de <https://github.com/apache/airflow/commit/c905fe88de6382cbf610b1fffa0159a7a0b5558f>`__  2023-11-25   ``Update information about links into the provider.yaml files (#35837)``
`0b23d5601c <https://github.com/apache/airflow/commit/0b23d5601c6f833392b0ea816e651dcb13a14685>`__  2023-11-24   ``Prepare docs 2nd wave of Providers November 2023 (#35836)``
`99534e47f3 <https://github.com/apache/airflow/commit/99534e47f330ce0efb96402629dda5b2a4f16e8f>`__  2023-11-19   ``Use reproducible builds for provider packages (#35693)``
`99df205f42 <https://github.com/apache/airflow/commit/99df205f42a754aa67f80b5983e1d228ff23267f>`__  2023-11-16   ``Fix and reapply templates for provider documentation (#35686)``
`1b059c57d6 <https://github.com/apache/airflow/commit/1b059c57d6d57d198463e5388138bee8a08591b1>`__  2023-11-08   ``Prepare docs 1st wave of Providers November 2023 (#35537)``
`706878ec35 <https://github.com/apache/airflow/commit/706878ec354cf867440c367a95c85753c19e54de>`__  2023-11-04   ``Remove empty lines in generated changelog (#35436)``
`052e26ad47 <https://github.com/apache/airflow/commit/052e26ad473a9d50f0b96456ed094f2087ee4434>`__  2023-11-04   ``Change security.rst to use includes in providers (#35435)``
`d1c58d86de <https://github.com/apache/airflow/commit/d1c58d86de1267d9268a1efe0a0c102633c051a1>`__  2023-10-28   ``Prepare docs 3rd wave of Providers October 2023 - FIX (#35233)``
`3592ff4046 <https://github.com/apache/airflow/commit/3592ff40465032fa041600be740ee6bc25e7c242>`__  2023-10-28   ``Prepare docs 3rd wave of Providers October 2023 (#35187)``
`dd7ba3cae1 <https://github.com/apache/airflow/commit/dd7ba3cae139cb10d71c5ebc25fc496c67ee784e>`__  2023-10-19   ``Pre-upgrade 'ruff==0.0.292' changes in providers (#35053)``
`f23170c9dd <https://github.com/apache/airflow/commit/f23170c9dd23556a40bd07b5d24f06220eec15c4>`__  2023-10-16   ``D401 Support - A thru Common (Inclusive) (#34934)``
==================================================================================================  ===========  ========================================================================

2.3.0
.....

Latest change: 2023-10-13

==================================================================================================  ===========  =======================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =======================================================================
`e9987d5059 <https://github.com/apache/airflow/commit/e9987d50598f70d84cbb2a5d964e21020e81c080>`__  2023-10-13   ``Prepare docs 1st wave of Providers in October 2023 (#34916)``
`0c8e30e43b <https://github.com/apache/airflow/commit/0c8e30e43b70e9d033e1686b327eb00aab82479c>`__  2023-10-05   ``Bump min airflow version of providers (#34728)``
`21990ed894 <https://github.com/apache/airflow/commit/21990ed8943ee4dc6e060ee2f11648490c714a3b>`__  2023-09-08   ``Prepare docs for 09 2023 - 1st wave of Providers (#34201)``
`c077d19060 <https://github.com/apache/airflow/commit/c077d190609f931387c1fcd7b8cc34f12e2372b9>`__  2023-08-26   ``Prepare docs for Aug 2023 3rd wave of Providers (#33730)``
`c645d8e40c <https://github.com/apache/airflow/commit/c645d8e40c167ea1f6c332cdc3ea0ca5a9363205>`__  2023-08-12   ``D401 Support - Providers: Airbyte to Atlassian (Inclusive) (#33354)``
==================================================================================================  ===========  =======================================================================

2.2.2
.....

Latest change: 2023-08-05

==================================================================================================  ===========  ===============================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ===============================================================================
`60677b0ba3 <https://github.com/apache/airflow/commit/60677b0ba3c9e81595ec2aa3d4be2737e5b32054>`__  2023-08-05   ``Prepare docs for Aug 2023 1st wave of Providers (#33128)``
`679c5b6177 <https://github.com/apache/airflow/commit/679c5b617752e060d3e9259e9ab12f7696805f39>`__  2023-08-01   ``Limit Asana Python client until provider is adapted to 4.* version (#32995)``
`73b90c48b1 <https://github.com/apache/airflow/commit/73b90c48b1933b49086d34176527947bd727ec85>`__  2023-07-21   ``Allow configuration to be contributed by providers (#32604)``
`225e3041d2 <https://github.com/apache/airflow/commit/225e3041d269698d0456e09586924c1898d09434>`__  2023-07-06   ``Prepare docs for July 2023 wave of Providers (RC2) (#32381)``
`3878fe6fab <https://github.com/apache/airflow/commit/3878fe6fab3ccc1461932b456c48996f2763139f>`__  2023-07-05   ``Remove spurious headers for provider changelogs (#32373)``
`cb4927a018 <https://github.com/apache/airflow/commit/cb4927a01887e2413c45d8d9cb63e74aa994ee74>`__  2023-07-05   ``Prepare docs for July 2023 wave of Providers (#32298)``
`8c37b74a20 <https://github.com/apache/airflow/commit/8c37b74a208a808d905c1b86d081d69d7a1aa900>`__  2023-06-28   ``D205 Support - Providers: Apache to Common (inclusive) (#32226)``
`09d4718d3a <https://github.com/apache/airflow/commit/09d4718d3a46aecf3355d14d3d23022002f4a818>`__  2023-06-27   ``Improve provider documentation and README structure (#32125)``
==================================================================================================  ===========  ===============================================================================

2.2.1
.....

Latest change: 2023-06-20

==================================================================================================  ===========  =============================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =============================================================
`79bcc2e668 <https://github.com/apache/airflow/commit/79bcc2e668e648098aad6eaa87fe8823c76bc69a>`__  2023-06-20   ``Prepare RC1 docs for June 2023 wave of Providers (#32001)``
`8b146152d6 <https://github.com/apache/airflow/commit/8b146152d62118defb3004c997c89c99348ef948>`__  2023-06-20   ``Add note about dropping Python 3.7 for providers (#32015)``
`9276310a43 <https://github.com/apache/airflow/commit/9276310a43d17a9e9e38c2cb83686a15656896b2>`__  2023-06-05   ``Improve docstrings in providers (#31681)``
`a59076eaee <https://github.com/apache/airflow/commit/a59076eaeed03dd46e749ad58160193b4ef3660c>`__  2023-06-02   ``Add D400 pydocstyle check - Providers (#31427)``
`9fa75aaf7a <https://github.com/apache/airflow/commit/9fa75aaf7a391ebf0e6b6949445c060f6de2ceb9>`__  2023-05-29   ``Remove Python 3.7 support (#30963)``
==================================================================================================  ===========  =============================================================

2.2.0
.....

Latest change: 2023-05-19

==================================================================================================  ===========  ======================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ======================================================================================
`45548b9451 <https://github.com/apache/airflow/commit/45548b9451fba4e48c6f0c0ba6050482c2ea2956>`__  2023-05-19   ``Prepare RC2 docs for May 2023 wave of Providers (#31416)``
`abea189022 <https://github.com/apache/airflow/commit/abea18902257c0250fedb764edda462f9e5abc84>`__  2023-05-18   ``Use '__version__' in providers not 'version' (#31393)``
`f5aed58d9f <https://github.com/apache/airflow/commit/f5aed58d9fb2137fa5f0e3ce75b6709bf8393a94>`__  2023-05-18   ``Fixing circular import error in providers caused by airflow version check (#31379)``
`7ebda3898d <https://github.com/apache/airflow/commit/7ebda3898db2eee72d043a9565a674dea72cd8fa>`__  2023-05-17   ``Fix missing line in index.rst for provider documentation (#31343)``
`d9ff55cf6d <https://github.com/apache/airflow/commit/d9ff55cf6d95bb342fed7a87613db7b9e7c8dd0f>`__  2023-05-16   ``Prepare docs for May 2023 wave of Providers (#31252)``
`eef5bc7f16 <https://github.com/apache/airflow/commit/eef5bc7f166dc357fea0cc592d39714b1a5e3c14>`__  2023-05-03   ``Add full automation for min Airflow version for providers (#30994)``
`a7eb32a5b2 <https://github.com/apache/airflow/commit/a7eb32a5b222e236454d3e474eec478ded7c368d>`__  2023-04-30   ``Bump minimum Airflow version in providers (#30917)``
`d23a3bbed8 <https://github.com/apache/airflow/commit/d23a3bbed89ae04369983f21455bf85ccc1ae1cb>`__  2023-04-04   ``Add mechanism to suspend providers (#30422)``
`2b92c3c74d <https://github.com/apache/airflow/commit/2b92c3c74d3259ebac714f157c525836f0af50f0>`__  2023-01-05   ``Fix providers documentation formatting (#28754)``
`c8e348dcb0 <https://github.com/apache/airflow/commit/c8e348dcb0bae27e98d68545b59388c9f91fc382>`__  2022-12-05   ``Add automated version replacement in example dag indexes (#28090)``
==================================================================================================  ===========  ======================================================================================

2.1.0
.....

Latest change: 2022-11-26

==================================================================================================  ===========  ====================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ====================================================================================
`25bdbc8e67 <https://github.com/apache/airflow/commit/25bdbc8e6768712bad6043618242eec9c6632618>`__  2022-11-26   ``Updated docs for RC3 wave of providers (#27937)``
`2e20e9f7eb <https://github.com/apache/airflow/commit/2e20e9f7ebf5f43bf27069f4c0063cdd72e6b2e2>`__  2022-11-24   ``Prepare for follow-up relase for November providers (#27774)``
`12c3c39d1a <https://github.com/apache/airflow/commit/12c3c39d1a816c99c626fe4c650e88cf7b1cc1bc>`__  2022-11-15   ``pRepare docs for November 2022 wave of Providers (#27613)``
`78b8ea2f22 <https://github.com/apache/airflow/commit/78b8ea2f22239db3ef9976301234a66e50b47a94>`__  2022-10-24   ``Move min airflow version to 2.3.0 for all providers (#27196)``
`2a34dc9e84 <https://github.com/apache/airflow/commit/2a34dc9e8470285b0ed2db71109ef4265e29688b>`__  2022-10-23   ``Enable string normalization in python formatting - providers (#27205)``
`81b5f50ae9 <https://github.com/apache/airflow/commit/81b5f50ae99eeadbaac093caa4cb41f1a51ca735>`__  2022-10-22   ``Allow and prefer non-prefixed extra fields for AsanaHook (#27043)``
`f8db64c35c <https://github.com/apache/airflow/commit/f8db64c35c8589840591021a48901577cff39c07>`__  2022-09-28   ``Update docs for September Provider's release (#26731)``
`06acf40a43 <https://github.com/apache/airflow/commit/06acf40a4337759797f666d5bb27a5a393b74fed>`__  2022-09-13   ``Apply PEP-563 (Postponed Evaluation of Annotations) to non-core airflow (#26289)``
==================================================================================================  ===========  ====================================================================================

2.0.1
.....

Latest change: 2022-07-13

==================================================================================================  ===========  =============================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  =============================================================================
`d2459a241b <https://github.com/apache/airflow/commit/d2459a241b54d596ebdb9d81637400279fff4f2d>`__  2022-07-13   ``Add documentation for July 2022 Provider's release (#25030)``
`0de31bd73a <https://github.com/apache/airflow/commit/0de31bd73a8f41dded2907f0dee59dfa6c1ed7a1>`__  2022-06-29   ``Move provider dependencies to inside provider folders (#24672)``
`510a6bab45 <https://github.com/apache/airflow/commit/510a6bab4595cce8bd5b1447db957309d70f35d9>`__  2022-06-28   ``Remove 'hook-class-names' from provider.yaml (#24702)``
`9c59831ee7 <https://github.com/apache/airflow/commit/9c59831ee78f14de96421c74986933c494407afa>`__  2022-06-21   ``Update providers to use functools compat for ''cached_property'' (#24582)``
`08b675cf66 <https://github.com/apache/airflow/commit/08b675cf6642171cb1c5ddfb09607b541db70b29>`__  2022-06-13   ``Fix links to sources for examples (#24386)``
==================================================================================================  ===========  =============================================================================

2.0.0
.....

Latest change: 2022-06-09

==================================================================================================  ===========  ==================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ==================================================================================
`dcdcf3a2b8 <https://github.com/apache/airflow/commit/dcdcf3a2b8054fa727efb4cd79d38d2c9c7e1bd5>`__  2022-06-09   ``Update release notes for RC2 release of Providers for May 2022 (#24307)``
`717a7588bc <https://github.com/apache/airflow/commit/717a7588bc8170363fea5cb75f17efcf68689619>`__  2022-06-07   ``Update package description to remove double min-airflow specification (#24292)``
`aeabe994b3 <https://github.com/apache/airflow/commit/aeabe994b3381d082f75678a159ddbb3cbf6f4d3>`__  2022-06-07   ``Prepare docs for May 2022 provider's release (#24231)``
`027b707d21 <https://github.com/apache/airflow/commit/027b707d215a9ff1151717439790effd44bab508>`__  2022-06-05   ``Add explanatory note for contributors about updating Changelog (#24229)``
`45fcfd31b7 <https://github.com/apache/airflow/commit/45fcfd31b7ba84718e44f3f2adb59dcf25ac9a11>`__  2022-06-03   ``Migrate Asana example DAGs to new design #22440 (#24131)``
`75c60923e0 <https://github.com/apache/airflow/commit/75c60923e01375ffc5f71c4f2f7968f489e2ca2f>`__  2022-05-12   ``Prepare provider documentation 2022.05.11 (#23631)``
`8b6b0848a3 <https://github.com/apache/airflow/commit/8b6b0848a3cacf9999477d6af4d2a87463f03026>`__  2022-04-23   ``Use new Breese for building, pulling and verifying the images. (#23104)``
`6933022e94 <https://github.com/apache/airflow/commit/6933022e94acf139b2dea9a589bb8b25c62a5d20>`__  2022-04-10   ``Fix new MyPy errors in main (#22884)``
==================================================================================================  ===========  ==================================================================================

1.1.3
.....

Latest change: 2022-03-22

==================================================================================================  ===========  ==============================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ==============================================================
`d7dbfb7e26 <https://github.com/apache/airflow/commit/d7dbfb7e26a50130d3550e781dc71a5fbcaeb3d2>`__  2022-03-22   ``Add documentation for bugfix release of Providers (#22383)``
==================================================================================================  ===========  ==============================================================

1.1.2
.....

Latest change: 2022-03-14

==================================================================================================  ===========  ====================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ====================================================================
`16adc035b1 <https://github.com/apache/airflow/commit/16adc035b1ecdf533f44fbb3e32bea972127bb71>`__  2022-03-14   ``Add documentation for Classifier release for March 2022 (#22226)``
==================================================================================================  ===========  ====================================================================

1.1.1
.....

Latest change: 2022-03-07

==================================================================================================  ===========  ======================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ======================================================================================
`f5b96315fe <https://github.com/apache/airflow/commit/f5b96315fe65b99c0e2542831ff73a3406c4232d>`__  2022-03-07   ``Add documentation for Feb Providers release (#22056)``
`d94fa37830 <https://github.com/apache/airflow/commit/d94fa378305957358b910cfb1fe7cb14bc793804>`__  2022-02-08   ``Fixed changelog for January 2022 (delayed) provider's release (#21439)``
`6c3a67d4fc <https://github.com/apache/airflow/commit/6c3a67d4fccafe4ab6cd9ec8c7bacf2677f17038>`__  2022-02-05   ``Add documentation for January 2021 providers release (#21257)``
`cb73053211 <https://github.com/apache/airflow/commit/cb73053211367e2c2dd76d5279cdc7dc7b190124>`__  2022-01-27   ``Add optional features in providers. (#21074)``
`602abe8394 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`__  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`730db3fb77 <https://github.com/apache/airflow/commit/730db3fb774f60127ab1c865e19031f1f9c193f7>`__  2022-01-18   ``Remove all "fake" stub files (#20936)``
`f8fd0f7b4c <https://github.com/apache/airflow/commit/f8fd0f7b4ca6cb52307be4323028bf4e409566e7>`__  2022-01-13   ``Explain stub files are introduced for Mypy errors in examples (#20827)``
`f77417eb0d <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`__  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b4 <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`__  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`3e48a49ab8 <https://github.com/apache/airflow/commit/3e48a49ab887135e2367144bb543df3aa4e0d001>`__  2021-12-30   ``Fix mypy errors in asana example dags (#20593)``
`a0821235fb <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`__  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`2fb5e1d0ec <https://github.com/apache/airflow/commit/2fb5e1d0ec306839a3ff21d0bddbde1d022ee8c7>`__  2021-12-15   ``Fix cached_property MyPy declaration and related MyPy errors (#20226)``
`dad2f8103b <https://github.com/apache/airflow/commit/dad2f8103be954afaedf15e9d098ee417b0d5d02>`__  2021-12-15   ``Fix mypy providers (#20190)``
`43de625d42 <https://github.com/apache/airflow/commit/43de625d4246af7014f64941f8effb09997731cb>`__  2021-12-01   ``Correctly capitalize names and abbreviations in docs (#19908)``
`853576d901 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`__  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`d9567eb106 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`__  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`840ea3efb9 <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`__  2021-09-30   ``Update documentation for September providers release (#18613)``
`ef037e7021 <https://github.com/apache/airflow/commit/ef037e702182e4370cb00c853c4fb0e246a0479c>`__  2021-09-29   ``Static start_date and default arg cleanup for misc. provider example DAGs (#18597)``
`1cb456cba1 <https://github.com/apache/airflow/commit/1cb456cba1099198bbdba50c2d1ad79664be8ce6>`__  2021-09-12   ``Add official download page for providers (#18187)``
==================================================================================================  ===========  ======================================================================================

1.1.0
.....

Latest change: 2021-08-30

==================================================================================================  ===========  ==============================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ==============================================================================
`0a68588479 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`__  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`be75dcd39c <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`__  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c6 <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`__  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`d11d3e617a <https://github.com/apache/airflow/commit/d11d3e617ad121e75fbc955ad3730857ae8edab4>`__  2021-08-13   ``Use built-in ''cached_property'' on Python 3.8 for Asana provider (#17597)``
`87f408b1e7 <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`__  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`0dbd0f420c <https://github.com/apache/airflow/commit/0dbd0f420cc08e011317e2a9f21f92fff4a64c1b>`__  2021-07-26   ``Remove/refactor default_args pattern for miscellaneous providers (#16872)``
`e7bd82acdf <https://github.com/apache/airflow/commit/e7bd82acdf3cf7628d5f3cdf223cf9cf01874c25>`__  2021-07-25   ``Improve documentation and examples in example_asana.py (#15959)``
`b916b75079 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`__  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`866a601b76 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`__  2021-06-28   ``Removes pylint from our toolchain (#16682)``
==================================================================================================  ===========  ==============================================================================

1.0.0
.....

Latest change: 2021-06-18

==================================================================================================  ===========  ====================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ====================================================================
`bbc627a3da <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`__  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`1fba5402bb <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`__  2021-06-15   ``More documentation update for June providers release (#16405)``
`9c94b72d44 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`__  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`1e647029e4 <https://github.com/apache/airflow/commit/1e647029e469c1bb17e9ad051d0184f3357644c3>`__  2021-06-01   ``Rename the main branch of the Airflow repo to be 'main' (#16149)``
`162e3204c0 <https://github.com/apache/airflow/commit/162e3204c000ca2ebdc42b9b90a1873d4362ed6e>`__  2021-05-17   ``Add Asana Provider (#14521)``
==================================================================================================  ===========  ====================================================================
