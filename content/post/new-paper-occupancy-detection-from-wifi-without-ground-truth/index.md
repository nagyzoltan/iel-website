---
title: "New Paper: Occupancy detection from WiFi without ground-truth"
date: 2022-04-16T19:06:22.045Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
We have a new paper out in Building & Environment, led by our former lab member Prof June Park (UT Arlington).

June Young Park, Kingsley Nweye, Edward Mbata, Zoltan Nagy, *CROOD: Estimating crude building occupancy from mobile device connections without ground-truth calibration*, Building and Environment, Volume 216, 2022,
<https://doi.org/10.1016/j.buildenv.2022.109040>.

**Abstract:** The occupancy information in buildings is fundamental for smart buildings (e.g., occupant-centric controls). Opportunistic occupancy detection (OOD) uses connection data of mobile devices. While OOD has been developed and applied, one critical drawback is that it requires the ground truth of occupants to calibrate, which is limited to gather. Here, we introduce CROOD: a capture and recapture (CRc) inspired OOD. In ecology, CRc has been established for the estimation of animal populations, when the manual count is impossible. We adopt this unique approach to estimate the number of mobile devices in a building. Then, using a simple estimate on the total population, CROOD determines the relationship between the numbers of occupants and mobile devices. We evaluate CROOD numerically on the synthetic building populations and demonstrate its application in a university library using WiFi connection data. We find that CROOD can estimate the number of mobile devices and subsequently the number of occupants with 1–2 weeks to converge a reasonable accuracy. A long term experiment shows that CROOD can adapt to varying population characteristics (e.g., occupants bring more mobile devices), outperforming the reference sample mean estimator. The real building implementation demonstrates that while in the first 1–2 weeks, the sample mean estimator is superior, eventually CROOD adapts and provides better estimates without ground-truth calibration. Although CROOD has a limitation of building types and systems, our results envision that CROOD could be a viable addition to other OOD methods to better utilize existing mobile device connection data to estimate occupancy in buildings.
Keywords: Smart building; Occupant behavior; Building occupancy; Opportunistic sensing; Capture and recapture estimation