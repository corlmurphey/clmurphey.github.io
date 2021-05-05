---
title: "Vocal Fold Vibration"
excerpt: "Simulations of vocal fold polyp growth and vocal fold vibration <br/><img src='/assets/images/portfolio/vf_vibration.png'>"
permalink: /posts/vf
tags:
  - vf
  - sim
layout: archive
---
# Vocal Folds

## Growth
As a classical singer, vocal polyp growth is a frightening yet all too real risk of my hobby. Vocal polyps grow when the vocal folds beat as a result of extensive abuse of the vocal folds, such as by yelling, singing, or talking loudly and for extending periods of time. I developed a model of vocal polyp growth, predicting the magnitude of forces and duration of time required to cause initial polyp growth. Once a polyp begins to grow, polyps grow exponentially due to larger surface area interfering with the natural motion of the vocal folds.

## Vibration
Years later I revisited vocal fold modeling to look at vocal fold motion. For this project, I studied 1-dimensional motion of the vocal folds in the transverse plane of the larynx. Building on existing models that examine motion in the frontal plane of the body, this model provides a different perspective on vocal fold motion crucial for building patient-specific diagnostic tool.  The Symmetric and Asymmetric Motion videos below are described by 1D equations of motion and solved by MATLAB's ODE solver ODE 45.


The approximated 1D wave equation model is an attempt to describe vocal fold motion via the 1D wave equation. This model assumes the edges of the vocal folds move like a 1D vibrating string or membrane. In this model, the 1D wave equation is solved via d'Alambert's solution to the 1D wave equation using the finite difference method.   This model presents a decent approximation of the motion and may be a valuable approximation for fast simulation of vocal fold motion.
You can view the presentation for this project here.


## References
1. SP Kumar, and J. Svec, “Simulation of Vocal Fold Mucosal Waves & Synthetic Kymograms,” 2018. [Online]. Available: https://www.mathworks.com/matlabcentral/fileexchnge/<...>.
2. L. Cveticanin, “Review on Mathematical and Mechanical Models of the Vocal Cord,” Journal of Applied Mathematics, Oct. 30, 2012. https://www.hindawi.com/journals/jam/2012/928591/ (accessed Oct. 05, 2020).
2. S. Deshmukh, M. A. Ismail, and R. Singh, “Interpreting glottal flow dynamics for detecting COVID-19 from voice,” arXiv:2010.16318 [cs, eess], Oct. 2020, Accessed: Nov. 22, 2020. [Online]. Available: http://arxiv.org/abs/2010.16318.
2. Fariborz  Alipour et al., “Mathematical Models and Numerical Schemes for the Simulation of Human Phonation,” Current Bioinformatics, vol. 6, no. 3, pp. 323–343, 2011, doi: 10.2174/157489311796904655.
2. “Voice Acoustics: an introduction to the science of speech and singing.” https://newt.phys.unsw.edu.au/jw/voice.html (accessed Oct. 05, 2020).
2. P. Šidlof and J. Horáček, “Vocal fold motion and voice production: Mathematical modelling and experiment,” Forum Acusticum Budapest 2005: 4th European Congress on Acustics, Jan. 2005.
2. C. S. N. V. Bôas and S. T. Gobara, “A model to explain human voice production,” Phys. Educ., vol. 53, no. 3, p. 033001, Jan. 2018, doi: 10.1088/1361-6552/aaa0e3.
2. L. P. Fulcher, R. C. Scherer, A. Melnykov, V. Gateva, and M. E. Limes, “Negative Coulomb damping, limit cycles, and self-oscillation of the vocal folds,” American Journal of Physics, vol. 74, no. 5, pp. 386–393, May 2006, doi: 10.1119/1.2173272.
2. A. M. Chodara, C. R. Krausert, and J. J. Jiang, “Kymographic characterization of vibration in human vocal folds with nodules and polyps,” Laryngoscope, vol. 122, no. 1, pp. 58–65, Jan. 2012, doi: 10.1002/lary.22324.
2. T. B. Martonen, Z. Zhang, and R. C. Lessmann, “Fluid Dynamics of the Human Larynx and Upper Tracheobronchial Airways,” Aerosol Science and Technology, vol. 19, no. 2, pp. 133–156, Jan. 1993, doi: 10.1080/02786829308959627.
2. R. Mittal, B. D. Erath, and M. W. Plesniak, “Fluid Dynamics of Human Phonation and Speech,” Annual Review of Fluid Mechanics, vol. 45, no. 1, pp. 437–467, 2013, doi: 10.1146/annurev-fluid-011212-140636.
2. F. Alipour, D. A. Berry, and I. R. Titze, “A finite-element model of vocal-fold vibration,” J Acoust Soc Am, vol. 108, no. 6, pp. 3003–3012, Dec. 2000, doi: 10.1121/1.1324678.
2. A. Vasudevan, “The voice box : a fast coupled vocal fold model for articulatory speech synthesis,” University of British Columbia, 2017.
2. R. Mittal, X. Zheng, R. Bhardwaj, J. H. Seo, Q. Xue, and S. Bielamowicz, “Toward A Simulation-Based Tool for the Treatment of Vocal Fold Paralysis,” Front Physiol, vol. 2, May 2011, doi: 10.3389/fphys.2011.00019.
2. C. Tao, J. J. Jiang, and Y. Zhang, “Simulation of vocal fold impact pressures with a self-oscillating finite-element model,” The Journal of the Acoustical Society of America, vol. 119, no. 6, pp. 3987–3994, Jun. 2006, doi: 10.1121/1.2197798.
2. K. A. Stevens, “Geometry and Material Properties of Vocal Fold Models,” p. 118.
2. N. Tayama, K. Kaga, R. W. Chan, and I. R. Titze, “Functional Definitions of Vocal Fold Geometry for Laryngeal Biomechanical Modeling,” Ann Otol Rhinol Laryngol, vol. 111, no. 1, pp. 83–92, Jan. 2002, doi: 10.1177/000348940211100114.
2. “Geometry of human vocal folds and glottal channel for mathematical and biomechanical modeling of voice production - ProQuest.” http://search.proquest.com/docview/1034930964?accountid=14503&pq-origsite=summon (accessed Nov. 17, 2020).
2. N. Tayama, K. Kaga, R. W. Chan, and I. R. Titze, “Geometric Characterization of the Laryngeal Cartilage Framework for the Purpose of Biomechanical Modeling,” Ann Otol Rhinol Laryngol, vol. 110, no. 12, pp. 1154–1161, Dec. 2001, doi: 10.1177/000348940111001213.
2. I. R. Titze, “The physics of small‐amplitude oscillation of the vocal folds,” The Journal of the Acoustical Society of America, vol. 83, no. 4, pp. 1536–1552, Apr. 1988, doi: 10.1121/1.395910.
2. K. Ishizaka and J. L. Flanagan, “Synthesis of voiced sounds from a two-mass model of the vocal cords,” The Bell System Technical Journal, vol. 51, no. 6, pp. 1233–1268, Jul. 1972, doi: 10.1002/j.1538-7305.1972.tb02651.x.
2. B. H. Story and I. R. Titze, “Voice simulation with a body‐cover model of the vocal folds,” The Journal of the Acoustical Society of America, vol. 97, no. 2, pp. 1249–1260, Feb. 1995, doi: 10.1121/1.412234.
2. F. Alipour and I. Titze, “A Navier-Stokes solution of laryngeal flow during vocal fold oscillations,” Journal of The Acoustical Society of America - J ACOUST SOC AMER, vol. 96, pp. 3341–3342, Dec. 1994, doi: 10.1121/1.410660.
2. R. L. Miller, “Nature of the Vocal Cord Wave,” The Journal of the Acoustical Society of America, vol. 31, no. 6, pp. 667–677, Jun. 1959, doi: 10.1121/1.1907771.
