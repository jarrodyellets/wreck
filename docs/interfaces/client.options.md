
# Interface: Options

## Hierarchy

* [Options](client.request.options.md)

* [Options](client.read.options.md)

  ↳ **Options**

## Index

### Properties

* [agent](client.options.md#optional-agent)
* [agents](client.options.md#optional-agents)
* [baseUrl](client.options.md#optional-baseurl)
* [beforeRedirect](client.options.md#optional-beforeredirect)
* [ciphers](client.options.md#optional-ciphers)
* [events](client.options.md#optional-events)
* [gunzip](client.options.md#optional-gunzip)
* [headers](client.options.md#optional-headers)
* [json](client.options.md#optional-json)
* [maxBytes](client.options.md#optional-maxbytes)
* [payload](client.options.md#optional-payload)
* [redirect303](client.options.md#optional-redirect303)
* [redirectMethod](client.options.md#optional-redirectmethod)
* [redirected](client.options.md#optional-redirected)
* [redirects](client.options.md#optional-redirects)
* [rejectUnauthorized](client.options.md#optional-rejectunauthorized)
* [secureProtocol](client.options.md#optional-secureprotocol)
* [socketPath](client.options.md#optional-socketpath)
* [timeout](client.options.md#optional-timeout)

## Properties

### `Optional` agent

• **agent**? : *Agent | Agent | false*

*Inherited from [Options](client.request.options.md).[agent](client.request.options.md#optional-agent)*

Node HTTP or HTTPS Agent object (false disables agent pooling).

___

### `Optional` agents

• **agents**? : *[Agents](client.agents.md)*

An object containing the node agents used for pooling connections for `http` and `https`.

___

### `Optional` baseUrl

• **baseUrl**? : *string*

*Inherited from [Options](client.request.options.md).[baseUrl](client.request.options.md#optional-baseurl)*

Fully qualified URL string used as the base URL.

___

### `Optional` beforeRedirect

• **beforeRedirect**? : *function*

*Inherited from [Options](client.request.options.md).[beforeRedirect](client.request.options.md#optional-beforeredirect)*

A function to call before a redirect is triggered.

**`param`** a string specifying the redirect method.

**`param`** HTTP status code of the response that triggered the redirect.

**`param`** The redirect location string.

**`param`** An object with the headers received as part of the redirection response.

**`param`** Options that will be applied to the redirect request. Changes to this object are applied to the redirection request.

**`param`** the callback function called to perform the redirection.

#### Type declaration:

▸ (`redirectMethod`: string, `statusCode`: number, `location`: string, `resHeaders`: Record‹string, string›, `redirectOptions`: [Options](client.request.options.md), `next`: function): *void*

**Parameters:**

▪ **redirectMethod**: *string*

▪ **statusCode**: *number*

▪ **location**: *string*

▪ **resHeaders**: *Record‹string, string›*

▪ **redirectOptions**: *[Options](client.request.options.md)*

▪ **next**: *function*

▸ (): *void*

___

### `Optional` ciphers

• **ciphers**? : *string*

*Inherited from [Options](client.request.options.md).[ciphers](client.request.options.md#optional-ciphers)*

TLS list of TLS ciphers to override node's default.

___

### `Optional` events

• **events**? : *boolean*

Enables events.

**`default`** false

___

### `Optional` gunzip

• **gunzip**? : *boolean | "force"*

*Inherited from [Options](client.request.options.md).[gunzip](client.request.options.md#optional-gunzip)*

*Overrides [Options](client.read.options.md).[gunzip](client.read.options.md#optional-gunzip)*

Determines how to handle gzipped payloads.

**`default`** false

___

### `Optional` headers

• **headers**? : *Record‹string, string›*

*Inherited from [Options](client.request.options.md).[headers](client.request.options.md#optional-headers)*

An object containing the request headers.

___

### `Optional` json

• **json**? : *boolean | "strict" | "force"*

*Inherited from [Options](client.read.options.md).[json](client.read.options.md#optional-json)*

Determines how to parse the payload as JSON.

___

### `Optional` maxBytes

• **maxBytes**? : *number*

*Inherited from [Options](client.read.options.md).[maxBytes](client.read.options.md#optional-maxbytes)*

The maximum allowed response payload size.

**`default`** 0

___

### `Optional` payload

• **payload**? : *[Payload](../modules/client.request.md#payload)*

*Inherited from [Options](client.request.options.md).[payload](client.request.options.md#optional-payload)*

The request body as a string, Buffer, readable stream, or an object that can be serialized using `JSON.stringify()`.

___

### `Optional` redirect303

• **redirect303**? : *boolean*

*Inherited from [Options](client.request.options.md).[redirect303](client.request.options.md#optional-redirect303)*

Enables redirects on 303 responses (using GET).

**`default`** false

___

### `Optional` redirectMethod

• **redirectMethod**? : *string*

*Inherited from [Options](client.request.options.md).[redirectMethod](client.request.options.md#optional-redirectmethod)*

Overrides the HTTP method used when following 301 and 302 redirections. Defaults to the original method.

___

### `Optional` redirected

• **redirected**? : *function*

*Inherited from [Options](client.request.options.md).[redirected](client.request.options.md#optional-redirected)*

A function to call when a redirect was triggered.

**`param`** HTTP status code of the response that triggered the redirect.

**`param`** the redirected location string.

**`param`** the new ClientRequest object which replaces the one initially returned.

#### Type declaration:

▸ (`statusCode`: number, `location`: string, `req`: ClientRequest): *void*

**Parameters:**

Name | Type |
------ | ------ |
`statusCode` | number |
`location` | string |
`req` | ClientRequest |

___

### `Optional` redirects

• **redirects**? : *number | false*

*Inherited from [Options](client.request.options.md).[redirects](client.request.options.md#optional-redirects)*

The maximum number of redirects to follow.

**`default`** false

___

### `Optional` rejectUnauthorized

• **rejectUnauthorized**? : *boolean*

*Inherited from [Options](client.request.options.md).[rejectUnauthorized](client.request.options.md#optional-rejectunauthorized)*

TLS flag indicating whether the client should reject a response from a server with invalid certificates.

___

### `Optional` secureProtocol

• **secureProtocol**? : *string*

*Inherited from [Options](client.request.options.md).[secureProtocol](client.request.options.md#optional-secureprotocol)*

TLS flag indicating the SSL method to use, e.g. `SSLv3_method` to force SSL version 3.

___

### `Optional` socketPath

• **socketPath**? : *string*

*Inherited from [Options](client.request.options.md).[socketPath](client.request.options.md#optional-socketpath)*

A UNIX socket path string for direct server connection.

___

### `Optional` timeout

• **timeout**? : *number*

*Inherited from [Options](client.request.options.md).[timeout](client.request.options.md#optional-timeout)*

*Overrides [Options](client.read.options.md).[timeout](client.read.options.md#optional-timeout)*

Number of milliseconds to wait without receiving a response before aborting the request.

**`default`** 0
