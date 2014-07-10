PHP-Parse.com-tools
===================

Tools for the main functions of the Parse.com REST API. (https://parse.com/docs/rest)

parseUpload($fileURL)
------------------------
Upload a file to Parse.com.
**input:** The file's URL

parseFetch($parseClassName, $parametersArray)
------------------------
Perform a query on a Parse.com class.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#queries)

parseCreate($parseClassName, $parameters)
------------------------
Create a data object.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#objects-creating)

parseDelete($parseClassName, $parseObjectID)
------------------------
Delete a data object.
**input:** Parse.com data class name, parameters (more: https://parse.com/docs/rest#objects-deleting)

parseUpdate($parseClassName, $parseObjectID, $parameters)
------------------------
Update a data object.
**input:** Parse.com data class name, object ID, parameters (more: https://parse.com/docs/rest#objects-updating)

