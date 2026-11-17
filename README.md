# San Jose VPS: Is RackNerd Worth $21.99 a Year, How Bad Is the Latency to Asia, and Which Plan Fits Your Project? (Full Plan Table + Renewal Fine Print)

RackNerd's cheapest San Jose KVM plan is **$21.99 for a full year**: 1 GB RAM, 20 GB SSD, 3 TB of transfer on a 1 Gbps port. The **2 GB plan at $35.99/year** is the one most side projects, staging boxes and small Docker hosts should take, and the 4 GB at $59.99/year covers a busier site without thinking about it.

Latency from Asia looks ordinary rather than magic. A reviewer who pinged the San Jose network reported roughly **110 ms from Tokyo, 160 ms from Hong Kong, 170–180 ms from Singapore, 70 ms from the US east coast and 140–150 ms from Europe**. Those are his measurements from his own connections, so treat them as a shape, not a promise. Ping **192.210.207.88** from your own line before you pay for anything; what comes back is close to what your box will see.

Below is the full plan table, the annual-versus-monthly arithmetic, the checkout step where people accidentally buy a server in the wrong city, and the refund question that a lot of guides answer wrongly.

> **Quick pick:** personal WireGuard or SOCKS endpoint → 1 GB at $21.99/year. Side project, Docker host or small WordPress site → 2 GB at $35.99/year or 4 GB at $59.99/year. Need 300 GB of disk → only the 12 GB standard plan at $55.99/month.
> 👉 [Compare the annual Special Promos](https://my.racknerd.com/aff.php?aff=11397&rp=/store/special-promos)

## What a RackNerd San Jose VPS actually is

KVM virtualization with full root, a dedicated IPv4, pure SSD in RAID-10, and a SolusVM panel for reboots, OS reinstalls, rDNS and console access. Activation is automatic: the welcome email with your IPv4, root password and panel login usually lands within five minutes of checkout. Payment options are card, PayPal, crypto (BTC, BCH, ETH, USDT, LTC) and Alipay in some regions. The OS list covers CentOS, Debian, Ubuntu, AlmaLinux, Rocky Linux, FreeBSD and a few others. There is no Windows image, so if you need RDP this is the wrong provider.

## Full San Jose plan table

These are the plans as listed by the RackNerd trackers that publish the same annual pricing, with the specs they attach to each tier. RackNerd splits its annual deals across more than one store page, so the order links below point at the store page each plan appears on; pick the matching plan there.

| Plan | RAM / vCPU | SSD (RAID-10) | Bandwidth | Price (annual billing) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM | 1 GB / 1 vCore | 20 GB | 3 TB @ 1 Gbps | **$21.99/yr** (≈$1.83/mo) | [Order the 1 GB annual plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 2 GB KVM | 2 GB / 2 vCores | 35 GB | 5 TB @ 1 Gbps | **$35.99/yr** (≈$3.00/mo) | [Order the 2 GB annual plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/special-promos) |
| 4 GB KVM | 4 GB / 2 vCores | 60 GB | 7 TB @ 1 Gbps | **$59.99/yr** (≈$5.00/mo) | [Order the 4 GB annual plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/special-promos) |
| 6 GB KVM | 6 GB / 6 vCores | 100 GB | 12 TB @ 1 Gbps | **$89.99/yr** (≈$7.50/mo) | [Order the 6 GB annual plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 8 GB KVM | 8 GB / 7 vCores | 150 GB | 20 TB @ 1 Gbps | **$119.99/yr** (≈$10.00/mo) | [Order the 8 GB annual plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/special-promos) |

The 4 GB tier ships with only 2 vCores while the 6 GB jumps to 6. If your workload is CPU-bound rather than RAM-hungry (build jobs, ffmpeg, scrapers), the extra $30 a year for the 6 GB buys four more cores and 40 more GB of disk.

The standard KVM line, which bills monthly and configures differently from the annual specials, looks like this:

| Plan | RAM / vCPU | SSD (RAID-10) | Bandwidth | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 512 MB | 512 MB / 1 vCore | 30 GB | 500 GB @ 1 Gbps | **$26.99/yr** (annual only) | [Order the 512 MB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 1 GB | 1 GB / 2 vCores | 50 GB | 1 TB @ 1 Gbps | **$17.99/mo** | [Order the standard 1 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 2 GB | 2 GB / 3 vCores | 75 GB | 2 TB @ 1 Gbps | **$20.59/mo** | [Order the standard 2 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 4 GB | 4 GB / 4 vCores | 130 GB | 3 TB @ 1 Gbps | **$24.59/mo** | [Order the standard 4 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 6 GB | 6 GB / 5 vCores | 170 GB | 4 TB @ 1 Gbps | **$27.59/mo** | [Order the standard 6 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 8 GB | 8 GB / 6 vCores | 220 GB | 5 TB @ 1 Gbps | **$36.59/mo** | [Order the standard 8 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |
| 12 GB | 12 GB / 7 vCores | 300 GB | 6 TB @ 1 Gbps | **$55.99/mo** | [Order the 12 GB plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps) |

Confirm the spec shown in your cart before paying; stock and configurations move, and only the order page has the final numbers.

## Where the box actually sits: San Jose or Santa Clara?

The product is sold as San Jose VPS, and the facility address published with it is **3223 Kenneth St., Santa Clara, CA 95045**. Santa Clara borders San Jose, and both sit in the same part of the South Bay, so the naming is marketing shorthand rather than a bait and switch. It does mean your "San Jose" server is technically in Santa Clara, which matters if you are matching against a competitor that publishes a real San Jose street address (more on that below).

The building is described as a 71,000 sq ft facility with carrier-neutral uplinks to **NTT, Telia, HE, GTT and Cogent**, five upstreams rather than one, with BGP choosing a path per destination. Five carriers is the reason a bad week at one network does not take your box off the air. Power is described as 2N redundant.

## Why pick San Jose over Los Angeles?

San Jose is the landing side for transpacific cable from Tokyo, Singapore, Hong Kong and Seoul, so a request from those cities reaches it without the extra hop that a badly-routed LA box sometimes adds. The reviewer quoted above measured **~110 ms Tokyo, ~160 ms Hong Kong, ~170–180 ms Singapore**, and noted the same shared 1 Gbps port typically returns **200–400 Mbps on speed tests depending on neighbour load**. That is plenty for a web app or a tunnel, and not enough if you plan to push multi-terabyte backups nightly.

Do your own measurement with the test IP **192.210.207.88**. Run `ping`, then `mtr`, from the machine or region your users are in. If the round trip from your city comes back at 250 ms while a competitor shows 150 ms, no price on this page saves the experience.

## What the annual price really costs over three years

The gap between annual and monthly is not small. A standard 2 GB plan at $20.59/month costs **$247.08 a year**; the annual special at $35.99 costs **$35.99**. Even allowing for the smaller disk (35 GB versus 75 GB) and fewer vCores, that is a different category of spend. The same comparison at 8 GB is $439.08/year versus $119.99/year.

The renewal line matters as much as the first invoice. The RackNerd guide that tracks these promotions states that **annual promo pricing is locked for the life of the service**, meaning year two and year three bill at the same rate instead of reverting to a standard price. That claim comes from a single third-party source, not a dated page on RackNerd's own site, so read the renewal amount in your cart before you commit. If it holds, the three-year cost of the 2 GB plan is $107.97; if it does not, you will see the real number at checkout.

Now the part most guides soften. RackNerd's own knowledgebase answers the refund question in one line: *"Per our terms of service, we do not offer refunds or have a money back guarantee."* Several write-ups circulating a 3-day money-back window on new VPS orders contradict that page, and where they disagree, the knowledgebase is the one that governs your money. Account credit and cancellations follow the same logic: cancelling a service does not return what you already paid.

So treat the first payment as committed rather than as a trial. That changes the sensible order of operations: ping the test IP, read the plan spec, then buy the smallest annual plan that proves the network works from your location. Upgrading later is easy; getting $119.99 back is not.
👉 [Start with the 1 GB annual plan and test the route](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps)

## Five things that trip people up at checkout

**1. The location dropdown defaults to "Multiple Locations."** Promo plans usually do not pre-select San Jose. You have to pick it manually during checkout, and it may read "San Jose, CA" or "US West — San Jose." Skip this and you can end up with a server in Ashburn.

**2. Seasonal specials sell out.** A 1 GB New Year special has been listed at **$11.29/year**, which is close to free, and the smallest tier is always the first to disappear. If it is gone, the 1 GB at $21.99/year or the 2 GB at $35.99/year is the fallback, not a wait-and-see.
👉 [Check whether the seasonal 1 GB special is in stock](https://my.racknerd.com/aff.php?aff=11397&rp=/store/new-year-specials)

**3. IPv6 in San Jose is not confirmed.** Free IPv6 blocks of up to 100 addresses are offered in Los Angeles and France; San Jose has been described as still rolling out. Open a ticket and ask before you design around it. IPv4-only works fine for most projects.

**4. The 1 Gbps port is shared.** Expect 200–400 Mbps on a speed test, not a gigabit, and plan sustained transfers accordingly.

**5. Annual promos bill annually only.** No monthly option on those tiers. If you need monthly flexibility, you are on the standard line and paying standard prices.

## When RackNerd is the wrong buy

Three situations where another provider is the better answer, with the numbers those providers publish:

| Provider | San Jose footprint | Entry price | What stands out |
| --- | --- | --- | --- |
| v.ps | Equinix SV10, 7 Great Oaks Blvd, San Jose, CA 95119; AS6233; upstreams include Tata, Orange, Misaka, China Telecom, China Unicom; Equinix IX peering | Cloud KVM from €8.95/mo; Mini KVM from €49.95/yr | 1 IPv4 + 1 IPv6 on every plan, 99.9% SLA, 14-day refund window on VPS products |
| DropVPS | San Jose, NVMe storage, DDoS protection included | $5.90/mo for 1 GB, 1 core, 20 GB NVMe, 1 TB | 99.99% uptime SLA claim, 60-second deploy, same price in every location |
| iHosting24 | San Jose, Ryzen and NVMe RAID claims | $3.50/mo for 1 GB, 1 core, 15 GB, 2 TB | Windows Server 2012–2025 images available; RAM, disk and bandwidth add-ons priced separately |

Read that as a map of trade-offs rather than a ranking. RackNerd wins on annual outlay by a wide margin: $35.99 for a year of 2 GB against $5.90/month. v.ps is the one to look at if mainland China routing is the point, since China Telecom and China Unicom appear in its upstream list, and it is also the only one of the four publishing both a real San Jose street address and a 14-day refund window. DropVPS suits people who want NVMe, a monthly exit and a written SLA. iHosting24 is the answer if you need a Windows image, which RackNerd does not offer at all.

One caution on the cheap end: the annual RackNerd plans are unmanaged. You get root and a panel. Nobody is patching your kernel.

## FAQ

**Is the San Jose datacenter in San Jose?**
The published address is 3223 Kenneth St., Santa Clara, CA 95045. Santa Clara borders San Jose, so the product name is regional shorthand. If an exact street address inside San Jose city limits is a requirement, v.ps publishes one.

**Can I get a refund if it does not work out?**
RackNerd's knowledgebase says no refunds and no money-back guarantee. Some guides mention a 3-day window; trust the knowledgebase and check the terms shown at checkout for your specific plan.

**Will the renewal price jump?**
The tracking guide says annual promo rates are locked for the life of the service. Verify the renewal amount on your cart page, since that is a single-source claim.

**Is 1 GB enough for Docker or WireGuard?**
A WireGuard endpoint, a SOCKS proxy or a couple of small containers run comfortably in 1 GB. Docker plus a build pipeline plus a database will not; take the 2 GB or 4 GB.

**Should I buy monthly first?**
Only if you specifically want the larger standard configs. The monthly 1 GB is $17.99, which is eight times the annual 1 GB per month. Test the network with the ping IP instead of paying for a monthly trial you did not need.

## Which one do you order?

Match the plan to the job and stop there:

- A tunnel, proxy or personal VPN endpoint → **1 GB at $21.99/year**.
- A side project, staging box, small WordPress or Ghost site → **2 GB at $35.99/year**, or **4 GB at $59.99/year** if you run a database alongside the app.
- Container builds, media processing, anything CPU-hungry → **6 GB at $89.99/year** for the core count.
- 100 GB or more of data with room to grow → **8 GB at $119.99/year**.
- 300 GB of fast disk → **12 GB at $55.99/month**, which has no annual equivalent.

Two things to confirm before you pay: ping **192.210.207.88** from where your traffic actually originates, and check that the location field in your cart reads San Jose rather than "Multiple Locations."

👉 [Pick your plan from the RackNerd KVM store](https://my.racknerd.com/aff.php?aff=11397&rp=/store/kvm-vps)
