### Desktop apps

🪨 **[Slate](https://github.com/jamesccupps/Slate)** A fast, simple Notepad replacement for Windows and Linux (Raspberry Pi included) that opens files of any size — an 800 MB JSON file opens instantly. Syntax colors for 52 languages, JSON and XML tools, tabs and unsaved changes that come back after a restart, automatic updates (signed exe on Windows, apt on Linux). Native Rust: Direct2D on Windows, GTK 4 on Linux — [website](https://jamesccupps.github.io/Slate/) · [download](https://github.com/jamesccupps/Slate/releases/latest).

📹 **[Protect Panes](https://github.com/jamesccupps/UnifiCameraViewer)** UniFi Protect live view for Windows: each camera in its own borderless window you can place and size anywhere, or several in one grid window, across several consoles. Video comes over Protect's own livestream (no RTSP), with a local login (no cloud account or MFA). Also 360° fisheye dewarping, saved layouts with Protect liveview import, camera previews, and signed in-place updates. Electron — [website](https://jamesccupps.github.io/UnifiCameraViewer/) · [download](https://github.com/jamesccupps/UnifiCameraViewer/releases/latest).

📦 **[UniFi Stock Watcher](https://github.com/jamesccupps/UnifiStockWatcher)** Alerts you the moment something you want is back in stock on the Ubiquiti Store. Checks the whole UniFi catalog on a timer, with a notification you can click, a sound and the product's page; restock estimates, a feed of every stock change across the store, and a history. Runs in the notification area and starts with Windows; installer or portable zip, with signed in-place updates. Python, tkinter — [website](https://jamesccupps.github.io/UnifiStockWatcher/) · [download](https://github.com/jamesccupps/UnifiStockWatcher/releases/latest).

🖥️ **[HW Blackbox](https://github.com/jamesccupps/HW-Blackbox)** A hardware monitor and black box for Windows that answers *why did the PC switch off, or why did that app close?* Every sensor every 5 s and the voltage rails four times a second, recorded from boot by a Windows service, with a report after every power-off or app crash. Local dashboard, optional Home Assistant status. Python — [website](https://jamesccupps.github.io/HW-Blackbox/) · [download](https://github.com/jamesccupps/HW-Blackbox/releases/latest).

📝 **[NoteForge](https://github.com/jamesccupps/NoteForge)** Encrypted offline note-taking with master-password and per-notebook locks. Electron + AES-256-GCM. Data stays local — no cloud, no account — [download](https://github.com/jamesccupps/NoteForge/releases/latest).

### Building automation and HVAC

🏢 **[HVAC-Network-Scanner](https://github.com/jamesccupps/HVAC-Network-Scanner)** Multi-protocol discovery and audit tool for building automation networks: BACnet/IP, MS/TP behind routers, BACnet/SC, Modbus TCP, KNXnet/IP, SNMP and Niagara Fox, with model fingerprinting for Trane, Siemens, JCI, Tridium and more. Raw-socket implementation, zero third-party dependencies, headless CLI and Tk GUI — [download](https://github.com/jamesccupps/HVAC-Network-Scanner/releases/latest).

🦈 **[P2_Wireshark_Dissector_and_P2_Scanner](https://github.com/jamesccupps/P2_Wireshark_Dissector_And_P2_Scanner)** Tools and a technical reference for P2 ("Protocol II"), the Siemens APOGEE building-automation protocol over TCP: a Wireshark dissector, a read-only scanner, a virtual PXC panel to develop against, and a P2→BACnet/IP bridge — for owner-operators working with their own legacy equipment.

⚙️ **[PPCL Workbench](https://github.com/jamesccupps/PPCL)** IDE, linter, simulator and debugger for Siemens PPCL — the line-numbered control language APOGEE and PXC field panels run. 90 lint rules, each citing the manual page it comes from; a browser IDE with a live point database; and an equipment bench that drives a program against a simulated air handler with sensor lag, actuator stroke time and injectable faults. Zero dependencies, Python stdlib only — nothing leaves the machine — [download](https://github.com/jamesccupps/PPCL/releases/latest).

📈 **[HVACTrend](https://github.com/jamesccupps/HVACTrend)** Read-only BACnet/IP trend logger, web trend viewer and rule-based alarms for building HVAC. Logs the points you pick every two minutes, charts years of history instantly, and sends equipment alarms (discharge air off setpoint, low duct static, a boiler enabled but not heating) to your phone. Never writes to a controller. Python, SQLite — [download](https://github.com/jamesccupps/HVACTrend/releases/latest).

🌡️ **[CoolingTowerSim](https://github.com/jamesccupps/CoolingTowerSim)** Physics-based browser simulator of a commercial building's condenser-water cooling loop. Animated process schematic, full tower-staging sequence of operations, and live power-draw KPIs. Single self-contained HTML file, calibrated against real BAS field trends — [live demo](https://jamesccupps.github.io/CoolingTowerSim/).

💧 **[Wetbulb](https://github.com/jamesccupps/Wetbulb)** Real-time, pressure-corrected wet-bulb temperature by ZIP, city, or GPS — with a cooling-tower approach reference, a shade-WBGT estimate, a 24-hour trend plus next-24h forecast peak, and a fully offline manual psychrometric calculator — [live demo](https://jamesccupps.github.io/Wetbulb/).

### Networking and security

📡 **[PingerPlot](https://github.com/jamesccupps/PingerPlot)** Continuous-traceroute network path monitor for Windows and Linux (MTR-style). Per-hop latency, packet loss, jitter, and MOS with live latency graphs, route changes, alerts and webhooks, and a world-map path view. Installer, portable zip or pipx, with signed updates. Pure Python standard library — zero dependencies, no admin needed in ICMP mode — [website](https://jamesccupps.github.io/PingerPlot/) · [download](https://github.com/jamesccupps/PingerPlot/releases/latest).

🛡️ **[NetSentinel](https://github.com/jamesccupps/NetSentinel)** Network monitor and intrusion detection for a Windows PC. Packet capture with process attribution, SNI and JA3/JA4 fingerprints from encrypted connections, Isolation Forest anomaly detection, beaconing detection, and rule-based detectors for scans, brute force, DNS tunnelling and exfiltration. Python — [download](https://github.com/jamesccupps/NetSentinel/releases/latest).

💡 **[Light Beam](https://github.com/jamesccupps/Light-Beam)** Self-hosted messenger and hub for your own devices: text and files of any size between them, phone notifications on your PCs, ring a lost phone, wake or remote-control a PC, and a private family chat. Runs on your own computer, and your devices reach it through Tailscale — no accounts, no third-party cloud. Node.js, with a web app and optional Windows and Android apps.

### Hardware

🖨️ **[CTP500 Print Server](https://github.com/jamesccupps/CTP500-Print-Server)** Your own app for the CTP500 Bluetooth thermal printer: a Raspberry Pi print server, a web app for any phone or computer, an instant camera on the Adafruit MEMENTO, lithophanes for a 3D printer, and an HTTP API for Home Assistant and scripts. No account, no cloud. Python.

🎹 **[MPK Macro Studio](https://github.com/jamesccupps/mpk-mini-iv-tools)** Turns an Akai MPK mini IV into a macro controller for Windows, and reads the keyboard's presets over a SysEx protocol reverse-engineered for this project and documented in [PROTOCOL.md](https://github.com/jamesccupps/mpk-mini-iv-tools/blob/main/PROTOCOL.md). Pure standard-library Python, Tkinter.

### Other projects

🐟 **[Synapse Reef](https://github.com/jamesccupps/Reef)** A neuroevolution lake in the browser. Six fish species, each thinking with its own small recurrent neural network, evolve and learn to forage, school, hunt, flee and breed in a lake with seasons, weather, dissolved oxygen, a nutrient cycle, plankton and plants. Click any fish to watch its brain fire live. Plain ES modules, nothing to build.

📊 **[Stock Oracle](https://github.com/jamesccupps/StockOracle)** Multi-signal stock prediction and monitoring for Windows: 39 data collectors, an ML ensemble and an optional Claude advisor in a tkinter app, plus a Bloomberg-style browser terminal (SEC filings, insiders, options, FRED macro, live quotes). A research tool, not financial advice.

🧪 **[FlavorForge](https://github.com/jamesccupps/FlavorForge)** Procedural cooking engine that builds recipes from molecular flavor pairing (326 ingredients, 82 aroma compounds), texture contrast and taste balance, with diet filtering. Tkinter GUI and CLI, pure Python stdlib, optional AI Chef via Ollama or Claude.

### Contact

📧 **<jamesccupps@proton.me>** — general questions, feedback, and security reports

🐛 **Bug reports and feature requests** — please open an issue on the relevant project

---

<p align="center">
  <a href="https://jamesccupps.github.io/">
    <code>C:\> start jamesccupps.github.io</code>
  </a>
</p>
