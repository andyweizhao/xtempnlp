# Cross-temporal NLP

## Overview

Temporality is a fundamental aspect of NLP technologies, which is extremely underrepresented in the NLP community compared to other widely recognized aspects such as multilinguality, cross-culturality, and multimodality. With the advent of LLMs, there have been many time-sensitive applications such as temporal reasoning, forecasting, and planning. Moreover, a growing number of interdisciplinary works rely on NLP technologies for cross-temporal studies in fields such as social science, psychology, cognitive science, environmental science, and clinical studies. Therefore, temporality has become a crucial aspect in NLP. However, LLMs are hindered in their understanding of time due to many different reasons, including temporal biases and knowledge conflicts in pretraining and RAG data but also a fundamental limitation in LLM tokenization that fragments a date into several meaningless subtokens. Such inadequate understanding of time would potentially lead to inaccurate reasoning, forecasting and planning, and incorrect scientific discoveries if they are time-sensitive. In this course, we will look into several issues in cross-temporal NLP and works that blend temporality into multilinguality, cross-culturality, and multimodality, as well as interdisciplinary applications beyond NLP.

This seminar series takes place at Heidelberg University on Tuesdays from 15:15 to 16:45 during the winter semester 2025. The course is planned to be held fully online via Teams.

## Organization

Each lecture includes two talks on the same topic; presenters cannot present the same paper. A list of papers is provided, and presenters could choose a paper not covered by the list but should contact us and have our consent before doing so. Enter your data into https://docs.google.com/spreadsheets/d/1E9hZaUB-22rfdrRw-PFAvEQ22yY5aPvq1MKeOwolpzQ/edit?usp=sharing 

## Language

The seminar will be held in English.

## Teams link
https://teams.microsoft.com/l/meetup-join/19%3ameeting_ODIwNzBmMjktYTFhMy00MDVjLTgxMzctYTc1MjNjNjcwMzMy%40thread.v2/0?context=%7b%22Tid%22%3a%228c2b19ad-5f9c-49d4-9077-3ec3cfc52b3f%22%2c%22Oid%22%3a%2234f4b4d6-add4-483e-ae24-0684a44308d3%22%7d

Meeting ID: 346 311 158 495 2

Passcode: 9Zp2wq2J

## Contact
crosstemporalnlp@gmail.com

## Programme 
| Date       | Topics                            | Presenters  |
|------------|-----------------------------------|----------------|
| 14/10/2025 | [Kick-off](/slides/w1-lecture.pdf) [organisation](/slides/organisation.pdf)   | Wei Zhao |     
| 21/10/2025 | No seminar (watch [workshop recordings](https://www.youtube.com/watch?v=Um27xolvBfc&t=9s))      | [XTempLLMs2025](https://xtempllms.github.io/2025/program.html) |
| 28/10/2025 | Temporal artefects [calendar](/slides/w3-calendar.pdf)      | Jonathan Rosing|
| 04/11/2025 | Knowledge conflicts  | Dominik Grosse [slides](/slides/w4-Dominik_Grosse.pdf) <br>Anni Wang [slides](/slides/w4-Anni_wang.pdf)| 
| 11/11/2025 | Knowledge conflicts       | Bohdana Ivakhnenko [slides](/slides/w5-Bohdana_Ivakhnenko.pdf) <br>Raziye Sari [slides](/slides/w5-Raziye_Sari.pdf)|    |
| 18/11/2025 | Temporal reasoning       |Shiya Feng [slides](/slides/w6-Shiya.pptx) <br>Zheng-Lin Lin [slides](https://drive.google.com/file/d/1tJQzrht9HMYD6ePqBdCGpeJnDKBQAJ_-/view) |
| 25/11/2025 | Temporal reasoning       |Binheng Zheng [slides](/slides/w7-Binheng_Zheng.pdf)|
| 02/12/2025 | Temporal reasoning in healthcare & finance       |Paul Dietze[slides](/slides/w8-Paul_Dietze.pdf) <br>Yuzhen He[slides](/slides/w8-Yuzhen_He.pdf)|
| 09/12/2025 | Time series forecasting       |Yingxin Yu[slides](/slides/w9-Yingxin_Yu.pdf) |
| 16/12/2025 | Time series forecasting       |Qingyang Cao[slides](/slides/w10-Qingyang_Cao.pdf) <br> Yuefeiyang Li[slides](/slides/w10-Yuefeiyang_Li.pdf) <br> Xinyi Cai |
| Winter Break                                   |                |                |            |
| 06/01/2026 | Temporal knowledge graph       |Amirreza Tarabkhah <br>Bingyue Li |
| 13/01/2026 | Temporal information retrieval       |Buse Erkiraz <br>Mario Kuzmanov[slides](/slides/w13-Mario_Kuzmanov.pdf)|
| 20/01/2026 | Cultural change over time       |Amir Safari <br> Yaxi Zhuang |  
| 27/01/2026 | Temporal social network       |Chuqiao Li <br> Yiting Tong |
| 03/02/2026 | Temporal reasoning in healthcare & finance       |Payam Soltanzadeh <br>Saliq Neyaz |

## Useful Links
previous course editions: https://github.com/andyweizhao/diaclms

## Best Term Papers

## Templates for Term Papers
https://www.overleaf.com/4222845983xxpyrsqbxzmt#2e3970

## References 
- Knowledge conflicts
  - DYNAMICQA: Tracing Internal Knowledge Conflicts in Language Models
  - Assessing and Mitigating Medical Knowledge Drift and Conflicts in Large Language Models
  - Taming Knowledge Conflicts in Language Models
  - What Is Seen Cannot Be Unseen: The Disruptive Effect of Knowledge Conflict on Large Language Models
  - Knowledge Conflicts for LLMs: A Survey
- Temporal reasoning
  - Temporal reasoning for timeline summarisation in social media
  - Learning to Reason Over Time: Timeline Self-Reflection for Improved Temporal Reasoning in Language Models
  - TReMu: Towards Neuro-Symbolic Temporal Reasoning for LLM-Agents with Memory in Multi-Session Dialogues
  - TRAVELER: A Benchmark for Evaluating Temporal Reasoning across Vague, Implicit and Explicit References
- Time series forecasting
  - LLM-Mixer: Multiscale Mixing in LLMs for Time Series Forecasting
  - Explainable Multi-modal Time Series Prediction with LLM-in-the-Loop
  - ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data
  - MoTime: A Dataset Suite for Multimodal Time Series Forecasting
  - MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering
- Temporal knowledge graph
  - When Will the Tokens End? Graph-Based Forecasting for LLMs Output Length
  - G2S: A General-to-Specific Learning Framework for Temporal Knowledge Graph Forecasting with Large Language Models
  - Towards Foundation Model on Temporal Knowledge Graph Reasoning
- Temporal reasoning in healthcare
  - Large Language Models with Temporal Reasoning for Longitudinal Clinical Summarization and Prediction
  - Agentic Temporal Graph of Reasoning with Multimodal Language Models: A Potential AI Aid to Healthcare
  - Libra: Leveraging Temporal Images for Biomedical Radiology Analysis
  - TIMER: Temporal Instruction Modeling and Evaluation for Longitudinal Clinical Records
  - TemMed-Bench: Evaluating Temporal Medical Image Reasoning in Vision-Language Models
- Temporal information retrieval
  - It’s High Time : A Survey of Temporal Information Retrieval and Question Answering
  - Temporal Information Retrieval via Time-Specifier Model Merging
  - TimeR4: Time-aware Retrieval-Augmented Large Language Models for Temporal Knowledge Graph Question Answering
- Cultural change over time
  - How Does Culture Evolve?
  - Cultural evolution in populations of Large Language Models
  - Light Will be Thrown: The Emerging Science of Cultural Evolution
- Temporal social network
  - Recommendation Fairness in Social Networks Over Time
  - The Evolution of Language in Social Media Comments
  - Evidence of equilibrium dynamics in human social networks evolving in time
- Temporal reasoning in finance
  - FinHEAR: Human Expertise and Adaptive Risk-Aware Temporal Reasoning for Financial Decision-Making
- Temporal artefects
  - Can Language Models Handle a Non-Gregorian Calendar?
  - Around the World in 24 Hours: Probing LLM Knowledge of Time and Place
  - DATETIME: A new benchmark to measure LLM translation and reasoning capabilities
  - Date Fragments: A Hidden Bottleneck of Tokenisation for Temporal Reasoning

