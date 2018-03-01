# The Projects

The aim of the opsmatters toolset is to dramatically accelerate the implementation of operational monitoring and alerting tools (such as [New Relic](http://newrelic.com)) by:
- Automating the deployment of configuration items such as Alerts and Dashboards
- Deploying changes quickly and easily using bulk import and export tools
- Using artefacts in standard formats that are easier to understand by users and version-control.

## New Relic API
A Java client library for the New Relic Monitoring and Alerting REST APIs built using Jersey and Gson.
The library implements over 110 operations across all of the available 35 New Relic services.
It is primarily used by applications to automate the configuration of New Relic Monitoring, Alerting and Dashboards, but can also be used for extracting incident and metric data, executing Insights queries, and uploading plugin metrics.

View the project on GitHub [here](https://github.com/opsmatters/newrelic-api)

Project status and latest version:  
[![Build Status](https://travis-ci.org/opsmatters/newrelic-api.svg?branch=master)](https://travis-ci.org/opsmatters/newrelic-api)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-api/badge.svg?style=blue)](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-api)
[![Javadocs](http://javadoc.io/badge/com.opsmatters/newrelic-api.svg)](http://javadoc.io/doc/com.opsmatters/newrelic-api)  

## New Relic Batch
Java library that allows New Relic objects to be created automatically from file based definitions.
New Relic Alerts can be configured from alert channels, policies and conditions in CSV or spreadsheet format.
New Relic Insights dashboards can be created from definition files in YAML format.
It provides a set of tools to accelerate or automate the deployment of New Relic Alerts and Insights dashboards.

View the project on GitHub [here](https://github.com/opsmatters/newrelic-batch)

Project status and latest version:  
[![Build Status](https://travis-ci.org/opsmatters/newrelic-batch.svg?branch=master)](https://travis-ci.org/opsmatters/newrelic-batch)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-batch/badge.svg?style=blue)](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-batch)
[![Javadocs](http://javadoc.io/badge/com.opsmatters/newrelic-batch.svg)](http://javadoc.io/doc/com.opsmatters/newrelic-batch)

## New Relic Command
Java library that allows New Relic Monitoring and Alerting configuration operations to be executed from a command line.
The library includes over 90 operations covering Alerts, Applications, Key Transactions, Deployments, Servers, Plugins, Monitors and Labels. 
It provides a set of tools to simplify or automate the configuration of New Relic Monitoring and Alerting.

View the project on GitHub [here](https://github.com/opsmatters/newrelic-command)

Project status and latest version:  
[![Build Status](https://travis-ci.org/opsmatters/newrelic-command.svg?branch=master)](https://travis-ci.org/opsmatters/newrelic-command)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-command/badge.svg?style=blue)](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/newrelic-command)
[![Javadocs](http://javadoc.io/badge/com.opsmatters/newrelic-command.svg)](http://javadoc.io/doc/com.opsmatters/newrelic-command)

## OpsMatters Core
Java library for the opsmatters suite including a data cache for New Relic Monitoring and Alerting, models, and reporting utilities.

View the project on GitHub [here](https://github.com/opsmatters/opsmatters-core)

Project status and latest version:  
[![Build Status](https://travis-ci.org/opsmatters/opsmatters-core.svg?branch=master)](https://travis-ci.org/opsmatters/opsmatters-core)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/opsmatters-core/badge.svg?style=blue)](https://maven-badges.herokuapp.com/maven-central/com.opsmatters/opsmatters-core)
[![Javadocs](http://javadoc.io/badge/com.opsmatters/opsmatters-core.svg)](http://javadoc.io/doc/com.opsmatters/opsmatters-core)

# License

The projects are licensed under the terms of the [Apache license 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).

# Contact Us

For further information on opsmatters projects email: **enquiries@opsmatters.com**

<sub>Copyright (c) 2018 opsmatters</sub>