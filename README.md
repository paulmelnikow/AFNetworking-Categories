AFNetworking-Categories
=======================

A category which extends AFHTTPClient to provide the queued operation to the caller.
 
Since the operation is **already queued** and may already be started, the caller should not attempt to modify it.
 
However, the caller may cancel the operation, wait until it's finished, or use it as a dependency for another NSOperation.