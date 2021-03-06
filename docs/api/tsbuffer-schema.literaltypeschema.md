<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tsbuffer-schema](./tsbuffer-schema.md) &gt; [LiteralTypeSchema](./tsbuffer-schema.literaltypeschema.md)

## LiteralTypeSchema interface

TypeScript literal type

<b>Signature:</b>

```typescript
export interface LiteralTypeSchema 
```

## Remarks

See: [https://www.typescriptlang.org/docs/handbook/literal-types.html](https://www.typescriptlang.org/docs/handbook/literal-types.html)

Literal type is very useful to reduce encoded buffer size. No matter how long the literal is, the encoded buffer is always less than 1 byte.

## Example


```ts
type A = 'XXXX';

// Always appears with UnionType, like:
type Gender = 'Male' | 'Female';

```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [literal?](./tsbuffer-schema.literaltypeschema.literal.md) | string \| number \| boolean \| null \| undefined | <i>(Optional)</i> |
|  [type](./tsbuffer-schema.literaltypeschema.type.md) | 'Literal' |  |

