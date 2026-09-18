![banner](./assets/bg.jpg)

<h1 align="center">Chang Chiang · 高性能计算工程师</h1>

- 📫 Email: [Chang_Chiang@outlook.com](mailto:Chang_Chiang@outlook.com)
- 🐙 GitHub: [Chang-Chiang](https://github.com/Chang-Chiang)
- 🔭 Focus: C++ Image Processing · HPC · Model Deployment
- 🌐 在线简历: [GitHub Pages](https://chang-chiang.github.io/Chang-Chiang/)

---

**📑 目录**

- [🔍 概览](#sec-overview)
- [🛠 核心技术栈](#sec-techstack)
- [💼 工作经历](#sec-work)
- [🚀 项目经历](#sec-projects)
- [📊 GitHub Stats](#sec-stats)

---

<a name="sec-overview"></a>

## 🔍 概览

- 🧰 **开发经验**：Linux 平台 C++ · **2 年**医疗影像设备领域，算法工程化落地经验丰富
- ⚡ **性能优化**：TMA 剖析 + SIMD/CUDA/多线程 · **9.6x** 加速（1621ms → 168ms）
- 🧠 **模型部署**：TensorRT/OpenVINO 双引擎 · GPU **≈20ms**/切面，主导开源框架 [**InferDeploy**](https://github.com/Chang-Chiang/InferDeploy)

<a name="sec-techstack"></a>

## 🛠 核心技术栈

- **编程语言**：[![C++](https://img.shields.io/badge/C%2B%2B-17/14/11-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/) [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/) [![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)](https://www.mathworks.com/products/matlab.html) [![x86 Assembly](https://img.shields.io/badge/x86%20Assembly-696969?style=flat-square&logo=intel&logoColor=white)](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html)
- **开发环境**：[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/) [![GCC](https://img.shields.io/badge/GCC-A42E2B?style=flat-square)](https://gcc.gnu.org/) [![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)](https://cmake.org/) [![GDB](https://img.shields.io/badge/GDB-41B4D0?style=flat-square)](https://www.sourceware.org/gdb/) [![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)](https://visualstudio.microsoft.com/)
- **性能分析**：[![Intel VTune](https://img.shields.io/badge/Intel%20VTune-0071C5?style=flat-square&logo=intel&logoColor=white)](https://www.intel.com/content/www/us/en/developer/tools/oneapi/vtune-profiler.html) [![Intel Advisor](https://img.shields.io/badge/Intel%20Advisor-0071C5?style=flat-square&logo=intel&logoColor=white)](https://www.intel.com/content/www/us/en/developer/tools/oneapi/advisor.html) [![Linux Perf](https://img.shields.io/badge/Linux%20Perf-DD4A22?style=flat-square&logo=linux&logoColor=white)](https://perf.wiki.kernel.org/) [![Flame Graph](https://img.shields.io/badge/Flame%20Graph-E8820C?style=flat-square)](https://github.com/brendangregg/FlameGraph)
- **性能优化**：[![SSE/AVX2](https://img.shields.io/badge/SSE%2FAVX2-0068B5?style=flat-square&logo=intel&logoColor=white)](https://www.intel.com/content/www/us/en/docs/intrinsics-guide/index.html) [![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-zone) [![OpenCL](https://img.shields.io/badge/OpenCL-000000?style=flat-square&logo=opencl&logoColor=white)](https://www.khronos.org/opencl/) [![OpenMP](https://img.shields.io/badge/OpenMP-4A8C2A?style=flat-square)](https://www.openmp.org/) [![MPI](https://img.shields.io/badge/MPI-2E5C8A?style=flat-square)](https://www.mpi-forum.org/) [![MKL](https://img.shields.io/badge/Intel%20MKL-0071C5?style=flat-square&logo=intel&logoColor=white)](https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html) [![LTO/PGO](https://img.shields.io/badge/LTO%2FPGO-8B5CF6?style=flat-square)](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html)
- **推理框架**：[![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/tensorrt) [![OpenVINO](https://img.shields.io/badge/OpenVINO-3B82F6?style=flat-square&logo=intel&logoColor=white)](https://docs.openvino.ai/) [![ONNX](https://img.shields.io/badge/ONNX-005FED?style=flat-square&logo=onnx&logoColor=white)](https://onnx.ai/)

<a name="sec-work"></a>

## 💼 工作经历

### 深圳开立生物医疗科技股份有限公司 · 软件工程师

*🗓 2024.04 – 2026.09*

- **算法工程化**：Matlab/Python 仿真方案 C++ 工程化落地，独立完成超声图像处理模块开发，推进模块化重构与技术文档沉淀
- **性能优化**：TMA 定位热点，SIMD 向量化 + 多线程并行 + 访存优化，ATI 整帧 1621ms → 168ms（**9.6x**）
- **推理部署**：主导超声主机 TensorRT 与 CUDA/cuDNN 多版本兼容性调研及推理环境搭建

<a name="sec-projects"></a>

## 🚀 项目经历

### 医学图像处理算法性能优化

*🗓 2024.06 – 2024.12*

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![AVX2](https://img.shields.io/badge/AVX2-0068B5?style=flat-square&logo=intel&logoColor=white) ![MKL](https://img.shields.io/badge/MKL-0071C5?style=flat-square&logo=intel&logoColor=white) ![OpenCL](https://img.shields.io/badge/OpenCL-000000?style=flat-square&logo=opencl&logoColor=white) ![VTune](https://img.shields.io/badge/Intel%20VTune-0071C5?style=flat-square&logo=intel&logoColor=white)

- **成果**：目标平台 i3-1115G4E 上 ATI 整帧耗时 1621ms → 168ms（**9.6x**），满足临床实时处理需求
- **剖析驱动**：VTune 全链路 TMA 剖析定位 Memory/Core Bound 瓶颈，按热点占比逐级实施优化
- **多层优化手段**：手写 SSE/AVX2 intrinsics；CUDA + cuFFT 批量化、前后处理 kernel 常驻显存；MKL DFTI 替代 `cv::dft`（948ms → 118ms、**8x**）；TBB 多线程；二维前缀和使 ROI 累加内存流量降低 160 倍；LTO 链接优化
- **跨平台与正确性**：OpenCL 覆盖 Intel/AMD/NVIDIA 无独显设备；分级验证规范——逻辑等价要求逐位一致、浮点重排允许 ulp 级差异

<details>
<summary>📊 剖析驱动优化闭环流程图（点击展开）</summary>
<br/>

```mermaid
flowchart LR
    A["🔍 VTune/Perf<br/>TMA 剖析"] --> B["🎯 定位瓶颈<br/>Memory / Core Bound"]
    B --> C["⚡ 按热点逐级优化<br/>SIMD · CUDA · MKL<br/>TBB · 前缀和 · LTO"]
    C --> D["✅ 分级验证<br/>逐位一致 / ulp 级容差"]
    D -- "未达目标 → 重新剖析" --> A
    D -- "达标" --> E["1621ms → 168ms 🚀 9.6x"]
    style A fill:#E3F2FD,stroke:#1565C0
    style B fill:#E3F2FD,stroke:#1565C0
    style C fill:#FFF3E0,stroke:#EF6C00
    style D fill:#E8F5E9,stroke:#2E7D32
    style E fill:#1565C0,stroke:#0D47A1,color:#fff
```

</details>

### 深度学习推理部署：CT/MR 关键切面检测与脏器分割

*🗓 2025.01 – 2025.04* | [🐙 InferDeploy](https://github.com/Chang-Chiang/InferDeploy)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white) ![OpenVINO](https://img.shields.io/badge/OpenVINO-3B82F6?style=flat-square&logo=intel&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

- **框架**：开源 InferDeploy 三层推理框架（Worker–InferTRT–Task），新任务仅重写预处理/后处理即可接入、零改核心代码
- **双引擎落地**：同一 ONNX 模型按设备自动选择 TensorRT GPU（≈20ms）或 OpenVINO CPU（≈100ms）引擎，覆盖 YOLO 关键切面检测与 UNet 脏器分割两任务
- **CUDA 三维后处理**：分割掩膜重建体数据 → 最大连通域筛选 → 3D 形态学开闭 → 3D 高斯平滑，支撑体积统计与三维可视化
- **吞吐与工程质量**：FP32/FP16/INT8 多精度 + INT8 校准链路（COCO 验证）；GPU 预处理 + 多 Stream 异步重叠提吞吐；RAII + `shared_ptr` 资源管理、六级日志与计时组件

<details>
<summary>🏗 双引擎部署架构图（点击展开）</summary>
<br/>

```mermaid
flowchart TB
    ONNX["📦 ONNX 模型"] --> GPU["🟢 TensorRT 引擎<br/>NVIDIA GPU · ≈20ms/切面"]
    ONNX --> CPU["🔵 OpenVINO 引擎<br/>无独显 CPU · ≈100ms/切面"]
    subgraph INF["InferDeploy 三层架构"]
        direction LR
        W["Worker 层<br/>极简对外接口"] --> I["InferTRT 核心层<br/>模型构建 + 推理执行"] --> T["Task 层<br/>预处理 / 后处理扩展"]
    end
    GPU --> POST["CUDA 三维后处理<br/>连通域筛选 · 形态学 · 高斯平滑"]
    CPU --> POST
    style ONNX fill:#F3E5F5,stroke:#7B1FA2
    style GPU fill:#E8F5E9,stroke:#2E7D32
    style CPU fill:#E3F2FD,stroke:#1565C0
    style POST fill:#FFF3E0,stroke:#EF6C00
```

</details>

### 性能分析与优化：知识体系与 TMA 实战（开源项目）

*🗓 2024.06 – 至今* | [🐙 Performance-Analysis-And-Tuning](https://github.com/Chang-Chiang/Performance-Analysis-And-Tuning)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Perf](https://img.shields.io/badge/Linux%20Perf-DD4A22?style=flat-square&logo=linux&logoColor=white) ![VTune/Advisor](https://img.shields.io/badge/VTune%2FAdvisor-0071C5?style=flat-square&logo=intel&logoColor=white) ![AVX2](https://img.shields.io/badge/AVX2-0068B5?style=flat-square&logo=intel&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![OpenMP](https://img.shields.io/badge/OpenMP-4A8C2A?style=flat-square) ![MPI](https://img.shields.io/badge/MPI-2E5C8A?style=flat-square)

- **知识体系**：27 篇技术文档 + 200 份 before/after 对照示例，覆盖性能度量 → 单核（ILP/DLP）→ 访存 → 并行的全链路
- **TMA 实战**：perf-ninja 16 项优化实验，加速比 1.14x ~ 70x（伪共享 15.8x、依赖链消除 20.9x、AVX2 15.1x、算法优化 70x）
- **方法论反哺**：完整 TMA 分析流水线 + 4 类优化 checklist，直接支撑"医学图像处理"项目 9.6x 加速落地

<details>
<summary>🧭 TMA 分析流水线图（点击展开）</summary>
<br/>

```mermaid
flowchart LR
    A["perf stat --topdown<br/>L1 瓶颈分类"] --> B["toplev -l2/-l3<br/>细粒度定位"]
    B --> C["perf record<br/>代码级采样"]
    C --> D["VTune Microbench<br/>交叉验证"]
    D --> E["🎯 定向优化<br/>编译/循环/访存/并行<br/>4 类 checklist"]
    style E fill:#1565C0,stroke:#0D47A1,color:#fff
```

</details>

<a name="sec-stats"></a>

## 📊 GitHub Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-trophy.vercel.app/?username=Chang-Chiang&theme=github-dark&no-frame=true&column=7"/>
    <img src="https://github-profile-trophy.vercel.app/?username=Chang-Chiang&theme=flat&no-frame=true&column=7" alt="trophy"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Chang-Chiang&show_icons=true&hide_border=true&theme=github_dark"/>
    <img src="https://github-readme-stats.vercel.app/api?username=Chang-Chiang&show_icons=true&hide_border=true" width="49%" alt="CC's github stats"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Chang-Chiang&layout=compact&hide_border=true&theme=github_dark"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chang-Chiang&layout=compact&hide_border=true" width="49%" alt="top langs"/>
  </picture>
</p>

<!---
Chang-Chiang/Chang-Chiang is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
