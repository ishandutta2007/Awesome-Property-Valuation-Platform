# Awesome-Property-Valuation-Platform

## Top Property Valuation Platform (AVM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Automated Valuation Models, Mass Appraisal, Property Analytics & Collateral Valuation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Property Valuation (AVM)**. These systems use statistical and machine-learning models to estimate residential (and sometimes commercial) property values at scale for lenders, investors, appraisers, and government assessors.



**Examples** include HouseCanary, Clear Capital, CoreLogic Total Home Value, Quantarium, ValueLink, Realyse, Hometrack, PriceHubble, GeoPhy, and PropMix (the category leaders).



**Open-source emphasis**: Production AVMs depend heavily on proprietary property data, transaction histories, and MLS feeds, so full commercial-grade platforms remain closed. Strong open modeling toolkits now exist (notably **OpenAVMKit**) for mass appraisal and research. This section highlights the best available open resources and is realistic about data limitations.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[HouseCanary](https://www.housecanary.com/)**  

  AI-powered property valuation and analytics platform covering large volumes of U.S. residential properties with AVMs and investment insights.



- **[Clear Capital](https://www.clearcapital.com/)**  

  Property valuation technology spanning AVMs, BPOs, and appraisal management for mortgage and collateral risk use cases.



- **[CoreLogic Total Home Value](https://www.corelogic.com/)**  

  Industry-standard property data and valuation solutions widely used by lenders and real-estate professionals.



- **[Quantarium](https://www.quantarium.com/)**  

  Advanced AVM and property intelligence platform focused on accuracy and analytics for valuation workflows.



- **[ValueLink](https://www.valuelinksoftware.com/)**  

  Valuation management and related technology supporting appraisal and automated valuation processes.



- **[Realyse](https://www.realyse.com/)**  

  Property valuation and analytics solutions used in various real-estate and lending contexts.



- **[Hometrack](https://www.hometrack.com/)**  

  Property data and valuation services (strong presence in certain markets) supporting AVMs and market insights.



- **[PriceHubble](https://www.pricehubble.com/)**  

  API-first property valuation and real-estate analytics platform used across multiple countries.



- **[GeoPhy](https://www.geophy.com/)**  

  Commercial real-estate data and valuation analytics platform (often focused on income-producing properties).



- **[PropMix](https://www.propmix.io/)**  

  Real-estate data and valuation-related technology solutions.



## Open-Source GitHub Projects

- **[OpenAVMKit](https://github.com/larsiusprime/openavmkit)**  

  Free and open-source Python toolkit for real-estate mass appraisal and automated valuation modeling. Supports data cleaning, enrichment, modeling, statistical evaluation, and jurisdiction-configurable workflows.



- **[re-avm and academic AVM implementations](https://github.com/rlowrance/re-avm)**  

  Open real-estate automated valuation model projects and research codebases demonstrating hedonic and machine-learning approaches.



- **[Jurisdiction-specific open appraisal models](https://github.com/)**  

  Public code from assessor offices and research groups (e.g., Cook County-inspired work) that implement mass appraisal pipelines.



- **[Hedonic and spatial regression open notebooks](https://github.com/)**  

  Educational and research repositories applying classic and modern statistical methods to property valuation.



- **[Feature engineering and data-cleaning open utilities](https://github.com/)**  

  Tools for preparing parcel, transaction, and neighborhood data for valuation models.



- **[Open property data integration projects](https://github.com/)**  

  Scripts and pipelines that combine public assessor data, open street maps, and other free sources for modeling.



- **[Model evaluation and fairness open frameworks](https://github.com/)**  

  Libraries and notebooks for measuring AVM accuracy, bias, and coverage.



- **[Geospatial enrichment open tools](https://github.com/)**  

  Components that add location-based features (distance to amenities, school quality proxies, etc.) to valuation datasets.



- **[Simple production-style AVM prototypes](https://github.com/)**  

  End-to-end open experiments that scrape or ingest data, train models, and serve predictions for specific markets.



- **[Reporting and export open helpers](https://github.com/)**  

  Tools for generating standardized valuation reports and diagnostics from model outputs.



### Additional Strong Open-Source Options

- Starting with **OpenAVMKit** when you have access to local transaction and parcel data and want a configurable mass-appraisal toolkit.

- Using academic and assessor open codebases as references for model design and evaluation.

- Building research or internal AVMs on public data while accepting coverage and accuracy limits compared with commercial providers.

- Accepting that nationwide or multi-country coverage, high hit rates, lender-grade confidence scores, and continuous data refresh still require commercial AVM platforms (HouseCanary, CoreLogic, Clear Capital, PriceHubble, etc.).

- Combining open modeling toolkits with licensed data feeds when higher accuracy is needed.



**Frameworks for building custom systems**: Acquire or license property and transaction data → clean and enrich with OpenAVMKit or custom pipelines → train and evaluate models → generate valuations and confidence metrics → monitor performance over time. Suitable for assessors, researchers, or specialized internal use. Commercial AVM platforms remain the practical choice for lenders, investors, and large-scale production valuation needs that require proven accuracy, coverage, and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Automated valuations are estimates only and are not formal appraisals. They can be inaccurate, especially for unique properties or thin markets. Use of AVMs in lending or regulatory contexts is subject to specific rules and guidelines. Open-source models inherit the quality and biases of their training data. This list is not financial, appraisal, or legal advice.



---

**Made for lenders, investors, assessors, and real-estate analysts who need scalable property valuation.**

Let's keep valuation methods transparent, measurable, and as open as practical.
