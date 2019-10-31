
# Module: request

## Callable

▸ **request**(`method`: string, `url`: string, `options?`: [Options](../interfaces/client.request.options.md)): *Promise‹IncomingMessage› & object*

Request an HTTP resource.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`method` | string | a string specifying the HTTP request method. Defaults to 'GET'. |
`url` | string | the URI of the requested resource. |
`options?` | [Options](../interfaces/client.request.options.md) | default options override.  |

**Returns:** *Promise‹IncomingMessage› & object*

a promise resolving into an HTTP response object with a 'req' property holding a reference to the HTTP request object.

## Index

### Interfaces

* [Options](../interfaces/client.request.options.md)
* [Response](../interfaces/client.request.response.md)

### Type aliases

* [Payload](client.request.md#payload)

## Type aliases

###  Payload

Ƭ **Payload**: *string | Buffer | Stream.Readable | object*
