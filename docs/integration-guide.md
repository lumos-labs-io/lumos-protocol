```md
# Integration Guide

1. Protect your endpoint: return 402 + bill until paid.
2. Client pays using wallet and Lumos SDK.
3. Backend verifies signature via `getParsedTransaction`.
4. Retry the request with a paid header → 200 OK.
```
