# SIMPLIFIED-WING: An MDO problem (January 2025)

Implementation of the problem described in:

Tribes, Dubé, Trépanier, *Decomposition of multidisciplinary optimization  
problems: formulations and application to a simplified wing design*.  
*Engineering Optimization*, 37(8):775–796, 2005.

## Problem specifications

- Input dimension: **7**
- Number of constraints: **3**
- Constraints must satisfy the form: **gᵢ(x) ≤ 0**

### Variable bounds

|                | x₁ | x₂  | x₃  | x₄   | x₅   | x₆  | x₇  |
|----------------|----|-----|-----|------|------|-----|-----|
| **Quantity**   | b  | Cᵣ  | λ   | αᵣ   | α₀ₜ  | dᵣ  | tᵣ  |
| **Lower bound**| 30 | 6   | 0.28| −1   | −1   | 1.6 | 0.30|
| **Upper bound**| 45 | 12  | 0.50| 3    | 3    | 5.0 | 0.79|
