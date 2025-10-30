# x402 — Payment Required (on-chain)

Servers return HTTP 402 with a JSON bill:

```json
{
  "protocol": "x402",
  "chain": "solana",
  "amount": "0.01",
  "memo": "article_42"
}
