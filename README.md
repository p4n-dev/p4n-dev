<div align="center">

# p4n - *formerly known as:* (`Pandora`)

**Full-Stack Game & Web Developer · Security Researcher · Reverse Engineer**

Building multiplayer virtual worlds, malware analysis platforms, and real-time endpoint defense tooling.

[![Website](https://img.shields.io/badge/p4n.dev-0d1117?style=for-the-badge&logo=cloudflare&logoColor=38bdf8&labelColor=161b22)](https://p4n.dev)
[![xThreat](https://img.shields.io/badge/xthreat.rip-0d1117?style=for-the-badge&logo=virustotal&logoColor=f43f5e&labelColor=161b22)](https://xthreat.rip)
[![Spotify](https://img.shields.io/badge/@Pandora-0d1117?style=for-the-badge&logo=spotify&logoColor=1ED760&labelColor=161b22)](https://open.spotify.com/user/vmsc8ydc9lv1zid5hmi0eutay)
[![GitHub](https://img.shields.io/badge/p4n--dev-0d1117?style=for-the-badge&logo=github&logoColor=e6edf3&labelColor=161b22)](https://github.com/p4n-dev)

</div>

---

### `01 // OVERVIEW`

I build custom online multiplayer games, full-stack web backends, and offensive/defensive security tooling. My work ranges from running a custom **Habbo Hotel Retro (`Sowa`)** on **Laravel, PHP, Redis, MySQL, and IIS** to building malware sandbox & C2 extraction infrastructure at **`xThreat`**.

- **Game Server & Web Architecture:** Custom Habbo Hotel retro development (`Sowa`), Nitro/HTML5 client & asset pipelines, real-time Redis state/caching, MySQL persistence, IIS production hosting, and bi-directional Discord bot integrations.
- **Security & Reverse Engineering:** Static binary unpacking (PE32/PE32+, JAR bytecode), automated malware config & C2 extraction, and real-time Windows anti-malware watchdogs.
- **Languages & Tooling:** `PHP` · `TypeScript / JavaScript` · `Python` · `C++` · `Lua` · `SQL` · `IDA Pro`

---

### `02 // FEATURED PROJECTS`

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🏨 Sowa — Habbo Hotel Retro & Discord Ecosystem</h4>
      <p>Custom multiplayer Habbo Hotel retro virtual world with a bespoke web CMS, real-time emulator synchronization, custom economy/assets, and an integrated Discord bot.</p>
      <p>
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
        <img src="https://img.shields.io/badge/IIS-0078D4?style=flat-square&logo=windows&logoColor=white" alt="IIS" />
        <img src="https://img.shields.io/badge/Discord_Bot-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord Bot" />
      </p>
      <ul>
        <li>Full-stack CMS, player economy, and live hotel management built on <strong>Laravel & PHP</strong></li>
        <li><strong>Redis</strong> caching & pub/sub bridging real-time in-game events, <strong>MySQL</strong> player/room data, and the live <strong>Discord Bot</strong></li>
        <li>Hosted and tuned in production on Windows Server with <strong>Microsoft IIS</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ <a href="https://xthreat.rip">xThreat (xthreat.rip)</a> — Malware Sandbox & Threat Intel</h4>
      <p>Multi-engine malware detonation, static binary inspection, and automated C2 configuration extraction workbench built for threat researchers.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Cloudflare_Workers_&_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
        <img src="https://img.shields.io/badge/Threat_Intel-f43f5e?style=flat-square" alt="Threat Intel" />
      </p>
      <ul>
        <li>Instant PE32/PE32+ section & import table analyzer, Shannon entropy calculation, and JLab JAR bytecode inspector</li>
        <li>Automated C2 & family config extraction alongside VirusTotal v3, Hatching Triage, and Falcon Sandbox orchestration</li>
        <li>Real-time Telegram threat feed alerts and IOC correlation engine</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔒 <a href="https://github.com/p4n-dev/LuckywareShieldUltra">Luckyware Shield Ultra</a> — Endpoint Watchdog</h4>
      <p>Real-time Windows security tool and CLI daemon designed to detect and neutralize supply-chain malware targeting developers and gamers.</p>
      <p>
        <img src="https://img.shields.io/badge/Python_3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Windows_Internals-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
        <img src="https://img.shields.io/badge/MIT_License-22c55e?style=flat-square" alt="MIT" />
      </p>
      <ul>
        <li>Scans Visual Studio projects (<code>.vcxproj</code>, <code>.props</code>, <code>.targets</code>) and Windows SDK paths for XOR-obfuscated infectors</li>
        <li>Blocks active C2 domains via local <code>hosts</code> & Windows Firewall rules (synced with <a href="https://github.com/p4n-dev/CG-Threat-Intelligence">CG-Threat-Intelligence</a> C2 link lists)</li>
        <li>Strips Registry persistence and locks Discord & Chromium token stores against exfiltration</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ Open-Source Utilities & Game Projects</h4>
      <p>Multiplayer browser games, C2 link feeds, and low-level Windows system utilities.</p>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS" />
        <img src="https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white" alt="Lua" />
      </p>
      <ul>
        <li><strong><a href="https://zeustanks.online">Zeus Tanks</a>:</strong> Real-time online tank battle project</li>
        <li><strong><a href="https://github.com/p4n-dev/CG-Threat-Intelligence">CG-Threat-Intelligence</a>:</strong> Repository of tracked malicious C2 links and domains</li>
        <li><strong>Windows Utilities:</strong> <a href="https://github.com/p4n-dev/Touchscreen-disabler">Touchscreen-disabler</a> (C++) & <a href="https://github.com/p4n-dev/NoMoreVanguard">NoMoreVanguard</a></li>
      </ul>
    </td>
  </tr>
</table>

---

### `03 // TECHNICAL STACK`

```text
BACKEND & INFRA   ::  Laravel · PHP 8 · Redis · MySQL · Microsoft IIS · Node.js · Cloudflare Workers & D1
GAME & BOTS       ::  Habbo Retro Emulation · Nitro Assets · Discord Bot API · Telegram Bot API · Lua
FRONTEND & WEB    ::  Next.js · React · TypeScript · Tailwind CSS · REST APIs · WebSockets
SECURITY & RE     ::  IDA Pro / IDAPython · PE32/PE32+ Internals · C2 Config Extraction · Python Watchdogs
```

<p align="left">
  <img src="https://img.shields.io/badge/Laravel-161b22?style=flat-square&logo=laravel&logoColor=FF2D20" alt="Laravel" />
  <img src="https://img.shields.io/badge/PHP-161b22?style=flat-square&logo=php&logoColor=777BB4" alt="PHP" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
  <img src="https://img.shields.io/badge/MySQL-161b22?style=flat-square&logo=mysql&logoColor=4479A1" alt="MySQL" />
  <img src="https://img.shields.io/badge/Windows_Server_/_IIS-161b22?style=flat-square&logo=windows&logoColor=0078D4" alt="IIS" />
  <img src="https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Next.js-161b22?style=flat-square&logo=nextdotjs&logoColor=ffffff" alt="Next.js" />
  <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/C++-161b22?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++" />
  <img src="https://img.shields.io/badge/Lua-161b22?style=flat-square&logo=lua&logoColor=2C2D72" alt="Lua" />
  <img src="https://img.shields.io/badge/Cloudflare-161b22?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Discord-161b22?style=flat-square&logo=discord&logoColor=5865F2" alt="Discord" />
</p>

---

<div align="center">
  <sub>🍌 <i>Don't forget to get some Potassium</i> · <a href="https://p4n.dev">p4n.dev</a></sub>
</div>
