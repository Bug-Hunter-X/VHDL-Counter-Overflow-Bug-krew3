# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: an integer overflow in a counter. The provided `counter_bug.vhdl` file contains a simple counter that does not handle overflow correctly. The `counter_solution.vhdl` file shows the correct implementation.

## Bug Description

The original counter code increments indefinitely, leading to an overflow when it exceeds its maximum value (15 in this case). This can cause unexpected behavior in simulations and hardware implementation.

## Solution

The solution code adds an overflow check before incrementing the counter.  If the counter reaches its maximum value, it resets to zero.

## How to Use

1.  Clone this repository.
2.  Simulate both `counter_bug.vhdl` and `counter_solution.vhdl` using your preferred VHDL simulator.
3.  Observe the differences in behavior, particularly when the counter approaches and exceeds its maximum value.
