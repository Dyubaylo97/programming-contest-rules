## Topic of the Contest
In this programming contest, we will accept applications that meet the **ObjectScript REST API** requirement. 
Your application could be a library, package or tool which exposes REST API or Web Sockets interface built on InterSystems IRIS or InterSystems IRIS for Health.

The application could be launched from either [InterSystems IRIS Community Edition](https://hub.docker.com/_/intersystems-iris-data-platform/plans/222f869e-567c-4928-b572-eb6a29706fbd?tab=instructions),
or [InterSystems IRIS for Health Community Edition](https://hub.docker.com/_/intersystems-iris-for-health/plans/80ae1325-d535-484e-8307-b643c2865dd8?tab=instructions).

When cloned or downloaded the application should be runnable with:
```
$ docker-compose up -d
```
Or installed as a ZPM module:
```
zpm:ANYNAMESPACE>install module-name
```
Once installed, REST API or Web Sockets application should be available at localhost:anyport/your/application.

### Technology bonuses

If the application satisfies some additional requirements listed below it gets additional technology votes, one per each requirement. 

Here are the technology bonuses for this contest:

- ZPM package - The solution should be installed via ZPM package
- [Open API (swagger)](https://swagger.io/specification/) documentation, available at /_spec endpoint of your REST API.

[Sample Application](https://openexchange.intersystems.com/package/objectscript-rest-docker-template)

**Don't forget to highlight in README of your application how it should be used.**

## How to Apply
Log in to Open Exchange, open your application page, make sure that it meets the requirements and click the "Apply for Contest" button. Your application will be sent for approval and once approved will appear on the Contest page eventually.

## Prizes and Nomination
**General Nomination**
- 1st place - $2,000
- 2nd place - $1,000
- 3nd place - $500

**Community Nomination**
- 1st place - $1,000
- 2nd place - $500

## Terms and Conditions, Rules and Judgment Criteria
By participating in the Contest you agree with the following [Terms and Conditions](https://openexchange.intersystems.com/markdown?url=/assets/doc/contest-terms.md)

[Read and discuss the rules, nominations, and judgment criteria](https://community.intersystems.com/post/contest-intersystems-developers-iris-docker-and-objectscript).
