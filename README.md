ECGALAXY maven role
===================

Installs Maven - https://maven.apache.org/

Requirements
------------

- A Java JDK, which can be provided by ecgalaxy.java_openjdk

Role Variables
--------------

- maven_version: the Maven version to be installed
- maven_download_url: the URL of the archive to be downloaded
- maven_checksum: the checksum of the archive
- maven_path: the path where Maven will be installed
- maven_bin: the path of the symlink which will point to the Maven executable

Dependencies
------------

- optional: ecgalaxy.bootstrap
- optional: ecgalaxy.java_openjdk

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.java_openjdk
        - ecgalaxy.maven

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
