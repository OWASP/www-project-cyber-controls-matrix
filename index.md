---

layout: col-sidebar
title: OWASP Cyber Controls Matrix (OCCM)
tags: map mapping mappings controls control framework frameworks standards regulations regulatory laws legal guidance best practice cyber security cybersecurity IT cloud OCCM CCM GRC governance risk compliance compliant implementation implementing IRM management ERM enterprise USM unified normalized normalization audit 3PAO matrix related relations relationships assessment gap gaps analysis application applications appsec secops devsecops top10 CIS SANS FISMA NIST 800-53 CMMC ISO ISO27k 27000 27001 27002 27017 27018
level: 2
type: documentation
pitch: Solve the problem of multiple cyber standards by consolidating them, reducing timelines and effort by months!

---

<meta property="og:type" content="website" />
<meta property="og:image" content="https://owasp.org/www-project-cyber-controls-matrix/assets/images/OCCM-logo-1000x348-wht.png" />

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
## Description

The OWASP Cyber Controls Matrix (OCCM) is an innovation in the mapping of cyber controls across different control sets and frameworks.
<p class="callout-mono left">Solve the problem of multiple cyber standards by consolidating them, reducing timelines and effort by months. The OCCM does this and much more!</p>

#### Consolidation

Most organizations today must comply with two or more standards in their quest for enhanced Cybersecurity and compliance. This has traditionally been a very linear process, but the OCCM transforms it into a much more parallel one: de-duplicating effort. This can reduce project duration and effort by months. The OCCM means less time implementing, less time documenting, better results, and no more backtracking.

#### Knowledge

Supercharging Cybersecurity knowledge, the OCCM points cyber analysts to the guidance, insights, references, and best practices available across all standards. This greatly improves understanding of how to implement and document controls, resulting in improved security and improved audit outcomes. Costly mistakes are also avoided thanks to visibility of other standards; ensuring that decisions also satisfy future security needs, not just the immediate ones.

#### Cyber Taxonomy

There is a multi-level cyber taxonomy at the core of the OCCM, to which all the control relationships are normalized. As a result, the mappings are more consistent, objective, organized, and reliable. No more vague groupings of controls or mysterious "black box" mappings. In the OCCM, it is clear how and why each control is related. Furthermore, the OCCM Cyber Taxonomy facilitates easy research of cyber topics and objectives across all standards.

#### Levels of Detail

Controls in the OCCM are included at all available levels and each of those controls is normalized to three separate levels of detail in the OCCM Cyber Taxonomy. Audit checks are also supported. This ensures a comprehensive mapping that dives deep into the control set / framework, versus the surface mappings common in the industry that only indicate top-level controls.

Every Control entry in the OCCM is given one Control Level and is assigned one or more groups of High Level, Medium Level, and Low Level Topics in the OCCM Cyber Taxonomy.

* Control Levels for Each Control

  - Control Families / Headings
  - Top-Level Controls
  - Sub-Controls
  - Enhancements
  - etc.
<p>
</p>

* Mapping Levels of Detail for Each Control

  - High Level Topics (Areas)
    - ex. "Disaster Recovery" within a Control stating "Ensure there is a <b>Disaster Recovery (H)</b> Policy (M) that identifies Roles and Responsibilities (L) and Mission-Critical Environments (L)."

  - Medium Level Topics (Objects)
    - ex. "Policy" within a Control stating "Ensure there is a Disaster Recovery (H) <b>Policy (M)</b> that identifies Roles and Responsibilities (L) and Mission-Critical Environments (L)."

  - Low Level Topics (Targets)
    - ex. "Roles and Responsibilities" within a Control stating "Ensure there is a Disaster Recovery (H) Policy (M) that identifies <b>Roles and Responsibilities (L)</b> and Mission-Critical Environments (L)."
    - ex. "Mission-Critical Environments" within a Control stating "Ensure there is a Disaster Recovery (H) Policy (M) that identifies Roles and Responsibilities (L) and <b>Mission-Critical Environments (L)</b>."

#### Relevance

Control relationships in the OCCM are directly mapped and viewable at the three separate levels of detail, resolving the fundamental issues of too-strict or too-loose mapping. Each individual control in the OCCM relates directly to other controls ("one-to-many"), instead of the common industry practice of grouping controls together ("many-to-many"). This common practice results in a handshake problem, where every control in group "A" is mapped to every other control in group "B".

For example, the group mapping "A1, A2, A3, A4, A5 -> B1, B2, B3, B4, B5" generates 25 total relationships! This requires analysis of 5 relationships per "A" control, some of which may have little to no direct relevance.

Using the OCCM, this example can be greatly simplified and reduced to...
- High Level Mapping &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "A1 -> B1, B2, B3" &nbsp;&nbsp; \[3 relationships]
-	Medium Level Mapping &nbsp;&nbsp;&nbsp; "A1 -> B1, B2" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \[2 relationships]
-	Low Level Mapping &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "A1 -> B1" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \[1 relationship]

#### Growth

The OCCM has been designed with the principles of easy contribution, accelerated growth, and continuous improvement. Once a new control is added and normalized, it is automatically mapped to every other control across all standards. There is no longer a need for an analyst to search for a mapping between two different standards or create their own. Every standard in the OCCM is automatically mapped to every other standard, exponentially increasing its scope.

***
## Industry Perspectives

<p class="callout-mono right small">"Complying with multiple cybersecurity frameworks is one of the top challenges we’ve heard from our Member organizations."<br>(Center for Internet Security, 3/2020)</p>

<p class="callout-mono right small">"... multiple frameworks are often needed, but the task of managing them becomes almost impossible to implement."<br>(CSO Online, 7/2010)</p>

<p class="callout-mono right small">"One major challenge compliance teams ran into again and again is that they tended to do a lot of duplicative work in order to meet multiple regulatory standards."<br>(Hyperproof, 3/2020)</p>

<p class="callout-mono right small">"Pursuing multiple frameworks at the same time can overwhelm founders, especially without expert guidance."<br>(Laika, 1/2020)</p>

<p class="callout-mono right small">"Between 2010 and 2020, hundreds of new cyber regulations, rules, or standards were introduced. This explosion of interest in cybersecurity from regulators has required nearly 98% of companies to comply with two or more cyber compliance standards, while nearly 70% are subject to compliance with more than five."<br>(Coalfire, 5/2020)</p>

***
## From the Creator / Project Leader

"The capabilities of the OWASP Cyber Controls Matrix are something I have wanted to see my entire career. It is my honor to create it and give it to the entire Cybersecurity industry as an open-source OWASP project. Per the license, I encourage commercial products, non-commercial products, and cyber practitioners to fully incorporate it and contribute back to the project. First and foremost, the OCCM is a community driven effort. All submissions, ideas, promotion, and discourse are greatly appreciated. Thank you for your support!"
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Eric Bragger [(LinkedIn)](https://www.linkedin.com/in/eric-bragger/) [(Email)](mailto://occm@cybercontrolsmatrix.com?subject=OCCM Website email)

***
## Contributions

Contributions to the OCCM are welcome and appreciated.

Contributors acknowledge that by contributing, copyright for all contributions will be transferred in full to the OWASP Foundation, Inc, the OCCM Creator, and the OCCM Project Leader. Please see the Legal section for further details.

***
## Core Team

Eric Bragger [(LinkedIn)](https://www.linkedin.com/in/eric-bragger/) [(Email)](mailto://occm@cybercontrolsmatrix.com?subject=OCCM Website email) \[Creator / Project Leader]

***
## Contributor List
Your Name Here (Your URL Here)

***
## Membership, Donations, and Sponsorship

Please indicate the OWASP Cyber Controls Matrix in membership, donation, and sponsorship comments if you wish to specifically and directly support this project. General contributions to the OWASP Foundation will also support this project and others like it.

All OWASP Projects are run and developed by volunteers and rely on [individual memberships](https://owasp.org/membership/), [personal donations](https://owasp.org/donate/), and [corporate memberships / sponsorships](https://owasp.org/supporters/) to continue their development. OWASP does not endorse or recommend commercial products or services, allowing our community to remain vendor neutral and focused on applying the collective wisdom of some of the best minds in Cybersecurity worldwide.

The OWASP Foundation, Inc. is a non-profit 501(c)(3) charitable organization. Some financial contributions may qualify for a tax deduction. Consult with a tax professional for details.

***
## Legal

For any questions regarding this section, send an email to: [occm@cybercontrolsmatrix.com](mailto://occm@cybercontrolsmatrix.com?subject=OCCM Legal Questions)

#### Image Use

Images created or taken from the OWASP Cyber Controls Matrix (OCCM), OCCM content, and this website may be used if the following attribution is given beneath the image or in the image caption: "Image credit https://cybercontrolsmatrix.com". If the image content has been modified (excluding size, color, positioning, and formatting changes) or added to other content, the following attribution must be given instead: "Adapted from https://cybercontrolsmatrix.com".

#### Required Attribution

Per the open license, all of the paragraphs within the License, Copyright & Trademarks, and Disclaimer & Limitations sections must be included as full attribution -- including the links in parenthesis, as functional or non-functional -- with, but not limited to: any written / electronic distribution, creation, content, output, or product; documentation; repository; webpage; software; or any other distribution, creation, content, output, or product that incorporates any part or whole of the OWASP Cyber Controls Matrix (OCCM) or associated content.

Partial exception is made for online postings and blog entries (personal or commercial), whose attribution must at minimum make mention of the "OWASP Cyber Controls Matrix (OCCM)". Mention of the website "https://cybercontrolsmatrix.com", the creator "Eric Bragger", and any other core team members is highly encouraged and appreciated.

Partial exception is made for commercial articles, white papers, documentation, and sales collateral; whose attribution must at minimum include the first paragraph in the Copyright & Trademarks section.

#### License

The OWASP Cyber Controls Matrix (OCCM) is licensed under a [Creative Commons Attribution 4.0 International (CC-BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license for free use and adaptation, including commercial and government, with attribution. Additional license terms and conditions, such as indemnification, are detailed within the Required Attribution section text that must be provided with use or distribution of the OCCM.

#### Copyright & Trademarks

The OWASP Cyber Controls Matrix (OCCM) [(https://cybercontrolsmatrix.com)](https://cybercontrolsmatrix.com) is copyright the OWASP Foundation, Inc. [(https://owasp.org)](https://owasp.org) and its creator Eric Bragger [(https://www.linkedin.com/in/eric-bragger/)](https://www.linkedin.com/in/eric-bragger/). All rights reserved. Control Identifiers (IDs), Control Names, Control Headings, Control Set Names, and Framework Names are copyright their respective owners. "OWASP"™ is trademark the OWASP Foundation, Inc. "Cyber Controls Matrix"™, "OCCM"™, and "OCCM Cyber Taxonomy"™, including their logos and trade dress, are trademark Eric Bragger. All other trademarks belong to their respective owners.

Contributors acknowledge that by contributing, copyright for all contributions will be transferred in full, without any obligation whatsoever expressed or implied, to: the OWASP Foundation, Inc., the OCCM Creator, and the OCCM Project Leader. Contributions may be used, shared, and disseminated at the complete discretion of the OWASP Foundation, Inc., the OCCM Creator, the OCCM Project Leader, and anyone associated with the project whether in an official or non-official capacity. Contributions may include, but are not limited to: information, content, assistance, ideas, software code, submissions, employment, licensing, financial support, marketing, promotion, endorsement, and sponsorship.

#### Disclaimer & Limitations

The OWASP Cyber Controls Matrix (OCCM) is provided as-is and is used at your own risk with zero expectations. Warranties, liabilities, claims, guarantees, and representation of any kind and for any purpose are fully disclaimed without limitation whether expressed, implied, or statutory with regard to the OCCM, its capabilities, its content, its copyright owners, its creator, any individuals associated with the OCCM, and any aspects of the OCCM. This includes, but is not limited to: negligence; infringement; licensing; fair use; attribution; lack of attribution; completeness; accuracy; applicability; acceptability; availability; correctness; reliability; objectivity; timeliness; practicality; effectiveness; fitness; merchantability; results obtained; claims; expectations; title; damages; losses; and use of, or inability to use, any information, content, or capabilities associated with the OCCM.

The OCCM shall always be considered as-is and is provided as-is with zero liability regardless of any claims, suppositions, beliefs, assumptions, expressions, implications, written agreements, or verbal agreements. The OCCM, its copyright owner, its creator, and any individuals associated with the project shall not be liable, under any circumstances, for any direct, indirect, incidental, special, or consequential damages concerning the OCCM, anything associated with the OCCM, individual associated with the OCCM, or any aspects of the OCCM whether in an official or non-official capacity. Liability shall not be accepted concerning any attribution, lack of attribution, or failure to remove attribution for contributions or contributors. Liability shall not be accepted concerning any third-party use, inclusion, reference, or claims. Liability shall not be accepted for any reason; expressed, implied, or statutory.

The OCCM in part or whole (including, but not limited to: its content and capabilities) is comprised of data, software code, subjective opinions, contributions, statements, descriptions, and other content; any or all of which may be in error for any reason including negligence and are not to be construed as objective, correct, accurate, informed, complete, reasonable, reliable, factual, or effective. The OCCM, its copyright owners, its creator, and any individuals associated with the OCCM do not make any warranty or representation of fitness or merchantability for any purpose.

You agree to indemnify, defend, and hold harmless the OCCM, its copyright owners, its creator, any individuals associated with it, and any aspects of it from any and all claims, liabilities, and expenses (including attorney fees, court fees, process costs, fines, damages, and any other losses) arising out of your use of the OCCM, interaction with the OCCM, any individuals associated with the OCCM, and any aspects of the OCCM; with no expectations whatsoever and regardless of disclosures, claims, discoveries, process, suits, or proceedings.

The [Creative Commons Attribution 4.0 International (CC-BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode) provides further important disclaimers, limitations, and legal text that also applies to the OCCM.

<br>
