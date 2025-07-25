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

Auth managers
-------------

This is a summary of all Apache Airflow Community provided implementations of auth managers
exposed via community-managed providers.

Airflow can be extended by providers with auth managers. Each provider can define their own auth manager,
that can be configured to handle user authentication and authorizations of their actions (UI and API).

The auth managers are explained in
:doc:`apache-airflow:core-concepts/auth-manager/index` and you can also see those
provided by the community-managed providers:

.. airflow-auth-managers::
   :tags: None
   :header-separator: "
