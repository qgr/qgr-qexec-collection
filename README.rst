====================
qgr-qexec-collection
====================

Qoogr Query Executor for Backbone Collections. Given a Collection to be
queried, this Executor interprets Qoogr Query Trees and returns result Models
in a new Backbone Collection.

Note: Only filter and limit operations are supported, since it is assumed that
a Collection of the same Models is desired as the output. Otherwise, the
Executor for Javascript Arrays (qgr-qexec-array) should be used, with the
Collection being transformed into an Array prior to querying.

