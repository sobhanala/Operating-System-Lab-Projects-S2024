# Operating Systems Lab — xv6 Extensions

An x86 xv6 coursework collection covering system calls, scheduling, synchronization, shared memory, and console behavior.

## Build and run

Use Linux or a suitable Unix development environment, GNU Make, an x86/32-bit GCC and binutils toolchain, and QEMU. On Windows, use a Linux environment with the required toolchain rather than native PowerShell.

```sh
git clone https://github.com/sobhanala/Operating-System-Lab-Projects-S2024.git
cd Operating-System-Lab-Projects-S2024/xv6
make
make qemu-nox
```

If the Makefile cannot locate your compiler or emulator, set its `TOOLPREFIX` and `QEMU` options for your environment. The Makefile defaults to four CPUs, matching the lab's multicore experiments.

The separate Linux kernel-module exercise under `EX1 - Introduction to xv6/Linux/` needs kernel headers matching the running kernel. Build or load kernel modules only in your intended lab environment.

## Contents

- `xv6/`: modified kernel and user programs.
- `EX1 - Introduction to xv6/` through `EX5 - Memory Managment/`: assignment descriptions and reports.
- `References/`: reference material.
- [Original experiment guide](docs/ORIGINAL_README.md): detailed console commands, system calls, scheduling policies, and lab workflows.

The repository name uses S2024, while the original experiment guide is labeled F2023. Both are preserved as source identifiers.

## License and attribution

Keep [LICENSE](LICENSE), [xv6/LICENSE](xv6/LICENSE), and the acknowledgments in [xv6/README](xv6/README). xv6 is upstream teaching code with additional coursework changes; this portfolio copy does not claim sole authorship.

No kernel build or QEMU run was performed during this documentation update.

## Project credits

This is Sobhan Alaeddini's portfolio fork of [Shahriar-0/Operating-System-Lab-Projects-S2024](https://github.com/Shahriar-0/Operating-System-Lab-Projects-S2024). The project was developed collaboratively; the upstream repository and Git history retain the original contributor credits. Documentation in this fork is maintained independently.
