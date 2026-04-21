# No State for White Men

> *California declared racism a public health crisis. The state's own data says the reverse.*

A four-stage investigation into California's race-crime data and the institutional apparatus built on top of it. Single-file HTML, no build step, every claim traceable to a primary source.

**[Read the article →](https://dont-shoot-the-data.github.io/no-state-for-white-men/)**

---

## The Argument

California declared racism a public health crisis in 2020. Twenty-four years of arrest data, published by five consecutive Democratic Attorneys General, say the opposite of what the declaration claims. Whites are disproportionately the interracial victim class. Blacks are disproportionately the interracial perpetrator class.

The state's response has not been to correct the narrative. It has been to double down through four mechanisms. This article walks through each one, in order, using evidence the state itself published.

## The Four Stages

| | Stage | What Happens |
|---|---|---|
| **1** | **Fake racism** | County declarations, racelighting theory, the Chyna Gibson mural, Stephon Clark as narrative |
| **2** | **Data says opposite** | Clark reality-check, T-CLEAR, SacPD public records (4 crimes), cross-city confirmation, Emma Roark, CA DOJ Table 31 |
| **3** | **Call the critic racist** | Harris's 2015 implicit-bias training. Newsom on Prop 36 |
| **4** | **Take the money** | Advance Peace, reparations, the Chinese Exclusion counter-test, the money trail |

## The Data

| Source | What's in it |
|---|---|
| **Sacramento PRR** | ~20,000 case-level incident records from SacPD, Jan 2016 to Mar 2024. Four violent crime categories. Black-on-White outnumbers White-on-Black **11 to 1** for robbery, **5.7 to 1** for homicide, **4.9 to 1** for kidnapping, **4.4 to 1** for rape. |
| **Cross-city PRR** | Public records requests filed with California's ten most populous cities. Five complied with usable case-level data. Same rank order in every one. |
| **CA DOJ Table 31** | 24 annual "Crime in California" reports, 2000 and 2002 to 2024 (2001 is a duplicate of 2002 in the source). Black homicide arrest multiplier: **4.34× in 2015, 4.97× in 2024**. |
| **T-CLEAR study** | Original decade-long dataset of **304 transgender fatal violence cases**, 2015 to 2024, cross-referenced against court records, booking photos, and local news. **65.1% of identified suspects are Black. 4.79× population share.** |

## Key Findings

- Across 24 consecutive years of California arrest data published under five Democratic Attorneys General, the rank order of homicide-arrest disproportionality never changes.
- California entered the Union as a free state in 1850. The Black homicide arrest multiplier in California is **4.4×**. The same multiplier in Virginia, a Confederate state with 245 years of slavery, is **3.4×**. Slavery history does not predict the disparity.
- Chinese Americans in California faced more severe legal discrimination than Black Americans on every major civil-rights dimension. Their homicide arrest rate is **one-tenth** the Black rate. Historical legal discrimination does not predict the disparity either.
- In Sacramento's highest-profile police-shooting case, one of the two officers who shot Stephon Clark is Black.
- The "Advance Peace" gun-violence program in Richmond and Sacramento recruits exclusively Black and Brown men while citing white-structural causes in its own peer-reviewed literature. Both positions cannot be operational.

## Companion Projects

- **[California Race Crime Investigation](https://dont-shoot-the-data.github.io/california-crime-data/).** The full multi-city public records dataset, statewide analysis, objections-and-answers, and a Transparency Scorecard documenting which departments complied.
- **[T-CLEAR](https://dont-shoot-the-data.github.io/TCLEAR/).** Transgender Comprehensive Lethal Evidence Analysis Report. Ten years of case-level data.

## Repository Contents

```
index.html                 the article, single-file HTML
tclear-chart-a.png         T-CLEAR disproportionality chart (Stage 2)
chyna-gibson-mural.jpg     Sacramento mural image (Stage 1)
emma-roark.jpg             Emma Roark photo (Stage 2, in-focus case)
mikilo-rawls.jpg           suspect photo (Stage 2, in-focus case)
README.md                  this file
```

## View Locally

```bash
git clone https://github.com/dont-shoot-the-data/no-state-for-white-men.git
cd no-state-for-white-men
open index.html
```

No build. No package install. The page pulls Chart.js and Google Fonts from public CDNs. Everything else is inline or local. No analytics. No trackers.

## Methodology

Every claim in this article links to a primary source. Every chart is backed by a public records request or a government-published dataset. Sacramento's data was obtained through formal PRRs filed with the Sacramento Police Department; raw response files and the full dataset are available through the companion California Race Crime Investigation site. Statewide data comes from the California Attorney General's "Crime in California" Table 31 reports, linked inline.

When direct quotes appear, they are attributed to the original source with a link. No quoted passage exceeds fifteen words.

## License

All rights reserved. Contact for republication requests.
