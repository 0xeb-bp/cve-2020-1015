# CVE-2020-1015
PoC for CVE-2020-1015

More detail available [here](https://0xeb-bp.github.io/blog/2020/05/12/cve-2020-1015-analysis.html)

To compile:
1. Create an empty C++ project in Visual Studio.
2. Add `cve_2020_1015.cpp` and `Source.idl` to the project as source files.
3. Compile `Source.idl`. This will generate three files: `Source_c.c`, `Source_h.h` and `Source_s.c`. 
4. Add the first two as source files to the project. 
5. Add `rpcrt4.lib` as an additional dependency to the project
6. Build! 
