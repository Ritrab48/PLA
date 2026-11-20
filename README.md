# 1.Project Overview
1. Technology node: 180nm
2. EDA tool: Cadence Virtuoso (Schematic, Layout XL, Calibre, Spectre)
3. Logic style: Static CMOS
4. Total Silicon Area: 0.11 mm^2
5. Total Power Consumption: 47.03 uW

# 2.Design Architecture
### Boolean functions
1. 𝑭𝟏(A,B,C,D)=∑𝒎(0,2,3,4,6,7,9,11,12,14,15)
2. 𝑭2(A,B,C,D)=∑𝒎(1,2,5,6,8,11,13,14)

### 4-Input PLA Truth Table
| A | B | C | D | $F_1$ | $F_2$ |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 0 | 0 | 0 | 0 | 1 | 0 |
| 0 | 0 | 0 | 1 | 0 | 1 |
| 0 | 0 | 1 | 0 | 1 | 1 |
| 0 | 0 | 1 | 1 | 1 | 0 |
| 0 | 1 | 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 0 | 1 | 1 |
| 0 | 1 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 0 | 0 | 1 |
| 1 | 0 | 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 | 1 | 1 |
| 1 | 1 | 0 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 1 | 1 | 0 |

