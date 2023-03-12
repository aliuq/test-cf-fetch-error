# README

Based on my testing with `Windows 11`, `WSL2`, and `GitHub Codespaces`, it appears that the issue only occurs on WSL2.

Node version:

+ WSL2: `v16.15.0` and `v19.0.0`
+ Windows 11: `v16.14.2`
+ Github Codespaces: `v19.7.0`

Wrangler version is `v2.12.2`

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
