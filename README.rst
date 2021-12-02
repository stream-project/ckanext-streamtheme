=============
ckanext-STREAMtheme
=============

This CKAN theme is based on the TIB theme: https://github.com/TIBHannover/ckanext-TIBtheme
It adds a view elements and styles to the CKAN installation.

------------
Requirements
------------

None.

------------
Installation
------------
In the dockerfile:
```
ADD ./Plugins/ckanext-streamtheme $CKAN_HOME/src/ckanext-streamtheme
RUN ckan-pip install -e $CKAN_HOME/src/ckanext-streamtheme
```

