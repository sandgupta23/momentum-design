<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@momentum-design/builder](./builder.md) &gt; [Builder](./builder.builder.md) &gt; [build](./builder.builder.build.md)

## Builder.build() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Build the output data based on the configuration provided to this Builder.

<b>Signature:</b>

```typescript
build(): Promise<this>;
```
<b>Returns:</b>

Promise&lt;this&gt;

- This Builder after executing this method.

## Remarks

This method triggers the configuration read flow, then the initialize flow then finally the process flow.
