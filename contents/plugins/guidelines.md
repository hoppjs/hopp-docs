# hopp Plugin Guidelines

We want to help ensure that the hopp plugin ecosystem is a
quality ecosystem and maintains the values of hopp. In an
attempt to accomplish this, we will be maintaining this set
of guidelines to define what a quality plugin is. If you fail
to meet these guidelines, we're afraid we cannot include your
plugin in the official plugin registry. So please make sure
you read this document before setting sail on your project.

 1. **An alternate plugin that solves the same goal must not
 exist.** For instance, if a `hopp-eslint` plugin already exists,
 there is no reason to create another plugin and name it something
 like `hopp-better-eslint`. Instead, try to contribute to the
 existing plugin repository and if there is a serious problem
 (such as the original maintainer no longer providing maintainence)
 then please [contact us](mailto:hopp@apps.alibhai.co) and we will
 try to help you out.

 2. **All plugins must be compatible with node v4 but promote modern
 development.** hopp provides legacy support for node v4 users - because
 we know there's a lot of you guys. However, we want to move forwards
 as much as possible towards the newer ECMAScript versions.