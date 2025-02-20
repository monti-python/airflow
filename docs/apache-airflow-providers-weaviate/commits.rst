
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

 .. NOTE! THIS FILE IS AUTOMATICALLY GENERATED AND WILL BE
    OVERWRITTEN WHEN PREPARING PACKAGES.

 .. IF YOU WANT TO MODIFY THIS FILE, YOU SHOULD MODIFY THE TEMPLATE
    `PROVIDER_COMMITS_TEMPLATE.rst.jinja2` IN the `dev/breeze/src/airflow_breeze/templates` DIRECTORY

 .. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!

Package apache-airflow-providers-weaviate
------------------------------------------------------

`Weaviate <https://weaviate.io/developers/weaviate>`__


This is detailed commit list of changes for versions provider package: ``weaviate``.
For high-level changelog, see :doc:`package information including changelog <index>`.



1.3.1
.....

Latest change: 2024-01-20

=================================================================================================  ===========  =============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================================
`3784cdf5ed <https://github.com/apache/airflow/commit/3784cdf5ed954bd356a3727988dd707cc5568a9c>`_  2024-01-20   ``init templated field explicitly in constructor (#36908)``
`6ff96af480 <https://github.com/apache/airflow/commit/6ff96af4806a4107d48ee2e966c61778045ad584>`_  2024-01-18   ``Fix stacklevel in warnings.warn into the providers (#36831)``
`ecb2c9f24d <https://github.com/apache/airflow/commit/ecb2c9f24d1364642604c14f0deb681ab4894135>`_  2024-01-09   ``Set min pandas dependency to 1.2.5 for all providers and airflow (#36698)``
`19ebcac239 <https://github.com/apache/airflow/commit/19ebcac2395ef9a6b6ded3a2faa29dc960c1e635>`_  2024-01-07   ``Prepare docs 1st wave of Providers January 2024 (#36640)``
`1cc9fe1df1 <https://github.com/apache/airflow/commit/1cc9fe1df111950327e9922b00222846196b029d>`_  2024-01-05   ``Add flake8-implicit-str-concat check to Ruff (#36597)``
=================================================================================================  ===========  =============================================================================

1.3.0
.....

Latest change: 2023-12-31

=================================================================================================  ===========  ===========================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===========================================================================================================
`24a532fb4c <https://github.com/apache/airflow/commit/24a532fb4c400b862f63b4327995dea8512abde9>`_  2023-12-31   ``Prepare documentation for weaviate ad-hoc rc2 release (#36508)``
`6937ae7647 <https://github.com/apache/airflow/commit/6937ae76476b3bc869ef912d000bcc94ad642db1>`_  2023-12-30   ``Speed up autocompletion of Breeze by simplifying provider state (#36499)``
`0a741b2fe6 <https://github.com/apache/airflow/commit/0a741b2fe674e62f693e73937aec5fb97c204b6a>`_  2023-12-28   ``Handle  list like input objects in weavaite's 'create_or_replace_document_objects' hook method (#36475)``
`9b5d6bfe27 <https://github.com/apache/airflow/commit/9b5d6bfe273cf6af0972e28ff97f99ea325cd991>`_  2023-12-28   ``Add documentation for 3rd wave of providers in Deember (#36464)``
`8850715e22 <https://github.com/apache/airflow/commit/8850715e22dc8fd69dfc234efed805cc75708938>`_  2023-12-26   ``Remove 'insertion_errors' as required argument (#36435)``
`97d2266b2d <https://github.com/apache/airflow/commit/97d2266b2dfe1c6d3a0185926a7508b7039575a2>`_  2023-12-24   ``Add WeaviateDocumentIngestOperator (#36402)``
`ff3b8daac0 <https://github.com/apache/airflow/commit/ff3b8daac0cbf3c885ea1479b1fb9cfcb2261f21>`_  2023-12-23   ``Add 'uuid_column', 'tenant' params to WeaviateIngestOperator (#36387)``
`75d74b1f3a <https://github.com/apache/airflow/commit/75d74b1f3a535fdc3624077bde3a34d1abcf641e>`_  2023-12-23   ``Add create_or_replace_document_objects method to weaviate provider (#36177)``
=================================================================================================  ===========  ===========================================================================================================

1.2.0
.....

Latest change: 2023-12-23

=================================================================================================  ===========  ===========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===========================================================================================
`b15d5578da <https://github.com/apache/airflow/commit/b15d5578dac73c4c6a3ca94d90ab0dc9e9e74c9c>`_  2023-12-23   ``Re-apply updated version numbers to 2nd wave of providers in December (#36380)``
`f5883d6e7b <https://github.com/apache/airflow/commit/f5883d6e7be83f1ab9468e67164b7ac381fdb49f>`_  2023-12-23   ``Prepare 2nd wave of providers in December (#36373)``
`7084429f42 <https://github.com/apache/airflow/commit/7084429f42d0a006e777612c07b3471100f953c9>`_  2023-12-21   ``Fixing template_fields for WeaviateIngestOperator (#36359)``
`5439b494b0 <https://github.com/apache/airflow/commit/5439b494b00daf0bb62d8f1f8a0f4d71c39f4923>`_  2023-12-11   ``Add helper function for CRUD operations on weaviate's schema and class objects (#35919)``
`a8333b778a <https://github.com/apache/airflow/commit/a8333b778ac2ec905d6f51ab408e807d1294bd5a>`_  2023-12-08   ``Add retry mechanism and dataframe support for WeaviateIngestOperator (#36085)``
=================================================================================================  ===========  ===========================================================================================

1.1.0
.....

Latest change: 2023-12-08

=================================================================================================  ===========  =======================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =======================================================================
`999b70178a <https://github.com/apache/airflow/commit/999b70178a1f5d891fd2c88af4831a4ba4c2cbc9>`_  2023-12-08   ``Prepare docs 1st wave of Providers December 2023 (#36112)``
`b2464477c4 <https://github.com/apache/airflow/commit/b2464477c472894f142c1a85f04a92af033e700e>`_  2023-12-07   ``Add object methods in weaviate hook (#35934)``
`d0918d77ee <https://github.com/apache/airflow/commit/d0918d77ee05ab08c83af6956e38584a48574590>`_  2023-12-07   ``Bump minimum Airflow version in providers to Airflow 2.6.0 (#36017)``
`8be03c9937 <https://github.com/apache/airflow/commit/8be03c99372cfaf7a86f31464959338f6f9b900f>`_  2023-12-01   ``Add a cache for weaviate client (#35983)``
`2919abe5b3 <https://github.com/apache/airflow/commit/2919abe5b3f2d186c896aebbc51acf98d554ef33>`_  2023-11-28   ``Add more ways to connect to weaviate (#35864)``
`0b23d5601c <https://github.com/apache/airflow/commit/0b23d5601c6f833392b0ea816e651dcb13a14685>`_  2023-11-24   ``Prepare docs 2nd wave of Providers November 2023 (#35836)``
`99534e47f3 <https://github.com/apache/airflow/commit/99534e47f330ce0efb96402629dda5b2a4f16e8f>`_  2023-11-19   ``Use reproducible builds for provider packages (#35693)``
`99df205f42 <https://github.com/apache/airflow/commit/99df205f42a754aa67f80b5983e1d228ff23267f>`_  2023-11-16   ``Fix and reapply templates for provider documentation (#35686)``
=================================================================================================  ===========  =======================================================================

1.0.0
.....

Latest change: 2023-11-08

=================================================================================================  ===========  =============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================
`1b059c57d6 <https://github.com/apache/airflow/commit/1b059c57d6d57d198463e5388138bee8a08591b1>`_  2023-11-08   ``Prepare docs 1st wave of Providers November 2023 (#35537)``
`4fe87eaa2d <https://github.com/apache/airflow/commit/4fe87eaa2ddbfbcd786d9c69572ce18c527fdff3>`_  2023-11-06   ``Add Weaviate Provider (#35060)``
=================================================================================================  ===========  =============================================================
