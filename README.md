RIP
===

REST in peace. A less-then-200-lines REST wrapper.

Opinions:
----------

 - /action/param1/value1/param2/value2...
 - supports all HTTP methods
 - create a class Action<Name>, let it extend Action, put it in the lib folder
 - implement your HTTP methods there, such as function doGET(){...}
 - all non implemented methods are ... guess what...
 - you can throw HTTP responses other then 200 using functions: error_malformed($msg)
 - check required parameters with $this->assertNotEmpty($param)
 - do rest in peace.
