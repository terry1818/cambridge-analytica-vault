---
date: 2026-05-22
description: Definitive investigative account of Russia's internet-surveillance architecture (SORM system), the FSB's digital control apparatus, and the struggle between state surveillance and online dissidents — essential technical-institutional background for understanding the Russian surveillance model that other state actors have studied.
tags: [source, book, russia, surveillance, digital-control]
type: source
tier: Tier-2
aliases: ["Source: Soldatov Borogan 2015"]
---

# Source — The Red Web: The Struggle Between Russia's Digital Dictators and the New Online Revolutionaries (Andrei Soldatov & Irina Borogan, 2015)

## Bibliographic
Andrei Soldatov and Irina Borogan; *The Red Web: The Struggle Between Russia's Digital Dictators and the New Online Revolutionaries*; PublicAffairs; 2015.

## Thesis & scope
Soldatov and Borogan — Russian investigative journalists and co-founders of Agentura.ru (a watchdog of Russian security services) — argue that Russia's approach to internet governance was never liberal: from the first commercial internet connections in the early 1990s, the FSB insisted on a mandatory eavesdropping architecture baked into every ISP. The core mechanism, **SORM**, predates the public internet in Russia and was extended to cover it almost immediately. The book traces this surveillance infrastructure from Soviet-era origins through the Snowden revelations (2013) to the escalating 2014–2015 crackdown following the Euromaidan, showing how the Kremlin progressively centralised control over information flows. The "revolutionaries" half of the title covers Russian activists, hackers, and civil-society figures who resisted digital surveillance — many of whom were subsequently imprisoned, exiled, or co-opted.

## Key content relevant to the vault

- **SORM architecture** (*Sistema Operativno-Rozysknikh Meropriyatiy*, System of Operative Search Measures):
  - **SORM-1** (1995): mandatory back-door for the FSB in all telephone networks, including mobile.
  - **SORM-2** (1998): extended to internet traffic — all ISPs required to install an FSB-controlled black box that copies all traffic to the FSB; ISPs pay for the hardware themselves; FSB does not need to show a warrant to the ISP (warrant is filed internally with FSB).
  - **SORM-3** (2014): expanded to cover all forms of electronic communication and to store data for three years.
  - The technical requirement to install FSB-controlled hardware at ISP premises with no disclosure obligation made Russia's surveillance model structurally more comprehensive than NSA PRISM (which required court orders and tech-company cooperation).
- **Roskomnadzor** (Federal Service for Supervision of Communications, Information Technology and Mass Media): the regulatory body responsible for internet blocking and censorship; Soldatov and Borogan document how it accumulated power rapidly after 2012, building a national filtering/blocking infrastructure.
- **SORM's institutional lineage**: The authors trace SORM back to *sharashkas* — Stalin-era prison-camp research institutes where scientists were forced to develop surveillance technologies; post-Soviet, the FSB retained control of the research institutes that continued developing interception and speech-recognition technologies, meaning the surveillance-industrial complex never actually dissolved.
- **Snowden episode in Moscow**: Soldatov and Borogan cover Snowden's 2013 transit through Moscow and the FSB's handling of it; Edward Snowden specifically praised Soldatov as "perhaps the single most prominent critic of Russia's surveillance apparatus."
- **[[Euromaidan 2013-2014]] and surveillance escalation**: The vault already has an Euromaidan node; the book documents how Ukraine's revolution accelerated Russian domestic internet-control measures as the Kremlin became alarmed by the role of social media in mass mobilisation.
- **SORM as an export model**: The book documents that Russia exported the SORM model — the requirement for ISPs to install FSB-controlled intercept hardware — to former Soviet states including Kazakhstan, Uzbekistan, and others. This is the precursor to the "surveillance state export" pattern documented in the vault for other contexts.
- **Activist resistance**: The book profiles specific Russian digital activists and the organisations they built, including [[Citizen Lab]]-adjacent figures; many were targeted by FSB-linked actors.
- **Yarovaya Law** (passed 2016, after book's publication, but anticipated in the 2015 edition's epilogue): legislation requiring all communications providers to store content data for six months and metadata for three years, and to hand over encryption keys — effectively SORM-4 in legislative form.

## How it maps to the vault

- **Russia cluster** (Lenses/Lens - Russia.md; Russian IRA MOC): Provides the technical/institutional infrastructure that makes Russian active measures possible — the vault's Russia coverage is currently strongest on operations (IRA, Doppelganger, Fancy Bear, Cozy Bear) but thin on the *domestic surveillance apparatus* that enables those operations.
- **[[GRU]]** (\03-Organizations\GRU.md) / **[[Cozy Bear (APT29)]]** / **[[Fancy Bear (APT28)]]**: SORM is the domestic counterpart to the offensive hacking infrastructure; understanding FSB surveillance architecture contextualises the offensive cyber operations.
- **[[Citizen Lab]]** (\03-Organizations\Investigative-Research\Citizen Lab.md): Soldatov and Borogan's investigative methodology is directly parallel to Citizen Lab's; cross-link appropriate.
- **[[Reflexive Control]]** (\05-Concepts\Cognitive-Warfare\Reflexive Control.md): The information-control architecture Soldatov/Borogan describe is the domestic complement to the offensive reflexive-control doctrine.
- **[[Euromaidan 2013-2014]]** (\04-Events\Euromaidan 2013-2014.md): The book provides the surveillance escalation context for that event.
- **[[Doppelganger]]** / **[[Internet Research Agency]]**: Both operations rely on the broader information-control infrastructure; The Red Web shows the domestic side of that infrastructure.

## GAPS — what this book raises that the vault appears to miss

1. **SORM (Sistema Operativno-Rozysknikh Meropriyatiy)** — Russia's mandatory ISP back-door surveillance architecture; three generations (SORM-1/2/3); FSB warrant-free access; ISP cost burden; history from Soviet sharashkas — not in inventory [verified-absent]
2. **Roskomnadzor** — Russian federal internet regulator with blocking/filtering powers; key institutional actor in domestic information control — not in inventory [verified-absent]
3. **Yarovaya Law** — 2016 Russian legislation mandating bulk data retention and encryption-key disclosure; effectively codifies SORM-3 in statute — not in inventory [verified-absent]
4. **Agentura.ru** — Soldatov and Borogan's watchdog organisation; Russian investigative journalism covering security services — not in inventory [verified-absent]
5. **SORM export model** — Russian export of mandatory ISP-intercept architecture to Central Asian and post-Soviet states; a precursor to the broader "authoritarian surveillance export" pattern — not in inventory as a distinct concept [candidate]
6. **Sharashka research institutes** — Soviet-era prison-camp science programmes that developed surveillance technology; post-Soviet continuity with FSB technical research institutes — not in inventory [verified-absent]
7. **RuNet (sovereign internet concept)** — Russia's concept of a separable, state-controllable national internet; Soldatov/Borogan trace its intellectual and institutional origins; the vault has some coverage of authoritarian internet governance but no dedicated RuNet treatment — not in inventory [verified-absent as distinct concept]

## Evidence tier
Tier-2. Written by two Russian investigative journalists with 15+ years covering Russian security services; Agentura.ru has been cited in academic, NGO, and intelligence-community reports; methodology relies on document review, official sources, and on-the-record interviews. Soldatov has subsequently been exiled from Russia for his reporting. Named Library Journal Best Book of 2015.

## Related
[[GRU]] · [[Cozy Bear (APT29)]] · [[Fancy Bear (APT28)]] · [[Citizen Lab]] · [[Active measures]] · [[Reflexive Control]] · [[Euromaidan 2013-2014]] · [[Doppelganger]] · [[Internet Research Agency]] · [[KGB Service A]] · [[Transnational kleptocracy]] · [[Source - Rid 2020 - Active Measures]] · [[Source - Snyder 2018 - Road to Unfreedom]] · [[Source - Belton 2020 - Putin's People]]
