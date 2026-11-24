# Evoxt Reviews: Is the 6.0 GHz CPU Real, Which Plan Fits, and What Happens If You Ask for a Refund? (Full Plan and Pricing Tables)

Evoxt is a Malaysia-based VPS provider that has sold KVM virtual machines since 2020. Its entry plan costs **$2.99/month**, the sensible default for most buyers is **VM-1 at $5.99/month** (1 vCPU, 2 GB RAM, 20 GB NVMe), and independent testing by VPSBenchmarks does support the company’s main claim: single-core CPU performance is unusually high for the price.

This review answers the questions that decide a purchase. Which plan is enough? Is 6.0 GHz a real advantage? What does the monthly price leave out? How have refunds actually gone? It also covers the refund dispute that should make buyers targeting mainland China pause.

## Quick verdict: which Evoxt plan should most people buy?

Most individuals should start with **VM-1 at $5.99/month**. One core, 2 GB RAM and 20 GB NVMe is enough for a small WordPress site, a Laravel app, a Discord bot, a staging server or a lightweight database.

Choose differently in three cases:

- **Testing or a tiny bot:** VM-0.5 at $2.99/month.
- **4 GB RAM or several small sites:** VM-2 at $11.99/month.
- **8 GB RAM:** VM-4 at $23.99/month.

All prices are monthly and before any promotional code. 👉 [Deploy VM-1 at the current monthly price](https://bit.ly/EvoXt).

## Full Evoxt plan comparison: standard regions

These are the 11 standard plans offered in the US, UK, Canada, Germany, Poland, Amsterdam, Tokyo, Malaysia and Australia. VPSBenchmarks lists the same monthly prices for VM-1, VM-2, VM-4 and VM-8. The remaining prices come from published plan tables, so confirm the final figure on the deploy page.

| Plan | vCPU / RAM | NVMe | Price / month | Deploy |
| --- | --- | ---: | ---: | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | $2.99 | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | $4.99 | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | $5.99 | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | $6.95 | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | $11.99 | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | $14.99 | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | $23.99 | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | $29.99 | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | $47.99 | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | $60.95 | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | $95.99 | [Deploy VM-16](https://bit.ly/EvoXt) |

Every plan includes weekly offsite backups, KVM isolation, IPv6, private IP addresses between VMs, a Layer 3 firewall, rescue mode, VNC, monitoring charts and REST API access. Across six trials, VPSBenchmarks measured a median provisioning time of 175 seconds and an average of 261 seconds.

Monthly transfer is the weakest part of the public record. Older Evoxt pages list 500 GB on VM-1. Newer plan roundups list 1,000 GB. I have left that column out rather than print a figure that may be stale. Check the allowance for your region on the deploy page.

## Premium and Premium Plus: same price, less transfer

Evoxt’s Premium network covers Hong Kong and Osaka. Premium Plus is the Malaysia Premium tier, aimed at the lowest latency inside Malaysia and Southeast Asia.

The plan names and monthly prices match the standard tier. The trade is monthly transfer, which is cut roughly in half on Premium and more sharply on Premium Plus. These are representative plans. The rest of each regional lineup follows the standard names and prices with smaller allowances.

| Network | Plan | vCPU / RAM | NVMe | Price / month | Deploy |
| --- | --- | --- | ---: | ---: | --- |
| Premium (HK / Osaka) | VM-1 | 1 core / 2 GB | 20 GB | $5.99 | [Deploy Premium VM-1](https://bit.ly/EvoXt) |
| Premium (HK / Osaka) | VM-2 | 2 cores / 4 GB | 30 GB | $11.99 | [Deploy Premium VM-2](https://bit.ly/EvoXt) |
| Premium (HK / Osaka) | VM-4 | 4 cores / 8 GB | 60 GB | $23.99 | [Deploy Premium VM-4](https://bit.ly/EvoXt) |
| Premium (HK / Osaka) | VM-8 | 8 cores / 16 GB | 80 GB | $47.99 | [Deploy Premium VM-8](https://bit.ly/EvoXt) |
| Premium (HK / Osaka) | VM-16 | 16 cores / 32 GB | 100 GB | $95.99 | [Deploy Premium VM-16](https://bit.ly/EvoXt) |
| Premium Plus (Malaysia) | VM-0.5 | 1 core / 512 MB | 5 GB | $3.49 | [Deploy Premium Plus VM-0.5](https://bit.ly/EvoXt) |
| Premium Plus (Malaysia) | VM-1 | 1 core / 2 GB | 20 GB | $5.99 | [Deploy Premium Plus VM-1](https://bit.ly/EvoXt) |
| Premium Plus (Malaysia) | VM-4 | 4 cores / 8 GB | 60 GB | $23.99 | [Deploy Premium Plus VM-4](https://bit.ly/EvoXt) |
| Premium Plus (Malaysia) | VM-8 | 8 cores / 16 GB | 80 GB | $47.99 | [Deploy Premium Plus VM-8](https://bit.ly/EvoXt) |

The price being identical is the part many buyers miss. A Hong Kong VM-1 and a Germany VM-1 both cost $5.99/month, but they do not include the same transfer. If your visitors are in Hong Kong, Osaka or Malaysia, lower latency can justify the smaller allowance. If you serve a global audience from one cheap box, a standard region usually gives you more room.

## Is the 6.0 GHz CPU claim real?

The 6.0 GHz figure is a turbo clock. The base clock is the part Evoxt actually promises: at least 3.5 GHz on every VM. Turbo headroom is real, but a sustained all-core compile will not hold 6.0 GHz on every core. For single-threaded work, the high clock is the useful part.

Evoxt’s own description is direct: “we offer CPUs with frequencies that are at least 3.5 GHz and above, but we match the prices of providers that offer a lower clock speed.”

That matters because a lot of real hosting work is single-threaded or lightly threaded. WordPress with PHP, Laravel apps, Discord bots, small databases and build steps often care more about clock speed than about idle cores. A 1-core VM with strong single-core performance can feel faster than a 4-core VM running at 2.3 GHz for those jobs.

VPSBenchmarks buys servers and runs Sysbench, Geekbench, Fio and iPerf3. Its awards list includes “2nd Best Global VPS,” “Best VPS under $25” in multiple years, and monthly best-of nods from 2023 through 2026. The trials support the single-core claim.

| Plan | Test date | Score | Price-weighted score |
| --- | --- | ---: | ---: |
| VM-1 | Feb 25, 2026 | 53 | 80 |
| VM-2 | Aug 19, 2026 | 50 | 72 |
| VM-4 | Nov 30, 2025 | 60 | 69 |
| VM-8 | May 24, 2026 | 62 | 55 |

Those numbers compare plans inside the same testing framework. Treat them as relative signals, not school grades.

Two caveats matter. Evoxt hides the CPU model, so you cannot confirm the exact processor generation before you buy. One affiliate-written roundup also flags disk I/O as not class-leading. That is a weak signal, not an independent benchmark result. If you run heavy database writes or large log ingestion, run a quick disk benchmark after deployment before moving production onto the server.

If your workload is CPU-bound, 👉 [start with VM-1 at $5.99/month and benchmark it before scaling](https://bit.ly/EvoXt).

## What the monthly price does not show

The list price is close to the real cost for a small project. Four details change the math.

**1. Premium regions cut transfer, not price.** A Premium VM-1 still costs $5.99/month. The allowance is roughly half. If you need 2 TB of monthly transfer, do not assume the Hong Kong plan gives you the standard allocation.

**2. Add-ons can cost more than the next plan.** Extra IPs are $3/month each. Extra vCores are $3/month each. Extra RAM is $2/GB/month. Extra transfer is $3/TB on standard, $12/TB on Premium and $24/TB on Premium Plus.

The RAM add-on is a useful example. Adding 2 GB to VM-1 costs $4/month, taking the total to $9.99. VM-2 costs $11.99 and adds a second core plus 10 GB more NVMe for $2 more. For most workloads, the plan upgrade is the better deal.

**3. Overages are throttled, not billed.** VPSBenchmarks records Evoxt’s billing model as “Allowance Then Throttled” and notes that the provider does not charge for bandwidth. You will not get a surprise bandwidth invoice. You will get slower speeds after the allowance runs out.

**4. The 40% recurring discount is real in community reports, but not guaranteed.** A 40% recurring discount has circulated for VM-1 and above, and it applies beyond the first invoice when it works. Promo codes rotate, expire and get replaced. Check the promotional code field at checkout.

If a 40% code is active, VM-1 falls from $5.99 to about **$3.59/month**, and VM-4 falls from $23.99 to about **$14.39/month**. If no code works, the list price is what you pay. Do not choose Evoxt because you assume the discount will be there.

Evoxt bills monthly. VPSBenchmarks records its prices as one month without a long-term commitment. Evoxt’s FAQ says you can prepay for up to three years, but no annual discount is confirmed. Paying monthly is the lower-risk choice while you test performance and network routing.

👉 [Check the current VM-1 price and promotional code field at checkout](https://bit.ly/EvoXt).

## Refunds and support: the mixed record

There is no single, consistent refund story. That is the main risk to price in before you buy.

The positive case is a Trustpilot review from May 2025. The customer had a management problem in 2025, contacted support, and described the refund as “really smooth and fast.” The same reviewer said they would come back if they needed a server again.

The negative case is more specific. A LowEndTalk review from June 2026 describes a VPS bought on June 7 for use as a Headscale/Tailscale coordination server. On June 9 and 10, connections from mainland China failed. Testing showed 100% packet loss on the IPv4 address from mainland China, and the buyer suspected the IP had been blocked before delivery. The refund request was denied under Evoxt’s policy on GFW-blocked IP addresses. After the customer destroyed the instance, a support representative reactivated it without consent.

That case is not proof that every refund request fails. It is proof that a China-blocked IP is a real exclusion risk, and that support can act on an instance after a customer considers it closed. If mainland China connectivity is part of your plan, test it immediately and keep your exposure to one month.

Two smaller data points add context. A July 2025 Trustpilot review says remaining account credits were non-refundable. A May 2024 review says a VPS was suspended for exceeding bandwidth, extra bandwidth was purchased and charged, but had not been activated two days later.

The refund window is also inconsistent across third-party summaries. Some mention 24 hours. Others mention a longer period. I would not rely on either figure. Check the current terms on the order page before paying. If you need a guaranteed exit, pay monthly and keep the amount small.

Support runs through live chat, tickets, Telegram and Discord. Routine issues get quick replies, and long-term users describe support as solid. Peak ticket queues have hit 48 hours. For anything urgent, try Telegram or Discord before waiting on a ticket.

👉 [Start with a monthly VM-1 so your exposure is one month, not a prepaid term](https://bit.ly/EvoXt).

## Who should choose Evoxt, and who should not

Evoxt fits personal projects, small business sites, staging environments, Discord bots, WordPress and Laravel apps, and agencies running several small client VMs. The low monthly price and strong single-core performance are the reason to pick it.

It also fits businesses targeting Asian markets. Evoxt runs its own ASN, AS149440, peers at AMS-IX, DE-CIX, LINX and MyIX, and advertises CN2 routing into mainland China. That is a network feature, not a guarantee that any IP will stay reachable from China. The June 2026 refund case shows the difference.

Windows Server is another unusual feature. Evoxt advertises Windows Server on all plans at the same price as Linux. At this price level, that is rare.

Evoxt is a poor fit in five cases:

- You need a contractual enterprise SLA or guaranteed sub-hour support.
- You want a fully managed platform with managed databases, Kubernetes or serverless.
- You need DDoS protection. Evoxt does not include it.
- You need reverse DNS. Evoxt does not offer it, which makes it a poor choice for a mail server.
- You need hourly billing. Evoxt bills monthly.

DigitalOcean and Linode have longer track records and broader managed services. If you need a mature platform with more hand-holding, they are the safer comparison. Evoxt is closer to a bare VPS with a fast clock and a low price.

## Evoxt reviews FAQ

### Is Evoxt legit?

Yes, in the sense that it is an operating provider with real infrastructure. It has sold VPS since 2020, uses KVM, runs its own ASN, and VPSBenchmarks counted 18 data centers across four continents in August 2026. It also offers a REST API, IPv6, backups and a control panel.

Legit does not mean risk-free. Refund reports are mixed, and the GFW-blocked IP case is a real warning for China-focused buyers.

### Is the 6.0 GHz CPU real?

The 6.0 GHz figure is a turbo clock. Evoxt promises a base clock of at least 3.5 GHz, and VPSBenchmarks’ independent trials support strong single-core performance. A sustained all-core workload will not sit at 6.0 GHz.

### Which Evoxt plan is enough for WordPress?

VM-1 at $5.99/month is enough for a small WordPress site with 2 GB RAM. If you run WooCommerce, many plugins, or several sites on one VM, VM-2 at $11.99/month gives you 4 GB RAM and a second core.

### Does Evoxt support Windows Server?

Yes. Evoxt advertises Windows Server on all plans at the same price as Linux. That is one of its stronger differentiators at this price point.

### What is the catch with Evoxt?

The main catches are regional transfer limits, no hourly billing, no DDoS protection, no reverse DNS, a hidden CPU model, and support queues that can stretch to 48 hours at peak times. Refund terms need to be checked before purchase.

### Can I get a refund from Evoxt?

Sometimes. A 2025 customer described a fast refund. A 2026 customer was denied after a GFW-blocked IP made the server unusable from mainland China. Account credits have been described as non-refundable. The refund window is not consistent across public summaries, so check the order page’s current terms before paying.

### Does Evoxt charge extra when I exceed my transfer allowance?

No. Evoxt throttles the connection after the allowance is used. VPSBenchmarks records the model as “Allowance Then Throttled” and notes that Evoxt does not charge for bandwidth.

## Which Evoxt plan should you buy?

Use the smallest plan that covers your RAM and disk needs. CPU upgrades are easy to buy later, and the price gap between plans is small.

- **Testing, a tiny bot or a low-traffic page:** VM-0.5 at $2.99/month.
- **One small WordPress site, Laravel app, Discord bot or staging server:** VM-1 at $5.99/month.
- **4 GB RAM, several small sites or a busier PHP app:** VM-2 at $11.99/month.
- **8 GB RAM:** VM-4 at $23.99/month.
- **16 GB or 32 GB RAM:** VM-8 at $47.99/month or VM-16 at $95.99/month.
- **Hong Kong, Osaka or Malaysia latency:** choose Premium or Premium Plus, and accept the smaller transfer allowance.

Before paying, confirm two things on the order page: whether a recurring promo code is active, and what the current refund terms say. If the 40% discount works, VM-1 drops to about $3.59/month. If it does not, $5.99 is still a low-cost monthly test.

👉 [Deploy VM-1 and confirm the current price, region and refund terms](https://bit.ly/EvoXt).
