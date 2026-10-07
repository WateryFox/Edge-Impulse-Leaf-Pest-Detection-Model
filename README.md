# Edge Impulse Leaf Pest Detection Model

This repository contains the standalone WebAssembly (WASM) and JavaScript deployment build exported from Edge Impulse for real-time leaf pest and disease classification. The model is optimized for lightweight, low-latency client-side inferencing on web and edge applications.

---

## Overview

The compiled model utilizes WebAssembly to execute machine learning inferencing directly inside modern web browsers or JavaScript runtimes without requiring external server-side API calls or cloud dependencies.

---

## Repository Structure

```text
.
├── LICENSE                        # Project license file
├── README.md                      # Project documentation
├── edge-impulse-standalone.js     # Edge Impulse JavaScript SDK runner
└── edge-impulse-standalone.wasm   # Compiled WebAssembly Machine Learning model
