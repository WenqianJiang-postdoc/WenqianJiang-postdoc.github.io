---
layout: archive
title: <span style="font-size:19px;">Carbon-Aware Coordination to Enhance Operational Sustainability</span>
permalink: /research2/
author_profile: true
# redirect_from:
#   - /resume
---
With the advancing adoption of sustainable practices, a growing number of electricity consumers, from individuals to large corporations, are seeking to increase the “cleanliness" of their electricity usage. These commitments are driven by regulation compliance, subsidy eligibility, or voluntary climate goals. For instance, AI data centers and hydrogen producers are incentivized to shift their loads to times or locations with lower carbon emissions. To effectively enable such carbon-aware practices, consumers require real-time “carbon signals” (similar to price signals) that reflect varying emissions intensities of electricity and an associated framework that supports carbon accounting. 

* **Equilibrium framework for effective carbon signal design**
<br>
The emission reduction efforts of carbon-sensitive consumers rely on carbon intensity information such as average carbon emission signals, but it is unclear whether load shifting based on these signals truly reduces emissions. To address this open question, we design an equilibrium framework, which expands the commonly used equilibrium model for standard (carbon-agnostic) electricity market clearing to include carbon-aware load shifting based on average carbon emissions [paper link](https://arxiv.org/pdf/2504.07248). Our analysis shows that this widely adopted signal may not be effective for guiding emission reduction because it fails to reflect marginal carbon impacts, ignores geographical differences, and may create new emissions-intensive demand peaks.
<br>
See more details in my [Poster](/equilibriumposter.pdf){:target="_blank"}.

* **Electricity market clearing with carbon preferences and allocation**
<br>
Accurate carbon accounting is crucial for implementing effective reduction strategies, as it identifies emission sources and potential reduction opportunities. Although the underlying driver for physical emissions, which happen at generation facilities, is end-user consumption, conventional carbon accounting, which primarily targets the generation side or measures regional totals (including both generators and consumers), fails to meet the need for carbon emission allocation to consumers. To bridge this gap, we present a novel market-clearing model considering consumers' carbon preferences, characterized by carbon cost bids, which is cleared to simultaneously dispatch generators and allocate carbon emissions to each consumer [paper link](https://doi.org/10.1016/j.segan.2025.101870). Starting from a centralized single optimization model, we derive an equivalent equilibrium model that incorporates a carbon allocation problem and gives rise to a set of carbon-adjusted electricity prices for both consumers and generators [paper link](https://arxiv.org/pdf/2508.01076). By guaranteeing dispatch priority for low-carbon generators, these updated prices allocate the associated increase in generation costs to consumers based on their submitted carbon costs. This work, to our knowledge, is the first to propose a model that elicits carbon costs from consumers and integrates a carbon allocation scheme that explicitly assigns emissions from generators to loads in the electricity market clearing. 
<br>
See more details in my [Poster](/carboncostposter.pdf){:target="_blank"} and [Presentation](/carboncostpresentation.pdf){:target="_blank"}.


