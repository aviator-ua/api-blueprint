# API Blueprint Glossary of Terms

A brief list of terms as used in the [API Blueprint](http://apiblueprint.org) context. 

Refer to W3C [Glossary of Terms for Device Independence](http://www.w3.org/TR/di-gloss/) for additional terms. 

## Glossary

<a name="def-action"></a>
### Action
A **HTTP transaction** (a request-response transaction).

<a name="def-api"></a>
### API
A **HTTP Application programming interface**. Might refer to an API description. See [**API Blueprint**](#def-api-blueprint).

<a name="def-api-blueprint"></a>
### API Blueprint
The **API Blueprint language**. A format used to describe API in an API blueprint file.

<a name="def-asset"></a>
### Asset
**Atomic data**. Most often representing one resource representation in the form of message-body or its validation schema.

<a name="def-blueprint"></a>
### Blueprint
An **API description**. A **blueprint file** (or a set of files) that describes an API using the API Blueprint language.

<a name="def-header"></a>
### Header
A [**message-header**](#def-message-header).

<a name="def-method"></a>
### Method
An [**HTTP Request Method**](http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods).

<a name="def-message"></a>
### Message
An **HTTP transaction message**.

<a name="def-message-body"></a>
### Message body
An [**asset**](#def-asset) representing [**HTTP transaction message body**](http://en.wikipedia.org/wiki/HTTP_body_data). 

<a name="def-message-header"></a>
### Message header
An [**asset**](#def-asset) representing [**HTTP transaction message header**](http://en.wikipedia.org/wiki/List_of_HTTP_header_fields). 

<a name="def-parameter"></a>
### Parameter
An [**URI template**](#def-uri-template) **variable**. Also a **message-body key** (field/object) where applicable. 

<a name="def-payload"></a>
### Payload
A **HTTP transaction message** as well as its **discussion**,  **parameters description** and any **additional** related [**assets**](#def-asset) such as a validation schema.

A payload may have its **identifier** – an alphanumerical string for a [request](#def-request) payload or an [HTTP status code](http://en.wikipedia.org/wiki/List_of_HTTP_status_codes) for a [response](#def-response) payload.

<a name="def-request"></a>
### Request
A [**payload**](#def-payload) containing one specific [HTTP Request](http://www.w3.org/TR/di-gloss/#def-http-request).

<a name="def-response"></a>
### Response
A [**payload**](#def-payload) containing one specific [HTTP Response](http://www.w3.org/TR/di-gloss/#def-http-response).

<a name="def-resource"></a>
### Resource
An API [**resource**](http://www.w3.org/TR/di-gloss/#def-resource) specified by its *URI*. It can also refer to a [**set of resources**](#def-resource) matching one [**URI template**](#def-uri-template).

<a name="def-resource-set"></a>
### Resource Set
A set of API [**resources**](http://www.w3.org/TR/di-gloss/#def-resource) its *URI* matches one specific  [**URI template**](#def-uri-template).

<a name="def-schema"></a>
### Schema
A **validation schema** in a form of an [**asset**](#def-asset) used to validate (or describe) a [**message-body**](#def-message-body).

<a name="def-uri-template"></a>
### URI template
A compact sequence of characters for describing a range of **Uniform Resource Identifiers** through **variable** expansion, see [**RFC 6570**](http://tools.ietf.org/html/rfc6570).