---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Midterms
---
# PURPOSE OF TRENDS 
---
- Purpose of Trends is to reduce failures and costs of computer systems used by businesses.

# TECHNOLOGY
---
- 
## Bandwidth
- Bandwidth refers to the amount of work done in a given amount of time. *volume*, *throughput*
## Latency
- Latency refers to the speed in which work is accomplished. *speed*, *response time*

# POWER AND ENERGY
---
## Maximum Power 
### Voltage Indexing Methods
- Voltage Indexing Methods allows processors to slow down and regulate voltages with a wider margin which ***[ trade-off ]** results in lower performance.*
## Sustained Power Consumption
- Sustained Power Consumption is measured by Thermal Design Power or TDP which determines the cooling requirement
### TDP for Power Supplies
- Power Supplies typically exceed the Thermal Design Power or TDP of a computer system
### TDP for Cooling Systems
- Cooling Systems are usually designed to match the Thermal Design Power or TDP of a computer system
## Energy Efficiency
### Power or Power  Consumption
- Power refers to the amount electricity that is needed to power or operate a computer system
- Power Consumption is useful for setting constraints when designing a computer system
$$ \textbf{power} = \frac{energy}{unit\; of \; time}$$
### Energy or Energy Consumption
- Energy refers to the amount of electricity used by the computer system in a given amount of time
- Energy Consumption is useful for comparing the efficiency between different computer systems.
$$ \textbf{energy\; consumption} = average\; power\; x \; execution\; time$$
### Assumptions on Large Servers and Cloud
- Large Servers and Cloud are assumed to have an infinite workload
# COST
---
## Learning Curve
- Learning Curve is a phenomenon in which manufacturing costs decrease over time.
## Yield
- Yield refers the percentage of manufactured devices that survive testing procedures.
## Wafer
- Wafer is a thin slice of a semiconductor, such as silicon, and is used in the fabrication of integrated circuits.
## Die 
- Die is a small block of semiconducting material cut from a wafer in which a functional circuit is fabricated.
## Cost Formulas
### Cost of an Integrated Circuit or IC
- The following is the formula for obtaining the cost of manufacturing a single Integrated Circuit:
$$ \textbf{cost}_{\textbf{IC}} = \frac{cost_{die} + cost_{testing\; die} + cost_{packaging\; and \; final\; test}}{final\; test\; yield}$$
### Cost of a Die
- The following is the formula for obtaining the cost of manufacturing a single Die:
$$ \textbf{cost}_{\textbf{die}} = \frac{cost_{wafer}}{dies\; per\; wafer\; \cdot\; die \; yield} $$
### Dies Per Wafer
- The following is the formula for obtaining the number of dies that can be fabricated from a single wafer
$$\textbf{dies\; per\; wafer} = \frac{\pi\; \cdot\; (\frac{wafer\; diameter}{2})^2}{die\; area}-\frac{\pi\; \cdot\; wafer\; diameter}{\sqrt{2\; \cdot\; die\; area}}$$
### Die Yield or Bose-Einstein Formula
- The following is the formula for the percentage of die yield from a wafer
$$\textbf{die\; yield} = wafer\; yield\; \cdot\; \frac{1}{(1 + defects\; per\; unit\; area\; \cdot\; die\; area)^N}$$
# DEPENDABILITY
---
- Dependability analyzes whether a system is operating properly
## Service Level Agreements (SLA) or Service Level Objectives (SLO)
- Service Level Agreements (SLA) or Service Level Objectives (SLO) are guarantees made internet providers that their network is dependable
## Service Accomplishment
- Service Accomplishment is when the specified service is delivered
## Service Interruption
- Service Interruption is when the delivered service is different from the SLA
## Redundancy
- Redundancy is a method of improving dependability through the use of backup or redundant components.
$$\textbf{MTTF} = \frac{\frac{MTTF}{n}}{\frac{MTTR}{MTTF}} = \frac{\frac{MTTF^n}{n}}{MTTR}=\frac{MTTF^n}{n\; \cdot\; MTTR}$$
# MODULE RELIABILITY
---
- Module Reliability is the continuous service accomplishment from a reference initial instance *(or ti time of failure)*
- Module Reliability is measured in mean time to failure *(MTTF)* or failure per billion hours of operation  *(FIT or Failure in Time)*
$$ \textbf{MTTF\; 1,000,000,000} = \frac{1,000,000,000}{1,000,000} \; or \; \textbf{1000\; FIT}$$
## Service Interruption
- Service Interruption is measured as mean time to repair *(MTTR)*
$$\textbf{MTBF} = MTTF + MTTR$$
## Module Availability
- Module Availability is the measure of service accomplishment with respect to the alternations between the two states of accomplishment and interruption
$$\textbf{module\; availability} = \frac{MTTF}{MTTF + MTTR}$$