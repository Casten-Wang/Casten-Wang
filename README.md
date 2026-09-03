### Hi, I'm Casten 👋

Systems engineer focused on **LLM inference** and **GPU kernel optimization** —
digging into low-level performance on the llama.cpp / ggml CUDA-HIP backend and
AMD GPUs.

- 🔧 **Work on:** inference performance, CUDA/HIP kernels, quantization, memory-bound ops
- 🖥️ **Daily hardware:** AMD Radeon 8060S · gfx1151 (RDNA3.5) · ROCm 7.1
- 🌱 **Exploring:** vLLM PD-disaggregation, speculative decoding, kernel autotuning

#### Recent work

- **llama.cpp** — added a shared-memory tiled-transpose fast path for F32 `CONCAT`
  on RDNA3.5. Measured prefill speedups of **+4% to +12%** with no decode
  regression and bit-identical output.
  → [ggml-org/llama.cpp#28303](https://github.com/ggml-org/llama.cpp/pull/28303) (open)

#### Tech

`C++` · `CUDA` · `HIP / ROCm` · `Python` · `llama.cpp / ggml` · `vLLM`

<!--
  Optional GitHub stats card — uncomment if you want it:
  ![Casten's stats](https://github-readme-stats.vercel.app/api?username=Casten-Wang&show_icons=true&hide_rank=true)
-->
