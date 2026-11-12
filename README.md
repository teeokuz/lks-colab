# lks-colab

Public batch runner for the **Last Known Seconds** YouTube channel (AI reconstructions of real disasters).
Open `LKS_gerador.ipynb` in Google Colab (free T4) and run all: it downloads the batch named in `atual.txt`
from `lotes/` and generates keyframes and video clips.

Models (all permissive licenses): FLUX.1-schnell (Apache 2.0, GGUF by city96), FastWan 2.2 TI2V-5B (Apache 2.0),
Real-ESRGAN general-x4v3 (BSD-3-Clause).
