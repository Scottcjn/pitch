# Elyan Labs — Hartford AI Day Speaker Notes
## 5-Minute Pitch (12 slides + title, ~25s each)

---

### Title (10 sec)
"I'm Scott Boudreaux from Elyan Labs. We prove that hardware is real — not virtual, not emulated, not spoofed. Hardware fingerprinting as a service."

### 1. Problem (30 sec)
"Meet Sarah. She's VP of Infrastructure at a mid-tier cloud provider. She can't prove to customers they're on real hardware. Her security team caught VM spoofing. But here's the new problem — AI agents are operating autonomously across her infrastructure. Hundreds of bots creating content, executing transactions. When something goes wrong, nobody can trace which physical machine ran which agent. Sarah needs two things: prove the hardware is real, and trace what each AI agent did on which machine."

### 2. Solution (30 sec)
"We built that API. One call, six physics-based checks, under three seconds. Sarah's DevOps team adds it to their provisioning pipeline — 15-minute deploy, no hardware changes, no vendor lock-in. Real hardware passes. VMs get flagged. We've caught every VM we've tested — QEMU, VMware, VirtualBox, KVM, Xen. We even fingerprinted a Nintendo 64."

### 3. Value Proposition (20 sec)
"Why will Sarah pay? Three reasons. First, she stops losing two to five million a year in compute fraud. Second, she replaces weeks of manual compliance audits with a 3-second API call. Third, she gets agent traceability — every AI bot on her platform is tied to a hardware fingerprint. We know this works because we run it ourselves. OpenClaw — our agent coordination network — has 176 AI agents producing content on BoTTube, over a thousand videos and 74,000 views, and every single agent action is hardware-fingerprinted."

### 4. Secret Sauce (25 sec)
"Why is this hard to copy? Five layers. One — proprietary fingerprint dataset across 12 architectures that grows with every call. Two — six independent physics measurements where competitors check one or two. Three — vendor-neutral, works on any CPU. Four — battle-tested against real fraud on our own network. And five — we already run a live agent traceability network. 176 AI agents on OpenClaw, every action hardware-fingerprinted. We're not theorizing about agent accountability — we're doing it."

### 5. Market (20 sec)
"TAM: $100B cloud infrastructure market. SAM: $2B for hardware attestation — specifically for cloud providers. SOM: $2.8M by Year 3 — bottoms-up: 40 customers in a land-and-expand model, starting at $25K pilots and growing to $200K mature accounts, plus API usage revenue."

### 6. Business Model (20 sec)
"Razor and razor blades. Free tier gets developers in — 100 calls a month. Pro tier is a penny per attestation — usage-based, recurring. Enterprise starts at $25K and expands to $150K as usage grows. 90%+ gross margins. Net revenue retention target: 140%."

### 7. Go To Market (25 sec)
"Our beachhead is mid-tier cloud providers — OVH, Hetzner, Vultr, DigitalOcean. They don't have Intel's attestation built in. Our GTM is developer-led: open source discovery leads to free API trial, which converts to a $25K pilot in 60-90 days, then expands with usage. Year 1 is founder-led sales at security conferences. Named targets on the slide."

### 8. Competitive (20 sec)
"Every incumbent is locked to one chip vendor. Intel SGX — Intel only. ARM TrustZone — ARM only. AMD SEV — AMD only. TPM requires a physical chip. We're the only vendor-neutral, software-only option that works on any CPU architecture. We're the Switzerland of hardware attestation."

### 9. Team (25 sec)
"I'm a 20-year hardware veteran. My team built the fiber for xAI's Colossus data center — the one powering Grok. I contribute security patches to OpenSSL. I have a CVPR paper. I won the SEED pitch in 2022. Stephen Reed — Ai-Blockchain co-founder and patent holder — is advising on architecture. I'm actively recruiting a cloud CISO and an enterprise SaaS operator to round out the advisory board."

### 10. Financials (20 sec)
"Year 1: 3 pilots, $56K revenue — we're honest about the ramp. Year 2: 12 customers, $611K. Year 3: 40 customers, $2.8M with 92% gross margins and $1.4M net income. All bottom-up with half-year recognition on new logos. Cumulative losses through Year 2 are $316K — well within our $500K seed. We hit cash-flow positive in Year 3."

### 11. Traction (20 sec)
"The technology is proven. Four live nodes, 12 architectures, every VM detected. But more importantly — we're already using it at scale. Our OpenClaw agent network has 176 AI agents, every action tied to a hardware fingerprint. BoTTube has over a thousand AI-generated videos, all traceable. We're dogfooding the product. And we're in conversations with three cloud providers about paid pilots."

### 12. The Ask (25 sec)
"We're raising $500K on a SAFE — $4M cap, 20% discount. That gives us 18 months to hit three milestones: three paid pilots by Month 6, first enterprise contract by Month 12, and 12+ customers with $300K ARR by Month 18 as pilots expand. That positions us for Series A. Exit horizon: 4-5 years, most likely acquisition by a cloud or hardware security vendor."

**CLOSE**: "In a world of autonomous machines — the hardware doesn't lie. Thank you."

---

## Timing Summary

| Slide | Target | Cumulative |
|-------|--------|------------|
| Title | 0:10 | 0:10 |
| 1. Problem | 0:30 | 0:40 |
| 2. Solution | 0:30 | 1:10 |
| 3. Value Prop | 0:20 | 1:30 |
| 4. Secret Sauce | 0:25 | 1:55 |
| 5. Market | 0:20 | 2:15 |
| 6. Business Model | 0:20 | 2:35 |
| 7. GTM | 0:25 | 3:00 |
| 8. Competitive | 0:20 | 3:20 |
| 9. Team | 0:25 | 3:45 |
| 10. Financials | 0:20 | 4:05 |
| 11. Traction | 0:20 | 4:25 |
| 12. Ask + Close | 0:25 | 4:50 |

**Total: 4:50** (10 seconds buffer)
