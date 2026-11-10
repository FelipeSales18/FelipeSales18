<div align="center">I build and evaluate AI systems end to end — from model fine-tuning and efficient inference to data pipelines, computer vision, and software integrations. I'm particularly interested in turning experimental ideas into reproducible, measurable systems.

My work spans LLM optimization on constrained hardware, natural-language analytics over cloud data, and visual recognition pipelines. I enjoy the engineering behind making a model useful: designing evaluations, measuring trade-offs, and documenting limitations.
Featured projects
LLM-PS4 — Running a fine-tuned Qwen3-1.7B on a PlayStation 4
Fine-tuned Qwen3-1.7B on GSM8K using GRPO + LoRA, converted the model to GGUF, and ran inference on a 2013 PlayStation 4 with Linux using llama.cpp, including GPU acceleration through Vulkan.
- 75.8% strict-format accuracy and 76.3% flexible answer accuracy on the full GSM8K test set (1,319 questions) with the full-precision tuned model.
- 1.56× faster answers on the PS4 GPU versus its CPU (11.18 s vs. 17.47 s per answer), measured on the same 100 questions.
- 72.9% flexible accuracy on all 1,319 questions using the quantized Q4_K_M model on the PS4 GPU.
- Includes reproducible experiments, evaluation scripts, quantization comparisons, and hardware benchmarks.
Stack: Python · PyTorch · GRPO/LoRA · Qwen3 · llama.cpp · GGUF · Vulkan · Linux
Links: Code & results · Model on Hugging Face
AI Financial Data Assistant — Reliable natural-language analytics on AWS
Built a hybrid AI analytics system that translates financial questions into validated, deterministic, read-only SQL, using LLM intent classification and querying partitioned data through Amazon Athena.
- 81.7% accuracy (49/60) on a frozen, previously unseen evaluation set.
- 59/59 applicable test cases applied partition pruning in that evaluation.
- Designed explicit prompt-injection checks, Pydantic validation, and SQL AST guardrails.
- Uses synthetic data, with documented methodology and known limitations.
Stack: Python · AWS S3/Athena/Glue · NVIDIA NIM · SQLGlot · Pydantic · Parquet · Streamlit
Link: Code, architecture & evaluations
Police Argos — Brazilian license plate recognition
Developed a computer-vision pipeline to detect Brazilian license plates and read their characters locally, supporting both older and Mercosul plate formats.
- YOLOv11 for plate detection and EasyOCR for text recognition.
- Multi-scale detection, image preprocessing, OCR voting, and confidence visualizations.
- Published a fine-tuned plate-detection model for reuse.
Stack: Python · YOLOv11 · EasyOCR · OpenCV
Links: Code · Detection model
Technical toolkit
Area	Technologies
AI & Machine Learning	PyTorch, Hugging Face, GRPO/LoRA, scikit-learn, YOLO, OpenCV
Data & Cloud	Python, Pandas, SQL, PostgreSQL, Parquet, AWS S3/Athena/Glue
Backend & Automation	Django/DRF, REST APIs, n8n, Supabase, Docker
Frontend & Development	JavaScript/TypeScript, React, Git/GitHub, Linux


Let's connect
I'm interested in applied AI, ML engineering, data engineering, and software development, especially opportunities to collaborate with experienced engineering teams.
- LinkedIn: felipe-dutrain-756135342
- Hugging Face: felipedutrain
- Email: felipedutrain@gmail.com
