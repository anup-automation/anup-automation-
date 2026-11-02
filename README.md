<!-- NOTE: Agar aapka username "anup-automation" nahi hai, to neeche "anup-automation" ko apne username se replace karo -->

<!-- ═══════════ HEADER ═══════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b132b,50:1c2541,100:f5b301&height=240&section=header&text=Anup%20%7C%20Electrical%20Engineer&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=PLC%20%E2%80%A2%20Motor%20Control%20%E2%80%A2%20Industrial%20Automation&descAlignY=58&descSize=18&descColor=FFD60A" width="100%" alt="header"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=FFD60A&center=true&vCenter=true&width=700&lines=%E2%9A%A1+Diploma+Electrical+Engineer;PLC+Programmer+%7C+Ladder+Logic;Motor+Control+%E2%80%A2+Interlocking+%E2%80%A2+Star-Delta;Powering+Industry+with+Automation" alt="typing"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ENERGIZED-2da44e?style=for-the-badge&labelColor=0d1117" alt="status"/>
  <img src="https://img.shields.io/badge/SUPPLY-415V_3%CE%A6-FFD60A?style=for-the-badge&labelColor=0d1117" alt="supply"/>
  <img src="https://img.shields.io/badge/FREQ-50Hz-1f6feb?style=for-the-badge&labelColor=0d1117" alt="freq"/>
  <img src="https://komarev.com/ghpvc/?username=anup-automation&label=VIEWS&color=e5534b&style=for-the-badge&labelColor=0d1117" alt="views"/>
</p>

---

## 🪪 Engineer Nameplate

| ⚙️ Parameter | 📋 Rating |
|:------------|:---------|
| **Name** | Anup |
| **Qualification** | Diploma in Electrical Engineering |
| **Domain** | PLC & Industrial Automation |
| **Focus** | Ladder Logic, Motor Control, Interlocking |
| **PLC Platform** | Allen-Bradley (Studio 5000 / RSLogix) |
| **Currently Learning** | Timers, Counters, SCADA / HMI, VFD basics |
| **Status** | 🟢 Energized & Learning |
| **Connect** | [LinkedIn · anup80](https://www.linkedin.com/in/anup80/) |

---

## 🔌 How My System Works (Single Line Diagram)

```mermaid
flowchart LR
    A["3Φ 415V Supply"] --> B["MCB / MCCB"]
    B --> C["Contactor + Overload Relay"]
    C --> D["3Φ Induction Motor"]
    E["Start / Stop / Sensors"] --> F["PLC Controller"]
    F -- "Control Signal" --> C
```

---

## 🧠 Ladder Logic Snapshot: Start-Stop with Seal-in

```text
 L1 |                                                    | L2
    |──┬──┤ START ├──┬──┤/ STOP ├──┤/ OL ├──( MOTOR )──|
    |  │            │
    |  └──┤ MOTOR ├──┘
    |
    |   START  = Normally Open push button
    |   STOP   = Normally Closed push button
    |   OL     = Overload relay contact
    |   MOTOR  = Output coil + seal-in (hold) contact
```

---

## 🎛️ Control Panel: Skills

| 🔧 Area | 🛠️ What I work on | 📶 Level |
|:-------|:------------------|:--------|
| **PLC Programming** | Ladder Logic, I/O mapping, logic gates | ✅ Practicing |
| **Motor Control** | DOL, Star-Delta starter, interlocking | ✅ Practicing |
| **Timers & Counters** | Sequencing, delay-based control | 🔄 Learning |
| **Electrical Basics** | 3-phase systems, control circuits, protection devices | ✅ Practicing |
| **SCADA / HMI** | Monitoring and operator interface | 🌱 Exploring |
| **VFD & Sensors** | Speed control, proximity / limit sensing | 🌱 Exploring |

<p align="center">
  <img src="https://img.shields.io/badge/PLC-Programming-FFD60A?style=for-the-badge&labelColor=0d1117" alt="plc"/>
  <img src="https://img.shields.io/badge/Ladder-Logic-8957e5?style=for-the-badge&labelColor=0d1117" alt="ladder"/>
  <img src="https://img.shields.io/badge/Motor-Control-e5534b?style=for-the-badge&labelColor=0d1117" alt="motor"/>
  <img src="https://img.shields.io/badge/Interlocking-Systems-2da44e?style=for-the-badge&labelColor=0d1117" alt="interlock"/>
  <img src="https://img.shields.io/badge/Industrial-Automation-1f6feb?style=for-the-badge&labelColor=0d1117" alt="automation"/>
</p>

### 🧰 Tools & Software

<p align="center">
  <img src="https://img.shields.io/badge/Allen--Bradley-PLC-CD163F?style=for-the-badge&logo=rockwellautomation&logoColor=white&labelColor=0d1117" alt="Allen-Bradley"/>
  <img src="https://img.shields.io/badge/Studio_5000-Logix_Designer-CD163F?style=for-the-badge&logo=rockwellautomation&logoColor=white&labelColor=0d1117" alt="Studio 5000"/>
  <img src="https://img.shields.io/badge/RSLogix-Ladder_Editor-CD163F?style=for-the-badge&logo=rockwellautomation&logoColor=white&labelColor=0d1117" alt="RSLogix"/>
</p>

---

## 🚀 Project Panel

| 🔹 Project | 📝 What it does | ⚡ Concepts | 🔗 Link |
|:----------|:---------------|:-----------|:-------|
| **All Gate Ladder Logic** | AND, OR, NOT, NAND, NOR, XOR & XNOR gates in ladder logic | Logic gates, I/O | [View](https://github.com/anup-automation/All-Gate-Ladder-Logic-Programe-) |
| **PLC Interlocking System** | Equipment interlocking for safe industrial operation | Interlocking, safety | [View](https://github.com/anup-automation/PLC-Interlocking-System) |
| **Star-Delta Starter Control** | Automatic Star → Delta switching of a 3-phase induction motor | Timers, motor control | [View](https://github.com/anup-automation/Star-Delta-Starter-PLC-Control) |

### ⭐ Star-Delta Sequence

```mermaid
flowchart LR
    S(["START pressed"]) --> K1["Main + Star contactor ON"]
    K1 --> T["Timer runs"]
    T --> K2["Star OFF, Delta ON"]
    K2 --> R(["Motor runs in Delta"])
```

---

## 🗺️ Learning Roadmap

- [x] Basic logic gates in ladder logic
- [x] Interlocking systems
- [x] Star-Delta starter
- [ ] DOL & Forward-Reverse motor control
- [ ] Timer / Counter based conveyor sequence
- [ ] Tank level control system
- [ ] Traffic light control
- [ ] SCADA / HMI basics
- [ ] VFD based speed control

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=anup-automation&show_icons=true&hide_border=true&bg_color=0d1117&title_color=FFD60A&icon_color=FFD60A&text_color=ffffff" alt="stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anup-automation&layout=compact&hide_border=true&bg_color=0d1117&title_color=FFD60A&text_color=ffffff" alt="langs"/>
</p>

---

## ⚠️ Safety First

> **De-energize. Lock out. Verify. Then work.**
> Good automation is not just smart, it is safe.

<p align="center">
  <a href="https://www.linkedin.com/in/anup80/">
    <img src="https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&labelColor=0d1117" alt="linkedin"/>
  </a>
</p>

<!-- ═══════════ FOOTER ═══════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f5b301,50:1c2541,100:0b132b&height=120&section=footer" width="100%" alt="footer"/>
</p>
