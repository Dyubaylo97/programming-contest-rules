## InterSystems IRIS, Docker and ObjectScript
We will choose the best application built using InterSystems ObjectScript and which could be launched on either [InterSystems IRIS Community Edition](https://hub.docker.com/_/intersystems-iris-data-platform/plans/222f869e-567c-4928-b572-eb6a29706fbd?tab=instructions),
or [InterSystems IRIS for Health Community Edition] (https://hub.docker.com/_/intersystems-iris-for-health/plans/80ae1325-d535-484e-8307-b643c2865dd8?tab=instructions).

InterSystems IRIS CE Docker and ObjectScript requirement:

If we clone or download the application it should be runnable with docker container. E.g.:
```
$ docker-compose up -d
```
[Example of an application](https://github.com/intersystems-community/objectscript-docker-template)

The application could be implemented as CLI, with execution in the IRIS terminal. e.g.:

```
$ docker-compose exec iris iris session iris

Node: 981b8e5c8f7a, Instance: IRIS

USER>w ##class(Your.Application).MakeTheWorldABetterPlace()
```

[Read and discuss the rules, nominationos and judgement](https://community.intersystems.com/post/contest-intersystems-developers-iris-docker-and-objectscript).
