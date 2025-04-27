# Contrast Description

## Overview
In this study, two main conditions were modeled during the antisaccade task:
- **NEUTRAL** condition: Task performed without reward.
- **REWARD** condition: Task performed with an incentive for correct performance.

To explore brain activation differences between these two conditions, we designed contrasts using the **General Linear Model (GLM)** framework in SPM.


## Contrasts Used

### 1. Reward > Neutral
- **Weight Vector**: `[1 -1]`
- **Interpretation**:  
  This contrast identifies brain regions that are **more active during the REWARD condition** compared to the NEUTRAL condition.  
  It helps investigate the **effect of reward** on cognitive control mechanisms.

### 2. Neutral > Reward
- **Weight Vector**: `[-1 1]`
- **Interpretation**:  
  This contrast identifies brain regions that are **more active during the NEUTRAL condition** compared to the REWARD condition.  
  It helps highlight areas that may **decrease in activation** when rewards are introduced, indicating **baseline cognitive control** activity.


## Reason for Choosing These Contrasts
Given the research goal to explore **cognitive control under reward influence**, it is important to test both directions:
- Where reward **enhances** brain activation (Reward > Neutral)
- Where reward possibly **suppresses** baseline cognitive effort (Neutral > Reward)

This two-way contrast design ensures a **comprehensive understanding** of how motivational factors modulate brain functions during inhibitory control tasks.

