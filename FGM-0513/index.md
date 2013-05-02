---
title       : HVTN204 Peptide Microarray Analysis
subtitle    : HVTN FGM, May 2013
author      : Raphael Gottardo
job         : Associate Member, Fred Hutchinson Cancer Research Center
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
logo: Logo.png
license: by-nc-sa
---
















## Array design overview and goals

* Identify regions of the HIV viral envelope that elicit antibodies during natural infection or after vaccination
* Array of overlapping gp160 peptides:
    * Peptides mosaic designed by Bette Korber at LANL
    * 1423 peptides (15 mers) across 7 sub-types
    * Serum + secondary antibody = Reactive peptides

* Data analyzed as described in Imholte *et al.* (2013, submitted to *JIM*).

---

## Aggregate response rate vs. HxB2

<img src="figure/hvtn-aggregate.png" title="plot of chunk hvtn-aggregate" alt="plot of chunk hvtn-aggregate" width="850px" />


<footer class="source">The aggregate response represents an average of all sub-types.</footer>  
Basically, we can only see <span class="red">two clear reactive regions in C1 and V3.</span>

---

## Subtype specific response rates

<img src="figure/hvtn-subtype.png" title="plot of chunk hvtn-subtype" alt="plot of chunk hvtn-subtype" width="850px" />

As expected &mdash; HVTN204 inserts are A, B, and C env &mdash; A, B and C show the largest response. <span class="red">There is virtually no CRF01 response.</span>

---

## Effect of Ad5 status on response rates

<img src="figure/aggregate-response-by-ad5.png" title="plot of chunk aggregate-response-by-ad5" alt="plot of chunk aggregate-response-by-ad5" width="850px" />

Prior Ad5 infection does not appear to induce a larger response. 
<span class="red">The profiles for Ad5+ and Ad5- individuals look similar.</span>

---

## How does HVTN204 compare?

<img src="figure/comparison-to-other-vax.png" title="plot of chunk comparison-to-other-vax" alt="plot of chunk comparison-to-other-vax" width="850px" />

C1 and V3 are comparable to RV144 and Vax003/004 but <span class = 'red'>no V2 and C5 responses.</span>

--- .thank-you-slide .segue
<aside class="gdbar right"><img src="assets/img/Logo.png"></aside>

## Acknowledgments

* David Montefiori (Duke)
* Robert Bailer and Ellen Turk (NVITAL)
* Bette Korber (LANL)
* Xiaoying Shen and Georgia D. Tomaras (Duke)
* MHRP, HVTN and CAVD.

