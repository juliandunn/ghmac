Description
===========

Installs GitHub Mac.

Requirements
============

OS X and a GitHub account.

Attributes
==========

* `node['ghmac']['url']` - URL to retrieve the zip file. Default is 1.0 (from version below.
* `node['ghmac']['checksum']` - sha256sum of the zip file. Default is 1.0's sha256sum.
* `node['ghmac']['version']` - version of GitHub Mac. Default "1.0".
* `node['ghmac']['install_to']` - location to extract the .zip. Default "/Applications"

Usage
=====

Add 'ghmac' recipe to a node and run Chef.

License and Author
==================

Author:: Joshua Timberman (<cookbooks@housepub.org>)

Copyright 2011, Joshua Timberman

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
