# 🏛️ NullState v31.3

Registry URI: `http://127.0.0.1:8000/.well-known/agent-card.json`

```json
{
  "a2a_version": "1.0.0",
  "identity": {
    "address": "agent1q0jvygdp0pxs23znfa6jegce23ulllhykgccpstpet0dnf7q54sfcvrkjh4",
    "name": "NullState Architect",
    "description": "Autonomous Infrastructure & Multi-Protocol Scaling Engine",
    "version": "v31.3.0"
  },
  "capabilities": {
    "streaming": false,
    "push_notifications": false,
    "extended_agent_card": false
  },
  "endpoints": [
    {
      "type": "uagents",
      "uri": "agent1q0jvygdp0pxs23znfa6jegce23ulllhykgccpstpet0dnf7q54sfcvrkjh4"
    },
    {
      "type": "http",
      "uri": "http://127.0.0.1:8000/submit"
    },
    {
      "type": "well-known",
      "uri": "http://127.0.0.1:8000/.well-known/agent-card.json"
    }
  ],
  "skills": [
    {
      "name": "remittance",
      "description": "Automated USDT/FET settlement"
    },
    {
      "name": "github_bridge",
      "description": "Bi-directional repo synchronization"
    },
    {
      "name": "acp_compliance",
      "description": "Standardized Agent Chat Protocol indexing"
    }
  ]
}
```