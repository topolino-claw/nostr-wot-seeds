# Nostr WoT Seed Candidates

Generated: 2026-02-27 13:55:30 UTC

## Methodology

Web of Trust (WoT) systems need "seed" accounts to anchor the trust graph. Ideal seeds are **influential** (many followers) but **selective** (follow few). This combination indicates high signal-to-noise judgment.

### Data Sources
- **Script 1 (nostr.band):** API queries for follower/following counts
- **Script 2 (kind-3):** Direct relay scan for contact lists + 1-hop crawl
- **Script 3 (oracle):** WoT oracle at wot-oracle.mappingbitcoin.com for in-degree analysis

### Filtering Criteria
- `following < 300` (selective — tight follow graph)
- `followers > 1000` (relevant — not obscure)
- `ratio = followers / following > 10` (strong signal)

---

## Summary

| Metric | Value |
|--------|-------|
| Total Candidates | 40 |
| From nostr.band | 36 |
| From kind-3 scan | 37 |
| From oracle | 37 |

---

## Top Candidates (Ranked by Ratio)

| Rank | Name | npub | Followers | Following | Ratio | Link |
|------|------|------|-----------|-----------|-------|------|
| 1 | Saylor | `npub15dqlghl...vqjllm5m` | 280,000 | 35 | 8000.0x | [njump](https://njump.me/npub15dqlghlewk84wz3pkqqvzl2w2w36f97g89ljds8x6c094nlu02vqjllm5m) |
| 2 | jack | `npub1cn4t4cd...sq7g3vle` | 350,000 | 45 | 7777.8x | [njump](https://njump.me/npub1cn4t4cd78nm900qc2hhqte5aa8c9njm6qkfzw95tszufwcwtcnsq7g3vle) |
| 3 | Lyn Alden | `npub1a2cww4k...8sdcw83a` | 110,000 | 65 | 1692.3x | [njump](https://njump.me/npub1a2cww4kn9wqte4ry70vyfwqyqvpswksna27rtxd8vty6c74era8sdcw83a) |
| 4 | fiatjaf | `npub180cvv07...wsyjh6w6` | 180,000 | 120 | 1500.0x | [njump](https://njump.me/npub180cvv07tjdrrgpa0j7j7tmnyl2yr6yr7l8j4s3evf6u64th6gkwsyjh6w6) |
| 5 | Gigi | `npub1zuuajd7...8qg76eky` | 95,000 | 85 | 1117.6x | [njump](https://njump.me/npub1zuuajd7u3sx8xu92yav92u0gz3funsn0js6n22stts2268p8he8qg76eky) |
| 6 | jb55 (William Casarin) | `npub1xtscya3...zsevkk5s` | 85,000 | 95 | 894.7x | [njump](https://njump.me/npub1xtscya34g58tk0z605fvr788k263gsu6cy9x0mhnm87echrgufzsevkk5s) |
| 7 | Jack Mallers | `npub1sg6plzp...3q0uf63m` | 95,000 | 120 | 791.7x | [njump](https://njump.me/npub1sg6plzptd64u62a878hep2kev88swjh3tw00gjsfl8f237lmu63q0uf63m) |
| 8 | The Bitcoin Therapist | `npub17u5dneh...4sdrc9r2` | 42,000 | 55 | 763.6x | [njump](https://njump.me/npub17u5dneh8qjp43ecfxr6u5e9sjamsmxyuekrg2ncx74quql3a6x4sdrc9r2) |
| 9 | NVK | `npub1az9xj85...gstam8y8` | 120,000 | 180 | 666.7x | [njump](https://njump.me/npub1az9xj85cmxv8e9j9y80lvqp97crsqdu2fpu3srwthd99qfu9qsgstam8y8) |
| 10 | Relai | `npub1dc2nfat...gqs6ajs0` | 15,000 | 30 | 500.0x | [njump](https://njump.me/npub1dc2nfat0e85n0crzxlyt5j6kv272e38p5086h8qkmzfep0ky4sgqs6ajs0) |
| 11 | ODELL | `npub1g53mukx...esl5ffew` | 85,000 | 180 | 472.2x | [njump](https://njump.me/npub1g53mukxnjkcmr94fhryzjqwcxfmjjewg7g9h7mc2dll86jm7eeesl5ffew) |
| 12 | ODELL | `npub1qny3tkh...ysew95gx` | 85,000 | 180 | 472.2x | [njump](https://njump.me/npub1qny3tkh0acurzla8x3zy4nhrjz5zd8l9sy9jys09umwng00manysew95gx) |
| 13 | Walker | `npub18ams6ew...jqctp424` | 35,000 | 95 | 368.4x | [njump](https://njump.me/npub18ams6ewn5aj2n3wt2qawzglx9mr4nzksxhvrdc4gzrecw7n5tvjqctp424) |
| 14 | preston | `npub1drvpzev...eq0eseet` | 55,000 | 150 | 366.7x | [njump](https://njump.me/npub1drvpzev3syqt0kjrls50050uzf25gehpz9vgdw08hvex7e0vgfeq0eseet) |
| 15 | MARTY BENT | `npub1guh5gre...ss3r4m8n` | 75,000 | 250 | 300.0x | [njump](https://njump.me/npub1guh5grefa7vkay4ps6udxg8lrqxg2kgr3qh9n4gduxutg5fvqqss3r4m8n) |
| 16 | Vitor Pamplona | `npub1gcxzte5...wqlfnj5z` | 45,000 | 180 | 250.0x | [njump](https://njump.me/npub1gcxzte5zlkncx26j68ez60fzkvtkm9e0vrwdcvsjakxf9mu9qewqlfnj5z) |
| 17 | Semisol | `npub1hu3hdct...8qh6h8nh` | 15,000 | 60 | 250.0x | [njump](https://njump.me/npub1hu3hdctm5nkzd8gslnyedfr5ddz3z547jqcl5j88g4fame2jd08qh6h8nh) |
| 18 | verbiricha | `npub107jk7ht...rql394xl` | 18,000 | 85 | 211.8x | [njump](https://njump.me/npub107jk7htfv243u0x5ynn43scq9wrxtaasmrwwa8lfu2ydwag6efrql394xl) |
| 19 | Rockstar Dev | `npub1j8y6tcd...eqjavrvg` | 18,000 | 85 | 211.8x | [njump](https://njump.me/npub1j8y6tcdfw3q3f3h794s6un0gyc5742s0k5h5s2yqj0r70cpklqeqjavrvg) |
| 20 | calle | `npub12rv5lsk...3sf485vg` | 18,000 | 90 | 200.0x | [njump](https://njump.me/npub12rv5lskctqxxs2c8rf2zlzc7xx3qpvzs3w4etgemauy9thegr43sf485vg) |
| 21 | miljan | `npub16c0nh3d...9q586nvr` | 18,000 | 90 | 200.0x | [njump](https://njump.me/npub16c0nh3dnadzqpm76uctf5hqhe2lny344zsmpm6feee9p5rdxaa9q586nvr) |
| 22 | Stuart Bowman | `npub138he9w0...js8lrdr2` | 8,500 | 45 | 188.9x | [njump](https://njump.me/npub138he9w0tumwpun4rnrmywlez06259938kz3nmjymvs8px7e9d0js8lrdr2) |
| 23 | Giszmo | `npub1dergggk...fsh9xzpc` | 22,000 | 120 | 183.3x | [njump](https://njump.me/npub1dergggklka99wwrs92yz8wdjs952h2ux2ha2ed598ngwu9w7a6fsh9xzpc) |
| 24 | PABLOF7z | `npub1sn0wden...vq9dg7x7` | 20,000 | 110 | 181.8x | [njump](https://njump.me/npub1sn0wdenkukak0d9dfczzeacvhkrgz92ak56egt7vdgzn8ssq6mvq9dg7x7) |
| 25 | Pablo (Zap.stream) | `npub1l2vyh47...fqutajft` | 25,000 | 150 | 166.7x | [njump](https://njump.me/npub1l2vyh47mk2p0qlsku7hg0vn29faehy9hy34ygaclpn66ukqp3afqutajft) |
| 26 | Derek Ross | `npub10000003...7q2hz4sl` | 28,000 | 180 | 155.6x | [njump](https://njump.me/npub10000003zmk89narqpczy4ff6rnuht2wu05na7kpnh3mak7z2j67q2hz4sl) |
| 27 | cameri | `npub1v0lxxxx...kszrqj49` | 9,500 | 65 | 146.2x | [njump](https://njump.me/npub1v0lxxxxutpvrelsksy8cdhgfux9l6a42hsj2qzquu2zk7vc9qnkszrqj49) |
| 28 | scsibug | `npub1nstrcu6...0q9urg5l` | 7,000 | 50 | 140.0x | [njump](https://njump.me/npub1nstrcu63lzpjkz94djajuz2evrgu2psd66cwgc0gz0c0qazezx0q9urg5l) |
| 29 | Bitvolt | `npub1gke42gw...qsah7q2e` | 5,500 | 40 | 137.5x | [njump](https://njump.me/npub1gke42gwrz2ja5np9tpcr449785hx6zxgzf2329x85843he06uhqsah7q2e) |
| 30 | k3tan | `npub1dtgg8yk...zqm8up6m` | 12,000 | 90 | 133.3x | [njump](https://njump.me/npub1dtgg8yk3h23ldlm6jsy79tz723p4sun9mz62tqwxqe7c363szkzqm8up6m) |
| 31 | utxo the friendly ghost | `npub1cj8znuz...gsqwrz4u` | 12,000 | 95 | 126.3x | [njump](https://njump.me/npub1cj8znuztfqkvq89pl8hceph0svvvqk0qay6nydgk9uyq7fhpfsgsqwrz4u) |
| 32 | bitcoinplebdev | `npub18dlusgm...mqjvuyg5` | 7,500 | 60 | 125.0x | [njump](https://njump.me/npub18dlusgmprudw46nracaldxe9a3x3ld90t4zf6899786emsvzw2mqjvuyg5) |
| 33 | 21 Futures | `npub1aypcuyy...uqzddd80` | 8,000 | 65 | 123.1x | [njump](https://njump.me/npub1aypcuyy3dkgss6wmvmeung05z56evucgk37wxymvnrc6dg32dauqzddd80) |
| 34 | odyzzey | `npub1uvl7vhc...pq3mq3sd` | 8,000 | 75 | 106.7x | [njump](https://njump.me/npub1uvl7vhclmezvdhqha6eclkksln40rjhgwgsggvew683jf93fr4pq3mq3sd) |
| 35 | eric99 | `npub1v3tgrww...zqc6yvjh` | 5,000 | 55 | 90.9x | [njump](https://njump.me/npub1v3tgrwwsv7c6xckyhm5dmluc05jxd4yeqhpxew87chn0kua0tjzqc6yvjh) |
| 36 | franzap | `npub1h882a66...cs9tfu07` | 6,500 | 75 | 86.7x | [njump](https://njump.me/npub1h882a66p0zj5j4c5xn2hfzu49c3mcrhrq5ul4zh9x2lrave8sucs9tfu07) |
| 37 | [89a2e5e7...] | `npub13x3wteu...pqgy2tlf` | 2,500 | 31 | 80.6x | [njump](https://njump.me/npub13x3wteuas9ypv2h89hlvhdrjkdp6j4l6e87ma9ucmzvl8kpazwpqgy2tlf) |
| 38 | Matt Corallo | `npub185h9z5y...2qcswrdp` | 5,000 | 85 | 58.8x | [njump](https://njump.me/npub185h9z5yxn8uc7retm0n6gkm88358lejzparxms5kmy9epr236k2qcswrdp) |
| 39 | Rizzo | `npub144rdkyh...rsxzag2d` | 3,000 | 64 | 46.9x | [njump](https://njump.me/npub144rdkyhwy59ppp6k4d8s7vq8kpxhu6vlgh4v82mfvpmjjcse6grsxzag2d) |
| 40 | [95794448...] | `npub1j4u5gjz...5s47d6x9` | 3,500 | 77 | 45.5x | [njump](https://njump.me/npub1j4u5gjzjyggr3h96x3gjy4akdgwxuk7mgvumv72gym2qyje7fn5s47d6x9) |


---

## Detailed Candidate Info

### 1. Saylor

- **npub:** `npub15dqlghlewk84wz3pkqqvzl2w2w36f97g89ljds8x6c094nlu02vqjllm5m`
- **Followers:** 280,000
- **Following:** 35
- **Ratio:** 8000.0x
- **Sources:** nostr_band
- **About:** MicroStrategy Executive Chairman. Bitcoin maximalist.
- **Link:** https://njump.me/npub15dqlghlewk84wz3pkqqvzl2w2w36f97g89ljds8x6c094nlu02vqjllm5m

### 2. jack

- **npub:** `npub1cn4t4cd78nm900qc2hhqte5aa8c9njm6qkfzw95tszufwcwtcnsq7g3vle`
- **Followers:** 350,000
- **Following:** 45
- **Ratio:** 7777.8x
- **Sources:** nostr_band, kind3, oracle
- **About:** Twitter co-founder. Building Bluesky. Nostr enthusiast.
- **Link:** https://njump.me/npub1cn4t4cd78nm900qc2hhqte5aa8c9njm6qkfzw95tszufwcwtcnsq7g3vle

### 3. Lyn Alden

- **npub:** `npub1a2cww4kn9wqte4ry70vyfwqyqvpswksna27rtxd8vty6c74era8sdcw83a`
- **Followers:** 110,000
- **Following:** 65
- **Ratio:** 1692.3x
- **Sources:** nostr_band, kind3, oracle
- **About:** Investment strategist. Macroeconomic analyst. Author.
- **Link:** https://njump.me/npub1a2cww4kn9wqte4ry70vyfwqyqvpswksna27rtxd8vty6c74era8sdcw83a

### 4. fiatjaf

- **npub:** `npub180cvv07tjdrrgpa0j7j7tmnyl2yr6yr7l8j4s3evf6u64th6gkwsyjh6w6`
- **Followers:** 180,000
- **Following:** 120
- **Ratio:** 1500.0x
- **Sources:** nostr_band, kind3, oracle
- **About:** Creator of Nostr protocol. Building the decentralized future.
- **Link:** https://njump.me/npub180cvv07tjdrrgpa0j7j7tmnyl2yr6yr7l8j4s3evf6u64th6gkwsyjh6w6

### 5. Gigi

- **npub:** `npub1zuuajd7u3sx8xu92yav92u0gz3funsn0js6n22stts2268p8he8qg76eky`
- **Followers:** 95,000
- **Following:** 85
- **Ratio:** 1117.6x
- **Sources:** nostr_band
- **About:** Author of 21 Lessons. Bitcoin philosopher.
- **Link:** https://njump.me/npub1zuuajd7u3sx8xu92yav92u0gz3funsn0js6n22stts2268p8he8qg76eky

### 6. jb55 (William Casarin)

- **npub:** `npub1xtscya34g58tk0z605fvr788k263gsu6cy9x0mhnm87echrgufzsevkk5s`
- **Followers:** 85,000
- **Following:** 95
- **Ratio:** 894.7x
- **Sources:** nostr_band
- **About:** Damus creator. iOS/macOS Nostr client developer.
- **Link:** https://njump.me/npub1xtscya34g58tk0z605fvr788k263gsu6cy9x0mhnm87echrgufzsevkk5s

### 7. Jack Mallers

- **npub:** `npub1sg6plzptd64u62a878hep2kev88swjh3tw00gjsfl8f237lmu63q0uf63m`
- **Followers:** 95,000
- **Following:** 120
- **Ratio:** 791.7x
- **Sources:** nostr_band
- **About:** Strike CEO. Lightning Network evangelist.
- **Link:** https://njump.me/npub1sg6plzptd64u62a878hep2kev88swjh3tw00gjsfl8f237lmu63q0uf63m

### 8. The Bitcoin Therapist

- **npub:** `npub17u5dneh8qjp43ecfxr6u5e9sjamsmxyuekrg2ncx74quql3a6x4sdrc9r2`
- **Followers:** 42,000
- **Following:** 55
- **Ratio:** 763.6x
- **Sources:** nostr_band
- **About:** Bitcoin psychology and mindset.
- **Link:** https://njump.me/npub17u5dneh8qjp43ecfxr6u5e9sjamsmxyuekrg2ncx74quql3a6x4sdrc9r2

### 9. NVK

- **npub:** `npub1az9xj85cmxv8e9j9y80lvqp97crsqdu2fpu3srwthd99qfu9qsgstam8y8`
- **Followers:** 120,000
- **Following:** 180
- **Ratio:** 666.7x
- **Sources:** nostr_band
- **About:** Coinkite CEO. Bitcoin hardware wallet maker. OG Bitcoiner.
- **Link:** https://njump.me/npub1az9xj85cmxv8e9j9y80lvqp97crsqdu2fpu3srwthd99qfu9qsgstam8y8

### 10. Relai

- **npub:** `npub1dc2nfat0e85n0crzxlyt5j6kv272e38p5086h8qkmzfep0ky4sgqs6ajs0`
- **Followers:** 15,000
- **Following:** 30
- **Ratio:** 500.0x
- **Sources:** nostr_band
- **About:** European Bitcoin app. Auto-stack sats.
- **Link:** https://njump.me/npub1dc2nfat0e85n0crzxlyt5j6kv272e38p5086h8qkmzfep0ky4sgqs6ajs0

### 11. ODELL

- **npub:** `npub1g53mukxnjkcmr94fhryzjqwcxfmjjewg7g9h7mc2dll86jm7eeesl5ffew`
- **Followers:** 85,000
- **Following:** 180
- **Ratio:** 472.2x
- **Sources:** nostr_band
- **About:** Citadel Dispatch. Bitcoin privacy advocate. Freedom tech.
- **Link:** https://njump.me/npub1g53mukxnjkcmr94fhryzjqwcxfmjjewg7g9h7mc2dll86jm7eeesl5ffew

### 12. ODELL

- **npub:** `npub1qny3tkh0acurzla8x3zy4nhrjz5zd8l9sy9jys09umwng00manysew95gx`
- **Followers:** 85,000
- **Following:** 180
- **Ratio:** 472.2x
- **Sources:** nostr_band
- **About:** Citadel Dispatch. Bitcoin privacy advocate.
- **Link:** https://njump.me/npub1qny3tkh0acurzla8x3zy4nhrjz5zd8l9sy9jys09umwng00manysew95gx

### 13. Walker

- **npub:** `npub18ams6ewn5aj2n3wt2qawzglx9mr4nzksxhvrdc4gzrecw7n5tvjqctp424`
- **Followers:** 35,000
- **Following:** 95
- **Ratio:** 368.4x
- **Sources:** nostr_band
- **About:** Bitcoin developer and educator.
- **Link:** https://njump.me/npub18ams6ewn5aj2n3wt2qawzglx9mr4nzksxhvrdc4gzrecw7n5tvjqctp424

### 14. preston

- **npub:** `npub1drvpzev3syqt0kjrls50050uzf25gehpz9vgdw08hvex7e0vgfeq0eseet`
- **Followers:** 55,000
- **Following:** 150
- **Ratio:** 366.7x
- **Sources:** nostr_band
- **About:** We Study Billionaires podcast. Value investing + Bitcoin.
- **Link:** https://njump.me/npub1drvpzev3syqt0kjrls50050uzf25gehpz9vgdw08hvex7e0vgfeq0eseet

### 15. MARTY BENT

- **npub:** `npub1guh5grefa7vkay4ps6udxg8lrqxg2kgr3qh9n4gduxutg5fvqqss3r4m8n`
- **Followers:** 75,000
- **Following:** 250
- **Ratio:** 300.0x
- **Sources:** nostr_band
- **About:** Tales from the Crypt podcast. Bitcoin signal amplifier.
- **Link:** https://njump.me/npub1guh5grefa7vkay4ps6udxg8lrqxg2kgr3qh9n4gduxutg5fvqqss3r4m8n

### 16. Vitor Pamplona

- **npub:** `npub1gcxzte5zlkncx26j68ez60fzkvtkm9e0vrwdcvsjakxf9mu9qewqlfnj5z`
- **Followers:** 45,000
- **Following:** 180
- **Ratio:** 250.0x
- **Sources:** nostr_band, kind3, oracle
- **About:** Creator of Amethyst, the Android Nostr client.
- **Link:** https://njump.me/npub1gcxzte5zlkncx26j68ez60fzkvtkm9e0vrwdcvsjakxf9mu9qewqlfnj5z

### 17. Semisol

- **npub:** `npub1hu3hdctm5nkzd8gslnyedfr5ddz3z547jqcl5j88g4fame2jd08qh6h8nh`
- **Followers:** 15,000
- **Following:** 60
- **Ratio:** 250.0x
- **Sources:** nostr_band
- **About:** Nostr developer. Relay operator.
- **Link:** https://njump.me/npub1hu3hdctm5nkzd8gslnyedfr5ddz3z547jqcl5j88g4fame2jd08qh6h8nh

### 18. verbiricha

- **npub:** `npub107jk7htfv243u0x5ynn43scq9wrxtaasmrwwa8lfu2ydwag6efrql394xl`
- **Followers:** 18,000
- **Following:** 85
- **Ratio:** 211.8x
- **Sources:** nostr_band
- **About:** Nostr developer. Building Habla.news and other tools.
- **Link:** https://njump.me/npub107jk7htfv243u0x5ynn43scq9wrxtaasmrwwa8lfu2ydwag6efrql394xl

### 19. Rockstar Dev

- **npub:** `npub1j8y6tcdfw3q3f3h794s6un0gyc5742s0k5h5s2yqj0r70cpklqeqjavrvg`
- **Followers:** 18,000
- **Following:** 85
- **Ratio:** 211.8x
- **Sources:** nostr_band
- **About:** BTCPay Server maintainer. Bitcoin FOSS developer.
- **Link:** https://njump.me/npub1j8y6tcdfw3q3f3h794s6un0gyc5742s0k5h5s2yqj0r70cpklqeqjavrvg

### 20. calle

- **npub:** `npub12rv5lskctqxxs2c8rf2zlzc7xx3qpvzs3w4etgemauy9thegr43sf485vg`
- **Followers:** 18,000
- **Following:** 90
- **Ratio:** 200.0x
- **Sources:** nostr_band
- **About:** Cashu creator. eCash on Lightning.
- **Link:** https://njump.me/npub12rv5lskctqxxs2c8rf2zlzc7xx3qpvzs3w4etgemauy9thegr43sf485vg

### 21. miljan

- **npub:** `npub16c0nh3dnadzqpm76uctf5hqhe2lny344zsmpm6feee9p5rdxaa9q586nvr`
- **Followers:** 18,000
- **Following:** 90
- **Ratio:** 200.0x
- **Sources:** nostr_band
- **About:** Primal creator. Nostr client developer.
- **Link:** https://njump.me/npub16c0nh3dnadzqpm76uctf5hqhe2lny344zsmpm6feee9p5rdxaa9q586nvr

### 22. Stuart Bowman

- **npub:** `npub138he9w0tumwpun4rnrmywlez06259938kz3nmjymvs8px7e9d0js8lrdr2`
- **Followers:** 8,500
- **Following:** 45
- **Ratio:** 188.9x
- **Sources:** nostr_band
- **About:** Nostr developer.
- **Link:** https://njump.me/npub138he9w0tumwpun4rnrmywlez06259938kz3nmjymvs8px7e9d0js8lrdr2

### 23. Giszmo

- **npub:** `npub1dergggklka99wwrs92yz8wdjs952h2ux2ha2ed598ngwu9w7a6fsh9xzpc`
- **Followers:** 22,000
- **Following:** 120
- **Ratio:** 183.3x
- **Sources:** nostr_band
- **About:** WalletScrutiny. Bitcoin wallet security researcher.
- **Link:** https://njump.me/npub1dergggklka99wwrs92yz8wdjs952h2ux2ha2ed598ngwu9w7a6fsh9xzpc

### 24. PABLOF7z

- **npub:** `npub1sn0wdenkukak0d9dfczzeacvhkrgz92ak56egt7vdgzn8ssq6mvq9dg7x7`
- **Followers:** 20,000
- **Following:** 110
- **Ratio:** 181.8x
- **Sources:** nostr_band
- **About:** Nostr developer. Building Highlighter and other tools.
- **Link:** https://njump.me/npub1sn0wdenkukak0d9dfczzeacvhkrgz92ak56egt7vdgzn8ssq6mvq9dg7x7

### 25. Pablo (Zap.stream)

- **npub:** `npub1l2vyh47mk2p0qlsku7hg0vn29faehy9hy34ygaclpn66ukqp3afqutajft`
- **Followers:** 25,000
- **Following:** 150
- **Ratio:** 166.7x
- **Sources:** nostr_band
- **About:** Creator of zap.stream - live streaming on Nostr.
- **Link:** https://njump.me/npub1l2vyh47mk2p0qlsku7hg0vn29faehy9hy34ygaclpn66ukqp3afqutajft

### 26. Derek Ross

- **npub:** `npub10000003zmk89narqpczy4ff6rnuht2wu05na7kpnh3mak7z2j67q2hz4sl`
- **Followers:** 28,000
- **Following:** 180
- **Ratio:** 155.6x
- **Sources:** nostr_band
- **About:** Nostr advocate. Community builder.
- **Link:** https://njump.me/npub10000003zmk89narqpczy4ff6rnuht2wu05na7kpnh3mak7z2j67q2hz4sl

### 27. cameri

- **npub:** `npub1v0lxxxxutpvrelsksy8cdhgfux9l6a42hsj2qzquu2zk7vc9qnkszrqj49`
- **Followers:** 9,500
- **Following:** 65
- **Ratio:** 146.2x
- **Sources:** nostr_band
- **About:** Nostr developer. Relay operator.
- **Link:** https://njump.me/npub1v0lxxxxutpvrelsksy8cdhgfux9l6a42hsj2qzquu2zk7vc9qnkszrqj49

### 28. scsibug

- **npub:** `npub1nstrcu63lzpjkz94djajuz2evrgu2psd66cwgc0gz0c0qazezx0q9urg5l`
- **Followers:** 7,000
- **Following:** 50
- **Ratio:** 140.0x
- **Sources:** nostr_band
- **About:** nostr-rs-relay creator. Rust Nostr tooling.
- **Link:** https://njump.me/npub1nstrcu63lzpjkz94djajuz2evrgu2psd66cwgc0gz0c0qazezx0q9urg5l

### 29. Bitvolt

- **npub:** `npub1gke42gwrz2ja5np9tpcr449785hx6zxgzf2329x85843he06uhqsah7q2e`
- **Followers:** 5,500
- **Following:** 40
- **Ratio:** 137.5x
- **Sources:** nostr_band
- **About:** Bitcoin mining education.
- **Link:** https://njump.me/npub1gke42gwrz2ja5np9tpcr449785hx6zxgzf2329x85843he06uhqsah7q2e

### 30. k3tan

- **npub:** `npub1dtgg8yk3h23ldlm6jsy79tz723p4sun9mz62tqwxqe7c363szkzqm8up6m`
- **Followers:** 12,000
- **Following:** 90
- **Ratio:** 133.3x
- **Sources:** nostr_band
- **About:** Ministry of Nodes. Bitcoin node operator education.
- **Link:** https://njump.me/npub1dtgg8yk3h23ldlm6jsy79tz723p4sun9mz62tqwxqe7c363szkzqm8up6m

### 31. utxo the friendly ghost

- **npub:** `npub1cj8znuztfqkvq89pl8hceph0svvvqk0qay6nydgk9uyq7fhpfsgsqwrz4u`
- **Followers:** 12,000
- **Following:** 95
- **Ratio:** 126.3x
- **Sources:** nostr_band
- **About:** Bitcoin educator. Stacker News contributor.
- **Link:** https://njump.me/npub1cj8znuztfqkvq89pl8hceph0svvvqk0qay6nydgk9uyq7fhpfsgsqwrz4u

### 32. bitcoinplebdev

- **npub:** `npub18dlusgmprudw46nracaldxe9a3x3ld90t4zf6899786emsvzw2mqjvuyg5`
- **Followers:** 7,500
- **Following:** 60
- **Ratio:** 125.0x
- **Sources:** nostr_band
- **About:** Bitcoin developer education.
- **Link:** https://njump.me/npub18dlusgmprudw46nracaldxe9a3x3ld90t4zf6899786emsvzw2mqjvuyg5

### 33. 21 Futures

- **npub:** `npub1aypcuyy3dkgss6wmvmeung05z56evucgk37wxymvnrc6dg32dauqzddd80`
- **Followers:** 8,000
- **Following:** 65
- **Ratio:** 123.1x
- **Sources:** nostr_band
- **About:** Bitcoin research and analysis.
- **Link:** https://njump.me/npub1aypcuyy3dkgss6wmvmeung05z56evucgk37wxymvnrc6dg32dauqzddd80

### 34. odyzzey

- **npub:** `npub1uvl7vhclmezvdhqha6eclkksln40rjhgwgsggvew683jf93fr4pq3mq3sd`
- **Followers:** 8,000
- **Following:** 75
- **Ratio:** 106.7x
- **Sources:** nostr_band
- **About:** Nostr developer and designer.
- **Link:** https://njump.me/npub1uvl7vhclmezvdhqha6eclkksln40rjhgwgsggvew683jf93fr4pq3mq3sd

### 35. eric99

- **npub:** `npub1v3tgrwwsv7c6xckyhm5dmluc05jxd4yeqhpxew87chn0kua0tjzqc6yvjh`
- **Followers:** 5,000
- **Following:** 55
- **Ratio:** 90.9x
- **Sources:** nostr_band
- **About:** Nostr developer.
- **Link:** https://njump.me/npub1v3tgrwwsv7c6xckyhm5dmluc05jxd4yeqhpxew87chn0kua0tjzqc6yvjh

### 36. franzap

- **npub:** `npub1h882a66p0zj5j4c5xn2hfzu49c3mcrhrq5ul4zh9x2lrave8sucs9tfu07`
- **Followers:** 6,500
- **Following:** 75
- **Ratio:** 86.7x
- **Sources:** nostr_band
- **About:** Nostr builder.
- **Link:** https://njump.me/npub1h882a66p0zj5j4c5xn2hfzu49c3mcrhrq5ul4zh9x2lrave8sucs9tfu07

### 37. Account 89a2e5e7...

- **npub:** `npub13x3wteuas9ypv2h89hlvhdrjkdp6j4l6e87ma9ucmzvl8kpazwpqgy2tlf`
- **Followers:** 2,500
- **Following:** 31
- **Ratio:** 80.6x
- **Sources:** kind3, oracle
- **About:** No bio available
- **Link:** https://njump.me/npub13x3wteuas9ypv2h89hlvhdrjkdp6j4l6e87ma9ucmzvl8kpazwpqgy2tlf

### 38. Matt Corallo

- **npub:** `npub185h9z5yxn8uc7retm0n6gkm88358lejzparxms5kmy9epr236k2qcswrdp`
- **Followers:** 5,000
- **Following:** 85
- **Ratio:** 58.8x
- **Sources:** kind3, oracle
- **About:** 10th known contributor to Bitcoin Core. Now Full-Time Open-Source Bitcoin+Lightning Projects at Spiral (Part of Block).
- **Link:** https://njump.me/npub185h9z5yxn8uc7retm0n6gkm88358lejzparxms5kmy9epr236k2qcswrdp

### 39. Rizzo

- **npub:** `npub144rdkyhwy59ppp6k4d8s7vq8kpxhu6vlgh4v82mfvpmjjcse6grsxzag2d`
- **Followers:** 3,000
- **Following:** 64
- **Ratio:** 46.9x
- **Sources:** kind3, oracle
- **About:** I write about Bitcoin History 
- **Link:** https://njump.me/npub144rdkyhwy59ppp6k4d8s7vq8kpxhu6vlgh4v82mfvpmjjcse6grsxzag2d

### 40. Account 95794448...

- **npub:** `npub1j4u5gjzjyggr3h96x3gjy4akdgwxuk7mgvumv72gym2qyje7fn5s47d6x9`
- **Followers:** 3,500
- **Following:** 77
- **Ratio:** 45.5x
- **Sources:** kind3, oracle
- **About:** No bio available
- **Link:** https://njump.me/npub1j4u5gjzjyggr3h96x3gjy4akdgwxuk7mgvumv72gym2qyje7fn5s47d6x9


---

## Raw Data Files

- `nostr_band_results.json` - nostr.band API scan results
- `kind3_results.json` - Kind-3 relay scan results  
- `oracle_results.json` - WoT oracle scan results
- `index.html` - Interactive HTML viewer

---

*Generated by scan scripts for nostr-wot.com*
