# Wang Kun

Beijing, China | Prefer opportunities in Beijing | Available immediately | Bachelor's-level education

Phone: +86 15801250949

Email: zimiao815@gmail.com

Target roles: Embedded Linux Engineer, Systems Platform Engineer, Wireless Engineer; also open to Embedded Systems Architect and Technical Lead positions.

## Professional Summary

- Embedded development experience since 2013, with a focus on embedded Linux and OpenWrt since 2015. Experience covers microcontrollers, board bring-up, platform adaptation, Linux C application development, and production support.
- Served as the core software lead for the AX3000 router, covering the full development lifecycle from development environment setup and hardware interface bring-up to boot and firmware upgrade design and mass-production delivery. Worked with hardware manufacturers and chipset vendors.
- Designed and developed Wi-Fi and ezMesh management software across Qualcomm and MediaTek platforms. Experienced in module design, cross-platform integration, complex troubleshooting, and technical collaboration, including technical leadership and coordination within small teams.
- Extensive hands-on experience in Linux system optimization and performance tuning, including memory management, swap and virtual memory, CPU scheduling, and I/O subsystems.

## Technical Skills (Optional Reading)

- **Systems and platforms**: Embedded Linux, OpenWrt, Qualcomm QSDK, U-Boot, Device Tree, eMMC partition planning, kernel configuration and footprint reduction, driver adaptation, cross-compilation, system integration, and OTA upgrades.
- **Applications and tools**: C, Shell, Lua, Linux system and network programming, GCC, GDB, Makefile, Git, and performance analysis tools.
- **Wireless networking**: IEEE 802.11, IEEE 1905, EasyMesh, and over-the-air packet capture analysis for connection, roaming, and forwarding issues.
- **Performance and hardware debugging**: Memory and performance analysis using perf, vmstat, and system logs; experience with schematics, PCB design, and board-level debugging.
- **AI-assisted coding**: Experience with a range of AI coding agents; currently use Codex as the primary tool.

## Professional Experience

### JD Technology | JD Cloud Wireless Router Product Department | Senior Embedded Software Engineer, P7

Aug 2021 - Aug 2026

**Embedded Systems Engineer / Wi-Fi Engineer**

#### Embedded Systems Engineering

- **OpenWrt platform development**: Responsible for U-Boot and the boot process, eMMC partition planning, Device Tree adaptation, kernel footprint reduction, package selection and development, fixes for open-source tools, and porting product applications. Participated in hardware and software validation against product specifications.
- **U-Boot dual-system recovery**: Designed and implemented an A/B firmware upgrade mechanism using U-Boot environment variables. Implemented boot count management, automatic tracking of boot failures, and automatic fallback to the backup system after repeated failures, improving OTA upgrade reliability and recovery in the field.
- **Device Tree adaptation**: Customized Device Trees and optimized system resource usage. Adjusted Wi-Fi device initialization order, optimized reserved memory layouts, and reduced memory allocated to unused radios to improve memory utilization.
- **Wi-Fi performance optimization**: Investigated Wi-Fi connection stability issues in IoT scenarios. Created monitor-mode interfaces and captured over-the-air 802.11 traffic with tcpdump to analyze abnormal beacon intervals and wireless noise levels. Adjusted CCA threshold parameters based on vendor documentation to improve connection stability in challenging radio environments.
- **Linux performance optimization**: Analyzed system performance issues, including a production incident involving sustained high CPU load. Used perf to identify hotspots, then vmstat and other tools to trace the load to I/O wait caused by excessive swapping. Analyzed Linux page swapping behavior and optimized memory usage, eliminating frequent swapping and restoring system performance. Received the JD Cloud H2 2023 Outstanding Problem-Solving Award for this work.
- **Customer issue troubleshooting**: Investigated and diagnosed Wi-Fi issues reported by end users. Used tcpdump, monitor mode, Wireshark, and Linux command-line tools to diagnose and validate fixes for IoT connection instability, abnormal Wi-Fi beacons, Mesh roaming failures, wireless performance issues, and Linux system performance problems. Received the Wireless Router Product Department Q3 2024 Outstanding Service Award for this work.

#### Wi-Fi Engineering

- **Wireless feature planning and development**: Responsible for Wi-Fi feature evolution and core feature development across the router product lineup. Contributed extensively to Wi-Fi 6/6E/7 protocol stack and driver adaptation, delivering Mesh networking, smart roaming with 802.11k/v/r, and unified SSIDs across frequency bands.
- **Wireless protocol and performance tuning**: Led RF parameter tuning and throughput optimization. Improved throughput and interference mitigation algorithms in environments with multiple interference sources, enhancing wireless communication quality under high client density.
- **Complex bug resolution and stability maintenance**: Investigated and fixed wireless-related crashes, unexpected disconnections, and roaming failures. Used Wireshark and other packet capture tools for over-the-air 802.11 protocol analysis, substantially improving wireless stability and connection success rates across the router lineup.

- **ezMesh unified networking platform: application architecture and core development**:
  - **ezMesh management daemon**: Developed a standalone ezMesh management process covering Mesh Controller and Agent management, Mesh state maintenance, network state synchronization, and application control logic. Centralized Mesh application state management and adapted the software across platforms.
  - **IEEE 1905 protocol extensions**: Worked with the chipset vendor's IEEE 1905 protocol stack. Extended the standard protocol with proprietary TLVs to implement Mesh heartbeats, network state synchronization, connectivity checks, proprietary Mesh controls, and custom application messaging while maintaining compatibility with the standard protocol.
  - **Mesh networking features**: Implemented push-button, mobile app, and web-based onboarding, along with cross-platform and mixed-brand Mesh networking. Supported unified Mesh functionality across Qualcomm and MediaTek platforms.
  - **China Unicom EasyMesh certification**: Participated in certification testing, including mixed-brand networking with Huawei optical network terminals, topology update validation, push-button onboarding of specified nodes, Mesh stability testing, 4K video roaming tests, and support for IPv6 testing. Helped complete product certification and delivery.
  - **Troubleshooting and maintenance**: Investigated complex Mesh issues and resolved compatibility problems.

#### AI Agent Development

- Contributed approximately 10 months of development to projects in another department, building scheduling, intent-routing, conversation suggestion, and AI investment research agents using LangChain and LangGraph.
- Used mem0 and memsearch for agent memory systems.
- Set up and integrated MCP servers.

### Beijing Maniu Technology Co., Ltd. | Embedded Software Engineer

Jun 2016 - Jul 2021

- Developed and maintained OpenWrt-based firmware across MT7620, QCA9531/QCA9563, IPQ4019, IPQ8064, and x86 platforms. Responsible for platform adaptation, firmware releases, remote upgrades, vulnerability fixes, and field issue resolution.
- Modified Device Trees and adapted and debugged Ethernet, Wi-Fi, and peripheral drivers, including support for 4G modules and SPI flash. Handled kernel configuration, package cross-compilation, dependencies, and compatibility across OpenWrt versions.
- Developed an AP management server and device-side communication software in Linux C, implementing Layer 2 discovery, TCP communication, configuration delivery, heartbeats, and online status management, integrated with configuration data stored in MySQL.
- Built hotspot authentication, allowlist/blocklist controls, and authentication reuse within the same venue using Wifidog. Contributed to nDPI protocol analysis, Wi-Fi probe functionality, configuration pages, and monitoring scripts, and provided technical training to colleagues.

### Early Embedded Development Experience

**Yantai Lanyang Electronic Technology Co., Ltd. | Linux Software and Hardware Engineer | Mar 2015 - Jun 2016**

- Began working with embedded Linux and OpenWrt. Participated in component selection, schematic and PCB design, soldering, and debugging for an MT7620N expansion board. Developed Linux C programs for serial GPS data transmission, reception, and parsing, and validated peripheral functionality.

**Shanghai Boyilai Electric Co., Ltd., Yantai R&D Center | Microcontroller Development Engineer | Jul 2013 - Feb 2015**

- Contributed to MSP430/PIC32-based industrial control equipment, implementing LCD and button interfaces and GSM module hardware and software, and performing integration debugging. Independently developed a PIC12-based undervoltage protector, with work covering voltage acquisition, protection control, watchdog functionality, and complete device validation.

## Education

- China University of Petroleum (East China) | Computer Science and Technology, undergraduate program (correspondence study) | Sep 2015 - Jul 2017
- Haidu College, Qingdao Agricultural University | Electronic Information Engineering Technology, three-year college diploma (full-time, national unified admissions) | Sep 2008 - Jul 2011

## Honors and Patents

- JD Cloud H2 2023 Outstanding Problem-Solving Award, for Linux system optimization.
- Wireless Router Product Department Q3 2024 Outstanding Service Award, for customer service.
- Wireless Router Product Department Q1 2022 Energy Star Award, for teamwork.
- Named as an inventor on three EasyMesh-related patent applications, currently under examination by the China National Intellectual Property Administration.

---

Detailed resume, project descriptions, and award photos: https://github.com/zimiao815/resume
