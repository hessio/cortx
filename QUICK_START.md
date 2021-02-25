## CORTX Quick Start Guide

1.  Download a CORTX virtual machine image for easy testing
    1.  Run it on a single node: [LINK](doc/CORTX_on_Open_Virtual_Appliance.rst)
    1.  Run it on a cluster: TODO
1.  Download CORTX as prepackaged software releases
    1.  Run it on a single node: TODO
    1.  Run it across a cluster: [DONE?](doc/scaleout/README.rst)
1.  Build motr from the source: [LINK](https://github.com/Seagate/cortx-motr/blob/main/doc/Quick-Start-Guide.rst)
    1.  Run freshly built motr on a single node: [LINK](https://github.com/Seagate/cortx-motr/blob/main/doc/Quick-Start-Guide.rst)
    1.  Run it on a cluster: [DONE?](https://github.com/Seagate/cortx/wiki/Build-Motr-from-Source-in-a-Cluster)
1.  Build motr + S3 from the source: [DONE?](https://github.com/Seagate/cortx-s3server/blob/main/docs/CORTX-S3%20Server%20Quick%20Start%20Guide.md)
    1.  Run it on a single node [DONE?](https://github.com/Seagate/cortx-s3server/blob/main/docs/CORTX-S3%20Server%20Quick%20Start%20Guide.md)
    1.  Run it on a cluster \[TODO\]
1.  Build entire CORTX from the source into binaries: [DONE?](https://github.com/Seagate/cortx/blob/main/doc/Release_Build_Creation.rst)
    1.  Run it on a single node: TODO
    1.  Run it on a cluster: TODO
1.  Build entire CORTX from the source into OVA: TODO
    1.  Run it on a single node: TODO
    1.  Run it on a cluster: TODO

Once you're ready to make more contributions, please check out our [Contribution Guide](CONTRIBUTING.md).

**"DONE?":** this guide exists but does not have a minimum of 2 people who have confirmed this guide works.

**"LINK":** at least 2 people have confirmed this guide works.

**"TODO":** we need to create this guide.

### What does this Guide mean?
    * This guide is a list of ways that you can try out or test the different CORTX configurations.
    * Each link above will navigate you to a configuration of CORTX, for example you can use Motr + HARE to run a single node setup of Motr, or you can run a single node setup of Motr + HARE + S3.
    * Currently if you want to test the entire CORTX system you will need to follow step 1. i.
    * To get the full CORTX experience you can download our OVA and set this up yourself (Link: 1. i.).
