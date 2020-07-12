---
title: Features
layout:  null
tab: true
order: 2
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
## Key Features

* **One-to-Many Control Mapping** (vs. Many-to-Many)
  - Each Control is individually evaluated to others, greatly reducing the analysis needed to only directly relevant Controls.
  - One-to-many mapping provides a very direct result:  ""A1 --> B1, B2, B3, B4, B5"".  \[5 relationships needing analysis.]
  - Many-to-many mapping provides an indirect, grouped result:  ""A1, A2, A3, A4, A5 --> B1, B2, B3, B4, B5"".  \[25 relationships needing analysis.]
<p></p>

* **Mapping at Three Separate Levels of Detail** (vs. One Level)
  - Enables the analysis of related Controls at general, specific, and detailed levels.
  - Ensures that Controls won't be missed because of a too general or too specific mapping approach.
<p></p>

* **Mapping of Sub-Controls, Control Enhancements, and Audit Checks** (vs. Only including Top-Level Controls)
  - Increases relevance and detail greatly by mapping directly to a Sub-Control and Control Enhancement rather than just its Top-Level Control.
  - Even though Sub-Controls and Control Enhancements are often required, they are usually missing from official and other sources' mappings.
<p></p>

* **Normalization of Controls across Control Sets** (vs. No points of reference for Control relationships and mapping)
  - Matching on a normalized taxonomy exposes the reason that Controls are mapped to each other.
  - Control mappings are no longer a mysterious black box.
<p></p>

* **Relation to Other Controls within the Same Control Set** (vs. Not knowing how Controls relate to each other)
  - See relations between Controls, irrespective of how they were organized in the Control Set.
<p></p>

* **Includes Mappings from Official and Other Sources** (vs. Having to go elsewhere for other mappings)
  - Referencing official and other mappings as a one-stop-shop.
  - Validation from mappings of official and other sources help ensure that normalizations are not being missed.
  - Official and other sources' mappings take a different, but still valid, approach.
  - Corollary:  "There's More Than One Way To Do It"  \[Perl motto]
  - Anti-Corollary: "There should be one — and preferably only one — obvious way to do it."  \[Zen of Python]
<p></p>
