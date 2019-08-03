# Kalman-Filter-Lab
KF - linear
EKF - nonlinear
UKF - highly nonlinear

μ: Mean of the prior belief 
σ^2: Variance of the prior belief 

v: Mean of the measurement 
r^2: Variance of the measurement

\tauτ: Mean of the posterior
s^2: Variance of the posterior

The new mean is a weighted sum of the prior belief and measurement means. With uncertainty, a larger number represents a more uncertain probability distribution.

μ' = (r^2 * μ + σ^2 * v)/(r^2 + σ^2)
σ^2' = 1/( (1/r^2)  + (1/σ^2)

The two Gaussians provide us with more information together than either Gaussian offered alone. As a result, our new state estimate is more confident than our prior belief and our measurement.
