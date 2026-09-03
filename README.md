<!-- ============================================================
     Casten-Wang · GitHub Profile
     Brand: infini — The Future Is Here (未来已来)
     Palette: violet #7C3AED · fuchsia #C026D3 · cyan #64FFDA
              violet-soft #A78BFA · ink #05060A · muted #9AA3BD
     All visuals are dynamic SVG services (GitHub strips CSS/JS).
     ============================================================ -->

<!-- ────────────  HERO  ──────────── -->
<div align="center">

<img width="100%" alt="infini — The Future Is Here"
     src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:C026D3,100:64FFDA&height=300&section=header&text=infini&fontSize=96&fontColor=ffffff&fontAlignY=40&font=Space%20Grotesk&desc=Casten%20Wang%20%C2%B7%20LLM%20Inference%20%26%20GPU%20Kernels&descSize=20&descAlignY=62&animation=fadeIn" />

<!-- animated tagline -->
<a href="https://github.com/Casten-Wang">
  <img alt="The Future Is Here"
       src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=27&pause=1100&color=A78BFA&center=true&vCenter=true&width=820&height=58&lines=The+Future+Is+Here;Optimizing+LLM+inference+from+operators+to+systems;Building+CUDA+%2F+HIP+kernels+for+real+hardware;Measure+first.+Optimize+what+matters." />
</a>

<br/>

**未来已来** &nbsp;·&nbsp; _building intelligence without limits_

<br/>

<img alt="Profile views"
     src="https://komarev.com/ghpvc/?username=Casten-Wang&label=PROFILE+VIEWS&color=7C3AED&style=for-the-badge" />
&nbsp;
<img alt="Focusing"
     src="https://img.shields.io/badge/%F0%9F%8E%AF-Focusing-C026D3?style=for-the-badge&labelColor=05060A" />
&nbsp;
<a href="https://github.com/Casten-Wang?tab=followers">
  <img alt="Followers"
       src="https://img.shields.io/github/followers/Casten-Wang?style=for-the-badge&label=FOLLOWERS&color=64FFDA&labelColor=05060A&logo=github&logoColor=64FFDA" />
</a>

<img width="100%" alt=""
     src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,50:C026D3,100:64FFDA&height=3&section=header" />

</div>

## About me

I'm a systems engineer focused on **LLM inference** and **GPU kernel optimization**. I enjoy tracing performance from model graphs down to memory access patterns, then validating improvements on real hardware.

- 🔧 &nbsp;Working on inference performance, CUDA/HIP kernels, quantization, and memory-bound operators
- 🖥️ &nbsp;Daily hardware: **AMD Radeon 8060S · gfx1151 (RDNA 3.5) · ROCm 7.1**
- 🌱 &nbsp;Exploring vLLM PD disaggregation, speculative decoding, and kernel autotuning
- 📐 &nbsp;Approach: **profile → isolate → optimize → verify correctness → benchmark**

## Featured work

### llama.cpp · RDNA 3.5 F32 `CONCAT` fast path

Added a shared-memory tiled-transpose path to the HIP backend for a non-contiguous F32 workload observed during Qwen3.6-35B-A3B prefill.

- **+4% to +12%** measured prefill throughput
- Bit-identical output for the copy/reorder operation
- No meaningful decode regression
- 32×32 shared-memory tiling with bank-conflict padding

<a href="https://github.com/ggml-org/llama.cpp/pull/28303">
  <img alt="View llama.cpp PR #28303"
       src="https://img.shields.io/badge/View%20on%20GitHub-llama.cpp%20PR%20%2328303-7C3AED?style=for-the-badge&logo=github&logoColor=ffffff&labelColor=05060A" />
</a>

## Toolbox

<p>
  <img alt="C++"        src="https://img.shields.io/badge/C%2B%2B-05060A?style=for-the-badge&logo=cplusplus&logoColor=64FFDA&labelColor=05060A" />
  <img alt="CUDA"       src="https://img.shields.io/badge/CUDA-05060A?style=for-the-badge&logo=nvidia&logoColor=64FFDA&labelColor=05060A" />
  <img alt="HIP / ROCm" src="https://img.shields.io/badge/HIP%20%2F%20ROCm-05060A?style=for-the-badge&logo=amd&logoColor=64FFDA&labelColor=05060A" />
  <img alt="Python"     src="https://img.shields.io/badge/Python-05060A?style=for-the-badge&logo=python&logoColor=64FFDA&labelColor=05060A" />
  <img alt="llama.cpp"  src="https://img.shields.io/badge/llama.cpp-05060A?style=for-the-badge&labelColor=05060A" />
  <img alt="vLLM"       src="https://img.shields.io/badge/vLLM-05060A?style=for-the-badge&labelColor=05060A" />
</p>

## GitHub activity

<div align="center">

<img width="82%" alt="Casten-Wang · GitHub profile summary"
     src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Casten-Wang&theme=radical" />

<img width="40%" alt="Most-used languages"
     src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Casten-Wang&theme=radical" />
<img width="40%" alt="Most productive time"
     src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Casten-Wang&theme=radical&utcOffset=8" />

</div>

<br/>

<div align="center">

_Interested in practical LLM systems performance, especially optimizations backed by reproducible measurements._

<img width="100%" alt="The Future Is Here"
     src="https://capsule-render.vercel.app/api?type=waving&color=0:64FFDA,50:C026D3,100:7C3AED&height=160&section=footer&text=The%20Future%20Is%20Here&fontSize=34&fontColor=ffffff&fontAlignY=64&animation=fadeIn" />

</div>
