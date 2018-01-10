## Cloud Foundry

### Domains

These domains are for the Pivotal Application Service.

```
  *.system.example.com
  *.apps.example.com
```

These domains are for Spring Cloud Services and/or User Account and Authentication.

```  
  *.login.system.example.com
  *.uaa.system.example.com

```

## Terraform

* [code repo](https://github.com/hashicorp/terraform)

### Providers

> A provider is responsible for understanding API interactions and exposing resources.

* [Providers](https://www.terraform.io/docs/providers/index.html)

These are **Major Cloud** providers that are used with BOSH.

* [AWS](https://www.terraform.io/docs/providers/aws/index.html)
* [Azure](https://www.terraform.io/docs/providers/azurerm/index.html)
* [Google Cloud](https://www.terraform.io/docs/providers/google/index.html)
* [VMWare vSphere](https://www.terraform.io/docs/providers/vsphere/index.html)
* [OpenStack](https://www.terraform.io/docs/providers/openstack/index.html)

### Book

* [The Terraform Book](https://terraformbook.com) by James Turnbull

## Credhub

### Code

* [Source Code](https://github.com/cloudfoundry-incubator/credhub)

### Guides

* [HOWTO Install BOSH with Credhub](https://github.com/pivotal-cf/credhub-release/blob/master/docs/bosh-install-with-credhub.md)

* [HOWTO Install credhub-cli](https://github.com/cloudfoundry-incubator/credhub-cli#installing-the-cli)

### References

* [API and CLI Reference](https://credhub-api.cfapps.io)
* [Source Code Documentation](https://github.com/cloudfoundry-incubator/credhub/tree/master/docs)
* [Release Specification](https://bosh.io/releases/github.com/pivotal-cf/credhub-release)

## UAA

### Code

* [Source Code](https://github.com/cloudfoundry/uaa)

### Guides

* [HOWTO Integrate LDAP with UAA](https://github.com/cloudfoundry/uaa/blob/master/docs/UAA-LDAP.md)

### References

* [API Reference](http://docs.cloudfoundry.org/api/uaa/version/4.8.0/index.html#overview)
* [Source Code Documentation](https://github.com/cloudfoundry/uaa/tree/master/docs)
* [Release Specification](https://bosh.io/releases/github.com/cloudfoundry/uaa-release)
