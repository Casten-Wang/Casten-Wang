<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0B1220,50:2563EB,100:22D3EE&text=Casten%20Wang&fontColor=FFFFFF&fontSize=42&fontAlignY=35&desc=LLM%20Inference%20%C2%B7%20GPU%20Kernels%20%C2%B7%20Systems%20Performance&descAlignY=58&animation=fadeIn" alt="Casten Wang — LLM inference and GPU kernels" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=720&lines=Optimizing+LLM+inference+from+operators+to+systems;Building+CUDA+%2F+HIP+kernels+for+real+hardware;Measure+first.+Optimize+what+matters." alt="Typing introduction" />
</a>

</div>

## About me

I'm a systems engineer focused on **LLM inference** and **GPU kernel optimization**. I enjoy tracing performance from model graphs down to memory access patterns, then validating improvements on real hardware.

- 🔧 Working on inference performance, CUDA/HIP kernels, quantization, and memory-bound operators
- 🖥️ Daily hardware: AMD Radeon 8060S · gfx1151 (RDNA 3.5) · ROCm 7.1
- 🌱 Exploring vLLM PD disaggregation, speculative decoding, and kernel autotuning
- 📐 Approach: profile → isolate → optimize → verify correctness → benchmark

## Featured work

### llama.cpp · RDNA 3.5 F32 `CONCAT` fast path

Added a shared-memory tiled-transpose path to the HIP backend for a non-contiguous F32 workload observed during Qwen3.6-35B-A3B prefill.

- **+4% to +12%** measured prefill throughput
- Bit-identical output for the copy/reorder operation
- No meaningful decode regression
- 32×32 shared-memory tiling with bank-conflict padding

➡️ [View ggml-org/llama.cpp PR #28303](https://github.com/ggml-org/llama.cpp/pull/28303)

## Toolbox

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/HIP%20%2F%20ROCm-ED1C24?style=for-the-badge&logo=amd&logoColor=white" alt="HIP and ROCm" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/llama.cpp-111827?style=for-the-badge" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/vLLM-7C3AED?style=for-the-badge" alt="vLLM" />
</p>

## GitHub activity

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Casten-Wang&theme=github_dark" alt="Casten's GitHub activity" />
</div>

<div align="center">

_Interested in practical LLM systems performance, especially optimizations backed by reproducible measurements._

</div>
