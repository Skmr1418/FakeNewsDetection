🧠 Fake News Detection System – README Summary
This project presents a Few-Shot Multimodal AI Framework for fake news detection, built to tackle real-world disinformation campaigns that exploit cognitive security through text, images, and videos. Traditional detection systems fall short in adaptability, explainability, and ethical deployment—this framework addresses those gaps.
🔍 Key Features
Multimodal Detection: Uses OpenCLIP (vision encoder) and RoBERTa (text encoder) with contrastive fusion to detect mismatches between textual and visual content.
Few-Shot Learning: Learns from as few as 5–10 samples per class, enabling fast adaptation to new disinformation topics and low-resource languages.
Knowledge Injection: Employs retrieval-augmented generation (RAG) with external sources like Wikidata for dynamic fact validation.
Explainability: Integrated Gradients (IG) offer visual/textual saliency maps for transparent predictions.
Ethical AI Design: Includes adversarial robustness, bias mitigation, input sanitization, and secure audit logging to ensure responsible deployment.
Deployment Ready: A REST API serves real-time predictions with output explanation and security controls.
🧪 Evaluation
Validated on multilingual and multimodal datasets (e.g., Fakeddit, Weibo, LIAR, FakeNewsNet), the model achieved strong performance in few-shot and zero-shot settings, demonstrating:
≥75% F1 in 5/10-shot scenarios
10%+ improvement over existing baselines
Human agreement ≥70% on IG explanations
