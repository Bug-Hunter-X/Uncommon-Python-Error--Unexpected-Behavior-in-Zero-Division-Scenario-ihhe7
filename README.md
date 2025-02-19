# Uncommon Python Error: Unexpected Behavior in Zero Division Scenario

This repository demonstrates an uncommon error in a simple Python function. The function `function_with_uncommon_error` exhibits unexpected behavior when both inputs are 0. Ideally, it should raise a ZeroDivisionError, but it returns 0 instead.

## The Bug

The bug lies in the lack of explicit handling for the case where both `a` and `b` are 0.  The function returns 0 silently instead of raising an exception, which may lead to hard-to-detect errors in larger applications. 

## The Solution

The solution modifies the function to explicitly check for both inputs being 0, thus raising the appropriate ZeroDivisionError for this specific edge case.
