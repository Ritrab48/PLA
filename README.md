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

I chose Static CMOS over pseudo NMOS/dynamic logic, because it has high noise immunity, zero static power dissipation

### PLA Schematic

<img width="1636" height="577" alt="image" src="https://github.com/user-attachments/assets/0fa15edf-e7dc-4ba2-a4c8-088f7cee31f2" />

### Layout

<img width="864" height="778" alt="image" src="https://github.com/user-attachments/assets/eb54e616-5138-4ed2-994e-8a5d68f6334e" />

### LVS
<img width="1348" height="677" alt="image" src="https://github.com/user-attachments/assets/99ac7b52-9096-450d-bdae-f98eab81e9a2" />

### DRC 
<img width="1335" height="758" alt="image" src="https://github.com/user-attachments/assets/c4c867e1-12dd-4c1f-8800-d1d949e88280" />


