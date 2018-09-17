# aws-securitygroup-grapher

This ansible role gets information from an aws VPC and generate a [graphical representation](CloudGrapher.png) of security groups through a dot file rendered by [Graphviz](https://graphviz.gitlab.io/)

## Requirements

[Boto](https://aws.amazon.com/fr/sdk-for-python/) library needs to be installed, as that is required by the EC2 Ansible modules.

To render (i.e. to draw and obtain a graphic file), Graphviz needs to be installed.
