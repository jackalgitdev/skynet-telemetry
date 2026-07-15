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

## 📂 Dataset

The official daily speed test dataset is stored in [`data/speed-tests.csv`](data/speed-tests.csv).

Post-firmware upgrade performance tests are stored separately in [`data/firmware-tests.csv`](data/firmware-tests.csv).

The dataset uses a simple machine-readable CSV structure:

- `date` — Test date in ISO 8601 format (`YYYY-MM-DD`)
- `download_mbps` — Download speed in Mbps
- `upload_mbps` — Upload speed in Mbps
- `latency_ms` — Latency in milliseconds

The daily dataset contains one official test per day. Post-firmware upgrade tests are tracked separately to preserve the integrity of the daily series.

## 🏆 Current Records

| Metric | Record | Date |
|---|---:|---:|
| ⬇️ Fastest Download | 401 Mbps | 27/06/2026 |
| ⬆️ Fastest Upload | 54 Mbps | 16/07/2026 |
| ⚡ Lowest Latency | 15 ms | 08/07/2026 |

## 🎯 Active Milestones

- ⬇️ Download >450 Mbps
- ⬇️ Download >500 Mbps
- ⬆️ Upload >55 Mbps
- ⬆️ Upload >60 Mbps
- ⚡ Latency <15 ms

## 📅 Data Collection

**Started:** 17 June 2026

The dataset is collected from a live residential Starlink connection and is intended to build a long-term picture of performance, variability and network behaviour over time.

---

*Skynet Telemetry is an independent personal project and is not affiliated with Starlink or SpaceX.*

<br>

<p align="center">
  <a href="https://www.tiktok.com/@jackalmuse">
    <img src="https://assets.jackalmuse.com/Socials/TikTok.PNG" alt="TikTok" width="32">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.instagram.com/jackaligram/">
    <img src="https://assets.jackalmuse.com/Socials/Instagram.PNG" alt="Instagram" width="32">
  </a>
</p>