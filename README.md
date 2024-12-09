# Tcl Division by Zero Bug

This repository demonstrates a common error in Tcl:  division by zero within a procedure. The `bug.tcl` file contains a procedure that does not handle the case where division by zero may occur. The `bugSolution.tcl` file provides a corrected version that avoids the error. 

## How to Reproduce the Bug

1. Run `bug.tcl`. 
2. Observe the error message indicating division by zero.

## Solution

The solution involves adding a check to prevent division by zero before executing the `expr` command.