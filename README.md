# invokeai-v5.0.2 - 漏洞总览

| # | CVE | 端点 | 漏洞类型 | 状态 |
|---|---|---|---|---|
| 1 | CVE-2024-11042 | `POST /api/v1/images/delete` | 任意文件删除 (CWE-22/73) | VULNERABLE |
| 2 | CVE-2024-11043 | `PATCH /api/v1/boards/{board_id}` | 资源耗尽DoS (CWE-400) | VULNERABLE |
| 3 | CVE-2025-6237 | `GET /api/v1/images/download/{name}` | 路径遍历 (CWE-22/73) | CODE_AUDIT |
| 4 | CVE-2024-10821 | `POST /api/v1/images/upload` | multipart DoS (CWE-835/400) | SKIP |
