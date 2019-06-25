![Apiary.](media/apiary.png "Apiary Data lake.")

# Overview

Apiary provides modules which can be combined to create a federated cloud data lake. These include:
* Read/write [Hive](https://hive.apache.org) metastore service
* Read only [Hive](https://hive.apache.org) metastore service
* [Waggle Dance](https://github.com/HotelsDotCom/waggle-dance) federated Hive metastore service
* [Shunting Yard](https://github.com/ExpediaGroup/shunting-yard) event-based data replication service
* Related infrastructure including load balancers
* Various extensions and plugins for adding additional functionality to the Hive metastore

## Components
Apiary consists of the following components which are managed in separate git repositories:
* [Apiary Authorization](https://github.com/ExpediaGroup/apiary-authorization)
* [Apiary Data Lake](https://github.com/ExpediaGroup/apiary-data-lake)
* [Apiary Replication](https://github.com/ExpediaGroup/apiary-replication)
* [Apiary Extensions](https://github.com/ExpediaGroup/apiary-extensions)
* [Apiary Federation](https://github.com/ExpediaGroup/apiary-federation)
* [Apiary Metastore Docker](https://github.com/ExpediaGroup/apiary-metastore-docker)
* [Apiary Ranger Docker](https://github.com/ExpediaGroup/apiary-ranger-docker)
* [Apiary Waggle Dance Docker](https://github.com/ExpediaGroup/apiary-waggledance-docker)
* [Apiary Shunting Yard Docker](https://github.com/ExpediaGroup/apiary-shuntingyard-docker)

# Contact

## Mailing List
If you would like to ask any questions about or discuss Apiary please join our mailing list at

  [https://groups.google.com/forum/#!forum/apiary-user](https://groups.google.com/forum/#!forum/apiary-user)

# Legal
This project is available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

Copyright 2018-2019 Expedia, Inc.
