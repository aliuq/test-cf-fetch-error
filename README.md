# README

```bash
[WARNING] Failed to get worker definitions TypeError: fetch failed

      at fetch
  (/apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:16584:17)
      at processTicksAndRejections (node:internal/process/task_queues:96:5)
      at async getRegisteredWorkers
  (/apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:126467:22)
      at async getBoundRegisteredWorkers
  (/apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:126486:29)
  {
    cause: ConnectTimeoutError: Connect Timeout Error
        at onConnectTimeout
  (/apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:7185:29)
        at
  /apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:7141:51
        at Immediate._onImmediate
  (/apps/__temp__/test-cf-fetch-error/node_modules/wrangler/wrangler-dist/cli.js:7173:13)
        at processImmediate (node:internal/timers:466:21) {
      code: 'UND_ERR_CONNECT_TIMEOUT'
    }
  }
```
