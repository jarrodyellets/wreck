
# Class: Client

An HTTP request client.

## Hierarchy

* **Client**

## Index

### Modules

* [parseCacheControl](../modules/client.parsecachecontrol.md)
* [read](../modules/client.read.md)
* [request](../modules/client.request.md)
* [toReadableStream](../modules/client.toreadablestream.md)

### Classes

* [Events](client.events.md)

### Interfaces

* [Agents](../interfaces/client.agents.md)
* [Options](../interfaces/client.options.md)

### Constructors

* [constructor](client.md#constructor)

### Properties

* [agents](client.md#agents)
* [events](client.md#optional-events)

### Methods

* [defaults](client.md#defaults)
* [delete](client.md#delete)
* [get](client.md#get)
* [patch](client.md#patch)
* [post](client.md#post)
* [put](client.md#put)

## Constructors

###  constructor

\+ **new Client**(`options?`: [Options](../interfaces/client.options.md)): *[Client](client.md)*

Creates a new client.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`options?` | [Options](../interfaces/client.options.md) | the client default options.  |

**Returns:** *[Client](client.md)*

## Properties

###  agents

• **agents**: *[Agents](../interfaces/client.agents.md)*

An object containing the node agents used for pooling connections for `http` and `https`.

___

### `Optional` events

• **events**? : *[Events](client.events.md)*

An event emitter used to deliver events when the `events` option is set.

## Methods

###  defaults

▸ **defaults**(`options`: [Options](../interfaces/client.options.md)): *[Client](client.md)*

Creates a new client using the current client options as defaults and the provided options as override.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`options` | [Options](../interfaces/client.options.md) | the client override options.  |

**Returns:** *[Client](client.md)*

a new client.

___

###  delete

▸ **delete**<**T**>(`uri`: string, `options?`: [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md)): *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

Performs an HTTP DELETE request.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | string | the resource URI. |
`options?` | [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

the received payload Buffer or parsed payload based on the options.

___

###  get

▸ **get**<**T**>(`uri`: string, `options?`: [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md)): *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

Performs an HTTP GET request.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | string | the resource URI. |
`options?` | [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

the received payload Buffer or parsed payload based on the options.

___

###  patch

▸ **patch**<**T**>(`uri`: string, `options?`: [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md)): *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

Performs an HTTP PATCH request.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | string | the resource URI. |
`options?` | [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

the received payload Buffer or parsed payload based on the options.

___

###  post

▸ **post**<**T**>(`uri`: string, `options?`: [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md)): *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

Performs an HTTP POST request.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | string | the resource URI. |
`options?` | [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

the received payload Buffer or parsed payload based on the options.

___

###  put

▸ **put**<**T**>(`uri`: string, `options?`: [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md)): *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

Performs an HTTP PUT request.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`uri` | string | the resource URI. |
`options?` | [Options](../interfaces/client.request.options.md) & [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹[Response](../interfaces/client.request.response.md)‹T››*

the received payload Buffer or parsed payload based on the options.
