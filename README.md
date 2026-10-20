# Beam Damage Detection using Machine Learning

Detects damage location and severity in a cantilever beam from vibration frequencies.

Method: Finite element beam model, then noisy frequency data, then Random Forest vs Neural Network.

Results: Location accuracy Random Forest 74.3%, Neural Network 75.5%, severity error Random Forest 4.52% Neural Network 4.19

Limits: Simulated data only, 1D beam, 5 frequencies. Not yet tested on real sensor data.
## Extra analysis
- Noise robustness: accuracy is high on clean data but falls quickly as sensor noise increases (see noise_robustness.png).
- Accuracy by location: see accuracy_by_location.png.

Conclusion: the approach needs noise-robust features or more sensors before real-world use.
