# PTX & SASS — The Real GPU Instruction Sets

PTX (NVIDIA's portable IR) and SASS (the actual per-architecture machine code) — what the CUDA compiler emits, how the SM executes it, and how to read it. Covers HMMA/WGMMA tensor-core instructions, LDMATRIX, sync primitives, predication, ptxas optimisations, with worked SASS examples from a hello-world kernel through to a CUTLASS-style WGMMA matmul. Includes an interactive SASS instruction decoder.

**Live site:** https://brendanjameslynskey.github.io/NVIDIA_GPU_21_PTX_and_SASS/

Part of the [NVIDIA GPU Architectures series](https://github.com/BrendanJamesLynskey/LLMs#nvidia-gpu-architectures).
