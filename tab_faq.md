---
title: FAQ
layout:  null
tab: true
order: 4
tags: OCCM
---

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-153589924-2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-153589924-2');
</script>

![OWASP Incubator Project](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OWASP-Incubator_Project-blue.svg)
![Release](https://owasp.org/www-project-cyber-controls-matrix/assets/images/release-tbd-blue.svg)
[![License](https://owasp.org/www-project-cyber-controls-matrix/assets/images/license-CC--BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

***
<p><h2 style="text-align:center" target="_blank"><a href="https://eepurl.com/g3kJBP">Click here to be notified of OCCM news and releases !</a></h2></p>

***
![OCCM Logo Banner](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OCCM-logo-1000x348-wht.png)

***
## Frequently Asked Questions (FAQ)

* **How can I help the project?**

  - Glad you asked! Please start by [joining the OCCM mailing list](https://eepurl.com/g3kJBP) and answering the optional questions on that page.
  - We'll eventually have content submission instructions and forms together, but our only priority right now is getting the first release out the door.

* **When will the first release of the OCCM occur and what will it include?**

  - Officially TBD, but planned before September.
  - Please see the Roadmap tab for an evolving list of target content.
  - Please also [join the OCCM mailing list](https://eepurl.com/g3kJBP) to be notified of OCCM-specific news and releases.
  - The OCCM project launched on May 11, 2020. Core functionality is operational (schema and code for automated mapping). It just takes time to create the initial Cybersecurity Taxonomy and normalize hundreds of Controls across the first Control Sets.

* **Will the OCCM map controls between \[Some-Control-Set] and \[Some-Other-Control-Set]**?

  - Yes, as long as both Control Sets are in the OCCM.
  - The OCCM automatically maps all Controls Sets to every other Control Set.
  - That's the power of normalizing each Control to the OCCM Cyber Taxonomy.
  - Please see the Roadmap tab for an evolving list of forthcoming Control Sets.

* **Will the OCCM automate control selection, documentation, and other aspects of my program?**

  - No. The OCCM is a documentation project driven by code and rich data. Its singular focus is to provide valuable information to assist in implementing and complying with cyber controls across multiple standards / control sets / frameworks.
  - However, we hope that all types of software will use and leverage the OCCM. The OCCM and its content is a gift to the cyber industry; freely licensed for commercial, non-commercial, and government use; with the only stipulation being required attribution.

* **How is the OCCM different from the Secure Controls Framework (SCF)?**

  - The approach of the OCCM is implementing and documenting the target control set while leveraging information from relevant controls in other control sets.
  - The approach of the SCF is implementing and documenting SCF controls (the meta-framework) as a baseline for compliance with other control sets. In other words, the SCF attempts to provide a universal control set with good coverage of other control sets. Of course, the SCF is unable to capture every specific requirement and guidance in those control sets, which is where control mapping from the SCF controls to the target controls is needed and provided.
  - Whether using the OCCM or a meta-framework like the SCF, working directly on a control set is currently the only way to ensure all requirements are fully met for audit and certification.
  - The OCCM provides transparency via the OCCM Cyber Taxonomy on why a specific control has been mapped at each level of detail (High, Medium, and Low); whereas the SCF mapping reason can only be inferred by analyzing the content of the SCF control and the SCF-provided mapping for that control.
  - The OCCM directly maps from one Control Set to all others (i.e. NIST->ISO). The SCM indirectly maps between Control Sets (i.e. NIST->SCF->ISO), except in the case that only SCF controls are being mapped (i.e. SCF->ISO).
  - The SCF license "No Derivatives" condition may hinder use in products and research, as no modification of the SCF controls can be distributed without being granted exception to the license. The OCCM license has no such hindrance. Both licenses require attribution.
  - The SCF is an excellent project and contribution to the industry, just very different in content and use than the OCCM.

<table align="center" style="font-size:70%;max-width:100%">
<thead>
  <tr>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center"></th>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center">OCCM</th>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center">SCF</th>
  </tr>
</thead>
<tbody>
  <tr><td style="text-align:right"><b>Design</b></td><td>Simple Matrix</td><td>Meta-Framework</td></tr>
  <tr><td style="text-align:right"><b>Separate Control Set</b></td><td>No</td><td>Yes. SCF Controls are required</td></tr>
  <tr><td style="text-align:right"><b>Approach</b></td><td>Control Set A + Control Set B, etc.</td><td>SCF Controls + Control Set A + Control Set B, etc.</td></tr>
  <tr><td style="text-align:right"><b>Mapping Capability</b></td><td>Direct (i.e. NIST->ISO)</td><td>Indirect (i.e. NIST->SCF->ISO)</td></tr>
  <tr><td style="text-align:right"><b>Mapping Detail</b></td><td>3 Levels of Detail (High, Medium, Low)</td><td>1 Level of Detail</td></tr>
  <tr><td style="text-align:right"><b>Mapping Reason</b></td><td>Specified via OCCM Cyber Taxonomy</td><td>Unspecified</td></tr>
  <tr><td style="text-align:right"><b>Maturity Model</b></td><td>Unspecified [control dependent]</td><td>SCF Controls [meta-framework dependent]</td></tr>
  <tr><td style="text-align:right"><b>License</b></td><td>Free. CC-BY 4.0</td><td>Free. CC-BY-ND 4.0 (No Derivatives)</td></tr>
  <tr><td style="text-align:right"><b>Parent Organization</b></td><td>OWASP Foundation, Inc. [501(c)(3) non-profit]</td><td>Secure Controls Framework Council, LLC</td></tr>
</tbody>
</table>

* **Why the name OWASP Cyber Controls Matrix (OCCM)?**

  - "OWASP" for the OWASP Foundation hosting and supporting the project.
  - "Cyber" because it represents both IT and Cybersecurity. While it is a common buzzword, "cyber" is the only word that represents both.
  - "Controls" because these are the individual, measurable items within a control set / framework.
  - "Matrix" because the OCCM generates a mapping table between every Control and every other Control. Even though arriving at that table requires a specific process, we did not want any distraction from what OCCM generates by calling it (yet another) a Framework or Methodology.
  - Apologies to the CSA Cloud Controls Matrix (CSA CCM). We tried to avoid using "CCM" in our acronym. We really did. The reasons above were too compelling. At least we're "OCCM".

### Don't see your question answered here or elsewhere on the website?
**[Click here to email us about it.](mailto:occm@cybercontrolsmatrix.com?subject=OCCM Website FAQ)**
