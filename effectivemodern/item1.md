# Item 1 : Understand template type deduction

What's to remember ? 

+ Reference arguments are treated as non-reference arguments
+ For by-value arguments, constness and volatileness are ignored
+ Arrays decay into pointers unless specified otherwise