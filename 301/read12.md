# Authentication

## What is a status code 202?

* In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

## What is a status code 308?

* This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

## What code would you use if an update didn’t return data to a client?

* 204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.

## What code would you use if a resource used to exist but no longer does?

* 410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.

## What is the ‘Forbidden’ status code?

* 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
