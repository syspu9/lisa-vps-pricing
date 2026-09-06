# LisaHost pricing: A full breakdown of VPS plans, residential IPs, and premium routes for cross-border work

If you've been shopping for a VPS lately and ended up typing "LisaHost pricing" into a search box, you're probably trying to answer one specific question: is this Hong Kong-based provider actually worth the money, or is it just another budget host with a slick landing page? Fair question. LisaHost has been around since 2017, and they've built a reputation in a particular niche — clean IPs and premium Asia-Pacific routing — but their pricing page is dense, the product list is long, and most of the marketing copy is in Chinese. This guide walks through what each plan actually costs, what you get, and which one makes sense depending on what you're trying to do.

## What LisaHost actually charges for

Before getting into specific numbers, it helps to understand that LisaHost isn't a general-purpose cloud provider like Vultr or DigitalOcean. Their whole pitch is built around two things that most budget hosts treat as afterthoughts:

- **IP quality**: They sell native IPs and dual-ISP residential IPs that look like genuine home internet connections rather than datacenter addresses. This matters if you're running TikTok accounts, doing cross-border e-commerce, or accessing region-locked streaming — platforms that flag datacenter IPs will often leave residential IPs alone.
- **Premium routing to and from China**: Their network uses CN2 GIA (China Telecom's premium route), AS9929 (China Unicom's premium backbone), and CMI (China Mobile International) — the "express lanes" that deliver lower latency and better stability than generic BGP routing.

So when you're looking at LisaHost pricing, you're not just paying for CPU and RAM. You're paying for the IP attribution and the route quality. That's why a 1-core/1GB plan here might cost more than a 4-core/8GB plan from a North American budget provider — different value proposition entirely.

## LisaHost pricing at a glance: the main product lines

LisaHost runs over two dozen product categories, but most buyers end up in one of these core lines. Here's the current pricing across the main options, with USD approximations based on roughly 1 USD ≈ 7 CNY.

| Product line | Location | Entry price (monthly) | What stands out |
| --- | --- | --- | --- |
| US CN2 GIA Premium | Los Angeles | ¥35 (~$5) | Cheapest premium-route option |
| US CERA CN2 High-Defense | Los Angeles | ¥40 (~$5.70) | Adds 50G DDoS protection |
| US 9929 Dual-ISP Residential | Los Angeles | ¥68 (~$9.70) | Genuine residential IP |
| Hong Kong CMI/CU2/CN2 | Hong Kong | ¥88 (~$12.60) | Sub-50ms to mainland China |
| Singapore Native IP | Singapore | ¥68 (~$9.70) | High bandwidth (300Mbps+) |
| Japan Native IP | Tokyo | ¥88 (~$12.60) | 300Mbps+ bandwidth, generous traffic |
| Annual promo VPS | Various | from ¥16/month | Best value for long-term users |

Prices above are the current promotional rates shown on the official cart pages. Most plans are labeled "限时特价" (limited-time special pricing), which means the regular price is higher — but the promo has been running long enough that it functions as the de facto current price.

## Full plan comparison: US CN2 GIA Premium Network

This is LisaHost's flagship line for anyone who needs premium routing into China without paying residential-IP prices. All plans use KVM virtualization, NVMe SSD storage, and include a dedicated IPv4 address.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Trial | 1 core | 1 GB | 10 GB SSD | — | 1 GB | ¥2/day | [ Get the trial](https://bit.ly/LiSaHost) |
| Basic | 1 core | 1 GB | 20 GB SSD | 10 Mbps | 500 GB | ¥35 | [ Order Basic](https://bit.ly/LiSaHost) |
| Standard | 2 cores | 2 GB | 40 GB SSD | 20 Mbps | 1 TB | ¥60 | [ Order Standard](https://bit.ly/LiSaHost) |
| Advanced | 4 cores | 4 GB | 80 GB SSD | 30 Mbps | 2 TB | ¥120 | [ Order Advanced](https://bit.ly/LiSaHost) |
| Annual promo | 1 core | 1 GB | 10 GB SSD | 50 Mbps | 600 GB/month | ¥399/year (~¥33/mo) | [ Order annual](https://bit.ly/LiSaHost) |

The annual promo is worth flagging — at ¥399/year it works out to about ¥33/month, and you get 50Mbps bandwidth (higher than the Basic monthly plan's 10Mbps) plus 600GB monthly traffic. If you're confident you'll use the service long-term, that's the best value in this line.

## Full plan comparison: US 9929 Dual-ISP Residential IP VPS

This is the line most TikTok operators and cross-border e-commerce people end up on. The "dual-ISP" part means the IP is registered with two ISPs, which makes it look even more like a genuine home broadband connection. All plans are in Los Angeles with the AS9929 premium route.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Lite | 1 core | 1 GB | 10 GB NVMe | 50 Mbps | 1 TB | ¥68 | [ Order Lite](https://bit.ly/LiSaHost) |
| Basic | 1 core | 1 GB | 20 GB NVMe | 60 Mbps | 2 TB | ¥88 | [ Order Basic](https://bit.ly/LiSaHost) |
| Advanced | 2 cores | 2 GB | 40 GB NVMe | 80 Mbps | 4 TB | ¥158 | [ Order Advanced](https://bit.ly/LiSaHost) |
| Premium | 4 cores | 4 GB | 80 GB NVMe | 100 Mbps | 8 TB | ¥899 | [ Order Premium](https://bit.ly/LiSaHost) |
| Unlimited Lite | 2 cores | 2 GB | 40 GB NVMe | 20 Mbps | Unlimited | ¥498 | [ Order Unlimited Lite](https://bit.ly/LiSaHost) |
| Unlimited Pro | 4 cores | 4 GB | 80 GB NVMe | 50 Mbps | Unlimited | ¥1,288 | [ Order Unlimited Pro](https://bit.ly/LiSaHost)) |
| Annual promo | 1 core | 1 GB | 10 GB NVMe | 50 Mbps | 600 GB/mo | ¥499/year (~¥41/mo) | [ Order annual](https://bit.ly/LiSaHost) |

The jump from Basic at ¥88 to Advanced at ¥158 is reasonable — you double CPU, RAM, storage, and bandwidth for less than double the price. The jump from Advanced to Premium at ¥899 is steep; you're paying for the 4-core/4GB config plus 100Mbps bandwidth and 8TB traffic. Most individual users won't need that.

## Full plan comparison: Hong Kong CMI/CU2/CN2 Premium Network

Hong Kong is the lowest-latency option for mainland China users — typically sub-50ms to major Chinese cities. These plans use three-network direct routing (CMI + CU2 + CN2), which means good performance regardless of which Chinese carrier your users are on.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Basic | 1 core | 1 GB | 20 GB NVMe | 30 Mbps | 1 TB | ¥88 | [ Order Basic](https://bit.ly/LiSaHost) |
| Advanced | 2 cores | 2 GB | 40 GB NVMe | 50 Mbps | 2 TB | ¥188 | [ Order Advanced](https://bit.ly/LiSaHost) |
| Unlimited Lite | 2 cores | 2 GB | 40 GB NVMe | 30 Mbps | Unlimited | ¥998 | [ Order Unlimited Lite](https://bit.ly/LiSaHost) |
| Unlimited Pro | 4 cores | 4 GB | 80 GB NVMe | 50 Mbps | Unlimited | ¥1,988 | [ Order Unlimited Pro](https://bit.ly/LiSaHost) |
| Annual promo | 1 core | 1 GB | 10 GB NVMe | 50 Mbps | 600 GB/mo | ¥566/year (~¥47/mo) | [ Order annual](https://bit.ly/LiSaHost) |

The Hong Kong line is notably more expensive than the US line for comparable specs — ¥88 vs ¥35 for a 1-core/1GB entry plan. You're paying for the location and the route. If your users are in China, the latency difference is worth it. If they're not, it isn't.

## Full plan comparison: US CERA CN2 High-Defense

This line adds DDoS protection on top of the CN2 GIA route. Default protection is 50G, upgradeable to 100G for an additional fee. Useful if you're running something that might attract attacks — game servers, controversial content, certain e-commerce setups.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Defense | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Trial | 1 core | 1 GB | 10 GB SSD | 10 Mbps | 1 GB | — | ¥2/day | [ Get the trial](https://bit.ly/LiSaHost) |
| Lite | 1 core | 512 MB | 10 GB SSD | 10 Mbps | 100 GB | 50G | ¥40/mo | [ Order Lite](https://bit.ly/LiSaHost) |
| Basic | 1 core | 1 GB | 20 GB SSD | 15 Mbps | 500 GB | 50G | ¥50/mo | [ Order Basic](https://bit.ly/LiSaHost) |
| Advanced | 2 cores | 2 GB | 20 GB SSD | 25 Mbps | 1.2 TB/mo | 50G | ¥256/quarter | [ Order Advanced](https://bit.ly/LiSaHost) |
| Premium | 4 cores | 4 GB | 40 GB SSD | 50 Mbps | 3 TB/mo | 50G | ¥396/mo | [ Order Premium](https://bit.ly/LiSaHost) |

Note that the Advanced plan here is billed quarterly (¥256/quarter ≈ ¥85/month), not monthly. The storage is also regular SSD rather than NVMe, which is a step down from the residential and native-IP lines.

## Full plan comparison: Singapore Native IP VPS

Singapore is positioned for Southeast Asia operations — TikTok, Shopee, regional e-commerce. The bandwidth here is generous (300Mbps+ on the entry plan), but the routing is BGP international, not China-optimized. LisaHost explicitly recommends using Hong Kong or Japan as a transit point if you're connecting from mainland China.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Basic | 1 core | 1 GB | 10 GB NVMe | 300 Mbps | 6 TB | ¥68 | [ Order Basic](https://bit.ly/LiSaHost) |
| Advanced | 2 cores | 2 GB | 20 GB NVMe | 500 Mbps | 10 TB | ¥88 | [ Order Advanced](https://bit.ly/LiSaHost) |
| Premium | 4 cores | 4 GB | 40 GB NVMe | 1 Gbps | 20 TB | ¥388 | [ Order Premium](https://bit.ly/LiSaHost) |
| Unlimited Lite | 2 cores | 2 GB | 40 GB NVMe | 200 Mbps | Unlimited | ¥398 | [ Order Unlimited Lite](https://bit.ly/LiSaHost) |
| Unlimited Pro | 4 cores | 4 GB | 80 GB NVMe | 500 Mbps | Unlimited | ¥898 | [ Order Unlimited Pro](https://bit.ly/LiSaHost) |
| Annual promo | 1 core | 1 GB | 10 GB NVMe | 300 Mbps | 2 TB/mo | ¥466/year (~¥38/mo) | [ Order annual](https://bit.ly/LiSaHost) |

The Singapore line has the best bandwidth-to-price ratio of any LisaHost location. ¥68/month for 300Mbps and 6TB is genuinely generous. The trade-off is that China connectivity isn't optimized — if that matters to you, pick Hong Kong or Japan instead.

## Full plan comparison: Japan Native IP VPS

Japan offers the same high-bandwidth approach as Singapore, with the added benefit of three-network optimization for mainland China. The native IPs unlock Japanese regional services — streaming, games, TikTok Japan, etc.

| Plan | CPU | RAM | Storage | Bandwidth | Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Basic | 1 core | 1 GB | 10 GB NVMe | 300 Mbps | 3 TB/mo | ¥88 | [ Order Basic](https://bit.ly/LiSaHost) |
| Advanced | 2 cores | 2 GB | 20 GB NVMe | 500 Mbps | 8 TB/mo | ¥158 | [ Order Advanced](https://bit.ly/LiSaHost) |
| Premium | 4 cores | 4 GB | 40 GB NVMe | 1 Gbps | 20 TB/mo | ¥300 | [ Order Premium](https://bit.ly/LiSaHost) |
| Unlimited Lite | 2 cores | 2 GB | 40 GB NVMe | 200 Mbps | Unlimited | ¥598 | [ Order Unlimited Lite](https://bit.ly/LiSaHost) |
| Unlimited Pro | 8 cores | 8 GB | 80 GB NVMe | 500 Mbps | Unlimited | ¥1,598 | [ Order Unlimited Pro](https://bit.ly/LiSaHost) |
| Annual promo | 1 core | 1 GB | 10 GB NVMe | 100 Mbps | 600 GB/mo | ¥499/year (~¥41/mo) | [ Order annual](https://bit.ly/LiSaHost) |

The Japan Unlimited Pro plan is the most powerful single-VPS config in LisaHost's lineup — 8 cores, 8GB RAM, 500Mbps unmetered. At ¥1,598/month (~$228) it's not cheap, but comparable specs from premium providers run two to three times that.

## Other locations worth knowing about

Beyond the core lines above, LisaHost sells native-IP and residential-IP VPS in several other locations. I haven't built full tables for these because the structure mirrors the lines above, but here's the quick pricing reference:

- **Taiwan Native IP VPS**: starts around ¥78/month, unlocks local streaming (Bahamut/动画疯, Netflix Taiwan, Disney+)
- **UK Dual-ISP Residential IP VPS**: starts around ¥68/month, fresh A-segment IPs, good for European TikTok operations
- **Korea Dual-ISP Residential VPS**: optimized for Korean regional services and TikTok
- **Germany Dual-Stack Native IP VPS**: native IPv4 + IPv6, AS9929 premium route, marketed for "AI全家桶" (AI tool access)
- **Vietnam Dual-ISP Residential VPS**: small Saigon telecom IP segment, niche but clean
- **US Chicago / New York large-bandwidth residential VPS**: unlimited-traffic residential options in non-LA locations

If your use case is specifically "I need a clean IP in country X for platform Y," there's a decent chance LisaHost has a product for it. The pricing pattern is consistent — entry plans around ¥68-88/month, advanced plans around ¥158-188/month, premium plans ¥300-400/month, unlimited plans ¥500-1,600/month depending on specs.

## The promo code situation

LisaHost runs a sitewide 10% discount with the code **TS-CBP205DQJE**. According to multiple sources, this code is reusable and works across all VPS plans regardless of location or tier. Applying it drops the ¥35 CN2 GIA Basic to ¥31.50, the ¥88 residential Basic to ¥79.20, and so on.

A few things to keep in mind about promos:

- The "限时特价" (limited-time special) prices shown on most plans are already discounted from the "原价" (original price) listed. The promo code stacks on top of that.
- The annual promo plans (¥399-¥566/year) are already aggressively priced — the 10% code still applies, but the marginal savings are small in absolute terms.
- Promo codes on VPS providers change. The code above has been documented as working through 2026, but verify it on the cart page before checkout. If it's expired, look for a current code on the LisaHost announcements page or in their Telegram group (t.me/lisahost_chat).

## What you're actually paying for vs. what you're not

It's worth being clear about what LisaHost pricing gets you and what it doesn't.

**What you're paying for:**
- Clean IP attribution (native or residential, depending on the line)
- Premium routing (CN2 GIA, AS9929, CMI) where advertised
- KVM virtualization with full root access
- NVMe SSD storage on most lines (the CERA high-defense line uses regular SSD)
- Instant automated deployment
- A 48-hour money-back guarantee on standard products

**What you're not paying for:**
- Massive storage — plans top out at 80GB on the premium tiers. If you need media hosting, look elsewhere.
- Ultra-high bandwidth on the China-optimized lines — the CN2 GIA Basic is 10Mbps. The high-bandwidth options (Singapore, Japan) trade China optimization for raw speed.
- Polished English support — LisaHost's primary market is Chinese-speaking. English support exists but is less comprehensive than the Chinese resources.
- Managed services — these are unmanaged VPS. You handle your own setup, security, and maintenance.

## How LisaHost pricing compares to alternatives

To put the numbers in context, here's how the main competitors stack up on the dimensions where LisaHost competes:

**BandwagonHost** — the established name in CN2 GIA. Their basic CN2 GIA plan runs around $49.99/year (~$4.17/month) for specs comparable to LisaHost's ¥35 Basic. Similar network quality, similar pricing. The difference: BandwagonHost doesn't focus on residential IPs. If you need residential attribution, LisaHost is the option; if you just need solid CN2 GIA routing, either works.

**RackNerd** — wins on raw budget value with frequent promotional deals. But their network is optimized for North America, not cross-Pacific. IPs are standard datacenter addresses. Different use case.

**DMIT** — premium positioning with excellent network quality and multiple locations. Pricing is notably higher than LisaHost for comparable specs. Good if budget isn't a constraint and you want white-glove service.

**Vultr / DigitalOcean** — global infrastructure, excellent documentation, consistent performance. But no China-optimized routing, datacenter IPs only, and higher pricing. Different category entirely.

The niche LisaHost occupies — premium Asia-Pacific routing at budget prices, plus genuine residential IP options — is genuinely uncommon. That's the whole reason their pricing structure looks the way it does: you're paying for things most providers don't offer, not competing on the same axis as everyone else.

## Which plan makes sense for what

Rather than a generic "best value" recommendation, here's how the pricing maps to actual use cases:

**For basic websites with China connectivity**: US CN2 GIA Basic at ¥35/month handles WordPress, small apps, dev environments. 500GB traffic covers moderate visitors. If you're committing long-term, the annual promo at ¥399/year is better value.

**For TikTok / social media account management**: Go straight to the US 9929 Dual-ISP Residential line. The ¥88 Basic gives you genuine residential attribution that keeps accounts in good standing. If you're running multiple accounts or significant traffic, the ¥158 Advanced or the unlimited plans prevent bandwidth from becoming a bottleneck.

**For e-commerce serving mainland China**: Hong Kong CMI/CU2/CN2 plans. The sub-50ms latency to mainland China makes checkout and admin feel instant. The ¥88 Basic is enough for small stores; the ¥188 Advanced for higher traffic.

**For accessing region-locked content**: Pick the native-IP line for the region. Japan for Japanese streaming/games, Singapore for Shopee and Southeast Asian services, UK for British content, Taiwan for Bahamut and local Taiwanese services.

**For high-bandwidth operations** (data scraping, continuous streaming, large transfers): Japan or Singapore lines. Japan's ¥158 Advanced with 500Mbps and 8TB/month is particularly strong value. Singapore's ¥68 Basic with 300Mbps and 6TB is the cheapest high-bandwidth entry point.

**For testing before committing**: The ¥2/day trial on the CN2 GIA and CERA lines. One day is enough to verify latency from your location, test platform access, and confirm routing works for your specific case.

## A few practical notes on buying

- **Payment methods**: Alipay, WeChat Pay, USDT (crypto), and major credit cards. International users outside China can use credit cards or USDT without issues.
- **Refund policy**: 48-hour unconditional money-back guarantee on standard products. Some specialized plans (Japan residential VDS, for example) refund to account balance rather than the original payment method — check the specific product page if this matters.
- **Deployment**: Genuinely instant. Order processes in minutes, credentials arrive immediately, no manual provisioning delays.
- **Operating systems**: All major Linux distributions (Debian, Ubuntu, CentOS, AlmaLinux). Higher-tier plans support Windows Server.
- **IP testing before scaling**: Before binding dozens of accounts to an IP, test it against your target platforms. Run actual logins, post test content, verify payment gateways don't flag it. The 48-hour refund window is designed for exactly this.

## The bottom line on LisaHost pricing

LisaHost isn't trying to be the cheapest VPS or the most premium. They're pricing for a specific combination — clean IPs plus premium Asia-Pacific routing — that most providers don't offer at all. The entry points (¥35 for CN2 GIA, ¥68 for residential, ¥88 for Hong Kong) are competitive for what you get, and the annual promos push the effective monthly cost even lower.

Where the pricing gets hard to justify is at the top of the residential and Hong Kong lines — ¥1,288/month for the US residential Unlimited Pro or ¥1,988/month for the Hong Kong Unlimited Pro is real money, and you'd want to be running serious operations to need that. For most individual users and small teams, the Basic-to-Advanced range (¥35-188/month) covers the use cases that brought you to LisaHost in the first place.

If you're still unsure which plan fits, start with the ¥2/day trial on the CN2 GIA line. Test the latency from your actual location, verify the platforms you care about work, and then decide whether to commit to a monthly plan. The trial exists specifically so you don't have to guess.

👉 [Browse all current LisaHost plans and pricing](https://bit.ly/LiSaHost)
