# jli_lib

Rebuilding a public version of my PhD tools that have been either lost (RIP) or hidden away in private repos. Now with cleaner structure and modernized practices.

## Initial framework

This repository is intentionally organized into modular sections so each area can be expanded independently:

- `src/jli_lib/regression_tools/` – regression-oriented Python utilities
- `src/jli_lib/data_processing_tools/` – data cleaning/transformation Python utilities
- `src/jli_lib/dft_tools/` – DFT workflow and analysis Python utilities
- `src/jli_lib/bash_tools/` – Python-side interfaces/wrappers for shell tooling
- `bash_tools/` – reusable bash scripts and shell function libraries
- `examples/` – usage examples and demos

## Layout

```text
.
├── bash_tools/
├── examples/
└── src/
    └── jli_lib/
        ├── bash_tools/
        ├── data_processing_tools/
        ├── dft_tools/
        └── regression_tools/
```

## Next steps

As modules are added, each section can be fleshed out with focused functions, tests, and examples without changing the top-level structure.
