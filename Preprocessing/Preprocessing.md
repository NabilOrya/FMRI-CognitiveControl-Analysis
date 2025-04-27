# Preprocessing Pipeline
## Steps used:
- **Slice Timing Correction:** Adjusts for time differences across brain slices.
- **Realignment (Motion Correction):** Corrects head motion artifacts.
- **Coregistration:** Aligns functional images to anatomical scans.
- **Normalization:** Transforms images into a standardized brain space (MNI).
- **Smoothing:** Improves signal-to-noise ratio with Gaussian kernel smoothing (FWHM: 6 mm).
- **Quality Control:** Checks for motion artifacts and outliers
