<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [CodingContract](./bitburner.codingcontract.md) &gt; [attempt](./bitburner.codingcontract.attempt.md)

## CodingContract.attempt() method

Attempts to solve the Coding Contract with the provided solution.

<b>Signature:</b>

```typescript
attempt(answer: string | string[] | number, fn: string, host?: string): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  answer | string \| string\[\] \| number | Solution for the contract. |
|  fn | string | Filename of the contract. |
|  host | string | Host or IP of the server containing the contract. Optional. Defaults to current server if not provided. |

<b>Returns:</b>

boolean

True if the solution was correct, false otherwise.

## Remarks

10 GB
