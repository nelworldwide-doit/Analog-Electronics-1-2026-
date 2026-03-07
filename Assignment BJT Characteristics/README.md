# BJT Characteristics Simulation (2N2222)

## DC Sweep Settings

Base current sweep:
.dc I1 0 1m 1u

Collector sweep:
.dc V1 0 10 0.1 I1 0 200u 50u

## Observations

The collector current increases as the base current increases. 
The relationship is approximately linear but not perfectly linear because the transistor current gain β changes with current.

## Estimated β values

IB = 0.1 mA 
IC ≈ 10 mA 
β ≈ 100

IB = 0.5 mA 
IC ≈ 55 mA 
β ≈ 110

IB = 1.0 mA 
IC ≈ 105 mA 
β ≈ 105

## Output Characteristics

For increasing base current, the collector current curves shift upward. 
When VCE is large, the transistor operates in the active region. 
When VCE becomes very small, the transistor enters saturation.
