
# Class: Events

## Hierarchy

* EventEmitter

  ↳ **Events**

## Index

### Type aliases

* [preRequest](client.events.md#static-prerequest)
* [request](client.events.md#static-request)
* [response](client.events.md#static-response)

### Properties

* [defaultMaxListeners](client.events.md#static-defaultmaxlisteners)

### Methods

* [addListener](client.events.md#addlistener)
* [emit](client.events.md#emit)
* [eventNames](client.events.md#eventnames)
* [getMaxListeners](client.events.md#getmaxlisteners)
* [listenerCount](client.events.md#listenercount)
* [listeners](client.events.md#listeners)
* [off](client.events.md#off)
* [on](client.events.md#on)
* [once](client.events.md#once)
* [prependListener](client.events.md#prependlistener)
* [prependOnceListener](client.events.md#prependoncelistener)
* [rawListeners](client.events.md#rawlisteners)
* [removeAllListeners](client.events.md#removealllisteners)
* [removeListener](client.events.md#removelistener)
* [setMaxListeners](client.events.md#setmaxlisteners)
* [listenerCount](client.events.md#static-listenercount)

## Type aliases

### `Static` preRequest

Ƭ **preRequest**: *function*

#### Type declaration:

▸ (`uri`: string, `options`: [Options](../interfaces/client.options.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`uri` | string |
`options` | [Options](../interfaces/client.options.md) |

___

### `Static` request

Ƭ **request**: *function*

#### Type declaration:

▸ (`req`: ClientRequest): *void*

**Parameters:**

Name | Type |
------ | ------ |
`req` | ClientRequest |

___

### `Static` response

Ƭ **response**: *function*

#### Type declaration:

▸ (`err`: Boom | undefined, `details`: object): *void*

**Parameters:**

▪ **err**: *Boom | undefined*

▪ **details**: *object*

Name | Type |
------ | ------ |
`req` | ClientRequest |
`res` | IncomingMessage &#124; undefined |
`start` | number |
`url` | URL |

## Properties

### `Static` defaultMaxListeners

▪ **defaultMaxListeners**: *number*

*Inherited from void*

## Methods

###  addListener

▸ **addListener**(`event`: "preRequest", `litener`: [preRequest](client.events.md#static-prerequest)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "preRequest" |
`litener` | [preRequest](client.events.md#static-prerequest) |

**Returns:** *this*

▸ **addListener**(`event`: "request", `listener`: [request](client.events.md#static-request)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "request" |
`listener` | [request](client.events.md#static-request) |

**Returns:** *this*

▸ **addListener**(`event`: "response", `listener`: [response](client.events.md#static-response)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "response" |
`listener` | [response](client.events.md#static-response) |

**Returns:** *this*

___

###  emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): *boolean*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |
`...args` | any[] |

**Returns:** *boolean*

___

###  eventNames

▸ **eventNames**(): *Array‹string | symbol›*

*Inherited from void*

*Overrides void*

**Returns:** *Array‹string | symbol›*

___

###  getMaxListeners

▸ **getMaxListeners**(): *number*

*Inherited from void*

*Overrides void*

**Returns:** *number*

___

###  listenerCount

▸ **listenerCount**(`type`: string | symbol): *number*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | string &#124; symbol |

**Returns:** *number*

___

###  listeners

▸ **listeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  off

▸ **off**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  on

▸ **on**(`event`: "preRequest", `litener`: [preRequest](client.events.md#static-prerequest)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "preRequest" |
`litener` | [preRequest](client.events.md#static-prerequest) |

**Returns:** *this*

▸ **on**(`event`: "request", `listener`: [request](client.events.md#static-request)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "request" |
`listener` | [request](client.events.md#static-request) |

**Returns:** *this*

▸ **on**(`event`: "response", `listener`: [response](client.events.md#static-response)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "response" |
`listener` | [response](client.events.md#static-response) |

**Returns:** *this*

___

###  once

▸ **once**(`event`: "preRequest", `litener`: [preRequest](client.events.md#static-prerequest)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "preRequest" |
`litener` | [preRequest](client.events.md#static-prerequest) |

**Returns:** *this*

▸ **once**(`event`: "request", `listener`: [request](client.events.md#static-request)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "request" |
`listener` | [request](client.events.md#static-request) |

**Returns:** *this*

▸ **once**(`event`: "response", `listener`: [response](client.events.md#static-response)): *this*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | "response" |
`listener` | [response](client.events.md#static-response) |

**Returns:** *this*

___

###  prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  rawListeners

▸ **rawListeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`event?` | string &#124; symbol |

**Returns:** *this*

___

###  removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  setMaxListeners

▸ **setMaxListeners**(`n`: number): *this*

*Inherited from void*

*Overrides void*

**Parameters:**

Name | Type |
------ | ------ |
`n` | number |

**Returns:** *this*

___

### `Static` listenerCount

▸ **listenerCount**(`emitter`: EventEmitter, `event`: string | symbol): *number*

*Inherited from void*

**`deprecated`** since v4.0.0

**Parameters:**

Name | Type |
------ | ------ |
`emitter` | EventEmitter |
`event` | string &#124; symbol |

**Returns:** *number*
