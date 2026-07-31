# 🤓 About Me:
I build web software for regulated industries, plus network security tooling in Go. Most of my work is a practice platform for cosmetic clinics, where the hard parts are Postgres row level security, audit trails that hold up when someone reads them properly, and keeping AI features well away from anything a prescriber signs.<br><br>
-> Currently working on **BaseClinical**, a clinic practice platform, and **tracehound**, a passive network sensor written in Go<br>
-> Currently learning JA4 TLS fingerprinting and flow analysis that survives encryption<br>
-> Looking to collaborate on open source security tooling, particularly detection engineering<br>
-> Looking for help with getting tracehound in front of people who run real networks<br>
-> Ask me about Postgres row level security, tamper evident audit logs, or shipping compliance heavy software as a team of one<br>
-> Also run a small homelab on Raspberry Pi, which is where I break things safely<br>
-> Fun fact: all of it on Windows, in PowerShell, on purpose.

## 🚀 What I'm building

| Project | What it is | Stack |
| --- | --- | --- |
| **[TraceHound](https://github.com/bader-a-tech/tracehound)** | Passive network sensor. Assembles bidirectional flows from a pcap or a live interface, fingerprints TLS clients with JA4, and maps seven detectors to MITRE ATT&CK: C2 beaconing, DNS tunnelling, port scans, host sweeps, exfiltration, new devices, rare TLS stacks. Every alert carries the numbers that produced it. One static binary, no cgo, no libpcap. | Go |
| **[BaseClinical](https://baseclinical.com.au)** | Practice platform for cosmetic clinics. Bookings, treatment plans, consent, quotes, campaigns, admin controlled feature access, tamper evident audit log. | Next.js, React, Supabase, Postgres, Cloudflare |
| **[Aldoseri.dev](https://aldoseri.dev)** | Portfolio with a terminal style interface, a scroll drawn git graph, and live CLI demos of my own products. | React 19, TanStack Start, Cloudflare Workers |
| **International Freight App** | Freight and quoting sites for multiple markets (100+ countries), with a customer portal and an ERP integration path. | HTML, CSS, JavaScript, Supabase |

## 📦 Scale the graph cannot see

Most of my work lives in private repos, so the cards below undercount it considerably.

- 376 commits and 113 versioned SQL migrations in BaseClinical, roughly 3.5 MB of TypeScript sitting on 780 KB of PL/pgSQL
- Row level security on every table, plus a hash chained audit log so tampering breaks the chain
- No ORM anywhere: hand written SQL, with `SECURITY DEFINER` functions where a policy cannot express the rule
- A hand written TLS ClientHello parser in tracehound, with GREASE stripping and fragmented handshake reassembly

# 🌐 Socials:
[![Website](https://img.shields.io/badge/aldoseri.dev-1F6FEB?style=for-the-badge&logo=safari&logoColor=white)](https://aldoseri.dev)

# 💻 Tech Stack:
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![Jellyfin](https://img.shields.io/badge/jellyfin-%23000B25.svg?style=for-the-badge&logo=Jellyfin&logoColor=00A4DC) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=for-the-badge&logo=playwright&logoColor=white) ![Vitest](https://img.shields.io/badge/-Vitest-252529?style=for-the-badge&logo=vitest&logoColor=FCC72B) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)

# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=baldoseri&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true&hide_rank=true&show_icons=true)<br/>
![](https://streak-stats.demolab.com/?user=baldoseri&theme=nightowl&hide_border=false)
