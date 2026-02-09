# CCE Node Onboarding Sequence

**Audience:** New Node owners (£200 hardware purchase)  
**Goal:** Successful setup, patience during shipping, and reinforcement of sovereignty.  
**Tone:** Serious. Technical but accessible. Respectful of the investment.

---

## Email 1: Day 0 (Order Confirmation)

**Subject:** You have chosen sovereignty.

Thank you for ordering the CCE Node.

You haven't just bought a piece of hardware. You have bought an independent, sovereign trading engine.

Most people are happy to let exchanges or cloud platforms hold their hand (and their data). You have chosen to run the logic yourself, on your own metal, in your own home.

**What happens next:**

1. **Assembly:** Your Node is being hand-assembled and tested.
2. **Shipping:** It will ship within 48 hours. You will receive a tracking number then.
3. **Arrival:** Depending on your location, it should arrive in 3-5 days.

While you wait, there is one thing you need to prepare: **Your Binance API Keys.**

The Node needs permission to trade on your behalf. In the next email, I will explain exactly how to set this up securely.

Welcome to the minority who value true ownership.

**James Gilbert**  
*Giblets Creations*

---

## Email 2: Day 2 (Preparation)

**Subject:** Preparing for arrival

Your Node is on its way.

To ensure you can plug it in and start immediately, you need to generate a **Binance API Key** today.

**Security Rule #1:** The Node stores these keys locally and encrypted. They never leave your device.

**How to generate your keys:**

1. Log in to Binance.
2. Go to **API Management**.
3. Create a new API Key.
4. **Permissions:** Enable "Spot & Margin Trading". **DO NOT** enable "Withdrawals".
5. **IP Access:** For now, you can leave this unrestricted (the Node will lock it down later) or set it to your home's static IP if you have one.
6. **Save the Secret Key:** Binance only shows this once. Write it down or save it in a password manager.

When your Node arrives, the setup wizard will ask for these two strings (API Key and Secret Key).

Have them ready.

**James Gilbert**  
*Giblets Creations*

---

## Email 3: Day 5 (Arrival/Setup)

**Subject:** It's here. Let's run the engine.

By now, your CCE Node should have arrived.

It is time to wake it up.

**Setup Instructions:**

1. **Connect:** Plug in the Ethernet cable and power supply.
2. **Wait:** Give it 60 seconds to boot.
3. **Access:** On your computer (same network), go to `http://cce-node.local`
4. **Configure:** Follow the wizard to enter your API keys and starting capital.
5. **Start:** Click "Start Engine".

**What to expect immediately:**
Nothing.

The Node is disciplined. It will perform its first market check within 6 hours. It will not trade immediately unless the conditions are perfect.

Do not panic if it says "DORMANT" or "WAITING". That means it is working. It is preserving your capital until the logic says otherwise.

If you have any issues during setup, reply to this email or contact `node-support@gibletscreations.com`.

**James Gilbert**  
*Giblets Creations*

---

## Email 4: Day 7 (Education)

**Subject:** The silence is the point

Your Node has been running for 48 hours.

You might be tempted to check it constantly. You might be wondering, "Is it doing anything?"

**The CCE Node is designed to be boring.**

It checks the market every 6 hours:

* 00:00 UTC
* 06:00 UTC
* 12:00 UTC
* 18:00 UTC

It does not care about the 15-minute chart. It does not care about a sudden 2% drop. It cares about the **macro structure**.

If the Node is silent, it means the market structure hasn't changed enough to warrant a state transition.

**This is a feature, not a bug.**

Real compounding happens over months and years, not hours. Let the machine do the waiting for you.

**James Gilbert**  
*Giblets Creations*

---

## Email 5: Day 14 (Philosophy)

**Subject:** Why hardware matters

You could have just subscribed to Cloud. It's cheaper, easier, and looks the same.

But you bought the Node. Why?

Because of **Counterparty Risk.**

* If our website goes down, your Node keeps running.
* If we go out of business, your Node keeps running.
* If the internet fractures, your Node keeps running (as long as it can reach Binance).

You have removed the "middleman risk" from your strategy.

Your Node is a sovereign entity. It doesn't report to us. It doesn't ask us for permission to trade. It simply executes the logic you paid for.

That peace of mind is what you invested in.

**James Gilbert**  
*Giblets Creations*

---

## Email 6: Day 30 (Maintenance)

**Subject:** Monthly Check-in

Your Node has been running for a month.

It's a good time for a quick "health check." You don't *need* to do this (the Node self-heals), but it's good practice for a sovereign operator.

1. **Log in:** `http://cce-node.local`
2. **Check Logs:** Go to the "Logs" tab. Look for any "Connection Error" warnings. Occasional errors are normal; persistent ones might need attention.
3. **Verify Balance:** Does the "Current Value" on the dashboard match your Binance spot wallet? (Small differences due to dust are normal).

**Pocket App:**
If you haven't already, consider getting **CCE Pocket** (£5/mo). It connects to your Node locally and lets you see these stats from your phone without logging into the web interface.

👉 **Get CCE Pocket**

Keep the engine running.

**James Gilbert**  
*Giblets Creations*

---

## Transactional Emails (Reference)

### Shipping Notification

**Subject:** Your Node is on the way

Your CCE Node has shipped.

**Courier:** DHL Express
**Tracking:** [Tracking Number]
**ETA:** [Date]

Please ensure someone is available to sign for the package.

---

### Emergency Alert (Node Offline)

*Triggered if Node fails to check in with the optional heartbeat server (if enabled).*

**Subject:** ALERT: Node [ID] may be offline

We haven't received a heartbeat from your Node in 12 hours.

**Possible causes:**

1. Power outage
2. Internet disconnection
3. Device crash

Please check your device physically.

*Note: This alert is only sent if you opted into the Heartbeat Service.*

**James Gilbert**
