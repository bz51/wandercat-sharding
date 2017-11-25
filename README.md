# WanderCat-Sharding [![Build Status](https://api.travis-ci.org/bz51/wandercat-sharding.svg?branch=master)](https://travis-ci.org/bz51/wandercat-sharding) [![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
<p align="center">
    <img src="wandercat-logo.jpg" />
</p>

WanderCat-Sharding is a smart but not simple distributed database middleware, as a JDBC driver extension. WanderCat-Sharding is considered as a micro-service-oriented java library, which provides sharding databases and tables, distributed sequence features, and provides the high-performance distributed transaction that based on Best Efforts 1PC.


# Feature
- **Smart but not simple**<br/>
WanderCat-Sharding uses the simplest way of implementation, and the code is easy to understand.

- **Detailed documentation**<br/>
I'll document the key techniques, including distributed transactions, data sharding strategies, distributed ID generation policies, SQL routing, SQL syntax parsing, and so on.


- **No data migration is required**<br/>
When the database needs to be extended, there is no need for any form of data migration, including table-level and row-level.

- **Distributed transaction**<br/>
Distributed transaction bases on Best Efforts 1PC. The final consistency of data is realized under the premise of guaranteed performance.

- **Low operation and maintenance cost**<br/>
It is simply a JDBC driver extension, not a database proxy, so no additional deployment is required, simple to use.

# About me
- [Blog:www.chaimm.com](http://www.chaimm.com)
- Mail:chaibozhou@foxmail.com

# License
This project is licensed under the Apache License 2.0 License - see the [LICENSE.md](https://github.com/bz51/wandercat-sharding/blob/master/LICENSE) file for details

