
# CCE Node

**Your Personal Trading Engine. Sovereign. Local. Deterministic.**

CCE Node is the real engine — a dedicated hardware device that runs the Cascade Compounding Engine locally, privately, and autonomously.

**Node is the execution layer of the ecosystem.**

---

## Features

- **Executes the full CCE strategy** — All seven states, complete logic
- **Runs the state machine locally** — No cloud dependency
- **Trades automatically** — Based on deterministic rules
- **24/7 operation** — Runs on your hardware, your network
- **Private API keys** — Never leave your device
- **Conservative behaviour** — Rules-based, no leverage, no prediction
- **Long-term compounding** — Discipline over years, not days
- **Full logging** — Every decision recorded locally

---

## What CCE Node Does NOT Do

- Does not rely on external servers
- Does not send your data anywhere
- Does not require trust in a third party
- Does not expose your keys
- Does not promise guaranteed returns

**Node is sovereign execution.**

---

## Why CCE Node Exists

**Because sovereignty matters.**

Cloud shows you the logic.  
**Node runs the logic.**

Node is the heart of the ecosystem — the part that actually compounds.

In a world where:

- Exchanges get hacked
- Platforms freeze withdrawals
- Algorithms change without warning
- Terms of service betray users

**Node is different.**

Your hardware.  
Your keys.  
Your rules.  
Your sovereignty.

---

## Who CCE Node Is For

- People who want **sovereignty**
- People who want **real execution**
- People who want **their own hardware**
- People who want a **plug-and-forget engine**
- People who value **privacy** over convenience
- People who think in **years**, not days

---

## Hardware Specifications

### What You Get

CCE Node ships as a complete, ready-to-run system:

**Hardware:**

- Raspberry Pi 5 (8GB RAM)
- 128GB NVMe SSD (Kingston)
- Official Pi 5 Active Cooler
- Official Pi 5 Power Supply (27W USB-C)
- Custom 3D-printed case (designed by Giblets Creations)
- Pre-installed and configured OS

**Software:**

- Debian 12 (Bookworm) 64-bit
- Python 3.11
- CCE Engine (production build)
- Auto-update system
- Systemd service configuration
- Log rotation and management

**Network:**

- Ethernet port (1 Gbps)
- WiFi 6 (802.11ax)
- Bluetooth 5.0

**Power:**

- 5V 5A via USB-C
- Average draw: 8-12W
- Peak draw: 20W (during trades)
- Annual electricity cost: ~£15-20 (UK average)

---

## Setup Process

### 1. Unbox and Connect

```
1. Remove Node from packaging
2. Connect Ethernet cable (or configure WiFi)
3. Plug in power supply
4. Wait 60 seconds for boot
```

### 2. Access Setup Interface

```
1. Open browser on same network
2. Navigate to http://cce-node.local
3. Follow setup wizard
```

### 3. Configure Exchange

```
1. Create Binance API key (read + trade permissions)
2. Whitelist Node IP address
3. Enter API credentials into setup wizard
4. Verify connection (test API call)
```

### 4. Set Initial Parameters

```
Starting Capital: [Your choice]
Risk Level: Conservative (default)
State Override: None (recommended)
Notification Email: [Optional]
```

### 5. Activate Engine

```
Press "Start Engine"
Node begins monitoring market
First check occurs within 6 hours
```

**Total setup time: 10-15 minutes**

---

## How It Works

### State Machine

CCE Node runs the full seven-state machine:

1. **DORMANT** — Waiting in USDT during extreme fear
2. **ANCHOR** — First BTC position (33% capital)
3. **IGNITION** — Market shows recovery (67% BTC)
4. **CASCADE_1** — Bull confirmed (100% BTC)
5. **CASCADE_2** — Momentum strong (100% BTC, tracking ATH)
6. **SPILLWAY** — Momentum weakening (exits triggered)
7. **EXTRACTION** — Bear confirmed (return to USDT)

Each state has strict entry/exit conditions.  
No emotion. No prediction. Pure logic.

### Check Schedule

Node checks market conditions every **6 hours**:

- 00:00 UTC
- 06:00 UTC
- 12:00 UTC
- 18:00 UTC

At each check:

1. Fetch current BTC price
2. Fetch Fear & Greed Index
3. Calculate trend indicators
4. Evaluate state transition rules
5. Execute trade if conditions met
6. Log decision and reasoning
7. Sleep until next check

### Trade Execution

When a state transition occurs:

```
1. Calculate target position
2. Determine order size
3. Place market order (Binance)
4. Verify execution
5. Update internal state
6. Log transaction
7. (Optional) Send notification
```

Trades are **market orders** for reliability.  
Slippage is typically <0.1% on BTC/USDT.

### Logging

Every action is logged locally:

```
/var/log/cce/
├── state_transitions.log
├── market_checks.log
├── trades.log
├── errors.log
└── performance.log
```

Logs rotate daily and are kept for 90 days.

---

## Performance Expectations

### Historical Backtest (2013-2024)

**Total Return:** +18,639%  
**Alpha vs BTC Buy-and-Hold:** +3,320%  
**Max Drawdown:** -34% (2018 bear)  
**Win Rate:** 73% (winning cycles)  
**Average Cycle Duration:** 187 days

### Conservative Forward Estimates

Node is designed for **long-term compounding**, not short-term gains.

**Realistic Annual Returns:**

- Bear market: -10% to +20%
- Sideways market: +15% to +40%
- Bull market: +50% to +200%

**Key Point:** Past performance ≠ future results.  
The CCE is a **discipline system**, not a crystal ball.

---

## Maintenance

### Required: None

Node is designed to run autonomously.

**You do not need to:**

- Update software (auto-updates weekly)
- Monitor the dashboard (optional)
- Restart the device (self-healing)
- Adjust parameters (set-and-forget)

### Recommended: Quarterly Check

Every 3 months:

1. Log into dashboard
2. Review performance
3. Verify logs are healthy
4. Check for any error alerts
5. (Optional) Withdraw profits to cold storage

**Time required: 5-10 minutes**

### Optional: Daily Monitoring

If you want to watch the engine:

- Access dashboard at `http://cce-node.local`
- View current state
- See recent trades
- Review performance charts

**But you don't have to.**  
Node is built to be ignored.

---

## Security

### API Key Safety

Your Binance API keys **never leave Node**.

- Stored in encrypted SQLite database
- Encrypted at rest using Fernet (symmetric encryption)
- Decrypted only in memory during API calls
- Never logged, never transmitted

### Network Security

Node runs a minimal attack surface:

- SSH disabled by default
- Firewall enabled (UFW)
- Only port 80 open (local web interface)
- No incoming connections from internet
- No cloud sync, no telemetry

### Physical Security

**Your responsibility:**

- Keep Node on your private network
- Don't expose to public WiFi
- Consider VPN for remote access
- Secure physical access to device

### Software Updates

Updates are **automatic but user-controlled**:

- New versions released monthly
- Downloaded in background
- Applied during maintenance window (04:00 UTC)
- Rollback available if issues occur
- Critical patches applied immediately

You can disable auto-updates in settings.

---

## Pricing

### £200 one-time

**Hardware + Software. One price. Forever yours.**

### What's Included

- Complete hardware system
- Lifetime software license
- Free updates forever
- Email support (first year)
- Access to Node Discord channel

### What's NOT Included

- Binance trading fees (~0.1% per trade)
- Electricity costs (~£15-20/year)
- Network/internet connection
- Extended support (£50/year after first year)

### ROI Estimate

**Scenario:** £5,000 starting capital, 30% annual return (conservative)

```
Year 1: £1,500 gain - £200 Node cost = £1,300 net profit
ROI: 650% on Node investment
Payback period: ~49 days
```

**Scenario:** £10,000 starting capital, 50% annual return (moderate bull)

```
Year 1: £5,000 gain - £200 Node cost = £4,800 net profit
ROI: 2,400% on Node investment
Payback period: ~15 days
```

Node pays for itself **fast** if the engine performs.

---

## Support

### Included Support (First Year)

**Email:** `node-support@gibletscreations.com`  
**Response time:** <48 hours (weekdays)

**Covered issues:**

- Hardware failures
- Software bugs
- Setup assistance
- Configuration questions

**NOT covered:**

- Trading strategy questions ("Why didn't it buy?")
- Exchange account issues
- Network/internet problems
- User error (deleted logs, changed config, etc.)

### Extended Support (After Year 1)

**£50/year**

Same coverage as included support.  
Optional — Node will keep running without it.

### Community Support (Free, Forever)

**Discord:** `discord.gg/cce-node`  
**Forum:** `forum.cce.gibletscreations.com`

Ask questions, share results, learn from other Node operators.

---

## FAQ

### Q: Do I need to leave Node running 24/7?

**A:** Yes.  

Node checks market conditions every 6 hours.  
If it's offline during a critical transition, you could miss an optimal entry/exit.

**Power consumption is minimal** (~8-12W average).  
Annual electricity cost: £15-20.

---

### Q: What if my internet goes down?

**A:** Node will resume when connection is restored.  

The engine is designed to handle network interruptions:

- Missed checks are logged
- Next check proceeds normally
- State transitions still occur based on next available data

**You won't lose money**, but you might miss an optimal trade timing.

---

### Q: Can I run multiple Nodes?

**A:** Yes, but why?  

Each Node is designed for one portfolio.  
If you want to run multiple strategies or test different parameters, you'd need multiple Nodes.

**Most users only need one.**

---

### Q: What if Node breaks?

**A:** Hardware warranty: 1 year (replace/repair).  

If hardware fails:

1. Email `node-support@gibletscreations.com`
2. We send replacement Node
3. You transfer SD card to new device
4. Engine resumes from last state

**Your data and state are preserved.**

---

### Q: Can I modify the strategy?

**A:** No.  

Node runs the CCE strategy only.  
The code is proprietary and not user-modifiable.

**If you want custom strategies**, you're looking for a different product.  
Node is a **sovereign execution device** for the CCE philosophy.

---

### Q: What exchanges does Node support?

**A:** Binance only (for now).  

**Roadmap:**

- Q3 2026: Coinbase Pro
- Q4 2026: Kraken
- 2027: OKX, Bybit

Binance was chosen because:

- Highest liquidity (lowest slippage)
- Reliable API
- Global availability
- 0.1% trading fees

---

### Q: Can I use Node in [my country]?

**A:** If Binance operates there, yes.  

Node itself is hardware — no geographic restrictions.  
**Your ability to use Node depends on Binance availability in your jurisdiction.**

Check Binance's list of supported countries.

---

### Q: What if Binance shuts down?

**A:** Node includes emergency shutdown.  

If Binance API becomes unavailable:

1. Node detects connection failure
2. Attempts graceful exit (sell all BTC → USDT)
3. Enters HALT state
4. Sends alert email
5. Waits for manual intervention

**You won't be left holding the bag.**

---

### Q: Do you offer refunds?

**A:** 30-day money-back guarantee.  

If Node doesn't meet expectations:

1. Email `node-support@gibletscreations.com` within 30 days
2. Return Node in original condition
3. Receive full refund (minus return shipping)

**No questions asked.**

---

### Q: Can I upgrade Node later?

**A:** Hardware: no. Software: yes.  

The Pi 5 is powerful enough for CCE.  
Upgrades aren't necessary.

**Software updates are free forever.**

---

### Q: How is Node different from running CCE myself?

**A:** Node is **plug-and-forget**.  

You could:

- Buy a Pi yourself (£80)
- Install Linux (30 min)
- Configure network (15 min)
- Install dependencies (20 min)
- Clone CCE repo (5 min)
- Configure API keys (10 min)
- Set up systemd service (15 min)
- Debug issues (2-6 hours)

**Or buy Node and skip all that.**

Node is for people who value their time.

---

## Roadmap

### Phase 1 (Current)

- ✅ Raspberry Pi 5 hardware
- ✅ Binance integration
- ✅ Seven-state machine
- ✅ Auto-update system
- ✅ Local web dashboard

### Phase 2 (Q2 2026)

- ⏳ Coinbase Pro support
- ⏳ Email notifications
- ⏳ SMS alerts (Twilio integration)
- ⏳ Performance export (CSV)

### Phase 3 (Q3 2026)

- ⏳ Multi-exchange portfolio (split capital)
- ⏳ Advanced dashboard (Cloud integration)
- ⏳ Remote access via VPN
- ⏳ Mobile app integration (Pocket)

### Phase 4 (2027)

- ⏳ Multi-currency support (ETH, SOL)
- ⏳ Cluster mode (multiple Nodes, one dashboard)
- ⏳ API access for developers
- ⏳ Custom state parameters (advanced users)

---

## Technical Specifications

### Software Stack

**Core Engine:**

- Python 3.11
- SQLite (state/logs)
- CCXT (exchange abstraction)
- APScheduler (cron)

**Web Dashboard:**

- Flask (backend)
- Jinja2 (templates)
- TailwindCSS (styling)
- Chart.js (performance graphs)

**System:**

- Systemd (service management)
- Logrotate (log management)
- UFW (firewall)
- Unattended-upgrades (OS patches)

### File Structure

```
/opt/cce/
├── engine/
│   ├── state_machine.py
│   ├── exchange.py
│   ├── indicators.py
│   └── config.yaml
├── dashboard/
│   ├── app.py
│   ├── templates/
│   └── static/
├── logs/
│   ├── state_transitions.log
│   ├── trades.log
│   └── errors.log
└── data/
    ├── state.db
    └── keys.db.encrypted
```

### Resource Usage

**Idle:**

- CPU: 2-5%
- RAM: 180-220 MB
- Disk I/O: <1 MB/hour

**During Check:**

- CPU: 15-25%
- RAM: 250-300 MB
- Network: 2-5 KB

**During Trade:**

- CPU: 30-40%
- RAM: 300-350 MB
- Network: 10-20 KB

---

## Warranty & Returns

### Hardware Warranty

**1 year** from date of purchase.

Covers:

- Manufacturing defects
- Component failures
- Power supply issues

Does NOT cover:

- Physical damage (drops, water, etc.)
- User modifications
- Lightning/power surge damage

### Software Warranty

**Lifetime** updates and bug fixes.

If a bug causes financial loss:

- We fix the bug immediately
- We investigate the incident
- We document the failure mode
- **We do NOT compensate losses** (trading involves risk)

### Return Policy

**30 days** from delivery.

Process:

1. Email request
2. Receive RMA number
3. Return Node (original packaging preferred)
4. Refund issued within 5 business days

**Return shipping cost:** Your responsibility

---

## Legal Disclaimer

**CCE Node is a tool, not financial advice.**

### Risk Warning

Cryptocurrency trading involves substantial risk of loss.

- Past performance ≠ future results
- Market conditions change
- Exchanges can fail
- Regulations can shift
- Technology can break

**You are responsible for:**

- Understanding the risks
- Securing your API keys
- Monitoring your portfolio
- Complying with local tax laws
- Making your own trading decisions

### No Guarantees

We make **zero promises** about:

- Future returns
- Uptime (99% target, not guaranteed)
- Exchange availability
- Regulatory compliance in your jurisdiction

**Use Node at your own risk.**

### Intellectual Property

The CCE strategy, state machine logic, and software are **proprietary**.

You may:

- Use Node for personal trading
- Monitor and analyse its behaviour

You may NOT:

- Reverse-engineer the software
- Extract or copy the strategy
- Resell or redistribute Node
- Claim the CCE methodology as your own

**Violation results in license termination.**

---

## Philosophy

CCE Node exists because **execution should be sovereign**.

In a world where:

- Platforms control your access
- Algorithms change without notice
- Terms of service trap users
- "Not your keys, not your coins" is gospel

**Node is different.**

Your hardware.  
Your keys.  
Your strategy.  
Your sovereignty.

Cloud shows you the engine.  
**Node IS the engine.**

---

## The CCE Ecosystem

### Cloud

Access anywhere. Observe everything.  
**£12/month**

### Node (you are here)

Sovereign execution. Your hardware.  
**£200 one-time**

### Pocket

Awareness. Clarity. Calm.  
**£5/month**

---

## Get Started

**Ready to run your own engine?**

👉 [Order Node at node.cce.gibletscreations.com](https://node.cce.gibletscreations.com)

**Limited to 50 units per month** (hand-assembled, quality-controlled).

---

## License

CCE Node software is proprietary.  
© 2026 Giblets Creations. All rights reserved.

Hardware is yours.  
Software is licensed (lifetime, non-transferable).

---

## Credits

**Built by:** James Gilbert (JamesTheGiblet)  
**Company:** Giblets Creations  
**Philosophy:** Sovereign. Deterministic. Disciplined.

---

**Cloud is proof.**  
**Node is execution.**  
**Pocket is presence.**

Welcome to sovereignty.
