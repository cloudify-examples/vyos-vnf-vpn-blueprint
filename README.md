# vyos-vnf-vpn-blueprint
This blueprint is an implementation of 2 provisioning services, and a configuration serice that relates to the 2 instances of vrouters to configure a tunnel in between them.

instructions for use is to take a release zip, and create a local blueprunt from each one of the 3 yaml files inside.
vyos-vnf-hub-baseline.yaml
vyos-vnf-branch-baseline.yaml
vyos-vpn-config-service.yaml

deploy&install the first 2 blueprints and after they are completed, deploy and isnatll the configuration service blueprint, with references to the previous 

** current architecture relay on openstack external network and vIP assoiciations to, if needed, make change in the external newtwork nod eof the VNF provisiong yamls
