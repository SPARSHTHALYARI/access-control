# access-control

## SomeContract Move Contract

This Move contract, named SomeContract, defines a structure (SomeStruct) with variables and functions demonstrating various access modifiers. It also includes a resource (SomeResource) and associated functions.

## Overview

- **SomeContract:** The main contract defining SomeStruct, functions, and a resource.
- **SomeStruct:**
  - Variables:
    - `a`: Can be read and modified from anywhere.
    - `b`: Can be read and modified from anywhere.
    - `c`: Can be read from anywhere but modified only within the contract.
    - `d`: Can be read and modified only within the struct.
  - Functions:
    - `publicFunc()`: Public function that can be called from anywhere.
    - `contractFunc()`: Function with contract-level access, can be called from within the contract.
    - `selfFunc()`: Function with self-level access, can be called from within the struct.

- **SomeResource:**
  - Variables:
    - `e`: An integer variable.
  - Functions:
    - `resourceFunc()`: Function demonstrating the usage of the resource.
