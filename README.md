
## 🛠 Installation

```bash
pip install torch transformers scipy numpy

```

## 🚀 Usage

### Attack ArrowCloak 

```bash
cd attack_arrowcloak
bash attack.sh

```

### Attack TEMPO 

```bash
cd attack_tempo
bash attack.sh

```

## ⚙️ Configuration

Modify the `.sh` files to adjust:

* **Script:** `gpt2.py`, `bert.py`, or `llama.py`.
* **Layer/Module:** Target specific weights (e.g., `attn.c_proj`, `self_attn.o_proj`).
* **Precision:** `float64` is recommended for ALS stability.


