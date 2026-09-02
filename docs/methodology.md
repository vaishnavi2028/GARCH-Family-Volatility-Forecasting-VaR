# Methodology

## Log Returns

r_t = ln(P_t / P_{t-1})

## GARCH(1,1)

σ²_t = ω + αε²_{t-1} + βσ²_{t-1}

## GJR-GARCH

The GJR-GARCH specification introduces an asymmetric response
to negative shocks.

## Value-at-Risk

VaR is estimated using the conditional volatility forecast
and the fitted Student-t innovation distribution.

## Kupiec Test

The unconditional coverage test evaluates whether the observed
frequency of VaR breaches is consistent with the target
confidence level.
