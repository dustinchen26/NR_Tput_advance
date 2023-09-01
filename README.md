# NR Throughput Advanced Calculator
online calculator: https://dustinchen26.github.io/NR_Tput_advance

## Example
NR Throughput Calculator
```
Ref: Spec 38.306, 38.214. Rmax = Target code Rate R/1024

example: 
O-RAN.TIFG.E2E-Test.0-v04.00 chap 5.1.2 5G NR 

Input:
► J (Number of aggregated component carriers in a band): 1
► Layers (Maximum number of layers): 2
► Select Table: Table 5.1.3.1-1
► Select MCS Index: MCS Index 28
► f (Scaling factor): 1
► RB Allocation: 106 (40MHz)
► μ Value: 0 (15 kHz)
► OH Value: 0.14 (FR1 DL)
► TDD Pattern: 0.7857
► BLER (range 0~1, ex: 0.18): 0

Calculate:
NR Throughput: 133.678 Mbps

```
