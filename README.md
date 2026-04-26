# Spectral-Error-Mitigation

Reproducible Qiskit implementation of Walsh-Hadamard Spectral Error Mitigation for noisy quantum circuits. Compares single-execution spectral filtering vs ZNE on FakeManilaV2 (GHZ/QAOA/random benchmarks, 24k shots). Matches IEEE Quantum Week manuscript Sec. 3-4. MIT license
## Setup
```bash
pip install -r requirements.txt
```

## Run
```bash
jupyter notebook Spectral_Error_Mitigation.ipynb
```
Generates tables/figures matching manuscript (FakeManilaV2, 24k shots)
