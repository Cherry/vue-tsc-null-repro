Reproduction for ...

Run `npm run test` to see the reported issue.

```
src/example.vue:20:26 - error TS18047: '__VLS_ctx.example.foo' is possibly 'null'.
```

## Workaround

- Run `npm i vue-tsc@2.2.4` to downgrade `vue-tsc` to `2.2.4`.
- Run `npm run test` and see the error no longer occurs

```
