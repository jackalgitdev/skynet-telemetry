# 📡 Skynet Telemetry

Long-term Starlink performance telemetry tracking speed, latency, firmware updates, network events, records and trends.

## 📡 System Profile

- **Service:** Starlink Residential
- **Plan:** Residential Max
- **Kit:** Starlink Standard Kit
- **Router:** Gen 3 Router
- **Region:** Queensland, Australia
- **Collection began:** 17 June 2026

## About

Skynet Telemetry is a personal long-term monitoring project documenting the real-world performance of a residential Starlink connection in Queensland, Australia.

The project began on 17 June 2026 with a simple daily speed test log and has since expanded to track performance trends, firmware changes, notable network events, records and milestones.

## 📊 What is tracked

- ⬇️ Download speed
- ⬆️ Upload speed
- ⚡ Latency
- 📡 Starlink firmware updates
- 🛜 Router firmware updates
- ❗ Network events affecting real-world use
- 🏆 Performance records
- 🎖️ Achievements
- 🎯 Milestones
- 📈 Long-term trends

## 🧪 Methodology

One official speed test is recorded per day.

Additional tests are permitted following firmware upgrades:

- One additional test after a 📡 Starlink firmware upgrade
- One additional test after a 🛜 Router firmware upgrade
- Up to two additional tests on the same day if both receive separate firmware upgrades

Firmware test entries record:

- Upgrade type
- Software version
- Download speed
- Upload speed
- Latency

### Investigation Thresholds

Not every fluctuation in speed or latency indicates a service issue. Results are treated as normal variability unless they cross an investigation threshold.

A result may warrant closer review or a Starlink debug report if any of the following occur:

- ⬇️ Download speed falls below 100 Mbps
- ⬆️ Upload speed falls below 20 Mbps
- ⚡ Latency exceeds 40 ms on its own

Latency above 25 ms is noted as context when download or upload performance is also degraded, but does not warrant investigation by itself.

## 📂 Dataset

The official daily speed test dataset is stored in [`data/speed-tests.csv`](data/speed-tests.csv).

Post-firmware upgrade performance tests are stored separately in [`data/firmware-tests.csv`](data/firmware-tests.csv).

The Skynet sequence countdown is available at [Sequence Status](https://jackalmuse.com/starlink/).

The dataset uses a simple machine-readable CSV structure:

- `date` — Test date in ISO 8601 format (`YYYY-MM-DD`)
- `download_mbps` — Download speed in Mbps
- `upload_mbps` — Upload speed in Mbps
- `latency_ms` — Latency in milliseconds

The daily dataset contains one official test per day. Post-firmware upgrade tests are tracked separately to preserve the integrity of the daily series.

## 🏆 Current Records

| Metric | Record | Date |
|---|---:|---:|
| ⬇️ Fastest Download | 431 Mbps | 26/07/2026 |
| ⬆️ Fastest Upload | 57 Mbps | 26/08/2026 |
| ⚡ Lowest Latency | 15 ms | 08/07/2026 |

## 📊 Current Averages

Based on official daily speed tests through **26/09/2026**.

| Metric | Average |
|---|---:|
| ⬇️ Download | 284.66 Mbps |
| ⬆️ Upload | 37.91 Mbps |
| ⚡ Latency | 21.52 ms |

## 🎯 Active Milestones

- ⬇️ Download >450 Mbps
- ⬇️ Download >500 Mbps
- ⬆️ Upload >60 Mbps
- ⚡ Latency <15 ms

## 📅 Data Collection

**Started:** 17 June 2026

The dataset is collected from a live residential Starlink connection and is intended to build a long-term picture of performance, variability and network behaviour over time.

---

## 📡 Starlink referral

**Get one month of Starlink free.**

Already thinking about joining Starlink? Sign up through my referral link as a new customer on an eligible Residential or Roam plan. You pay for month one; a service credit covers month two.

<p align="center">
  <a href="https://starlink.com/?referral=RC-500727-18339-12&amp;app_source=qr">
    <img src="assets/starlink-referral-qr-v111-r1.png" alt="Scan to open my Starlink referral link" width="180" height="180">
  </a>
</p>

<p align="center">
  <a href="https://starlink.com/?referral=RC-500727-18339-12&amp;app_source=share"><strong>Use my Starlink referral link →</strong></a>
</p>

<details>
<summary>Who qualifies &amp; how it works</summary>

- For new customers on qualifying plans; existing and returning customers are excluded.
- Order through the referral link on starlink.com, activate your kit and stay subscribed for at least two months.
- Kits purchased from retailers or resellers, and transferred kits, are not eligible.
- Check [Starlink’s current eligibility and credit details](https://starlink.com/au/support/article/1361c631-2c31-271a-732b-bab080fb1384) before ordering.

</details>

Using this link also supports jackalmuse through a referral reward. [View the referral page on my website](https://jackalmuse.com/starlink/referral/).

*Offer checked 26 September 2026. Starlink sets the offer and eligibility.*

---

## 🌐 Find me online

<p align="center">
  <a href="https://profile.playstation.com/jackalmuse" title="PlayStation Network"><img src="assets/icons/playstation-v107.png" alt="PlayStation Network" width="56" height="56"></a>
  &nbsp;
  <a href="https://www.tiktok.com/@jackalmuse" title="TikTok"><img src="assets/icons/tiktok-v107.png" alt="TikTok" width="56" height="56"></a>
  &nbsp;
  <a href="https://x.com/jackalmuse" title="X"><img src="assets/icons/x-v107.png" alt="X" width="56" height="56"></a>
  &nbsp;
  <a href="https://github.com/jackalgitdev" title="GitHub"><img src="assets/icons/github-v107.png" alt="GitHub" width="56" height="56"></a>
  &nbsp;
  <a href="https://suno.com/@jackalmuse" title="Suno"><img src="assets/icons/suno-v107.png" alt="Suno" width="56" height="56"></a>
</p>

<p align="center">
  <a href="https://youtube.com/@jackalmuse" title="YouTube"><img src="assets/icons/youtube-v107.png" alt="YouTube" width="56" height="56"></a>
  &nbsp;
  <a href="https://www.paypal.com/paypalme/jackalpay" title="PayPal"><img src="assets/icons/paypal-v107.png" alt="PayPal" width="56" height="56"></a>
  &nbsp;
  <a href="https://pin.it/5Uq3CPnzT" title="Pinterest"><img src="assets/icons/pinterest-v107.png" alt="Pinterest" width="56" height="56"></a>
  &nbsp;
  <a href="https://www.facebook.com/share/1Lyn1GgMNn/?mibextid=wwXIfr" title="Facebook"><img src="assets/icons/facebook-v107.png" alt="Facebook" width="56" height="56"></a>
  &nbsp;
  <a href="https://www.instagram.com/itsjackalmuse" title="Instagram"><img src="assets/icons/instagram-v107.png" alt="Instagram" width="56" height="56"></a>
</p>

<p align="center"><a href="https://jackalmuse.com/">jackalmuse.com</a></p>

*Skynet Telemetry is an independent personal project and is not affiliated with Starlink or SpaceX.*
