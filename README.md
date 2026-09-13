# Veterinary Clinic Value-Creation & Acquisition Model

*Private Equity | Financial Modeling | Value Creation | Scenario Analysis*

> Financial-modeling project completed at **Lionchase North America** in support of underwriting for the **Acxtus Fund's approximately $20M veterinary clinic acquisition**.

---

## Overview

The objective was to develop a **five-year acquisition and value-creation model** translating operating improvements, redevelopment requirements, and capacity expansion into forward-looking cash-flow and investment economics.

The model incorporated:

* Revenue and operating assumptions
* Operating-cost reductions
* Redevelopment CAPEX
* Capacity expansion
* Cash-flow improvement
* NPV analysis
* Scenario and sensitivity analysis
* Comparable-property analysis

The purpose was to test whether the proposed operating and redevelopment strategy could create sufficient economic value to support the investment thesis.

---

## Investment Problem

A value-creation thesis is only meaningful if the proposed operational changes can be translated into measurable financial outcomes.

For this transaction, the model needed to answer:

* How much capital would redevelopment require?
* How would expanded capacity affect future operating performance?
* What happens if operating expenses are reduced?
* How does the resulting cash-flow profile change?
* What is the present value of those future economics?
* Which assumptions have the greatest impact on investment value?
* How does the asset compare with relevant properties?
* What happens if execution is weaker than expected?

The financial model therefore served as the bridge between the **operating plan and investment decision**.

---

## What I Built

I built a **five-year value-creation and acquisition model** incorporating the major operational and financial assumptions affecting the transaction.

Key components included:

* Five-year operating forecast
* Revenue and operating-cost assumptions
* Redevelopment CAPEX
* Capacity-expansion assumptions
* Operating-efficiency improvements
* Cash-flow forecasting
* Net Present Value analysis
* Scenario and sensitivity analysis
* Comparable-property analysis

The operating plan included analysis around a targeted approximately **10% reduction in operating expenses**.

---

# Model Architecture

The model was structured using a view-based approach separating investment assumptions, financial transformation, and decision outputs.

---

## View 01 — Model Context

```text
                INVESTMENT THESIS
                       │
                       ▼
             ┌───────────────────┐
             │ VALUE-CREATION    │
             │      MODEL        │
             └─────────┬─────────┘
                       │
       ┌───────────────┼───────────────┐
       ▼               ▼               ▼
   OPERATIONS        CAPEX /        CAPACITY /
                    REDEVELOPMENT     EXPANSION
       │               │               │
       └───────────────┼───────────────┘
                       ▼
                  CASH FLOW
                       │
                       ▼
               INVESTMENT VALUE
```

The model translates the operating and redevelopment strategy into financial consequences.

---

## View 02 — Functional Architecture

```text
┌──────────────────────────────┐
│ Establish Base-Case          │
│ Operating Economics          │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Define Revenue &             │
│ Capacity Assumptions         │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Model Operating-Cost         │
│ Improvements                 │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Incorporate Redevelopment    │
│ CAPEX                        │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Forecast 5-Year Cash Flow    │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Calculate NPV                │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Run Scenario &               │
│ Sensitivity Analysis         │
└──────────────┬───────────────┘
               ▼
┌──────────────────────────────┐
│ Evaluate Investment Case     │
└──────────────────────────────┘
```

The architecture allows each operating assumption to be traced through the forecast to its impact on investment value.

---

## Value-Creation Logic

The operating strategy can be represented as two primary economic channels.

### Growth

**Capacity Expansion → Increased Service Capability → Revenue Growth → Higher Cash Flow**

### Efficiency

**Operating Improvements → Lower Operating Costs → Margin / Cash-Flow Improvement**

Redevelopment then acts as the required investment enabling portions of that future operating state:

**Redevelopment CAPEX → Expanded / Improved Asset → Future Operating Benefit**

The complete value-creation chain becomes:

**CAPEX + Operating Improvement + Capacity Expansion → Future Cash Flow → Present Value → Investment Economics**

---

## Net Present Value

The model evaluated the present value of projected future cash flows:

**NPV = Present Value of Future Cash Flows − Required Investment**

NPV provided a framework for comparing the expected economic benefits of the operating and redevelopment strategy with the capital required to execute it.

---

## Scenario & Sensitivity Analysis

Because the investment case depended on several assumptions, the model tested how changing those assumptions affected the transaction.

```text
                    BASE CASE
                        │
           ┌────────────┼────────────┐
           ▼            ▼            ▼
        UPSIDE        BASE        DOWNSIDE
           │            │            │
     Stronger Growth   Plan     Higher Costs /
     Better Execution           Lower Growth
           │            │            │
           └────────────┼────────────┘
                        ▼
                CASH-FLOW OUTCOME
                        │
                        ▼
                  NPV / VALUE
```

Sensitivity analysis focused on the assumptions most capable of changing the investment outcome, including:

* Revenue growth
* Operating-cost improvement
* Redevelopment CAPEX
* Capacity assumptions
* Operating margins
* Other key transaction assumptions

This provided visibility into both **upside potential and downside risk**.

---

## Comparable-Property Analysis

Comparable properties provided an external reference for evaluating the transaction's property economics and assumptions.

The analysis helped place the asset within a broader market context and provided another reference point when evaluating the investment case.

The analytical chain followed:

**Comparable Assets → Market Reference → Transaction Assumptions → Investment View**

---

## View 03 — Financial Model Implementation

```text
                 MODEL INPUTS
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
     REVENUE          OPEX           CAPEX
   ASSUMPTIONS     ASSUMPTIONS    ASSUMPTIONS
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                5-YEAR FORECAST
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
     REVENUE        COSTS          CASH FLOW
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                     NPV
                       │
                       ▼
             SCENARIO / SENSITIVITY
                       │
                       ▼
                INVESTMENT VIEW
```

The model creates direct traceability from individual operating assumptions to the resulting investment economics.

---

## What the Model Measures

| **Investment Question**                      | **Model Output**                                                      |
| -------------------------------------------- | --------------------------------------------------------------------- |
| **What does the future business look like?** | Five-year revenue, expenses, operating performance, and cash flow     |
| **What does the strategy require?**          | Redevelopment CAPEX and capacity investment                           |
| **Where does value creation come from?**     | Growth, cost reduction, capacity expansion, and operating improvement |
| **What is that future value worth today?**   | NPV and projected cash-flow economics                                 |
| **What happens if assumptions change?**      | Base, upside, downside, and sensitivity analysis                      |
| **How does the asset compare externally?**   | Comparable-property analysis                                          |

---

## Investment Impact

The model translated a physical and operational improvement plan into an investment-level financial framework.

It connected:

**Redevelopment → Operations → Revenue / Cost → Cash Flow → NPV → Investment Decision**

and:

**Assumption Change → Financial Impact → Sensitivity → Downside / Upside**

The project demonstrated how private-market investors can evaluate value creation by connecting **operating improvements, capital deployment, forward cash flows, and valuation** within a single acquisition model.
