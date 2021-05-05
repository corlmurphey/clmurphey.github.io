---
title: "Biventricular Pacing"
date: 2021-05-05
excerpt: "Model of biventricular contraction and electrical conduction due to stimulation by pacemaker electrodes<br/><img src='/assets/images/portfolio/biventricular-pacing.png'>"
permalink: /posts/bvp
tags:
  - bvp
  - sim
layout: archive
---

# Biventricular Cardiac Pacing

I worked with Professor Ellen Kuhl on computational models of the heart, skin, red blood cells, and vocal folds.  In this project, I developed a model of biventricular contraction and electrical conduction due to stimulation by pacemaker electrodes, implanted in the walls of both ventricles. Through this model, we were able to simulate EKGs representing electrical conductance of the myocardium viewed from  different planes of the heart.  The projections that simulate the EKG data are depicted on the right; pacing locations can be found to the left. (You can find the resulting conference paper below.)


## Voltage Conductance
Here you can visualize propagation of electrochemical voltages through the myocardium. Using a tetrahedral mesh of a healthy human heart with 3129 nodes and 11347 elements, a computational model based on the two- parameter Aliev-Panfilov excitation model was used to simulate the propagating depolarization and repolarization of the myocardium, with voltages φ between -80 and +20 mV [2].


## Resulting EKGs
To generate virtual ECG images, we project the heart vector onto six predefined lead vectors that mimic the six frontal leads of electrocardiogram electrodes within the plane of the person’s chest. Each of the six electrocardiogram leads displays a characteristic temporal evolution in voltage in the ventricular myocardium.

## Conference Paper
