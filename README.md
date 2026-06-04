# QUBO-Inspired Inventory-Aware PCB Drill-Bit Optimization

This repository provides the source code and synthetic CSV input data for the paper:

**QUBO-Inspired Inventory-Aware Optimization for PCB Drill-Bit Allocation and Production Sequencing**

## Overview

This project demonstrates a CSV-driven QUBO-inspired decision framework for PCB drill-bit allocation and production sequencing. The model compares traditional greedy policies with a balanced dynamic method that considers tool-change count, dynamic drill-bit cost, due-priority penalty, quality rules, and inventory-overuse penalty.

## Repository Structure

```text
src/
  drill_bit_csv_driven_dynamic_inventory_inventory_aware_v3.py

data/
  production_plan_template.csv
  drill_inventory_template_corrected.csv
  daily_policy_template.csv
  hole_regrind_rule_template.csv

results/
  best_sequence_summary.csv
  common_evaluation_summary.csv
  inventory_usage_summary.csv
  sequence_summary.csv
