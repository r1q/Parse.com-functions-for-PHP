Parse.com functions for PHP
===================

Tools for the main functions of the Parse.com REST API. (https://parse.com/docs/rest). Include it in your PHP file and you're ready to go.

parseUpload($fileURL)
------------------------
Upload a file to Parse.com.
**input:** The file's URL
**JSON output:** Parse.com response or error

parseFetch($parseClassName, $parametersArray)
------------------------
Perform a query on a Parse.com class.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#queries)
**JSON output:** Parse.com response or error

parseCreate($parseClassName, $parameters)
------------------------
Create a data object.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#objects-creating)
**JSON output:** Parse.com response or error

parseDelete($parseClassName, $parseObjectID)
------------------------
Delete a data object.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#objects-deleting)
**JSON output:** Parse.com response or error

parseUpdate($parseClassName, $parseObjectID, $parameters)
------------------------
Update a data object.
**input:** Parse.com data class name, object ID, parameters (more: https://parse.com/docs/rest#objects-updating)
**JSON output:** Parse.com response or error
