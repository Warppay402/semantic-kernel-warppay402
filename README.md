# Semantic Kernel Plugin for WarpPay402

This package provides Microsoft Semantic Kernel plugin bindings for WarpPay402 x402 monetized tools.

## Installation

```bash
pip install semantic-kernel-warppay402
```

## Usage

```python
import semantic_kernel as sk
from semantic_kernel_warppay402 import WarpPayPlugin

kernel = sk.Kernel()
warppay_plugin = kernel.add_plugin(WarpPayPlugin(), plugin_name="WarpPay")
```
