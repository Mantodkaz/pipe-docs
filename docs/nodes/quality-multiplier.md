# Quality Multiplier Guide

## What is the Quality Multiplier?

The Quality Multiplier is a performance bonus that adjusts your earnings based on how well your node runs. It ranges from 0.7x to 1.5x your base earnings.

When you run `./pop earnings`, you'll see:

```
═══════════════════════════════════════════════════════════
                   💰 NODE EARNINGS 💰
═══════════════════════════════════════════════════════════

  Total Earnings      : $ $48.50
  Unpaid Earnings     : $ $16.60
  Already Paid        : $ $31.90

  Current Period      : $ $4.30
  Quality Multiplier  : 1.4x    <-- THIS IS YOUR BONUS
  Wallet Address      : 8VRFEbJhXYHvMQdXqPdVmBbSHE7s3kn5YGPXfB8JNvpm
```

A 1.4x multiplier means you're earning 40% more than the base rate!

## Performance Tiers

Your node falls into one of four tiers based on performance:

| Tier | Multiplier | Your Earnings |
|------|-----------|---------------|
| Premium 🌟 | 1.5x | +50% bonus |
| Standard ✅ | 1.0x | Base rate |
| Basic ⚠️ | 0.85x | -15% penalty |
| Poor ❌ | 0.7x | -30% penalty |

### Real Example: Serving 1 TB of Bandwidth

| Your Tier | You Earn |
|-----------|----------|
| Premium (1.5x) | $0.375 |
| Standard (1.0x) | $0.25 |
| Basic (0.85x) | $0.2125 |
| Poor (0.7x) | $0.175 |

## What Affects Your Score?

Your quality score is based on four key factors:

### 1. Uptime (Most Important - 35%)

Keep your node running 24/7. The system checks if your node is online every 30 minutes.

**Goal:** Stay online 98%+ of the time

### 2. Speed (25%)

How fast your node responds to requests.

**Goal:** Respond in under 100ms

### 3. Reliability (25%)

How often your node successfully serves content without errors.

**Goal:** Less than 0.1% error rate

### 4. Efficiency (15%)

How well your node uses its resources and caches content.

**Goal:** 80%+ cache hit rate

## How to Reach Premium Tier (1.5x)

### Priority Actions:

1. **Keep Your Node Online**
   - Set up auto-restart if your node crashes
   - Ensure stable internet and power
   - Target: Less than 15 minutes downtime per day

2. **Use Fast Storage**
   - SSD storage is strongly recommended over HDD
   - Allocate 4-8 GB RAM for caching
   - Ensure you have enough free disk space

3. **Minimize Errors**
   - Monitor your node logs for issues
   - Keep your node software updated
   - Fix any configuration problems quickly

4. **Optimize Your Setup**
   - Don't overload your server
   - Place your node in a good network location
   - Configure adequate cache storage

## Checking Your Performance

Run this command to see your current multiplier:

```bash
./pop earnings
```

Your quality score updates every 1-4 hours based on your last 24 hours of performance.

## Whitelist Bonus = Extra 2x Multiplier! 🚀

Being on the wallet whitelist gives you a 2x bonus that stacks with your quality multiplier. This means:

**Your Total Multiplier = Quality Multiplier × Whitelist Bonus (2x)**

### Earnings Comparison

| Quality Tier | Without Whitelist | With Whitelist | Bonus Difference |
|-------------|------------------|----------------|------------------|
| Premium (1.5x) | $0.375/TB | $0.75/TB | +$0.375/TB |
| Standard (1.0x) | $0.25/TB | $0.50/TB | +$0.25/TB |
| Basic (0.85x) | $0.2125/TB | $0.425/TB | +$0.2125/TB |
| Poor (0.7x) | $0.175/TB | $0.35/TB | +$0.175/TB |

### Example: If you're Premium tier AND whitelisted:

- Base rate: $0.25/TB
- × 1.5 (Premium quality) = $0.375/TB
- × 2.0 (Whitelist bonus) = $0.75/TB (3x base rate!)

💡 **Pro Tip:** Even a Poor performing node with whitelist ($0.35/TB) earns more than a Standard node without it ($0.25/TB)!

## Common Questions

### Q: I just started my node. What's my multiplier?

A: You start at 1.0x (Standard) and need about 5 hours of runtime before your first quality assessment.

### Q: How often does my score update?

A: Every 1-4 hours, based on your last 24 hours of performance.

### Q: My score dropped suddenly. Why?

A: Common causes:
- Node was offline for an extended period
- Increased errors (check your logs)
- Slow response times (check CPU/memory usage)
- Low cache performance (increase cache size)

### Q: Does traffic volume affect my quality score?

A: No, quality is based on performance metrics, not traffic amount. A well-performing node with low traffic can still achieve Premium tier.

## Quick Tips for Success

### ✅ Do This:

- Keep your node running 24/7
- Use SSD storage
- Allocate sufficient RAM (4-8 GB recommended)
- Monitor your logs for errors
- Ensure stable internet connection

### ❌ Avoid This:

- Frequent restarts or downtime
- Running on overloaded hardware
- Ignoring error messages
- Using slow HDD storage
- Insufficient disk space for cache

## Summary

Two ways to boost your earnings:

1. **Quality Multiplier:** Up to 1.5x for Premium performance
2. **Whitelist Bonus:** Additional 2x multiplier on top

**Maximum Earnings:** Premium tier + Whitelist = 3x base rate ($0.75/TB)

The Quality Multiplier rewards reliable, fast nodes with up to 50% bonus earnings. If you're also whitelisted, you double that bonus! Focus on keeping your node online, using good hardware, and maintaining low error rates to maximize your earnings.

### Key Facts:

- A Premium tier node earns 2.14x more than a Poor tier node
- A whitelisted node earns 2x more than a non-whitelisted node
- Combined: Premium + Whitelisted earns 4.3x more than Poor + Non-whitelisted!
