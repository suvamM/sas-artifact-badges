# Static Analysis Symposium Artifact Badges

This repository contains the `Validated`, `Extensible` and `Available` badges for the Static Analysis Symposium (SAS) Artifact Evaluation. Please include the badges awarded to you in your artifact review. Refer to the SAS [Call for Artifacts](https://conf.researchr.org/home/sas-2021#Call-for-Artifacts) page for additional details on the badges.

## Latex code for adding the badges
There is no generic template to add the badges in the LNCS format. The following code snippet should help you get started with the badge placements. However, you might need to adjust the parameters to meet the publication requirements.

```\usepackage{graphicx}
\usepackage[firstpage]{draftwatermark}
\SetWatermarkText{\raisebox{22cm}{%
  \hspace{5cm} \includegraphics[scale=0.16]{figures/ValidatedBadge.png} \includegraphics[scale=0.16]{figures/ExtensibleBadge.png} \includegraphics[scale=0.16]{figures/AvailableBadge.png}%
}}
\SetWatermarkAngle{0}
```
This snippet is based on the code suggested by Claus Schatzle and Daniel Dietsch for the [VMCAI badges](https://github.com/schaetzc/vmcai-badges).

## Badges
The SAS Artifact Evaluation badges were designed by [Arpita Biswas](https://sites.google.com/view/arpitabiswas) and [Suvam Mukherjee](https://suvamm.github.io/).
