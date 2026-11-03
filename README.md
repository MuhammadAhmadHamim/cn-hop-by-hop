<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:161d25,50:222c37,100:313d4b&height=230&section=header&text=cn-hop-by-hop&fontSize=54&fontColor=3dd1f0&fontAlignY=40&desc=Computer%20Networks%20Lab%20%E2%80%94%20One%20Hop%20at%20a%20Time&descSize=18&descAlignY=63&descColor=e6eef3&animation=fadeIn&fontFamily=Georgia" alt="cn-hop-by-hop banner"/>

<br/>

![Tool](https://img.shields.io/badge/Tool-Packet%20Tracer-3dd1f0?style=for-the-badge&labelColor=161d25)
![Focus](https://img.shields.io/badge/Focus-Computer%20Networks-e6eef3?style=for-the-badge&labelColor=161d25)
![Semester](https://img.shields.io/badge/Semester-4%20%C2%B7%20Fall%202026-5f7083?style=for-the-badge&labelColor=161d25)
![Status](https://img.shields.io/badge/Status-🔨%20Actively%20Growing-3dd1f0?style=for-the-badge&labelColor=161d25)

> *"Be conservative in what you do, be liberal in what you accept from others."*
> — **Jon Postel**, RFC 793 *(the rule the whole internet quietly runs on)*

<br/>

</div>

---

## ◈ What Lives Here

Every lab from my Computer Networks course, saved as the actual network I built: **Cisco Packet Tracer topologies**, **Wireshark captures**, and the **CLI commands** behind each configuration. Topologies, DHCP, subnetting, VLSM, packet analysis, and web, mail and DNS servers and many more, all in one place.

A packet never travels the whole path in one jump. It goes **hop by hop**, and each device only decides the next step. This repo follows the same idea: one hop of the course at a time, from a single cable between two PCs to servers answering requests.

Not archived. Every lab that lands gets added the week it's understood, not the week it's due.

---

## ◈ Vault Structure

```
cn-hop-by-hop/
│
└── 🕸️ 01_topologies/
       ├── bus.pkt
       └── point_to_point.pkt
```

<details>
<summary><b>🕸️ 01 — Topologies &nbsp;|&nbsp; Six Ways to Wire the Same Idea</b></summary>
<br/>

| Topology | What It Shows |
|---|---|
| **Point-to-Point** | A direct link between exactly two devices |
| **Bus** | Devices sharing a single backbone |

> *Every later lab sits on top of one of these shapes.*

</details>

**Coming up:** whatever the rest of the course covers. This section gets updated as labs land.

---

## ◈ The Route

```
C:\> tracert cn-hop-by-hop

Tracing the course, one hop at a time:

  1   01_topologies              bus · point-to-point
  2      *        *        *     Request timed out.

Trace not complete.
```

Hop 2 is the next lab. It hasn't answered yet.

---

## ◈ How to Explore

```bash
git clone https://github.com/MuhammadAhmadHamim/cn-hop-by-hop.git
```

- **`.pkt` files** open in [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (built with version `9.0.1.858`). A free Cisco Networking Academy account is needed to download it.

---

## ◈ Skills Being Forged

<div align="center">

![](https://img.shields.io/badge/Tool-Cisco_Packet_Tracer-3dd1f0?style=flat-square&logo=cisco&logoColor=white)
![](https://img.shields.io/badge/CLI-Cisco_IOS-5f7083?style=flat-square&logo=cisco&logoColor=white)
![](https://img.shields.io/badge/Design-Network_Topologies-3dd1f0?style=flat-square&logoColor=white)

</div>

---

## ◈ A Note on This Work

This repo holds everything I learned in the course, not just a final project. Some labs are small and some are large, and they sit side by side because each one was a hop toward understanding how data actually moves.

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:313d4b,50:222c37,100:161d25&height=120&section=footer&animation=fadeIn" alt="footer"/>

*One hop at a time. TTL not yet exceeded.*

</div>