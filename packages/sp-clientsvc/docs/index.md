# @pnp/sp-clientsvc

This library provides base classes for working with the legacy SharePoint client.svc/ProcessQuery endpoint. The base classes support most of the possibilities for types of query calls, as well as supporting fluent batching and cachine. They are based on the same @pnp/odata foundation as the other libraries so should feel familiar when extending. You can see [@pnp/sp-taxonomy](../sp-taxonomy) for an example showing how to extend these base classes into a functional fluent model.