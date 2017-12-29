

# NGS_ChIP-Seq_Sperm_Histones

One of the main goals is to make the access to entire tool suites as easy as possible. Usually,
this includes the setup of a public available web-service that needs to be maintained, or that the Tool-user needs to either setup a Galaxy Server by its own or to have Admin access to a local Galaxy server.
With docker, tool developers can create their own Image with all dependencies and the user only needs to run it within docker.

The Image is based on [Ubuntu 14.04 LTS](http://releases.ubuntu.com/14.04/) and all recommended Galaxy requirements are installed. The following chart should illustrate the [Docker](http://www.docker.io) image hierarchy we have build to make is as easy as possible to build on different layers of our stack and create many exciting Galaxy flavors.

![Docker hierarchy](https://raw.githubusercontent.com/dktanwar/NGS_ChIP-Seq_Sperm_Histones/blob/master/12dockergalaxy.png)
