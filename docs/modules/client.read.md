
# Module: read

## Callable

▸ **read**<**T**>(`res`: Stream.Readable | IncomingMessage, `options?`: [Options](../interfaces/client.read.options.md)): *Promise‹T›*

Reads a readable stream and returns the parsed payload.

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`res` | Stream.Readable &#124; IncomingMessage | the readable stream. |
`options?` | [Options](../interfaces/client.read.options.md) | default options override.  |

**Returns:** *Promise‹T›*

the parsed payload based on the provided options.

## Index

### Interfaces

* [Options](../interfaces/client.read.options.md)
