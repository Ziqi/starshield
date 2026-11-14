# StarShield Documentation & Evidentiary Workpaper Portal

[![Live Portal](https://img.shields.io/badge/Live%20Portal-ziqi.github.io%2Fstarshield-0A66C2)](https://ziqi.github.io/starshield/)
[![Core Library: starshield-forensics](https://www.bestpractices.dev/projects/16602/badge)](https://www.bestpractices.dev/projects/16602)
[![OpenSSF Scorecard](https://img.shields.io/endpoint?url=https%3A%2F%2Fziqi.github.io%2Fstarshield%2Fscorecard.json)](https://github.com/Ziqi/starshield-forensics/actions/workflows/scorecard.yml)
[![Fuzzing: 10/10](https://img.shields.io/badge/Scorecard%20Fuzzing-10%2F10%20%28ClusterFuzzLite%29-brightgreen)](https://github.com/Ziqi/starshield-forensics/actions/workflows/cflite.yml)
[![PyPI](https://img.shields.io/pypi/v/starshield-forensics?label=PyPI%20%28PEP%20740%29&color=blue)](https://pypi.org/project/starshield-forensics/0.3.7/)
[![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/starshield-forensics/attestations)
[![UK FSR Statutory Code / ISO 17025 Validation](https://img.shields.io/badge/Validation-UK%20FSR%20%28FSA--DIG--100%29%20%26%20ISO%2017025%20Aligned-blue)](https://github.com/Ziqi/starshield-forensics/blob/main/VALIDATION_REPORT_FSR_ISO17025.md)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24145804.svg)](https://doi.org/10.5281/zenodo.24145804)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

**Official web documentation portal, OpenSSF Scorecard badge endpoint, and clean-room evidentiary triage workpaper repository for [`starshield-forensics`](https://github.com/Ziqi/starshield-forensics).**

---

## Quick Links

- **Live Documentation Portal:** <https://ziqi.github.io/starshield/>
- **Core Python Library & CLI (`starshield-forensics v0.3.7`):** <https://github.com/Ziqi/starshield-forensics>
  - **10-Second Zero-Install Showcase:** `uvx --from starshield-forensics starshield demo`
  - **OpenSSF Best Practices:** [`Project #16602 (Silver — 226%)`](https://www.bestpractices.dev/projects/16602)
  - **OpenSSF Scorecard & Fuzzing:** [`7.9 / 10 (Fuzzing 10/10 via ClusterFuzzLite/Atheris)`](https://github.com/Ziqi/starshield-forensics/actions/workflows/scorecard.yml) · [`SLSA Build Level 3`](https://github.com/Ziqi/starshield-forensics/attestations)
  - **PyPI Package (PEP 740 Attested):** `pip install starshield-forensics`
  - **Method Validation:** [`UK FSR Statutory Code (FSA – DIG 100) / ISO 17025 Summary`](https://github.com/Ziqi/starshield-forensics/blob/main/VALIDATION_REPORT_FSR_ISO17025.md)
  - **Zenodo Archival DOI:** [`10.5281/zenodo.24145804`](https://doi.org/10.5281/zenodo.24145804) (`v0.3.7`: [`10.5281/zenodo.24156262`](https://doi.org/10.5281/zenodo.24156262))
- **Sample Clean-Room Evidentiary Workpaper (PDF):** [`Sample_Evidentiary_Triage_Workpaper.pdf`](./Sample_Evidentiary_Triage_Workpaper.pdf) *(100% synthetic supplier-invoice benchmark scenario; zero real case data)*

---

## 中文说明（StarShield 在线文档与净室合成基准底稿门户）

本仓库承载 **[`starshield-forensics`](https://github.com/Ziqi/starshield-forensics)**（获颁 Linux 基金会 **OpenSSF Best Practices `Silver` 银牌 `#16602` [226%]**、**OpenSSF Scorecard `7.9/10` [含 `ClusterFuzzLite` 持续模糊测试 `Fuzzing 10/10`]** 及 **SLSA Level 3** 的纯离线电子数据取证工具包）的静态文档站点与标准化证据初筛工作底稿示例：

1. **在线门户站点**：[`https://ziqi.github.io/starshield/`](https://ziqi.github.io/starshield/)（由仓库根目录 `index.html` 驱动）。
2. **合成案例示范底稿**：[`Sample_Evidentiary_Triage_Workpaper.pdf`](./Sample_Evidentiary_Triage_Workpaper.pdf) 展示了如何按 `OBSERVED` / `DERIVED` / `INFERRED` / `UNKNOWN` 四级认知标准向律所与调查机构呈现技术初筛结论（内含数据 100% 为净室虚构测试向量）。
3. **源码安装与使用**：请前往主代码仓 **[`Ziqi/starshield-forensics`](https://github.com/Ziqi/starshield-forensics)**，直接执行免安装体验 `uvx --from starshield-forensics starshield demo` 或 `pip install starshield-forensics`。
