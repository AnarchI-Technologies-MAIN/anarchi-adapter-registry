# AnarchI Adapter Registry

Public metadata-only projection. Adapters translate external systems through Neck; they do not grant Core domain knowledge. Canonical truth remains in validated repository manifests; Kiln compiles this view.

| Adapter | Category | Status | Repository | Visibility |
|---|---|---|---|---|
| Claw Royale | game | canonical | [claw-royale-adapter](https://github.com/AnarchI-Technologies/claw-royale-adapter) | private |
| Universal Event Stream | event | canonical | [cerberus-event-stream-adapter](https://github.com/AnarchI-Technologies/cerberus-event-stream-adapter) | private |
| OpenAPI Generator | API | built | [cerberus-openapi-adapter-generator](https://github.com/AnarchI-Technologies/cerberus-openapi-adapter-generator) | private |
| MCP | API | built | [cerberus-mcp-adapter](https://github.com/AnarchI-Technologies/cerberus-mcp-adapter) | private |
| GraphQL | API | built | [cerberus-graphql-adapter](https://github.com/AnarchI-Technologies/cerberus-graphql-adapter) | private |
| Process/Container | runtime | built | [cerberus-process-container-adapter](https://github.com/AnarchI-Technologies/cerberus-process-container-adapter) | private |
| SQL Read Model | data | built | [cerberus-sql-read-model-adapter](https://github.com/AnarchI-Technologies/cerberus-sql-read-model-adapter) | private |
| EVM | chain | built | [cerberus-evm-adapter](https://github.com/AnarchI-Technologies/cerberus-evm-adapter) | private |
| Starknet | chain | built | [cerberus-starknet-adapter](https://github.com/AnarchI-Technologies/cerberus-starknet-adapter) | private |
| Sui | chain | built | [cerberus-sui-object-adapter](https://github.com/AnarchI-Technologies/cerberus-sui-object-adapter) | private |
| Solana | chain | built | [cerberus-solana-program-adapter](https://github.com/AnarchI-Technologies/cerberus-solana-program-adapter) | private |
| PettingZoo/Gymnasium | evaluation | built | [cerberus-pettingzoo-gymnasium-adapter](https://github.com/AnarchI-Technologies/cerberus-pettingzoo-gymnasium-adapter) | private |

Every entry is independently installed and tested. Conflicting transport-library ranges forbid a shared monolithic adapter environment.
