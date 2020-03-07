## InterSystems IRIS, Docker and ObjectScript
In the contest we will accept and then choose the best application built using InterSystems ObjectScript and which could be launched on either [InterSystems IRIS Community Edition](https://hub.docker.com/_/intersystems-iris-data-platform/plans/222f869e-567c-4928-b572-eb6a29706fbd?tab=instructions),
or [InterSystems IRIS for Health Community Edition] (https://hub.docker.com/_/intersystems-iris-for-health/plans/80ae1325-d535-484e-8307-b643c2865dd8?tab=instructions).

The application also must meet the ObjectScript CLI requirement. Your application could be be the library, package or a tool, can be used as a method call from another ObjectScript class or simply in IRIS Terminal.

If git cloned or download the application should be runnable with docker container. E.g.:
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
**Make sure to highlight in README.md of your repository how it could be used.**

[Read and discuss the rules, nominationos and judgement](https://community.intersystems.com/post/contest-intersystems-developers-iris-docker-and-objectscript).
