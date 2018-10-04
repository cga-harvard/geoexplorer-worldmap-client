This is the WorldMap GeoExplorer client source code, which is part of GeoNode WorldMap contrib application, and deployed at pypi here: https://pypi.org/project/django-geoexplorer-worldmap/

JavaScript Developers can switch to using unminified scripts by cloning this repository and:

```
$ cd geonode-client
$ ant init debug
```

Set the GEONODE_CLIENT_LOCATION entry in to http://localhost:9090/ in GeoNode settings.

To build the library:

```
$ cd geonode-client
$ ant buildjs
```
