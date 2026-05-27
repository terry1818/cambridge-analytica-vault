---
date: 2026-05-22
description: Three case studies — Indiana welfare automation, Los Angeles homeless housing triage, and Allegheny County child-protective risk scoring — demonstrate that algorithmic public-sector tools systematically punish poor and working-class Americans and conceal poverty from public view.
tags: [source, book, algorithmic-harm, welfare-state, surveillance]
type: source
tier: Tier-2
aliases: ["Source: Eubanks 2018"]
---

# Source — Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor (Virginia Eubanks, 2018)

## Bibliographic
- **Author:** Virginia Eubanks (political scientist, University at Albany, SUNY)
- **Publisher:** St. Martin's Press / Picador, 2018
- **ISBN:** 9781250074317
- **Method:** Investigative journalism combined with academic analysis; extensive interviews with affected individuals and caseworkers across three US states

## Thesis & scope
Eubanks argues that algorithmic decision-making in public services is not a revolution — it is the latest instrument in an unbroken two-century history of using administrative tools to police, discipline, and exclude poor people. Automation did not replace the moral judgments embedded in older systems; it laundered them into the language of objectivity. The book's three case studies cover welfare eligibility, homeless housing allocation, and child-protective services — domains where automated denial can be life-or-death. A key structural observation: digital poverty management hides poor people from middle-class awareness, providing "ethical distance" that enables more severe policy decisions.

## Key content relevant to the vault

**Case Study 1: Indiana welfare automation (2006–2009).** In 2006, Governor Mitch Daniels signed a $1.34 billion contract with IBM and ACS (Affiliated Computer Services) to automate welfare eligibility — moving approximately 1,500 frontline caseworkers out of local county offices and into privatised call centres. The result: applications denied doubled, exceeding one million denials in three years. A 2009 audit found systemic error rates. The state cancelled the contract, but IBM sued for breach and recovered partial payment. Eubanks frames this as the paradigmatic case of privatisation-plus-automation: the vendor profited whether the system worked or not, and denied applicants had no effective appeal mechanism.

**Case Study 2: Los Angeles Coordinated Entry System.** A scoring algorithm ranks homeless individuals by need severity to allocate scarce housing placements. Eubanks documents that the tool is opaque to the people being scored, that social workers distrust its outputs and work around it, and that the data inputs are coercive (individuals must disclose trauma histories to be scored). She frames LA's system as another instance of surveillance imposed on people who cannot refuse participation.

**Case Study 3: Allegheny Family Screening Tool (AFST), Pittsburgh.** The AFST uses 130 variables from administrative data — including public-benefit receipt — to generate a score predicting future child abuse or neglect, used when a call is made to the child abuse hotline. Eubanks finds that the tool disproportionately flags families in poverty regardless of actual maltreatment risk, because public-benefit utilisation is a primary predictor. Families already known to the state are flagged more readily than equally at-risk families with no public-sector contact, because the latter have no data profile. This creates an "invisible" middle class of at-risk children and a hyper-surveilled poor.

**"Digital poorhouse" thesis.** Eubanks coins this as an update to the 19th-century poorhouse: a dispersed network of databases, scoring systems, and digital barriers that performs the same social sorting function — identifying who deserves aid and disciplining those who do not — while appearing technically neutral.

**Ethical distance mechanism.** Automation allows governments to impose harsher outcomes (mass benefit denials, family separations) than would be politically sustainable if caseworkers made individual judgments under public scrutiny. The algorithm provides cover.

## How it maps to the vault
The vault's primary surveillance thread covers commercial/political data (CA, Palantir, Flock) but has minimal coverage of welfare-state automation — a distinct mechanism that pre-dates and parallels the CA model. Eubanks' "digital poorhouse" thesis is relevant to the vault's [[ImmigrationOS]] concept and the [[Federated Master Database]] concept, because the infrastructure of government-facing automated scoring (benefits systems, child-protective systems) is part of the same administrative-data ecosystem that immigration enforcement tools exploit. The IBM/ACS Indiana case is also relevant to the vault's vendor-dependence thread (Palantir, Flock Safety, etc.) — privatised government IT with no accountability when it fails.

## GAPS — what this book raises that the vault appears to miss

1. **Virginia Eubanks** — no person node in vault. [verified-absent] Vault thread: investigators / academics
2. **Allegheny Family Screening Tool (AFST)** — the specific algorithm, its 130-variable structure, its demographic disproportion, and its 2016–present operational status — no vault node. [verified-absent] Vault thread: algorithmic governance / surveillance
3. **Indiana welfare privatisation (IBM / ACS contract, 2006–2009)** — specific named event: Mitch Daniels, $1.34B contract, double error rate, contract cancellation, IBM lawsuit — no vault event node. [verified-absent] Vault thread: vendor dependence / privatised government IT
4. **ACS / Affiliated Computer Services** — the welfare-automation vendor (later acquired by Xerox); a significant player in government IT privatisation — not in vault. [verified-absent] Vault thread: private surveillance/government IT vendors
5. **Los Angeles Coordinated Entry System** — the homeless housing ranking algorithm; coercive data collection from unhoused people — not in vault. [verified-absent] Vault thread: algorithmic governance
6. **"Digital poorhouse" concept** — Eubanks' named framework for algorithmic poverty management as continuity with historical disciplinary institutions — no vault concept node. [verified-absent] Vault thread: algorithmic harm / surveillance
7. **Mitch Daniels** — Indiana governor who signed the automation contract; the political sponsor of the privatisation — no vault person node. [verified-absent] Vault thread: political figures / government IT

## Evidence tier
**Tier-2.** Rigorous investigative book by a political scientist with primary-source interviews and document review. The Indiana figures (contract value, error rates, denial counts) are drawn from government audits and court records. The AFST analysis is based on published technical documentation and interviews with Allegheny County officials. Interpretive claims (automation as continuity with historical poorhouses) are author's argument, clearly framed.

## Related
- [[ImmigrationOS]], [[Federated Master Database]], [[Palantir Technologies]]
- [[Source - Brayne 2020 - Predict and Surveil]] (parallel: discretion and data in law enforcement)
- [[Source - Zuboff 2019 - Age of Surveillance Capitalism]]
- [[DOGE]] (current federal administrative data integration effort)
