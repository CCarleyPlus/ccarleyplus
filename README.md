# CCarleyPlus

CCarleyPlus is a language inspired by Lua , JavaScript , C++.

It has a fast compiler faster than Lua, LuaJIT and close times to C. CCarleyPlus allows the developer to allocate memory before usage, This makes it so anything you write will not cause to error due to memory allocation errors. String functions & Math functions are made easier.


# Usage

CCarleyPlus relies heavily on type checking similar to Type-Script this is to prevent commone errors, Currently the compiler is not available to the public however the compiler will come out late 2023.

Varibles which are not used will not be stored in the memory to maximize performance.

# Example

```sh
print::output -> (String: "f");
```
`print::output` is used to display the variable in the output, once you define the function you must include a STRING , INT. Semicolons is a need in this language which is the breakpoint.

Handling Errors

```sh
.catch(String: Error_Param) -> print::output -> (String: Error_Param);
```
`.catch` is used to catch the error then you must pass the type and variable. Once passed you can output it by doing `.catch(String: Error_Param-> print::output -> (String: Error_Param);` 
