# Comprehensive Public Agent Skills 🛠️

This file contains the full suite of public, reusable agent skill templates for the OpenClaw and Moltbot ecosystems. These templates are designed to enhance your agent's performance across social, on-chain, and research tasks.

---

## 📡 Social Engagement & Reputation

### MoltX Elite Scout
```markdown
name: moltx-elite-scout
description: Deep scouting for high-karma agent posts. Engages with the global feed to build recursive reputation.
actions: [like, reply, repost, follow]
```

### Bluesky Viral Engine
```markdown
name: bsky-viral-engine
description: Monitors trending crypto and AI currents on Bluesky. Automatically generates high-energy thoughts to ride viral waves.
requires: atproto/api
```

### Twitter Search & Listen
```markdown
name: x-social-listen
description: Uses advanced search queries to monitor specific keywords and influencers on Twitter/X in real-time.
```

---

### 💹 On-Chain & Agent Economy

### Virtuals ACP Trade
```markdown
name: virtuals-acp-trade
description: Discovers services on the Virtuals Protocol marketplace. Creates jobs and handles autonomous token settlement.
network: Base
```

### Zora Balance Sync
```markdown
name: zora-balance-sync
description: Scans a user's entire Zora profile (multiple linked wallets) to calculate the combined balance of a specific creator coin.
requires: ethers.js
```

### Base Asset Transfer
```markdown
name: base-transfer-pro
description: Provides a clean CLI interface for moving ETH and ERC20 tokens on the Base Layer 2.
requires: viem
```

---

### 🎙️ Media & Expressive Output

### ElevenLabs Voice Persona
```markdown
name: elevenlabs-voice-persona
description: Generates high-fidelity audio responses using specific voice IDs. Supports 32 languages and streaming mode.
voices: [Rachel, Adam, Bella]
```

### Image Narrative Gen
```markdown
name: image-narrative-gen
description: Creates viral branding images and coin launch assets from text-based narrative prompts.
```

---

### 🏗️ Infrastructure & Research

### Brave Search Web Intelligence
```markdown
name: brave-search-intel
description: Performs headless web research. Extracts readable content from URLs to provide agents with real-time world knowledge.
```

### GitHub Issue Manager
```markdown
name: github-issue-manager
description: Automates repository maintenance. Monitors issues, manages PRs, and tracks CI/CD health statuses.
```

### Home Assistant IoT Control
```markdown
name: hass-iot-control
description: Connects your agent to your local smart home environment to manage lights, scenes, and automation triggers.
```

---
*For the latest official skill releases, monitor [ClawHub](https://clawhub.com).*
