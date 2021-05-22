# Deterministic models for optimizing circular supply chain

## Overview

Supply chain has become an integral part of every company and also one of the most researched fields for optimizing, cutting costs and time. However, research on the environmental aspects of supply chain is just picking up its pace in the recent years.
Circular supply chain emerged as one of the potential solutions to reduce the carbon footprint of a company, be collecting back the products from the customers, recycling them and reusing the material to produce new goods.

In this project we use Linear Mixed Integer Programming techniques often termed as LMIP or Linear MIP, to optimize the costs and carbon footprint of a company at each stage of the circular supply chain. 

At a high level, the model is split into two major phases.

* Forward cycle
* Reverse cycle

There are variables that are common to both the cycles. 

*Variable dictionary is available in the report*

The final objective function looks as follows,

![MIP Model](https://github.com/ShravyaChalla/Optimization-of-Circular-supply-chain/blob/main/model.PNG)

## Tools

* We used **OpenSolver** to solve this model, with random sample of values extracted from a ship building example.
* Other tools like IBM'S CPLEX, Gurobi can be used to solve the model, but some of them are paid and licensed softwares.

## Scope

We primarily focus on deterministic models in this project. However there are stochastic and robust models that are extensively researched and developed. Literature review and references are presented in the report for future reference.