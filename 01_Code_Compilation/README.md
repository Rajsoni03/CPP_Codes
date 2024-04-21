# C++ Code Compilation

YouTube Video : <br>
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Li2QuRJZBPo/hqdefault.jpg)](https://youtu.be/Li2QuRJZBPo?si=1gGtVRQs-B60s2ca)


Please refer to the [Table of Contents](../README.md) for the complete list of tutorials.

In this, we will cover the source code compilation steps in C++.

1. **Compiler** (Convert the source code into object code)
    ```bash
    # compile source file without linking 
    g++ -c source_file.cpp
    ```
2. **Linker** (Convert the object code into executable file)
    ```bash
    # linked object file with header and crteate executable file 
    g++ object_file.o -o executable_file.out
    ```
3. **Loader** (Convert the object code into executable file)
    ```bash
    # run the code
    ./executable_file.exe
    ```

<hr>

Bonus: (Convert the source code directly into executable file)
```bash
# compile and create executable file at once
# (source file -> executable file)
g++ source_file.cpp -o executable_file.out
```

<hr>

Join us in this video to gain a solid understanding of C++ from basics to advance.

Remember to like, share, and subscribe for more informative content on C++ programming!

[YouTube](https://www.youtube.com/@raj_soni03)
