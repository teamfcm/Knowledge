# Item 1 : Understand template type deduction
<a href="Knowledge/effectivemodern.html" class="fork">Return</a>

What's to remember ? 

```c++
template    <typename Type>
void        func(ParamType param);
```

+ ParamType is not necessarily Type
+ Reference arguments are treated as non-reference arguments
+ For by-value arguments, constness and volatileness are ignored
+ Arrays decay into pointers unless specified otherwise