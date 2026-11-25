<div align="center">

# Taihau Marchal

**Infrastructure & Information-Security Director at [Oraclia](https://oraclia.ai) · Tahiti 🌺**
*Directeur Infrastructure & Sécurité SI chez [Oraclia](https://oraclia.ai) — Te Mana O Te IA*

[![Oraclia](https://img.shields.io/badge/Oraclia-IA%20sur%20mesure-0b1f3a?style=for-the-badge)](https://oraclia.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Taihau%20Marchal-0a66c2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/taihau-marchal-91495ab9/)
[![Email](https://img.shields.io/badge/Contact-tma%40oraclia.ai-444?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:tma@oraclia.ai)

</div>

> *« En aéronautique, la panne n'est pas une option. J'applique la même règle à votre système d'information. »*

21+ years on critical systems in **aviation, banking and hospitality**. As CTO of Phinance SAS I designed
**WINGGATE**, the operations management system that runs the airports of  Bora Bora , Rangiroa and Raiatea.
At [Oraclia](https://oraclia.ai) I lead infrastructure, information security and *DSI as a Service*
(managed IT, outsourced CISO, Microsoft 365 governance, disaster recovery) for clients in French Polynesia,
New Caledonia and Luxembourg.

**Today: sovereign, on-premise AI.** Large language models that run on the hardware you already own — no cloud,
no data leaving the building.

## ⚡ Featured — a 27B LLM at 11–13 tokens/s on a laptop iGPU

[**qwen3.8-27b-Q4-openvino-intel-laptop**](https://github.com/TaihauMarchal/qwen3.8-27b-Q4-openvino-intel-laptop)
— Qwen3.8-27B (INT4) running locally on an Intel Core Ultra laptop (integrated Arc 140T GPU, 32 GB shared memory)
with OpenVINO:

| | Decode speed |
|---|---|
| Stock OpenVINO, no speculative decoding | 4.6 tokens/s |
| My final stack, mixed prompts | **11.2–11.3 tokens/s** |
| My final stack, 15-round tool-calling agent loop | **13.2 tokens/s** |
| Time to first token on follow-up turns | 16–19 s → **~2 s** |

Measured, reproducible, with scripts, profiles and the lessons learned (memory bandwidth ceiling, GPU hangs
under memory pressure, thermals).

## 🔧 Upstream contributions — Intel OpenVINO

<!-- CONTRIB-LINKS -->
- 🟢 [**[GPU] Add optimized GatedDeltaNet kernel for single-token decode** — openvinotoolkit/openvino#40286](https://github.com/openvinotoolkit/openvino/pull/40286): 1.4× faster linear-attention decode kernel on Intel GPUs (Qwen3-Next / Qwen3.5 / Qwen3.8 family)
- 🟢 [**[MTP] `mtp_draft_vocab` — restrict the MTP draft lm_head to a token subset** — openvinotoolkit/openvino.genai#5029](https://github.com/openvinotoolkit/openvino.genai/pull/5029) (issue [#5027](https://github.com/openvinotoolkit/openvino.genai/issues/5027)): **+20 % decode speed** for MTP speculative decoding, outputs unchanged
- 💬 [Show and tell: Qwen3.8-27B at 11–13 tokens/s on a laptop iGPU](https://github.com/openvinotoolkit/openvino/discussions/40307)

## 🇫🇷 En bref

Directeur Infrastructure & Sécurité SI chez [Oraclia](https://oraclia.ai), basé à Tahiti. 21 ans de systèmes
critiques (aéronautique, banque, hôtellerie), concepteur de WINGGATE. Aujourd'hui : l'IA souveraine sur site —
un modèle de 27 milliards de paramètres à 11–13 jetons/s sur un simple ultraportable Intel, et des
contributions au projet OpenVINO d'Intel.

**Un projet IA ?** → [oraclia.ai](https://oraclia.ai) · [tma@oraclia.ai](mailto:tma@oraclia.ai)
