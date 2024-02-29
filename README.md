Task

1. Implement Stores api
   http://localhost:3001/stores?\_page={page_no}&\_per_page={per_page}&\_sort={key/-key}

Query Parameters
\_page: The page number of the results to fetch.

Type: Integer
Description: Specifies the page of results to return.
Required: No
Default: 1
\_per_page: The number of items per page.

Type: Integer
Description: Limits the number of items returned in one request, allowing for pagination.
Required: No
Default: 10
\_sort: The key to sort the results by.

Type: String
Description: Determines the sorting order of the results based on the specified field. Prepend with - for descending order.
Required: No
Examples:
name: Sorts the stores by name in ascending order.
-name: Sorts the stores by name in descending order.

Reference web page => https://lbp8.enactweb.com/all-stores
