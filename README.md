# Production System Simulation – Engineomatic Inc.

Discrete-event simulation project completed as part of the **Simulation of Production Systems (MPR271)** course at Chalmers University of Technology.

## Project Overview

This project investigates the production system of Engineomatic Inc., a company producing steel components for high-end engines. The objective was to identify bottlenecks and evaluate improvement strategies to increase production throughput and delivery precision while working within a fixed investment budget of **$150,000**.

The production system was modeled and analyzed using **Siemens Tecnomatix Plant Simulation**.

## My Role

**Team members:**
- Aakarsh Sudhakaran
- Vaishal Ashish Solanki

The project involved developing and analyzing the discrete-event simulation model, performing bottleneck analysis, evaluating improvement alternatives, and implementing the selected improvements within the investment constraint.

## Methodology

The study followed a discrete-event simulation approach:

1. Problem formulation
2. Conceptual modeling of the production system
3. Development of the simulation model in Tecnomatix Plant Simulation
4. Model verification and validation
5. Bottleneck identification using resource statistics
6. Theory of Constraints (TOC) analysis
7. One Factor at a Time (OFAT) experiments
8. Evaluation of improvement alternatives
9. Comparison of base and improved system performance

## Production System

The modeled production system included:

- Cutting
- Turning and grinding
- Polishing
- Surface treatment
- Cooling
- Inspection and packaging
- Buffers and material flow
- Machine failures and maintenance

The model represented different product dimensions and incorporated production variability, processing times, failures, buffers, and maintenance resources.

## Bottleneck Analysis

Bottlenecks were identified using simulation observations and resource statistics, including:

- Working time
- Blocked time
- Failure time
- Waiting time

The analysis was combined with **Theory of Constraints** to identify constraints limiting production throughput.

OFAT experiments were then used to evaluate the effect of individual changes on system throughput.

## Improvement Strategy

A total of **17 improvements** were evaluated within the $150,000 investment budget.

Examples included:

- Reducing processing times
- Increasing buffer capacities
- Increasing MTBF
- Reducing MTTR
- Increasing conveyor speed
- Adding a fixture
- Enabling machines to process different product dimensions
- Updating the control system
- Adding maintenance capacity

The final investment plan used the complete **$150,000 budget**.

## Results

The base model produced approximately **140 products** in the simulated week.

After implementing the proposed improvements, the improved model produced approximately **317 products**.

The project reported a **126% increase in productivity** compared with the base system.

The mean simulated output increased from **129.79 products to 284.26 products**.

The analysis also showed substantial changes in machine utilization, blocking, and failure behavior across the production system.

## SimTalk

The model included SimTalk programming for several aspects of the production system, including:

- Cutting method and product generation
- Processing-time changes
- Product routing
- Product delivery
- Material ordering
- Part movement
- Rework logic

## Tools & Methods

- Siemens Tecnomatix Plant Simulation
- Discrete-Event Simulation (DES)
- SimTalk
- Theory of Constraints (TOC)
- Bottleneck analysis
- One Factor at a Time (OFAT)
- Experiment Manager
- Resource statistics
- MTBF / MTTR analysis

## Project Report

The complete project report is included in this repository.

## Note

This was an academic simulation project based on the Engineomatic case provided as part of the MPR271 Simulation of Production Systems course at Chalmers University of Technology.

The simulation results are dependent on the assumptions and limitations of the model and therefore should not be interpreted as direct predictions of real-world production performance.
