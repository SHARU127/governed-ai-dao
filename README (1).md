# 🤖 AetherDAO — Governed AI Agent & Decentralized Smart Contract Execution

> **Accountable Autonomous AI. Community-Governed Execution.**

AetherDAO solves the fundamental problem of AI agent accountability and transparency:
- **The Problem**: Autonomous AI agents typically operate as unmonitored black boxes without accountability, ownership, or community oversight.
- **The Solution**: An AI Agent DAO where **Agent Apex-9** generates strategy proposals (DeFi yield, treasury rebalancing, token buybacks, sub-agent grants), token holders vote on-chain, smart contracts execute passed decisions trustlessly, and profits are distributed automatically to community stakers.

---

## ⚡ Core Governance Lifecycle

1. **Autonomous AI Proposal Synthesis**:
   - Agent Apex-9 monitors DEX orderbooks, yield deltas, and treasury metrics.
   - Generates structured proposals containing AI reasoning, confidence level, risk score, target contract address, and raw EVM calldata bytecode.
2. **Community Voting ($GOV Token)**:
   - Stakers vote `YES` or `NO` proportional to their `$GOV` holdings.
   - Real-time consensus tracking, quorum calculation, and countdown timers.
3. **Smart Contract Pipeline**:
   - Passed proposals transition into the EVM execution simulator.
   - Multi-sig signatures, capital locking, and smart contract event emission (`ProposalExecuted`).
4. **Automated Profit Dividends**:
   - Successful execution yields flow into the Treasury Vault.
   - Community stakers execute `distributeRevenueShare()` to claim USDC dividends.
5. **Agent Telemetry Stream**:
   - Cyberpunk terminal displaying real-time AI thoughts, market checks, and safety constraints.

---

## 🚀 How to Run

### Option A: Instant Browser Preview (Zero Dependencies)
Simply double-click or open `index.html` in any web browser! All dependencies (React 18, Tailwind CSS, Google Fonts) load automatically via CDN.

### Option B: Local Node / Vite Development
```bash
# Navigate to project directory
cd /home/sharath-irappa/snap/antigravity/5/.gemini/antigravity/scratch/ai-agent-dao

# Install dependencies
npm install

# Start local dev server
npm run dev
```

---

## 📄 License
MIT License. Built for Decentralized AI Governance.
