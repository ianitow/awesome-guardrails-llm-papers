## Table of Contents

* [Papers](#papers)
    * [Benchmark general-purpose](#benchmark-general-purpose)
    * [Jailbreaking](#jailbreaking)
        * [Benchmark](#benchmark)
        * [Black-box](#black-box)
            * [Automation](#automation)
            * [Delicately Designed Attacks](#delicately-designed-attacks)
            * [Prompt Injection](#prompt-injection)
        * [Defense](#defense)
        * [Frameworks](#frameworks)
        * [Gray-box](#gray-box)
        * [Others](#others)
        * [White-box](#white-box)
    * [Llama Guard](#llama-guard)
    * [Metrics](#metrics)
        * [Biases](#biases)
        * [Ethical](#ethical)
        * [Fairness](#fairness)
        * [Hallucination](#hallucination)
        * [Performance](#performance)
        * [Privacy](#privacy)
        * [Reliability](#reliability)
        * [Robustness](#robustness)
        * [Safety](#safety)
        * [Security](#security)
        * [Toxicity](#toxicity)
        * [Uncertainty](#uncertainty)
    * [Multimodality](#multimodality)
    * [Overview, State-of-art](#overview-state-of-art)
    * [Popular frameworks](#popular-frameworks)
        * [Nvidia NeMo](#nvidia-nemo)
    * [Techniques](#techniques)
        * [Adversarial Learning](#adversarial-learning)
        * [Causal analysis](#causal-analysis)
        * [Chain of thought](#chain-of-thought)
        * [Fine-tunning](#fine-tunning)
        * [Machine Learning Classifiers](#machine-learning-classifiers)
        * [Optimization-based Approaches](#optimization-based-approaches)
        * [Probabilistic Graphical Mode](#probabilistic-graphical-mode)
        * [Supervised Learning](#supervised-learning)

## Papers

### Benchmark general-purpose

<a id="online-safety-analysis-for-llms-a-benchmark-an-assessment-and-a-path-forward"></a>
1. "Online Safety Analysis for LLMs: a Benchmark, an Assessment, and a Path Forward". [Paper](https://arxiv.org/abs/2404.08517)
<a id="openeval-benchmarking-chinese-llms-across-capability-alignment-and-safety"></a>
2. "OpenEval: Benchmarking Chinese LLMs across Capability, Alignment and Safety". [Paper](https://arxiv.org/abs/2403.12316)
<a id="position-building-guardrails-for-large-language-models-requires-systematic-design"></a>
3. "Position Building Guardrails for Large Language Models Requires Systematic Design". [Paper](https://openreview.net/forum?id=JvMLkGF2Ms)
<a id="r-judge-benchmarking-safety-risk-awareness-for-llm-agents"></a>
4. "R-Judge: Benchmarking Safety Risk Awareness for LLM Agents". [Paper](https://arxiv.org/abs/2401.10019)
<a id="walledeval-a-comprehensive-safety-evaluation-toolkit-for-large-language-models"></a>
5. "WalledEval A Comprehensive Safety Evaluation Toolkit for Large Language Models". [Paper](https://arxiv.org/abs/2408.03837)

### Jailbreaking

<a id="how-alignment-and-jailbreak-work-explain-llm-safety-through-intermediate-hidden-states"></a>
1. "How Alignment and Jailbreak Work Explain LLM Safety through Intermediate Hidden States". [Paper](https://arxiv.org/abs/2406.05644)
<a id="jailbreak-attacks-and-defenses-against-large-language-models-a-survey"></a>
2. "Jailbreak Attacks and Defenses Against Large Language Models A Survey". [Paper](https://arxiv.org/abs/2407.04295)
<a id="jailbreaking-and-mitigation-of-vulnerabilities-in-large-language-models"></a>
3. "Jailbreaking and Mitigation of Vulnerabilities in Large Language Models". [Paper](https://arxiv.org/abs/2410.15236)

#### Benchmark

<a id="impact-of-non-standard-unicode-characters-on-security-and-comprehension-in-large-language-models"></a>
1. "Impact of Non-Standard Unicode Characters on Security and Comprehension in Large Language Models". [Paper](https://arxiv.org/abs/2405.14490)
<a id="injecguard-benchmarking-and-mitigating-over-defense-in-prompt-injection-guardrail-models-1"></a>
2. "InjecGuard Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models 1". [Paper](https://arxiv.org/abs/2410.22770)
<a id="jade-a-linguistics-based-safety-evaluation-platform-for-large-language-models"></a>
3. "JADE: A Linguistics-based Safety Evaluation Platform for Large Language Models". [Paper](https://arxiv.org/abs/2311.00286)
<a id="jailbreakbench-an-open-robustness-benchmark-for-jailbreaking-large-language-models"></a>
4. "JailbreakBench An Open Robustness Benchmark for Jailbreaking Large Language Models". [Paper](https://arxiv.org/abs/2404.01318)
<a id="jailbreaking-large-language-models-against-moderation-guardrails-via-cipher-characters"></a>
5. "Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters". [Paper](https://arxiv.org/abs/2405.20413)
<a id="jailbroken-how-does-llm-safety-training-fail"></a>
6. "Jailbroken: How Does LLM Safety Training Fail?". [Paper](https://arxiv.org/abs/2307.02483)
<a id="llms-lost-in-translation-m-alert-uncovers-cross-linguistic-safety-gaps"></a>
7. "LLMs Lost in Translation: M-ALERT uncovers Cross-Linguistic Safety Gaps". [Paper](https://arxiv.org/abs/2412.15035)
<a id="llms-for-multi-modal-knowledge-extraction-and-analysis-in-intelligencesafety-critical-applications"></a>
8. "LLMs for Multi-Modal Knowledge Extraction and Analysis in Intelligence/Safety-Critical Applications". [Paper](https://arxiv.org/abs/2312.03088)
<a id="longsafetybench-long-context-llms-struggle-with-safety-issues"></a>
9. "LongSafetyBench: Long-Context LLMs Struggle with Safety Issues". [Paper](https://arxiv.org/abs/2411.06899)
<a id="sg-bench-evaluating-llm-safety-generalization-across-diverse-tasks-and-prompt-types"></a>
10. "SG-Bench: Evaluating LLM Safety Generalization Across Diverse Tasks and Prompt Types". [Paper](https://arxiv.org/abs/2410.21965)
<a id="the-art-of-defending-a-systematic-evaluation-and-analysis-of-llm-defense-strategies-on-safety-and-over-defensiveness"></a>
11. "The Art of Defending A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness". [Paper]()
<a id="the-art-of-defending-a-systematic-evaluation-and-analysis-of-llm-defense-strategies-on-safety-and-over-defensiveness"></a>
12. "The Art of Defending: A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness". [Paper](https://arxiv.org/abs/2401.00287)

#### Black-box

<a id="do-anything-now-characterizing-and-evaluating-in-the-wild-jailbreak-prompts-on-large-language-models"></a>
1. ""Do Anything Now" Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models". [Paper](https://dl.acm.org/doi/abs/10.1145/3658644.3670388?casa_token=6LkeuCb-cCkAAAAA:Tthu9sQK2mKBsn8R80bffKB0_V5MVnSReTi0PSIduYZJAC6-CbrrVvVYIELhwW08VP7Cd9qmfi26)
<a id="moralized-multi-step-jailbreak-prompts-black-box-testing-of-guardrails-in-large-language-models-for-verbal-attacks"></a>
2. ""Moralized" Multi-Step Jailbreak Prompts Black-Box Testing of Guardrails in Large Language Models for Verbal Attacks". [Paper](https://arxiv.org/abs/2411.16730)
<a id="moralized-multi-step-jailbreak-prompts-black-box-testing-of-guardrails-in-large-language-models-for-verbal-attacks"></a>
3. ""Moralized" Multi-Step Jailbreak Prompts: Black-Box Testing of Guardrails in Large Language Models for Verbal Attacks". [Paper](https://arxiv.org/abs/2411.16730)
<a id="how-johnny-can-persuade-llms-to-jailbreak-them-rethinking-persuasion-to-challenge-ai-safety-by-humanizing-llms"></a>
4. "How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs". [Paper](https://arxiv.org/abs/2401.06373)
<a id="jailbreaking-black-box-large-language-models-in-twenty-queries"></a>
5. "Jailbreaking Black Box Large Language Models in Twenty Queries". [Paper](https://arxiv.org/abs/2310.08419)
<a id="jailbreaking-llm-controlled-robots"></a>
6. "Jailbreaking LLM-Controlled Robots". [Paper](https://arxiv.org/abs/2410.13691)
<a id="jailbreaking-large-language-models-in-infinitely-many-ways"></a>
7. "Jailbreaking Large Language Models in Infinitely Many Ways". [Paper](https://arxiv.org/abs/2501.10800)
<a id="jailbreaking-leading-safety-aligned-llms-with-simple-adaptive-attacks"></a>
8. "Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks". [Paper]()
<a id="llm-defenses-are-not-robust-to-multi-turn-human-jailbreaks-yet"></a>
9. "LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet". [Paper](https://arxiv.org/abs/2408.15221)
<a id="large-language-models-are-vulnerable-to-bait-and-switch-attacks-for-generating-harmful-content"></a>
10. "Large Language Models are Vulnerable to Bait-and-Switch Attacks for Generating Harmful Content". [Paper](https://arxiv.org/abs/2402.13926)
<a id="sop-unlock-the-power-of-social-facilitation-for-automatic-jailbreak-attack"></a>
11. "SoP: Unlock the Power of Social Facilitation for Automatic Jailbreak Attack". [Paper](https://arxiv.org/abs/2407.01902)
<a id="speechguard-exploring-the-adversarial-robustness-of-multimodal-large-language-models-1"></a>
12. "SpeechGuard Exploring the Adversarial Robustness of Multimodal Large Language Models 1". [Paper](https://arxiv.org/abs/2405.08317)
<a id="the-language-barrier-dissecting-safety-challenges-of-llms-in-multilingual-contexts"></a>
13. "The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts". [Paper](https://arxiv.org/abs/2401.13136)
<a id="when-llm-meets-drl-advancing-jailbreaking-efficiency-via-drl-guided-search"></a>
14. "When LLM Meets DRL Advancing Jailbreaking Efficiency via DRL-guided Search". [Paper](https://arxiv.org/abs/2406.08705)

##### Automation

<a id="mart-improving-llm-safety-with-multi-round-automatic-red-teaming"></a>
1. "MART: Improving LLM Safety with Multi-round Automatic Red-Teaming". [Paper](https://arxiv.org/abs/2311.07689)
<a id="tree-of-attacks-jailbreaking-black-box-llms-automatically"></a>
2. "Tree of Attacks: Jailbreaking Black-Box LLMs Automatically". [Paper](https://arxiv.org/abs/2312.02119)

##### Delicately Designed Attacks

<a id="multilingual-blending-llm-safety-alignment-evaluat"></a>
1. "Multilingual Blending LLM Safety Alignment Evaluat". [Paper](https://arxiv.org/abs/2407.07342)

##### Prompt Injection

<a id="wordgame-efficient-effective-llm-jailbreak-via-simultaneous-obfuscation-in-query-and-response"></a>
1. "WordGame Efficient & Effective LLM Jailbreak via Simultaneous Obfuscation in Query and Response". [Paper](https://arxiv.org/abs/2405.14023)

#### Defense

<a id="humorreject-decoupling-llm-safety-from-refusal-prefix-via-a-little-humor"></a>
1. "HumorReject: Decoupling LLM Safety from Refusal Prefix via A Little Humor". [Paper](https://arxiv.org/abs/2501.13677)
<a id="immune-improving-safety-against-jailbreaks-in-multi-modal-llms-via-inference-time-alignment"></a>
2. "Immune: Improving Safety Against Jailbreaks in Multi-modal LLMs via Inference-Time Alignment". [Paper](https://arxiv.org/abs/2411.18688)
<a id="injecguard-benchmarking-and-mitigating-over-defense-in-prompt-injection-guardrail-models"></a>
3. "InjecGuard Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models". [Paper](https://arxiv.org/abs/2410.22770)
<a id="instructional-segment-embedding-improving-llm-safety-with-instruction-hierarchy"></a>
4. "Instructional Segment Embedding: Improving LLM Safety with Instruction Hierarchy". [Paper](https://arxiv.org/abs/2410.09102)
<a id="jailbreaking-llms-safeguard-with-universal-magic-words-for-text-embedding-models"></a>
5. "Jailbreaking LLMs' Safeguard with Universal Magic Words for Text Embedding Models". [Paper](https://arxiv.org/abs/2501.18280)
<a id="llmguard-guarding-against-unsafe-llm-behavior"></a>
6. "LLMGuard Guarding against Unsafe LLM Behavior". [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30566)
<a id="lionguard-building-a-contextualized-moderation-classifier-to-tackle-localized-unsafe-content"></a>
7. "LionGuard: Building a Contextualized Moderation Classifier to Tackle Localized Unsafe Content". [Paper](https://arxiv.org/abs/2407.10995)
<a id="lora-guard-parameter-efficient-guardrail-adaptation-for-content-moderation-of-large-language-models"></a>
8. "LoRA-Guard Parameter-Efficient Guardrail Adaptation for Content Moderation of Large Language Models". [Paper](https://arxiv.org/abs/2407.02987)
<a id="maatphor-automated-variant-analysis-for-prompt-injection-attacks"></a>
9. "Maatphor: Automated Variant Analysis for Prompt Injection Attacks". [Paper](https://arxiv.org/abs/2312.11513)
<a id="mogu-a-framework-for-enhancing-safety-of-open-sourced-llms-while-preserving-their-usability"></a>
10. "MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability". [Paper](https://arxiv.org/abs/2405.14488)
<a id="moje-mixture-of-jailbreak-experts-naive-tabular-classifiers-as-guard-for-prompt-attacks"></a>
11. "MoJE Mixture of Jailbreak Experts, Naive Tabular Classifiers as Guard for Prompt Attacks". [Paper](https://ojs.aaai.org/index.php/AIES/article/view/31638)
<a id="on-promptdriven-safeguarding-for-large-language-models"></a>
12. "On PromptDriven Safeguarding for Large Language Models". [Paper](https://openreview.net/forum?id=ugxGpOEkox)
<a id="overthink-slowdown-attacks-on-reasoning-llms"></a>
13. "OverThink: Slowdown Attacks on Reasoning LLMs". [Paper](https://arxiv.org/abs/2502.02542)
<a id="prp-propagating-universal-perturbations-to-attack-large-language-model-guard-rails"></a>
14. "PRP Propagating Universal Perturbations to Attack Large Language Model Guard-Rails". [Paper](https://arxiv.org/abs/2402.15911)
<a id="primeguard-safe-and-helpful-llms-through-tuning-free-routing"></a>
15. "PrimeGuard Safe and Helpful LLMs through Tuning-Free Routing". [Paper]()
<a id="refuse-whenever-you-feel-unsafe-improving-safety-in-llms-via-decoupled-refusal-training"></a>
16. "Refuse Whenever You Feel Unsafe: Improving Safety in LLMs via Decoupled Refusal Training". [Paper](https://arxiv.org/abs/2407.09121)
<a id="representation-noising-a-defence-mechanism-against-harmful-finetuning"></a>
17. "Representation Noising: A Defence Mechanism Against Harmful Finetuning". [Paper](https://arxiv.org/abs/2405.14577)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content"></a>
18. "RigorLLM Resilient Guardrails for Large Language Models against Undesired Content". [Paper](https://arxiv.org/abs/2403.13031)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content"></a>
19. "RigorLLM: Resilient Guardrails for Large Language Models against Undesired Content". [Paper](https://arxiv.org/abs/2403.13031)
<a id="robust-llm-safeguarding-via-refusal-feature-adversarial-training"></a>
20. "Robust LLM safeguarding via refusal feature adversarial training". [Paper](https://arxiv.org/abs/2409.20089)
<a id="safeguarding-system-prompts-for-llms"></a>
21. "Safeguarding System Prompts for LLMs". [Paper](https://arxiv.org/abs/2412.13426)
<a id="safety-layers-in-aligned-large-language-models-the-key-to-llm-security"></a>
22. "Safety Layers in Aligned Large Language Models: The Key to LLM Security". [Paper](https://arxiv.org/abs/2408.17003)
<a id="securing-retrieval-augmented-generation-pipelines-a-comprehensive-framework"></a>
23. "Securing Retrieval-Augmented Generation Pipelines A Comprehensive Framework". [Paper](https://www.neliti.com/publications/590025/securing-retrieval-augmented-generation-pipelines-a-comprehensive-framework)
<a id="self-guard-empower-the-llm-to-safeguard-itself"></a>
24. "Self-Guard Empower the LLM to Safeguard Itself". [Paper](https://arxiv.org/abs/2310.15851)
<a id="shieldlm-empowering-llms-as-aligned-customizable-and-explainable-safety-detectors"></a>
25. "ShieldLM: Empowering LLMs as Aligned, Customizable and Explainable Safety Detectors". [Paper](https://arxiv.org/abs/2402.16444)
<a id="smoothllm-defending-large-language-models-against-jailbreaking-attacks"></a>
26. "SmoothLLM Defending Large Language Models Against Jailbreaking Attacks". [Paper](https://arxiv.org/abs/2310.03684)
<a id="strengthening-llm-trust-boundaries-a-survey-of-prompt-injection-attacks"></a>
27. "Strengthening LLM Trust Boundaries A Survey of Prompt Injection Attacks". [Paper](https://www.researchgate.net/profile/Missy-Cummings/publication/378072627_Strengthening_LLM_Trust_Boundaries_A_Survey_of_Prompt_Injection_Attacks/links/65c57ac379007454976ae142/Strengthening-LLM-Trust-Boundaries-A-Survey-of-Prompt-Injection-Attacks.pdf)
<a id="superficial-safety-alignment-hypothesis"></a>
28. "Superficial Safety Alignment Hypothesis". [Paper](https://arxiv.org/abs/2410.10862)
<a id="tamper-resistant-safeguards-for-open-weight-llms"></a>
29. "Tamper-Resistant Safeguards for Open-Weight LLMs". [Paper](https://arxiv.org/abs/2408.00761)
<a id="targeting-alignment-extracting-safety-classifiers-of-aligned-llms"></a>
30. "Targeting Alignment: Extracting Safety Classifiers of Aligned LLMs". [Paper](https://arxiv.org/abs/2501.16534)
<a id="targeting-alignment-extracting-safety-classifiers-of-aligned-llms"></a>
31. "Targeting Alignment: Extracting Safety Classifiers of Aligned LLMs". [Paper](https://arxiv.org/abs/2501.16534)
<a id="the-instruction-hierarchy-training-llms-to-prioritize-privileged-instructions"></a>
32. "The Instruction Hierarchy Training LLMs to Prioritize Privileged Instructions". [Paper](https://arxiv.org/abs/2404.13208)
<a id="torchopera-a-compound-ai-system-for-llm-safety"></a>
33. "TorchOpera A Compound AI System for LLM Safety". [Paper](https://arxiv.org/abs/2406.10847)
<a id="wildguard-open-one-stop-moderation-tools-for-safety-risks-jailbreaks-and-refusals-of-llms"></a>
34. "WildGuard: Open One-Stop Moderation Tools for Safety Risks, Jailbreaks, and Refusals of LLMs". [Paper](https://arxiv.org/abs/2406.18495)

#### Frameworks

<a id="uniguard-towards-universal-safety-guardrails-for-jailbreak-attacks-on-multimodal-large-language-models"></a>
1. "UniGuard Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models". [Paper]()

#### Gray-box

<a id="increased-llm-vulnerabilities-from-fine-tuning-and-quantization"></a>
1. "INCREASED LLM VULNERABILITIES FROM FINE-TUNING AND QUANTIZATION". [Paper]()
<a id="jailbreaking-llm-controlled-robots-1-1"></a>
2. "Jailbreaking LLM-Controlled Robots 1 1". [Paper](https://arxiv.org/abs/2410.13691)
<a id="language-model-unalignment-parametric-red-teaming-to-expose-hidden-harms-and-biases"></a>
3. "Language Model Unalignment Parametric Red-Teaming to Expose Hidden Harms and Biases". [Paper](https://arxiv.org/abs/2310.14303)
<a id="lora-as-an-attack-piercing-llm-safety-under-the-share-and-play-scenario"></a>
4. "LoRA-as-an-Attack! Piercing LLM Safety Under The Share-and-Play Scenario". [Paper](https://arxiv.org/abs/2403.00108)
<a id="peering-behind-the-shield-guardrail-identification-in-large-language-models"></a>
5. "Peering Behind the Shield Guardrail Identification in Large Language Models". [Paper](https://arxiv.org/abs/2502.01241)
<a id="safeguard-is-a-double-edged-sword-denial-of-service-attack-on-large-language-models"></a>
6. "Safeguard is a Double-edged Sword Denial-of-service Attack on Large Language Models". [Paper](https://arxiv.org/abs/2410.02916)
<a id="sowing-the-wind-reaping-the-whirlwind-the-impact-of-editing-language-models"></a>
7. "Sowing the Wind, Reaping the Whirlwind: The Impact of Editing Language Models". [Paper](https://arxiv.org/abs/2401.10647)
<a id="stochastic-monkeys-at-play-random-augmentations-cheaply-break-llm-safety-alignment"></a>
8. "Stochastic Monkeys at Play: Random Augmentations Cheaply Break LLM Safety Alignment". [Paper](https://arxiv.org/abs/2411.02785)
<a id="the-language-barrier-dissecting-safety-challenges-of-llms-in-multilingual-contexts"></a>
9. "The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts". [Paper](https://arxiv.org/abs/2401.13136)
<a id="virus-harmful-fine-tuning-attack-for-large-language-models-bypassing-guardrail-moderation"></a>
10. "Virus: Harmful Fine-tuning Attack for Large Language Models Bypassing Guardrail Moderation". [Paper](https://arxiv.org/abs/2501.17433)

#### Others

<a id="on-evaluating-the-durability-of-safeguards-for-open-weight-llms"></a>
1. "On Evaluating the Durability of Safeguards for Open-Weight LLMs". [Paper](https://arxiv.org/abs/2412.07097)
<a id="purple-teaming-llms-with-adversarial-defender-training"></a>
2. "Purple-teaming LLMs with Adversarial Defender Training". [Paper](https://arxiv.org/abs/2407.01850)
<a id="purple-teaming-llms-with-adversarial-defender-training"></a>
3. "Purple-teaming LLMs with Adversarial Defender Training". [Paper](https://arxiv.org/abs/2407.01850)

#### White-box

<a id="jailbreaking-llm-controlled-robots-1"></a>
1. "Jailbreaking LLM-Controlled Robots 1". [Paper](https://arxiv.org/abs/2410.13691)
<a id="jailbreaking-large-language-models-in-infinitely-many-ways"></a>
2. "Jailbreaking Large Language Models in Infinitely Many Ways". [Paper](https://arxiv.org/abs/2501.10800)
<a id="sleeper-agents-training-deceptive-llms-that-persist-through-safety-training"></a>
3. "Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training". [Paper](https://arxiv.org/abs/2401.05566)
<a id="soft-prompt-threats-attacking-safety-alignment-and-unlearning-in-open-source-llms-through-the-embedding-space"></a>
4. "Soft Prompt Threats: Attacking Safety Alignment and Unlearning in Open-Source LLMs through the Embedding Space". [Paper](https://arxiv.org/abs/2402.09063)
<a id="speechguard-exploring-the-adversarial-robustness-of-multimodal-large-language-models-1-1"></a>
5. "SpeechGuard Exploring the Adversarial Robustness of Multimodal Large Language Models 1 1". [Paper](https://arxiv.org/abs/2405.08317)

### Llama Guard

<a id="llama-guard-llm-based-input-output-safeguard-for-human-ai-conversations"></a>
1. "Llama Guard LLM-based Input-Output Safeguard for Human-AI Conversations". [Paper](https://arxiv.org/abs/2312.06674)

### Metrics

#### Biases

<a id="intentional-biases-in-llm-responses"></a>
1. "Intentional Biases in LLM Responses". [Paper](https://ieeexplore.ieee.org/abstract/document/10316060)
<a id="the-silence-of-the-llms-cross-lingual-analysis-of-guardrail-related-political-bias-and-false-information-prevalence-in-chatgpt-google-bard-gemini-and-bing-chat"></a>
2. "The silence of the LLMs Cross-lingual analysis of guardrail-related political bias and false information prevalence in ChatGPT, Google Bard (Gemini), and Bing Chat". [Paper]()
<a id="when-in-doubt-cascade-towards-building-efficient-and-capable-guardrails"></a>
3. "When in Doubt, Cascade: Towards Building Efficient and Capable Guardrails". [Paper](https://arxiv.org/abs/2407.06323)

#### Ethical

<a id="right-to-be-forgotten-in-the-era-of-large-language-models-implications-challenges-and-solutions"></a>
1. "Right to be Forgotten in the Era of Large Language Models: Implications, Challenges, and Solutions". [Paper](https://arxiv.org/abs/2307.03941)

#### Fairness

<a id="insaaf-incorporating-safety-through-accuracy-and-fairness-are-llms-ready-for-the-indian-legal-domain"></a>
1. "InSaAF: Incorporating Safety through Accuracy and Fairness | Are LLMs ready for the Indian Legal Domain?". [Paper](https://arxiv.org/abs/2402.10567)
<a id="watching-the-ai-watchdogs-a-fairness-and-robustness-analysis-of-ai-safety-moderation-classifiers"></a>
2. "Watching the AI Watchdogs: A Fairness and Robustness Analysis of AI Safety Moderation Classifiers". [Paper](https://arxiv.org/abs/2501.13302)

#### Hallucination

<a id="the-need-for-guardrails-with-large-language-models-in-medical-safety-critical-settings-an-artificial-intelligence-application-in-the-pharmacovigilance-ecosystem"></a>
1. "The Need for Guardrails with Large Language Models in Medical Safety-Critical Settings: An Artificial Intelligence Application in the Pharmacovigilance Ecosystem". [Paper](https://arxiv.org/abs/2407.18322)

#### Performance

<a id="lightweight-safety-guardrails-using-fine-tuned-bert-embeddings"></a>
1. "Lightweight Safety Guardrails Using Fine-tuned BERT Embeddings". [Paper](https://arxiv.org/abs/2411.14398)

#### Privacy

<a id="unique-security-and-privacy-threats-of-large-language-model-a-comprehensive-survey"></a>
1. "Unique Security and Privacy Threats of Large Language Model A Comprehensive Survey". [Paper](https://arxiv.org/abs/2406.07973)

#### Reliability

<a id="is-safer-better-the-impact-of-guardrails-on-the-argumentative-strength-of-llms-in-hate-speech-countering"></a>
1. "Is Safer Better? The Impact of Guardrails on the Argumentative Strength of LLMs in Hate Speech Countering". [Paper](https://arxiv.org/abs/2410.03466)
<a id="on-calibration-of-llm-based-guard-models-for-reliable-content-moderation"></a>
2. "On Calibration of LLM-based Guard Models for Reliable Content Moderation". [Paper]()
<a id="plan-grounded-large-language-models-for-dual-goal-conversational-settings"></a>
3. "Plan-Grounded Large Language Models for Dual Goal Conversational Settings". [Paper](https://arxiv.org/abs/2402.01053)
<a id="trust-oriented-adaptive-guardrails-for-large-language-models"></a>
4. "Trust-Oriented Adaptive Guardrails for Large Language Models". [Paper]()

#### Robustness

<a id="locking-down-the-finetuned-llms-safety"></a>
1. "Locking Down the Finetuned LLMs Safety". [Paper](https://arxiv.org/abs/2410.10343)
<a id="marco-multi-agent-real-time-chat-orchestration"></a>
2. "MARCO: Multi-Agent Real-time Chat Orchestration". [Paper](https://arxiv.org/abs/2410.21784)
<a id="ml-on-rails-safeguarding-machine-learning-models-in-software-systems-a-case-study"></a>
3. "ML-On-Rails Safeguarding Machine Learning Models in Software Systems A Case Study". [Paper]()
<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
4. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content-1"></a>
5. "RigorLLM Resilient Guardrails for Large Language Models against Undesired Content 1". [Paper](https://arxiv.org/abs/2403.13031)
<a id="towards-assurance-of-llm-adversarial-robustness-using-ontology-driven-argumentation"></a>
6. "Towards Assurance of LLM Adversarial Robustness using Ontology-Driven Argumentation". [Paper](https://arxiv.org/abs/2410.07962)

#### Safety

<a id="llm-safety-alignment-is-divergence-estimation-in-disguise"></a>
1. "LLM Safety Alignment is Divergence Estimation in Disguise". [Paper](https://arxiv.org/abs/2502.00657)
<a id="large-language-model-safety-a-holistic-survey"></a>
2. "Large Language Model Safety A Holistic Survey". [Paper]()
<a id="locking-down-the-finetuned-llms-safety"></a>
3. "Locking Down the Finetuned LLMs Safety". [Paper](https://arxiv.org/abs/2410.10343)
<a id="mapping-llm-security-landscapes-a-comprehensive-stakeholder-risk-assessment-proposal"></a>
4. "Mapping LLM Security Landscapes A Comprehensive Stakeholder Risk Assessment Proposal". [Paper](https://arxiv.org/abs/2403.13309)
<a id="on-the-role-of-attention-heads-in-large-language-model-safety"></a>
5. "On the Role of Attention Heads in Large Language Model Safety". [Paper](https://arxiv.org/abs/2410.13708)
<a id="pku-saferlhf-towards-multi-level-safety-alignment-for-llms-with-human-preference"></a>
6. "PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs with Human Preference". [Paper](https://arxiv.org/abs/2406.15513)
<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
7. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="root-defence-strategies-ensuring-safety-of-llm-at-the-decoding-level"></a>
8. "Root Defence Strategies: Ensuring Safety of LLM at the Decoding Level". [Paper](https://arxiv.org/abs/2410.06809)
<a id="scans-mitigating-the-exaggerated-safety-for-llms-via-safety-conscious-activation-steering"></a>
9. "SCANS: Mitigating the Exaggerated Safety for LLMs via Safety-Conscious Activation Steering". [Paper](https://arxiv.org/abs/2408.11491)
<a id="seal-safety-enhanced-aligned-llm-fine-tuning-via-bilevel-data-selection"></a>
10. "SEAL: Safety-enhanced Aligned LLM Fine-tuning via Bilevel Data Selection". [Paper](https://arxiv.org/abs/2410.07471)
<a id="safeguarding-ai-agents-developing-and-analyzing-safety-architectures"></a>
11. "Safeguarding AI Agents Developing and Analyzing Safety Architectures". [Paper](https://arxiv.org/abs/2409.03793)
<a id="safeguarding-ai-agents-developing-and-analyzing-safety-architectures"></a>
12. "Safeguarding AI Agents: Developing and Analyzing Safety Architectures". [Paper](https://arxiv.org/abs/2409.03793)
<a id="scisafeeval-a-comprehensive-benchmark-for-safety-alignment-of-large-language-models-in-scientific-tasks"></a>
13. "SciSafeEval: A Comprehensive Benchmark for Safety Alignment of Large Language Models in Scientific Tasks". [Paper](https://arxiv.org/abs/2410.03769)
<a id="trust-safety-of-llms-and-llms-in-trust-safety"></a>
14. "Trust & Safety of LLMs and LLMs in Trust & Safety". [Paper](https://arxiv.org/abs/2412.02113)

#### Security

<a id="picky-llms-and-unreliable-rms-an-empirical-study-on-safety-alignment-after-instruction-tuning"></a>
1. "Picky LLMs and Unreliable RMs: An Empirical Study on Safety Alignment after Instruction Tuning". [Paper](https://arxiv.org/abs/2502.01116)

#### Toxicity

<a id="llms-with-personalities-in-multi-issue-negotiation-games"></a>
1. "LLMs with Personalities in Multi-issue Negotiation Games". [Paper](https://arxiv.org/abs/2405.05248)
<a id="toxicity-in-chatgpt-analyzing-persona-assigned-language-models"></a>
2. "Toxicity in ChatGPT: Analyzing Persona-assigned Language Models". [Paper](https://arxiv.org/abs/2304.05335)

#### Uncertainty

<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
1. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="uncertainty-based-abstention-in-llms-improves-safety-and-reduces-hallucinations"></a>
2. "Uncertainty-Based Abstention in LLMs Improves Safety and Reduces Hallucinations". [Paper]()

### Multimodality

<a id="how-many-unicorns-are-in-this-image-a-safety-evaluation-benchmark-for-vision-llms"></a>
1. "How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs". [Paper](https://arxiv.org/abs/2311.16101)
<a id="learning-to-see-but-forgetting-to-follow-visual-instruction-tuning-makes-llms-more-prone-to-jailbreak-attacks"></a>
2. "Learning To See But Forgetting To Follow: Visual Instruction Tuning Makes LLMs More Prone To Jailbreak Attacks". [Paper](https://arxiv.org/abs/2405.04403)
<a id="safewatch-an-efficient-safety-policy-following-video-guardrail-model-with-transparent-explanations"></a>
3. "SafeWatch An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations". [Paper]()
<a id="speechguard-exploring-the-adversarial-robustness-of-multimodal-large-language-models-1-1-1"></a>
4. "SpeechGuard Exploring the Adversarial Robustness of Multimodal Large Language Models 1 1 1". [Paper](https://arxiv.org/abs/2405.08317)
<a id="the-vllm-safety-paradox-dual-ease-in-jailbreak-attack-and-defense"></a>
5. "The VLLM Safety Paradox: Dual Ease in Jailbreak Attack and Defense". [Paper](https://arxiv.org/abs/2411.08410)
<a id="video-watermarking-safeguarding-your-video-from-unauthorized-annotations-by-video-based-llms"></a>
6. "Video Watermarking: Safeguarding Your Video from (Unauthorized) Annotations by Video-based LLMs". [Paper](https://arxiv.org/abs/2407.02411)
<a id="visual-adversarial-examples-jailbreak-aligned-large-language-models"></a>
7. "Visual Adversarial Examples Jailbreak Aligned Large Language Models". [Paper](https://arxiv.org/abs/2306.13213)

### Overview, State-of-art

<a id="safeguarding-large-language-models-a-survey"></a>
1. "Safeguarding Large Language Models A Survey". [Paper]()

### Popular frameworks

#### Nvidia NeMo

<a id="nemo-guardrails-a-toolkit-for-controllable-and-safe-llm-applications-with-programmable-rails"></a>
1. "NeMo Guardrails A Toolkit for Controllable and Safe LLM Applications with Programmable Rails". [Paper]()

### Techniques

#### Adversarial Learning

<a id="a-causal-explainable-guardrails-for-large-language-models"></a>
1. "A Causal Explainable Guardrails for Large Language Models". [Paper](https://arxiv.org/abs/2405.04160)

#### Causal analysis

<a id="a-causal-explainable-guardrails-for-large-language-models"></a>
1. "A Causal Explainable Guardrails for Large Language Models". [Paper](https://arxiv.org/abs/2405.04160)
<a id="integrating-emotional-and-linguistic-models-for-ethical-compliance-in-large-language-models"></a>
2. "Integrating Emotional and Linguistic Models for Ethical Compliance in Large Language Models". [Paper](https://arxiv.org/abs/2405.07076)

#### Chain of thought

<a id="refining-input-guardrails-enhancing-llm-as-a-judge-efficiency-through-chain-of-thought-fine-tuning-and-alignment"></a>
1. "Refining Input Guardrails: Enhancing LLM-as-a-Judge Efficiency Through Chain-of-Thought Fine-Tuning and Alignment". [Paper](https://arxiv.org/abs/2501.13080)

#### Fine-tunning

<a id="a-flexible-large-language-models-guardrail-development-methodology-applied-to-off-topic-prompt-detection"></a>
1. "A Flexible Large Language Models Guardrail Development Methodology Applied to Off-Topic Prompt Detection". [Paper](https://arxiv.org/abs/2411.12946)
<a id="improved-generation-of-adversarial-examples-against-safety-aligned-llms"></a>
2. "Improved Generation of Adversarial Examples Against Safety-aligned LLMs". [Paper](https://arxiv.org/abs/2405.20778)
<a id="multitask-mayhem-unveiling-and-mitigating-safety-gaps-in-llms-fine-tuning"></a>
3. "Multitask Mayhem: Unveiling and Mitigating Safety Gaps in LLMs Fine-tuning". [Paper](https://arxiv.org/abs/2409.15361)
<a id="navigating-the-safety-landscape-measuring-risks-in-finetuning-large-language-models"></a>
4. "Navigating the Safety Landscape Measuring Risks in Finetuning Large Language Models". [Paper](https://arxiv.org/abs/2405.17374)
<a id="overriding-safety-protections-of-open-source-models"></a>
5. "Overriding Safety protections of Open-source Models". [Paper](https://arxiv.org/abs/2409.19476)
<a id="overriding-safety-protections-of-open-source-models"></a>
6. "Overriding Safety protections of Open-source Models". [Paper](https://arxiv.org/abs/2409.19476)
<a id="picky-llms-and-unreliable-rms-an-empirical-study-on-safety-alignment-after-instruction-tuning"></a>
7. "Picky LLMs and Unreliable RMs: An Empirical Study on Safety Alignment after Instruction Tuning". [Paper](https://arxiv.org/abs/2502.01116)
<a id="safeguard-fine-tuned-llms-through-pre--and-post-tuning-model-merging"></a>
8. "Safeguard Fine-Tuned LLMs Through Pre- and Post-Tuning Model Merging". [Paper](https://arxiv.org/abs/2412.19512)

#### Machine Learning Classifiers

<a id="juree-not-judges-safeguarding-llm-interactions-with-small-specialised-encoder-ensembles"></a>
1. "JurEE not Judges: safeguarding llm interactions with small, specialised Encoder Ensembles". [Paper](https://arxiv.org/abs/2410.08442)

#### Optimization-based Approaches

<a id="pal-proxy-guided-black-box-attack-on-large-language-models"></a>
1. "PAL: Proxy-Guided Black-Box Attack on Large Language Models". [Paper](https://arxiv.org/abs/2402.09674)
<a id="pathseeker-exploring-llm-security-vulnerabilities-with-a-reinforcement-learning-based-jailbreak-approach"></a>
2. "PathSeeker Exploring LLM Security Vulnerabilities with a Reinforcement Learning-Based Jailbreak Approach". [Paper](https://arxiv.org/abs/2409.14177)
<a id="privagent-agentic-based-red-teaming-for-llm-privacy-leakage"></a>
3. "PrivAgent Agentic-based Red-teaming for LLM Privacy Leakage". [Paper]()

#### Probabilistic Graphical Mode

<a id="guard-robust-reasoning-enabled-llm-guardrail-via"></a>
1. "Guard Robust Reasoning Enabled LLM Guardrail via". [Paper](https://arxiv.org/abs/2407.05557)

#### Supervised Learning

<a id="a-three-branch-checks-and-balances-frameworkfor-context-aware-ethical-alignment-of-large-language-models"></a>
1. "A Three-Branch Checks-and-Balances Frameworkfor Context-Aware Ethical Alignment of Large Language Models". [Paper](https://arxiv.org/abs/2502.00136)

