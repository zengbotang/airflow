
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


Package apache-airflow-providers-apache-drill
------------------------------------------------------

`Apache Drill <https://drill.apache.org/>`__.


This is detailed commit list of changes for versions provider package: ``apache.drill``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.0.0
.....

Latest change: 2022-06-07

=================================================================================================  ===========  ===========================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===========================================================================
`aeabe994b3 <https://github.com/apache/airflow/commit/aeabe994b3381d082f75678a159ddbb3cbf6f4d3>`_  2022-06-07   ``Prepare docs for May 2022 provider's release (#24231)``
`b4a5783a2a <https://github.com/apache/airflow/commit/b4a5783a2a90d9a0dc8abe5f2a47e639bfb61646>`_  2022-06-06   ``chore: Refactoring and Cleaning Apache Providers (#24219)``
`027b707d21 <https://github.com/apache/airflow/commit/027b707d215a9ff1151717439790effd44bab508>`_  2022-06-05   ``Add explanatory note for contributors about updating Changelog (#24229)``
`a27206915b <https://github.com/apache/airflow/commit/a27206915bfe958e70de3041c0d0ded6bc0b1c02>`_  2022-06-05   ``AIP-47 - Migrate drill DAGs to new design #22439 (#24206)``
`75c60923e0 <https://github.com/apache/airflow/commit/75c60923e01375ffc5f71c4f2f7968f489e2ca2f>`_  2022-05-12   ``Prepare provider documentation 2022.05.11 (#23631)``
`428a439953 <https://github.com/apache/airflow/commit/428a43995390b3623a51aa7bac7e21da69a8db22>`_  2022-05-09   ``Clean up in-line f-string concatenation (#23591)``
=================================================================================================  ===========  ===========================================================================

1.0.4
.....

Latest change: 2022-03-22

=================================================================================================  ===========  ==============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==============================================================
`d7dbfb7e26 <https://github.com/apache/airflow/commit/d7dbfb7e26a50130d3550e781dc71a5fbcaeb3d2>`_  2022-03-22   ``Add documentation for bugfix release of Providers (#22383)``
=================================================================================================  ===========  ==============================================================

1.0.3
.....

Latest change: 2022-03-14

=================================================================================================  ===========  ====================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================
`16adc035b1 <https://github.com/apache/airflow/commit/16adc035b1ecdf533f44fbb3e32bea972127bb71>`_  2022-03-14   ``Add documentation for Classifier release for March 2022 (#22226)``
=================================================================================================  ===========  ====================================================================

1.0.2
.....

Latest change: 2022-03-07

=================================================================================================  ===========  ================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ================================================================================
`f5b96315fe <https://github.com/apache/airflow/commit/f5b96315fe65b99c0e2542831ff73a3406c4232d>`_  2022-03-07   ``Add documentation for Feb Providers release (#22056)``
`d94fa37830 <https://github.com/apache/airflow/commit/d94fa378305957358b910cfb1fe7cb14bc793804>`_  2022-02-08   ``Fixed changelog for January 2022 (delayed) provider's release (#21439)``
`6c3a67d4fc <https://github.com/apache/airflow/commit/6c3a67d4fccafe4ab6cd9ec8c7bacf2677f17038>`_  2022-02-05   ``Add documentation for January 2021 providers release (#21257)``
`602abe8394 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`f77417eb0d <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b4 <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`83f8e178ba <https://github.com/apache/airflow/commit/83f8e178ba7a3d4ca012c831a5bfc2cade9e812d>`_  2021-12-31   ``Even more typing in operators (template_fields/ext) (#20608)``
`a1d457a77c <https://github.com/apache/airflow/commit/a1d457a77c2027d02f3d40825bc04479b4b0dc58>`_  2021-12-30   ``Fix mypy errors in apache/drill/operators and /apache/pig/operators (#20597)``
`d56e7b56bb <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`a0821235fb <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`433e0296ad <https://github.com/apache/airflow/commit/433e0296ad1a5ff1c545aa477fe08000089a6e1e>`_  2021-12-14   ``Fix MyPy Errors for Apache Drill provider. (#20268)``
`853576d901 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`_  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`ae044884d1 <https://github.com/apache/airflow/commit/ae044884d1dacce8dbf47c618f543b58f9ff101f>`_  2021-11-03   ``Cleanup of start_date and default arg use for Apache example DAGs (#18657)``
=================================================================================================  ===========  ================================================================================

1.0.1
.....

Latest change: 2021-08-30

=================================================================================================  ===========  ============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================================
`0a68588479 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`42e13e1a5a <https://github.com/apache/airflow/commit/42e13e1a5a4c97a2085ddf96f7d93e7bf71949b8>`_  2021-08-30   ``Remove all deprecation warnings in providers (#17900)``
`be75dcd39c <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c6 <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`b82bbe83dd <https://github.com/apache/airflow/commit/b82bbe83ddb0d3c589ce5037eff526b7bedf7307>`_  2021-08-02   ``Example DAG-related updates for Apache Drill (#17384)``
=================================================================================================  ===========  ============================================================================

1.0.0
.....

Latest change: 2021-07-12

=================================================================================================  ===========  ====================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================
`8808b64194 <https://github.com/apache/airflow/commit/8808b641942e1b81c21db054fd6d36e2031cfab8>`_  2021-07-12   ``AIRFLOW-5529 Add Apache Drill provider. (#16884)``
=================================================================================================  ===========  ====================================================
