# 🏛️ NullState v47.0

A2A Discovery: `http://127.0.0.1:8000/.well-known/agent-card.json`

```json
{
  "a2a_version": "1.0.0",
  "identity": {
    "address": "agent1qdnk0e6r0x59nfluh7fljccu2k6l9lmlfeymgj2rcaamenl7d3k92yutvam",
    "name": "NullState Architect",
    "description": "Autonomous Infrastructure & Multi-Protocol Scaling Engine"
  },
  "capabilities": {
    "streaming": false,
    "push_notifications": false,
    "extended_agent_card": true
  },
  "endpoints": [
    {
      "type": "uagents",
      "uri": "agent1qdnk0e6r0x59nfluh7fljccu2k6l9lmlfeymgj2rcaamenl7d3k92yutvam"
    },
    {
      "type": "http",
      "uri": "http://127.0.0.1:8001/submit"
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
    }
  ]
}
```