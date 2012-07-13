# yum-repo-client
===============

## Aim
yum-repo-client is a command line interface for interacting with the yum-repo-server [http://github.com/is24-herold/yum-repo-server]
The aim is to provide a command line wrapper for every functionality the yum-repo-server provides so you don't have to fiddle with REST requests.

## Features
The yum-repo-client currently supports
* Remote repository creation
* RPM upload and remote deletion
* Virtual repository creation, linking and deletion
* Optional authentication and yum-repo-server host parametrization
* Smart bash autocompletion

## Getting started

### Using the yum-repo-client
Simply call <code> repoclient </code> to display the help text that includes call syntax and operation description