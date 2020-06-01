Role Name
=========

Role that installs OpenRefine.
OpenRefine is a free, open source power tool for working with messy data and improving it. <https://openrefine.org/>

Role Variables
--------------

The list of extensions

``` yaml
openrefine_extensions:
  - { url: 'https://github.com/FAIRDataTeam/OpenRefine-metadata-extension/releases/download/v1.4.0/metadata-1.4.0-OpenRefine-3.3.tgz', name: 'metadata' }
  - { url: 'https://github.com/stkenny/grefine-rdf-extension/releases/download/v1.2.0-orefine-3.3/rdf-extension-1.2.0-orefine-3.3.zip', name: 'rdf' }
```

Dependencies
------------

openjdk

License
-------

EUPL-1.2

Author Information
------------------

Andrea Dell'Amico, <andrea.dellamico@isti.cnr.it>
