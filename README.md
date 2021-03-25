<!--
# Copyright 2019 Spotify AB. All rights reserved.
# Copyright 2021 DataStax, Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
-->

Medusa for Apache Cassandra&trade;
==================================

Medusa is an Apache Cassandra backup system.

Features
--------
Medusa is a command line tool that offers the following features:

* Single node backup
* Single node restore
* Cluster wide in place restore (restoring on the same cluster that was used for the backup)
* Cluster wide remote restore (restoring on a different cluster than the one used for the backup)
* Backup purge
* Support for local storage, Google Cloud Storage (GCS) and AWS S3 through [Apache Libcloud](https://libcloud.apache.org/). Can be extended to support other storage providers supported by Apache Libcloud.
* Support for clusters using single tokens or vnodes
* Full or differential backups

Medusa currently does not support (but we would gladly accept help with changing that):

* Cassandra deployments with multiple data folder directories.

Documentation
-------------
* [Installation](docs/Installation.md)
* [Configuration](docs/Configuration.md)
* [Usage](docs/Usage.md)

For user questions and general/dev discussions, please join the #cassandra-medusa channel on the ASF slack at [http://s.apache.org/slack-invite](http://s.apache.org/slack-invite).

