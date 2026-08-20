`2026-7001-D/README.md`

---

**CLASSIFICATION**: D  

**Document Reference**: `2026-7001-D-read-000`  

# Stack Asset Registry  
### Tooling  

**Version**: 0.1  

William Murray  
Research Architect  
19 August 2026  

**Status**: Draft  

**Scope**  
This registry provides a unified index of all major digital assets within the `stack` directory. It includes specifications, whitepapers, and operational tooling that collectively define and support the local AI engineering environment.

**Primary Model / Scheme**  [2026-0001-D-tmpl-001](https://github.com/WilliamMurray-research/2026-0001-D/blob/main/docs/tmpl/001.md)  

---

<div align="center">

  <h1>Stack Assets</h1>

| Document Reference | Version | Title | Description |
|---|---|---|---|
| stack-software-specs-000 | 0.1 | Software Specifications Registry | Registry of all specification documents governing architecture, workflows, and tooling within the software subsystem. |
| stack-software-000 | 0.1 | Software Whitepaper Registry | Registry of all whitepapers describing conceptual models, engineering patterns, and system‑level reasoning for the local AI stack. |
| stack-tools-000 | 0.1 | Bash Tools Registry | Index of lightweight Bash utilities for GPU control, resource tracking, and system monitoring within the engineering environment. |

</div>

---

# Bash Tools Registry  
**Document Reference**: `stack-tools-000`  

This section provides a top‑level overview of the operational Bash utilities included in the `tools` subsystem. These scripts support hardware control, experiment tracking, and general system observability within the local AI engineering stack.

---

## Included Toolsets

- **FanManagement**  
  GPU fan control utilities for maintaining stable thermals during long‑running workloads.

- **ResourceTracking**  
  Lightweight runtime tracking utilities for CPU, GPU, memory, and wall‑clock usage.

---

## Directory Structure
```
stack/
├── software/
│   ├── specs/
│   └── whitepaper/
│
├── tools/
│   ├── FanManagement/
│   ├── ResourceTracking/
│   ├── LICENSE
│   └── README.md
│
└── README.md
```

---

## Dependencies
- Bash  
- nvidia-smi  
- Standard Linux utilities  

---

## Notes
These tools are intentionally minimal and designed for personal use within a local AI engineering workflow. Additional utilities will be added as the stack evolves.

---

