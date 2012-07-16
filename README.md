# yum-repo-client
===============

## Aim
yum-repo-client is a command line interface for interacting with the yum-repo-server [http://github.com/is24-herold/yum-repo-server]
The aim is to provide a command line wrapper for every functionality the yum-repo-server provides so you don't have to fiddle with REST requests.
This is especially good for automations that can run command line tools because you can modify the yum-repo-server as you wish without breaking your automation (provided you include the modifications in the yum-repo-client).

## Features
The yum-repo-client currently supports
* Remote repository creation
* RPM upload and remote deletion
* Virtual repository creation, linking and deletion
* Optional authentication and yum-repo-server host parametrization
* Smart bash autocompletion

## Getting started
### Building the yum-repo-client
First of all it is recommendet to run the tests:
<code>
python setup.py test
</code>

These should always be successfull. 
Optionally after that you can run:
<code>
python setup.py bdist_rpm
</code>
to get an rpm of the yum-repo-client.
### Installing the yum-repo-client
If you have build a rpm file in the step above, then you can install it as usual.
Without the rpm file you can install the yum-repo-client with:
<code>
python setup.py install
</code>
### Using the yum-repo-client
Simply call 
<code> [you@yourhost ~]$ repoclient </code> 
to display the help text that includes call syntax and operation description
### Extending or customizing the yum-repo-client
