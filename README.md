# Awesome TinkerPop with stars

![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/tinkerpop-splash.png)

A curated list of only awesome TinkerPop libraries on Github.

> Apache TinkerPop™ is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP).

### Table of Contents

* [TinkerPop3](#tinkerpop3)
  * [Implementations](#tinkerpop3-implementations)
  * [Wrappers/Clients](#wrappers)
  * [Query Languages](#qlang)
* [TinkerPop2](#tinkerpop2)
* [Communites](#communites)
* [People to Follow](#people-to-follow)
* [Tutorials and Resources](#tutorials-and-resources)
* [How to Contribute](#contributing)
* [License](#license)

### <A NAME="tinkerpop3"></A>TinkerPop3 Libraries

#### <A NAME="tinkerpop3-implementations"></A>Implementations

* [JanusGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,829 | 🐛 598 | 🌐 Java | 📅 2026-07-23 - JanusGraph: an open-source, distributed graph database <http://janusgraph.org>
* [TinkerPop3 implementation](https://github.com/apache/tinkerpop) ⭐ 2,142 | 🐛 52 | 🌐 Java | 📅 2026-08-13 - Mirror of Apache TinkerPop.
* [blazegraph](https://github.com/blazegraph/database) ⚠️ Archived - TinkerPop3 [implementation](https://github.com/blazegraph/tinkerpop3) ⚠️ Archived for Blaze Graph; a high performance graph database.
* [JanusGraph for DynamoDB (Amazon)](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) ⚠️ Archived - The Amazon DynamoDB storage backend for JanusGraph.
* [hgraphdb](https://github.com/rayokota/hgraphdb) ⭐ 264 | 🐛 12 | 🌐 Java | 📅 2026-04-29 - HBase as a TinkerPop Graph Database.
* [sqlg](https://github.com/pietermartin/sqlg) ⭐ 260 | 🐛 25 | 🌐 HTML | 📅 2026-08-13 - Sqlg is a implementation of TinkerPop3 on a RDBMS.
* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) ⭐ 215 | 🐛 27 | 🌐 JavaScript | 📅 2018-04-21 - JavaScript graph database client for TinkerPop3 Gremlin Server.
* [Unipop](https://github.com/rmagen/unipop) ⭐ 213 | 🐛 29 | 🌐 Java | 📅 2026-08-02 - OLTP Elasticsearch and JDBC backed graph.
* [orientdb-gremlin](https://github.com/orientechnologies/orientdb-gremlin) ⭐ 97 | 🐛 43 | 🌐 Java | 📅 2026-07-20 - TinkerPop3 Graph Structure Implementation for OrientDB.
* [tinkergraph-js](https://github.com/jbmusso/tinkergraph-js) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2016-03-28 - A pure JavaScript implementation of TinkerPop's TinkerGraph in-memory graph database.
* [Elastic Gremlin](https://github.com/rmagen/elastic-gremlin) ⭐ 70 | 🐛 22 | 🌐 Java | 📅 2015-10-26 - TinkerPop3 implementation on Elasticsearch backend.
* [DuctileDB](https://github.com/PureSolTechnologies/DuctileDB) ⭐ 15 | 🐛 0 | 🌐 Java | 📅 2018-01-03 - Ductile DB is a graph database based on Hadoop/HBase which provides a vast set of features.
* [Hadoop (Giraph)](http://tinkerpop.apache.org/docs/current/reference/#giraphgraphcomputer) - OLAP graph processor using Giraph.
* [Hadoop (Spark)](http://tinkerpop.apache.org/docs/current/reference/#sparkgraphcomputer) - OLAP graph processor using Spark.
* [IBM Graph](https://console.ng.bluemix.net/catalog/services/ibm-graph/) - OLTP graph database as a service.
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database.
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support.
* [TinkerGraph](http://tinkerpop.apache.org/docs/current/reference/#tinkergraph-gremlin) - In-memory OLTP and OLAP reference implementation.

#### <A NAME="wrappers"></A>Wrappers/Clients

##### C# .NET

* [Teva Gremlin](https://www.nuget.org/packages/Teva.Common.Data.Gremlin/) (.NET - C#) - A Gremlin Server driver for .NET.

##### Clojure

* [ogre](https://github.com/clojurewerkz/ogre) ⭐ 130 | 🐛 5 | 🌐 Clojure | 📅 2021-09-01 - Clojure library for querying TinkerPop graphs.
* [scalajs-gremlin-client](https://github.com/viagraphs/scalajs-gremlin-client) ⭐ 7 | 🐛 0 | 🌐 Scala | 📅 2020-01-01 (scala) - A Gremlin-Server client with ad-hoc extensible, reactive, typeclass based API.

##### Go

* [grammes](https://github.com/northwesternmutual/grammes) ⭐ 126 | 🐛 26 | 🌐 Go | 📅 2024-05-27 - A Go package built to communicate with Apache TinkerPop™ Graph computing framework using Gremlin.
* [go-gremlin](https://github.com/go-gremlin/gremlin) ⭐ 117 | 🐛 8 | 🌐 Go | 📅 2020-02-05 - Go graph database client for TinkerPop3 Gremlin Server.
* [Gremgo](https://github.com/qasaur/gremgo) ⚠️ Archived - A fast, efficient, and easy-to-use Go client for the TinkerPop graph database stack.

##### Haskell

* [greskell-websocket](https://github.com/debug-ito/greskell) ⭐ 27 | 🐛 3 | 🌐 Haskell | 📅 2026-05-25 - Haskell client for TinkerPop3 Gremlin Server.

##### Java

* [Ferma](https://github.com/Syncleus/Ferma) ⭐ 142 | 🐛 15 | 🌐 Java | 📅 2022-05-20 - An ORM / OGM for the TinkerPop graph stack.
* [neo4j-tinkerpop-api](https://github.com/neo4j-contrib/neo4j-tinkerpop-api) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2019-01-16 - Apache Licensed Neo4j API for TinkerPop3.
* [neo4j-gremlin-bolt](https://github.com/SteelBridgeLabs/neo4j-gremlin-bolt) ⭐ 0 | 🐛 10 | 🌐 Java | 📅 2023-12-05 - Allows use of the Apache Tinkerpop Java API with the neo4j server using the BOLT protocol.
* [gremlin-driver](http://tinkerpop.apache.org/docs/current/reference/#connecting-via-java) (java) - A Gremlin Server driver for Java.

##### Javascript

* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) ⭐ 215 | 🐛 27 | 🌐 JavaScript | 📅 2018-04-21 (js) - A Gremlin Server driver for JavaScript.
* [ts-tinkerpop](https://github.com/RedSeal-co/ts-tinkerpop) ⭐ 53 | 🐛 2 | 🌐 TypeScript | 📅 2015-11-18 - Utilities for using TinkerPop3 via the node-java API in Typescript.

##### PHP

* [gremlin-php](https://github.com/PommeVerte/gremlin-php) ⭐ 75 | 🐛 6 | 🌐 PHP | 📅 2023-04-19 - gremlin-server php driver compatible with TinkerPop3. It will allow you to connect to gremlin-server and it's backends (Neo4J, Titan, etc.).

##### Python

* [goblin](https://github.com/ZEROFAIL/goblin) ⭐ 90 | 🐛 17 | 🌐 Python | 📅 2018-11-06 - OGM for TinkerPop3 Gremlin Server.
* [goblin 3.5](https://github.com/davebshow/goblin) ⭐ 90 | 🐛 17 | 🌐 Python | 📅 2018-11-06 - A Python 3.5 rewrite of the TinkerPop 3 OGM Goblin.
* [aiogremlin](https://github.com/davebshow/aiogremlin) ⭐ 43 | 🐛 6 | 🌐 Python | 📅 2019-12-27 (python) - A Python 3 library based on asyncio and aiohttp that uses websockets to communicate with the Gremlin Server.
* [Mogwai](https://github.com/platinummonkey/mogwai) ⚠️ Archived - TinkerPop3 Graph Database Library for Python.
* [gremlinclient](https://github.com/davebshow/gremlinclient) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2016-06-15 - An asynchronous Python 2/3 client for Gremlin Server that allows for flexible coroutine syntax - Trollius, Tornado, Asyncio.
* [python-gremlin-rest](https://github.com/windj007/python-gremlin-rest) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2016-12-09 - A REST-based client for Gremlin Server.
* [gremlinrestclient](http://gremlinrestclient.readthedocs.org/en/latest/) (python) - Python 2/3 library that uses HTTP to communicate with the Gremlin Server over REST.

##### Reactive

* [reactive-gremlin](https://github.com/coreyauger/reactive-gremlin) ⭐ 30 | 🐛 0 | 🌐 Scala | 📅 2018-11-13 (scala) - An Akka HTTP Websocket Connector.

##### Scala

* [Gremlin Scala](https://github.com/mpollmeier/gremlin-scala) ⭐ 478 | 🐛 34 | 🌐 Scala | 📅 2022-10-20 - Scala wrapper for Apache TinkerPop3 Graph DSL.
* [blueprints-scala](https://github.com/anvie/blueprints-scala) ⭐ 76 | 🐛 4 | 🌐 Scala | 📅 2016-04-05 - Tinkerpop Blueprints Scala.

#### <A NAME="qlang"></A>Query Languages

* [gremlin-scala](https://github.com/mpollmeier/gremlin-scala) ⭐ 478 | 🐛 34 | 🌐 Scala | 📅 2022-10-20 - A Scala language wrapper for TinkerPop3.
* [Cypher for Gremlin](https://github.com/opencypher/cypher-for-gremlin) ⭐ 373 | 🐛 36 | 🌐 Java | 📅 2026-01-14 -  Cypher for Gremlin adds Cypher support to any Gremlin graph database.
* [sql-gremlin](https://github.com/twilmes/sql-gremlin) ⭐ 74 | 🐛 12 | 🌐 Java | 📅 2023-06-14 - A SQL to Gremlin traversal compiler.
* [sparql-gremlin](https://github.com/dkuppitz/sparql-gremlin) ⭐ 70 | 🐛 9 | 🌐 Java | 📅 2018-02-15 - A SPARQL to Gremlin traversal compiler.
* [gremlin-py](https://github.com/emehrkay/gremlinpy) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2017-07-30 - Write pure Python Gremlin that can be sent to Gremlin Server.
* [Peapod](https://github.com/bayofmany/peapod) ⭐ 42 | 🐛 5 | 🌐 Java | 📅 2021-03-31 - A new object-graph-wrapper for the Tinkerpop3 graph stack.
* [ipython-gremlin](https://github.com/davebshow/ipython-gremlin) ⭐ 41 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2022-01-21 - Gremlin in IPython and Jupyter.
* [greskell](https://github.com/debug-ito/greskell) ⭐ 27 | 🐛 3 | 🌐 Haskell | 📅 2026-05-25 - Haskell binding for Gremlin graph query language
* [gremlin-template-string](https://github.com/jbmusso/gremlin-template-string) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-26 - A Javascript Gremlin language builder.
* [ogre](http://ogre.clojurewerkz.org/) - A Clojure language wrapper for TinkerPop3.

### <A NAME="tinkerpop2"></A>TinkerPop 2 Libraries

* [Ferma](https://github.com/Syncleus/Ferma) ⭐ 142 | 🐛 15 | 🌐 Java | 📅 2022-05-20 - An ORM / OGM for the TinkerPop graph stack.
* [Frames](https://github.com/tinkerpop/frames) ⭐ 140 | 🐛 27 | 🌐 Java | 📅 2021-08-18 - An Object to Graph Framework.
* [blueprints-scala](https://github.com/anvie/blueprints-scala) ⭐ 76 | 🐛 4 | 🌐 Scala | 📅 2016-04-05 - TinkerPop Blueprints Scala.
* [spring-data-gremlin](https://github.com/gjrwebber/spring-data-gremlin) ⭐ 71 | 🐛 33 | 🌐 Java | 📅 2018-10-06 - Spring data gremlin makes it easier to implement Graph based repositories. This module extends Spring Data to allow support for potentially any Graph database that implements the TinkerPop Blueprints 2.x API.
* [Archimedes](https://github.com/clojurewerkz/archimedes) ⭐ 38 | 🐛 3 | 🌐 Clojure | 📅 2022-09-06 - Clojure library for Blueprints (part of the TinkerPop graph stack).
* [Mogwai](https://github.com/platinummonkey/mogwai) ⚠️ Archived - TinkerPop 2 Graph Database Library for Python.
* [AccumuloGraph](https://github.com/JHUAPL/AccumuloGraph) ⚠️ Archived - An implementation of TinkerPop Blueprints using Accumulo.
* [Frontenac](https://github.com/Loupi/Frontenac) ⭐ 28 | 🐛 3 | 🌐 C# | 📅 2019-03-17 - A .NET port of the TinkerPop Stack.

## <A NAME="communites"></A>Communities

* [Gremlin-users](https://groups.google.com/forum/#!forum/gremlin-users) - Mailing list for Gremlin users.
* [Stack Overflow](http://stackoverflow.com/questions/tagged/tinkerpop3) - Stack Overflow has a relatively active community.
* [TinkerPop-dev](http://mail-archives.apache.org/mod_mbox/incubator-tinkerpop-dev/) - Mailing list for TP3 deverlopers.

## <A NAME="people-to-follow"></A>People to Follow

* [Marko Rodriguez](https://markorodriguez.com/) - Founder of TinkerPop and Aurelius.
* [Stephen Mallette](https://twitter.com/spmallette?lang=en-gb) - Senior developer for Gremlin, TinkerPop and Titan DB.
* [Daniel Kuppitz](https://about.me/daniel.kuppitz) - One of the main developers of Gremlin.
* [Jason Plurad](https://github.com/pluradj) - Senior Developer at IBM. TinkerPop committer and active on the community.

## <A NAME="tutorials-and-resources"></A>Tutorials and Resources

* [Introduction to Gremlin](http://tinkerpop.apache.org/gremlin.html) - Official introduction to the Gremlin language.
* [Datastax Introduction](https://academy.datastax.com/resources/getting-started-tinkerpop-and-gremlin) - A tutorial provided by Datastax to Gremlin and TinkerPop3.
* [TinkerPop Book](http://www.tinkerpopbook.com/) - A long promised book for Tinkeprop but never fulfilled until now. You cans till request a notification.
* [Linux Foundation Presentation](http://events.linuxfoundation.org/sites/events/files/slides/ApacheCon2015TinkerPop3.pdf) - A presentation by Linux Foundation given by David Robinson at IBM aboit Apache TinkerPop3.
* [Getting Started with TinkerPop](http://tinkerpop.apache.org/docs/current/tutorials/getting-started/) - Learn the basics of getting up and going with TinkerPop.
* [The Gremlin Console](http://tinkerpop.apache.org/docs/current/tutorials/the-gremlin-console/) - Discusses uses cases of the Gremlin Console and usage patterns.
* [Gremlin Recipes](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/recipes/) - Reference for common traversal patterns and style.
* [Gremlin Language Variants](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/tutorials/gremlin-language-variants/) - Learn how to embed Gremlin in a host programming language.
* [SQL2Gremlin](http://sql2gremlin.com/) - Learn Gremlin using typical patterns found when querying data with SQL.
* [Getting Started with Graph Databases](https://academy.datastax.com/demos/getting-started-graph-databases) - Compares relational databases to graph databases and SQL to Gremlin.
* [Graph](https://github.com/krlawrence/graph) ⭐ 864 | 🐛 17 | 🌐 Ruby | 📅 2026-02-26 - Graph Databases, Gremlin and TinkerPop - A Tutorial.

## <A NAME="contributing"></A>How to Contribute

![alt tag](awesome-tinkerpop.jpg)

Please follow the [guidelines here](contributing.md). Please, make sure your contribution and PR are awesome!

## <A NAME="license"></A>License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@mohataher](https://github.com/mohataher) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
