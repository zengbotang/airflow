
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


Package apache-airflow-providers-dbt-cloud
------------------------------------------------------

`dbt Cloud <https://www.getdbt.com/product/what-is-dbt/>`__


This is detailed commit list of changes for versions provider package: ``dbt.cloud``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.0.0
.....

Latest change: 2022-06-07

=================================================================================================  ===========  ===============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===============================================================================
`aeabe994b3 <https://github.com/apache/airflow/commit/aeabe994b3381d082f75678a159ddbb3cbf6f4d3>`_  2022-06-07   ``Prepare docs for May 2022 provider's release (#24231)``
`7498fba826 <https://github.com/apache/airflow/commit/7498fba826ec477b02a40a2e23e1c685f148e20f>`_  2022-06-06   ``Enable dbt Cloud provider to interact with single tenant instances (#24264)``
`5e6997ed45 <https://github.com/apache/airflow/commit/5e6997ed45be0972bf5ea7dc06e4e1cef73b735a>`_  2022-06-06   ``Update dbt.py (#24218)``
`027b707d21 <https://github.com/apache/airflow/commit/027b707d215a9ff1151717439790effd44bab508>`_  2022-06-05   ``Add explanatory note for contributors about updating Changelog (#24229)``
`8f2213fcd0 <https://github.com/apache/airflow/commit/8f2213fcd0b8f775792bf2fd4931607992649046>`_  2022-06-05   ``AIP-47 - Migrate dbt DAGs to new design #22472 (#24202)``
`75c60923e0 <https://github.com/apache/airflow/commit/75c60923e01375ffc5f71c4f2f7968f489e2ca2f>`_  2022-05-12   ``Prepare provider documentation 2022.05.11 (#23631)``
`8b6b0848a3 <https://github.com/apache/airflow/commit/8b6b0848a3cacf9999477d6af4d2a87463f03026>`_  2022-04-23   ``Use new Breese for building, pulling and verifying the images. (#23104)``
`f935c9f163 <https://github.com/apache/airflow/commit/f935c9f163bbc2de9034ddf4c0a0cc960a031661>`_  2022-04-23   ``Fix typo in dbt Cloud provider description (#23179)``
`49e336ae03 <https://github.com/apache/airflow/commit/49e336ae0302b386a2f47269a6d13988382d975f>`_  2022-04-13   ``Replace usage of 'DummyOperator' with 'EmptyOperator' (#22974)``
`6933022e94 <https://github.com/apache/airflow/commit/6933022e94acf139b2dea9a589bb8b25c62a5d20>`_  2022-04-10   ``Fix new MyPy errors in main (#22884)``
=================================================================================================  ===========  ===============================================================================

1.0.2
.....

Latest change: 2022-03-22

=================================================================================================  ===========  ==============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==============================================================
`d7dbfb7e26 <https://github.com/apache/airflow/commit/d7dbfb7e26a50130d3550e781dc71a5fbcaeb3d2>`_  2022-03-22   ``Add documentation for bugfix release of Providers (#22383)``
=================================================================================================  ===========  ==============================================================

1.0.1
.....

Latest change: 2022-03-14

=================================================================================================  ===========  ==================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================================
`16adc035b1 <https://github.com/apache/airflow/commit/16adc035b1ecdf533f44fbb3e32bea972127bb71>`_  2022-03-14   ``Add documentation for Classifier release for March 2022 (#22226)``
`c1ab8e2d7b <https://github.com/apache/airflow/commit/c1ab8e2d7b68a31408e750129592e16432474512>`_  2022-03-14   ``Protect against accidental misuse of XCom.get_value() (#22244)``
`d08284ed25 <https://github.com/apache/airflow/commit/d08284ed251b7c5712190181623b500a38cd640d>`_  2022-03-11   `` Add map_index to XCom model and interface (#22112)``
`f8c01317ef <https://github.com/apache/airflow/commit/f8c01317ef35110217b0054d472d9a276d2924b0>`_  2022-03-10   ``Pass explicit overrides in 'DbtCloudJobRunOperator' to 'DbtCloudHook' (#22136)``
`4388808e0e <https://github.com/apache/airflow/commit/4388808e0e81beb78d48e125c7f51a1283cf1084>`_  2022-03-10   ``Add more template fields to 'DbtCloudJobRunOperator' (#22126)``
`08575ddd8a <https://github.com/apache/airflow/commit/08575ddd8a72f96a3439f73e973ee9958188eb83>`_  2022-03-01   ``Change BaseOperatorLink interface to take a ti_key, not a datetime (#21798)``
`e782b37a3f <https://github.com/apache/airflow/commit/e782b37a3fdf58e60cdefea33b5b865deb69b1d7>`_  2022-02-27   ``Add dbt Cloud provider (#20998)``
=================================================================================================  ===========  ==================================================================================
