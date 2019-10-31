
# Module: toReadableStream

## Callable

▸ **toReadableStream**(`payload`: [Payload](client.toreadablestream.md#payload), `encoding?`: string): *Stream.Readable*

Converts a buffer, string, or an array of them into a readable stream.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`payload` | [Payload](client.toreadablestream.md#payload) | a string, buffer, or an array of them. |
`encoding?` | string | the payload encoding.  |

**Returns:** *Stream.Readable*

a readable stream.

## Index

### Type aliases

* [Item](client.toreadablestream.md#item)
* [Payload](client.toreadablestream.md#payload)

## Type aliases

###  Item

Ƭ **Item**: *string | Buffer*

___

###  Payload

Ƭ **Payload**: *[Item](client.toreadablestream.md#item) | [Item](client.toreadablestream.md#item)[]*
