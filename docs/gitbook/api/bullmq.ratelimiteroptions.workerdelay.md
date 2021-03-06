<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [RateLimiterOptions](./bullmq.ratelimiteroptions.md) &gt; [workerDelay](./bullmq.ratelimiteroptions.workerdelay.md)

## RateLimiterOptions.workerDelay property

This option enables a heuristic so that when a queue is heavily rete limited, it delays the workers so that they do not try to pick jobs when there is no point in doing so. Note: It is not recommended to use this option when using groupKeys unless you have a big amount of workers since you may be delaying workers that could pick jobs in groups that have not been rate limited.

<b>Signature:</b>

```typescript
workerDelay?: boolean;
```
