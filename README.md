# CBOR RPC

[Concise Binary Object Representation (CBOR)](https://en.wikipedia.org/wiki/CBOR).

Inspired by 
- [Crazyradio 2.0 CBOR RPC specification](https://www.bitcraze.io/documentation/repository/crazyradio2-firmware/main/functional-areas/CBOR-RPC/)
- [JSON-RPC 2.0 Specification](https://www.jsonrpc.org/specification)

## Implementation

- [actor](https://github.com/crosstyan/booru-explorer/blob/ad23707f9ec2a92f4e0b2722ec1014da22468a5f/src/cborpc/stream.ts#L144-L222)
- [caller](https://github.com/crosstyan/pg-arrow-query/blob/48bcfd4897c77cd5125b06ac24e9e8f7c8b8694c/client/src/cborpc/stream.ts#L137-L221)
- [server](https://github.com/crosstyan/pg-arrow-query/blob/48bcfd4897c77cd5125b06ac24e9e8f7c8b8694c/serve.py#L47-L105) A crude implementation in Python

## See

[Specification](spec.adoc)

## See also

- [aaronhuggins/cbor-redux](https://github.com/aaronhuggins/cbor-redux)

