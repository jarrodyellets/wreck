
# Interface: Options

## Hierarchy

* **Options**

  ↳ [Options](client.options.md)

## Index

### Properties

* [gunzip](client.read.options.md#optional-gunzip)
* [json](client.read.options.md#optional-json)
* [maxBytes](client.read.options.md#optional-maxbytes)
* [timeout](client.read.options.md#optional-timeout)

## Properties

### `Optional` gunzip

• **gunzip**? : *boolean | "force"*

Determines how to handle gzipped payloads.

**`default`** false

___

### `Optional` json

• **json**? : *boolean | "strict" | "force"*

Determines how to parse the payload as JSON.

___

### `Optional` maxBytes

• **maxBytes**? : *number*

The maximum allowed response payload size.

**`default`** 0

___

### `Optional` timeout

• **timeout**? : *number*

The number of milliseconds to wait while reading data before aborting handling of the response.

**`default`** 0
