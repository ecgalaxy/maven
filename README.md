ECGALAXY maven role
==================

Installs Maven - https://maven.apache.org/

Requirements
------------

* A Java JDK, which can be provided by ecgalaxy.java8_openjdk

Role Variables
--------------

* maven_version: the Maven version to be installed
* maven_download_url: the URL of the archive to be downloaded
* maven_checksum: the checksum of the archive
* maven_path: the path where Maven will be installed
* maven_bin: the path of the symlink which will point to the Maven executable

Dependencies
------------

* optional: ecgalaxy.bootstrap
* optional: ecgalaxy.java8_openjdk

Example Playbook
----------------

TODO.

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
