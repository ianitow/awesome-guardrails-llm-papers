## Table of Contents
* [Overview, State-of-art](#overview-state-of-art)
* [Techniques](#techniques)
    * [Adversarial Learning](#adversarial-learning)
    * [Causal analysis](#causal-analysis)
    * [Chain of thought](#chain-of-thought)
    * [Fine-tunning](#fine-tunning)
    * [Machine Learning Classifiers](#machine-learning-classifiers)
    * [Optimization-based Approaches](#optimization-based-approaches)
    * [Probabilistic Graphical Mode](#probabilistic-graphical-mode)
    * [Supervised Learning](#supervised-learning)
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

* [Popular frameworks](#popular-frameworks)
    * [Llama Guard](#llama-guard)
    * [Nvidia NeMo](#nvidia-nemo)
* [Specific-Domain](#specific-domain)

## Overview, State-of-art

<a id="a-survey-on-hallucination-in-large-language-models-principles-taxonomy-challenges-and-open-questions"></a>
1. "A Survey on Hallucination in Large Language Models Principles, Taxonomy, Challenges, and Open Questions". [Paper](https://arxiv.org/abs/2311.05232)
<a id="ai-safety-in-generative-ai-large-language-models-a-survey"></a>
2. "AI Safety in Generative AI Large Language Models A Survey". [Paper](https://arxiv.org/abs/2407.18369)
<a id="breaking-down-the-defenses-a-comparative-survey-of-attacks-on-large-language-models"></a>
3. "Breaking Down the Defenses A Comparative Survey of Attacks on Large Language Models". [Paper](https://arxiv.org/abs/2403.04786)
<a id="building-guardrails-for-large-language-models"></a>
4. "Building Guardrails for Large Language Models". [Paper](https://arxiv.org/abs/2402.01822)
<a id="current-state-of-llm-risks-and-ai-guardrails"></a>
5. "Current state of LLM Risks and AI Guardrails". [Paper]()
<a id="grounding-and-evaluation-for-large-language-models-practical-challenges-and-lessons-learned-survey"></a>
6. "Grounding and Evaluation for Large Language Models Practical Challenges and Lessons Learned (Survey)". [Paper](https://dl.acm.org/doi/abs/10.1145/3637528.3671467?casa_token=lZW_sxgpn64AAAAA:a9GJzQHhhP8SeMWukFPgFPiHMbvpsjGorrZUjFaCGZzoCpmzV10l-l0fYnJF2q2dMI9hUA-Pyg7o)
<a id="safeguarding-large-language-models-a-survey"></a>
7. "Safeguarding Large Language Models A Survey". [Paper](https://arxiv.org/abs/2406.02622)
<a id="swiss-cheese-model-for-ai-safety-a-taxonomy-and-reference-architecture-for-multi-layered-guardrails-of-foundation-model-based-agents"></a>
8. "Swiss Cheese Model for AI Safety A Taxonomy and Reference Architecture for Multi-Layered Guardrails of Foundation Model Based Agents". [Paper](https://arxiv.org/abs/2408.02205)


## Techniques

### Adversarial Learning

<a id="a-causal-explainable-guardrails-for-large-language-models"></a>
1. "A Causal Explainable Guardrails for Large Language Models". [Paper](https://arxiv.org/abs/2405.04160)

### Causal analysis

<a id="a-causal-explainable-guardrails-for-large-language-models"></a>
1. "A Causal Explainable Guardrails for Large Language Models". [Paper](https://arxiv.org/abs/2405.04160)
<a id="integrating-emotional-and-linguistic-models-for-ethical-compliance-in-large-language-models"></a>
2. "Integrating Emotional and Linguistic Models for Ethical Compliance in Large Language Models". [Paper](https://arxiv.org/abs/2405.07076)

### Chain of thought

<a id="refining-input-guardrails-enhancing-llm-as-a-judge-efficiency-through-chain-of-thought-fine-tuning-and-alignment"></a>
1. "Refining Input Guardrails: Enhancing LLM-as-a-Judge Efficiency Through Chain-of-Thought Fine-Tuning and Alignment". [Paper](https://arxiv.org/abs/2501.13080)

### Fine-tunning

<a id="a-flexible-large-language-models-guardrail-development-methodology-applied-to-off-topic-prompt-detection"></a>
1. "A Flexible Large Language Models Guardrail Development Methodology Applied to Off-Topic Prompt Detection". [Paper](https://arxiv.org/abs/2411.12946)
<a id="alignment-with-preference-optimization-is-all-you-need-for-llm-safety"></a>
2. "Alignment with Preference Optimization Is All You Need for LLM Safety". [Paper](https://arxiv.org/abs/2409.07772)
<a id="cross-task-defense-instruction-tuning-llms-for-content-safety"></a>
3. "Cross-Task Defense: Instruction-Tuning LLMs for Content Safety". [Paper](https://arxiv.org/abs/2405.15202)
<a id="fine-tuning-quantization-and-llms-navigating-unintended-outcomes"></a>
4. "Fine-Tuning, Quantization, and LLMs: Navigating Unintended Outcomes". [Paper](https://arxiv.org/abs/2404.04392)
<a id="finetuning-as-a-defense-against-llm-secret-leaking"></a>
5. "Finetuning as a Defense Against LLM Secret-leaking". [Paper](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2024/EECS-2024-135.pdf)
<a id="guardrail-baselines-for-unlearning-in-llms"></a>
6. "Guardrail Baselines for Unlearning in LLMs". [Paper]()
<a id="improved-generation-of-adversarial-examples-against-safety-aligned-llms"></a>
7. "Improved Generation of Adversarial Examples Against Safety-aligned LLMs". [Paper](https://arxiv.org/abs/2405.20778)
<a id="multitask-mayhem-unveiling-and-mitigating-safety-gaps-in-llms-fine-tuning"></a>
8. "Multitask Mayhem: Unveiling and Mitigating Safety Gaps in LLMs Fine-tuning". [Paper](https://arxiv.org/abs/2409.15361)
<a id="navigating-the-safety-landscape-measuring-risks-in-finetuning-large-language-models"></a>
9. "Navigating the Safety Landscape Measuring Risks in Finetuning Large Language Models". [Paper](https://arxiv.org/abs/2405.17374)
<a id="overriding-safety-protections-of-open-source-models"></a>
10. "Overriding Safety protections of Open-source Models". [Paper](https://arxiv.org/abs/2409.19476)
<a id="overriding-safety-protections-of-open-source-models"></a>
11. "Overriding Safety protections of Open-source Models". [Paper](https://arxiv.org/abs/2409.19476)
<a id="picky-llms-and-unreliable-rms-an-empirical-study-on-safety-alignment-after-instruction-tuning"></a>
12. "Picky LLMs and Unreliable RMs: An Empirical Study on Safety Alignment after Instruction Tuning". [Paper](https://arxiv.org/abs/2502.01116)
<a id="safeguard-fine-tuned-llms-through-pre--and-post-tuning-model-merging"></a>
13. "Safeguard Fine-Tuned LLMs Through Pre- and Post-Tuning Model Merging". [Paper](https://arxiv.org/abs/2412.19512)

### Machine Learning Classifiers

<a id="juree-not-judges-safeguarding-llm-interactions-with-small-specialised-encoder-ensembles"></a>
1. "JurEE not Judges: safeguarding llm interactions with small, specialised Encoder Ensembles". [Paper](https://arxiv.org/abs/2410.08442)

### Optimization-based Approaches

<a id="pal-proxy-guided-black-box-attack-on-large-language-models"></a>
1. "PAL: Proxy-Guided Black-Box Attack on Large Language Models". [Paper](https://arxiv.org/abs/2402.09674)
<a id="pathseeker-exploring-llm-security-vulnerabilities-with-a-reinforcement-learning-based-jailbreak-approach"></a>
2. "PathSeeker Exploring LLM Security Vulnerabilities with a Reinforcement Learning-Based Jailbreak Approach". [Paper](https://arxiv.org/abs/2409.14177)
<a id="privagent-agentic-based-red-teaming-for-llm-privacy-leakage"></a>
3. "PrivAgent Agentic-based Red-teaming for LLM Privacy Leakage". [Paper]()

### Probabilistic Graphical Mode

<a id="guard-robust-reasoning-enabled-llm-guardrail-via"></a>
1. "Guard Robust Reasoning Enabled LLM Guardrail via". [Paper](https://arxiv.org/abs/2407.05557)

### Supervised Learning

<a id="a-three-branch-checks-and-balances-frameworkfor-context-aware-ethical-alignment-of-large-language-models"></a>
1. "A Three-Branch Checks-and-Balances Frameworkfor Context-Aware Ethical Alignment of Large Language Models". [Paper](https://arxiv.org/abs/2502.00136)



## Benchmark general-purpose

<a id="alert-a-comprehensive-benchmark-for-assessing-large-language-models-safety-through-red-teaming"></a>
1. "ALERT: A Comprehensive Benchmark for Assessing Large Language Models' Safety through Red Teaming". [Paper](https://arxiv.org/abs/2404.08676)
<a id="agent-safetybench-evaluating-the-safety-of-llm-agents"></a>
2. "Agent-SafetyBench: Evaluating the Safety of LLM Agents". [Paper](https://arxiv.org/abs/2412.14470)
<a id="benchmarking-llm-guardrails-in-handling-multilingual-toxicity"></a>
3. "Benchmarking LLM Guardrails in Handling Multilingual Toxicity". [Paper]()
<a id="cfsafety-comprehensive-fine-grained-safety-assessment-for-llms"></a>
4. "CFSafety: Comprehensive Fine-grained Safety Assessment for LLMs". [Paper](https://arxiv.org/abs/2410.21695)
<a id="heuristic-analysis-for-security-privacy-and-bias-of-text-generative-ai-ghatgpt-35-case-as-of-june-2023"></a>
5. "Heuristic Analysis for Security, Privacy and Bias of Text Generative AI GhatGPT-3.5 case as of June 2023". [Paper](https://ieeexplore.ieee.org/abstract/document/10397858)
<a id="online-safety-analysis-for-llms-a-benchmark-an-assessment-and-a-path-forward"></a>
6. "Online Safety Analysis for LLMs: a Benchmark, an Assessment, and a Path Forward". [Paper](https://arxiv.org/abs/2404.08517)
<a id="openeval-benchmarking-chinese-llms-across-capability-alignment-and-safety"></a>
7. "OpenEval: Benchmarking Chinese LLMs across Capability, Alignment and Safety". [Paper](https://arxiv.org/abs/2403.12316)
<a id="position-building-guardrails-for-large-language-models-requires-systematic-design"></a>
8. "Position Building Guardrails for Large Language Models Requires Systematic Design". [Paper](https://openreview.net/forum?id=JvMLkGF2Ms)
<a id="r-judge-benchmarking-safety-risk-awareness-for-llm-agents"></a>
9. "R-Judge: Benchmarking Safety Risk Awareness for LLM Agents". [Paper](https://arxiv.org/abs/2401.10019)
<a id="walledeval-a-comprehensive-safety-evaluation-toolkit-for-large-language-models"></a>
10. "WalledEval A Comprehensive Safety Evaluation Toolkit for Large Language Models". [Paper](https://arxiv.org/abs/2408.03837)

## Jailbreaking

<a id="1---top-can-safety-fine-tuning-be-more-principled-lessons-learned-from-cybersecurity"></a>
1. "1 - TOP Can Safety Fine-Tuning Be More Principled? Lessons Learned from Cybersecurity". [Paper](https://arxiv.org/abs/2501.11183)
<a id="attacks-defenses-and-evaluations-for-llm-conversation-safety-a-survey"></a>
2. "Attacks, Defenses and Evaluations for LLM Conversation Safety: A Survey". [Paper](https://arxiv.org/abs/2402.09283)
<a id="bypassing-the-safety-training-of-open-source-llms-with-priming-attacks"></a>
3. "Bypassing the Safety Training of Open-Source LLMs with Priming Attacks". [Paper](https://arxiv.org/abs/2312.12321)
<a id="clas-2024-the-competition-for-llm-and-agent-safety"></a>
4. "CLAS 2024 The Competition for LLM and Agent Safety". [Paper](https://openreview.net/forum?id=GIDw94AlZK)
<a id="code-switching-red-teaming-llm-evaluation-for-safety-and-multilingual-understanding"></a>
5. "Code-Switching Red-Teaming: LLM Evaluation for Safety and Multilingual Understanding". [Paper](https://arxiv.org/abs/2406.15481)
<a id="codeattack-revealing-safety-generalization-challenges-of-large-language-models-via-code-completion"></a>
6. "CodeAttack: Revealing Safety Generalization Challenges of Large Language Models via Code Completion". [Paper](https://arxiv.org/abs/2403.07865)
<a id="deepinception-hypnotize-large-language-model-to-be-jailbreaker"></a>
7. "DeepInception: Hypnotize Large Language Model to Be Jailbreaker". [Paper](https://arxiv.org/abs/2311.03191)
<a id="derail-yourself-multi-turn-llm-jailbreak-attack-through-self-discovered-clues"></a>
8. "Derail Yourself Multi-turn LLM Jailbreak Attack through Self-discovered Clues". [Paper](https://arxiv.org/abs/2410.10700)
<a id="developing-assurance-cases-for-adversarial-robustness-and-regulatory-compliance-in-llms"></a>
9. "Developing Assurance Cases for Adversarial Robustness and Regulatory Compliance in LLMs". [Paper](https://ieeexplore.ieee.org/abstract/document/10771205)
<a id="does-safety-training-of-llms-generalize-to-semantically-related-natural-prompts"></a>
10. "Does Safety Training of LLMs Generalize to Semantically Related Natural Prompts?". [Paper](https://arxiv.org/abs/2412.03235)
<a id="emerging-vulnerabilities-in-frontier-models-multi-turn-jailbreak-attacks"></a>
11. "Emerging Vulnerabilities in Frontier Models: Multi-Turn Jailbreak Attacks". [Paper](https://arxiv.org/abs/2409.00137)
<a id="fundamental-limitations-of-alignment-in-large-language-models"></a>
12. "Fundamental Limitations of Alignment in Large Language Models". [Paper](https://arxiv.org/abs/2304.11082)
<a id="how-unethical-are-instruction-centric-responses-of-llms-unveiling-the-vulnerabilities-of-safety-guardrails-to-harmful-queries"></a>
13. "How (un)ethical are instruction-centric responses of LLMs? Unveiling the vulnerabilities of safety guardrails to harmful queries". [Paper](https://arxiv.org/abs/2402.15302)
<a id="how-alignment-and-jailbreak-work-explain-llm-safety-through-intermediate-hidden-states"></a>
14. "How Alignment and Jailbreak Work Explain LLM Safety through Intermediate Hidden States". [Paper](https://arxiv.org/abs/2406.05644)
<a id="how-alignment-and-jailbreak-work-explain-llm-safety-through-intermediate-hidden-states"></a>
15. "How Alignment and Jailbreak Work: Explain LLM Safety through Intermediate Hidden States". [Paper](https://arxiv.org/abs/2406.05644)
<a id="jailbreak-attacks-and-defenses-against-large-language-models-a-survey"></a>
16. "Jailbreak Attacks and Defenses Against Large Language Models A Survey". [Paper](https://arxiv.org/abs/2407.04295)
<a id="jailbreaking-and-mitigation-of-vulnerabilities-in-large-language-models"></a>
17. "Jailbreaking and Mitigation of Vulnerabilities in Large Language Models". [Paper](https://arxiv.org/abs/2410.15236)
<a id="top-4---all-things-adversarial-in-llms-a-survey"></a>
18. "TOP 4 - All things Adversarial in LLMs A survey". [Paper](https://sachit3022.github.io/files/Adverserial_text.pdf)
<a id="top-5---attack-atlas-a-practitioners-perspective-on-challenges-and-pitfalls-in-red-teaming-genai"></a>
19. "TOP 5 - Attack Atlas A Practitioner's Perspective on Challenges and Pitfalls in Red Teaming GenAI". [Paper]()

### Benchmark

<a id="agentharm-a-benchmark-for-measuring-harmfulness-of-llm-agents"></a>
1. "AgentHarm A Benchmark for Measuring Harmfulness of LLM Agents". [Paper](https://arxiv.org/abs/2410.09024)
<a id="bells-a-framework-towards-future-proof-benchmarks-for-the-evaluation-of-llm-safeguards"></a>
2. "BELLS: A Framework Towards Future Proof Benchmarks for the Evaluation of LLM Safeguards". [Paper](https://arxiv.org/abs/2406.01364)
<a id="impact-of-non-standard-unicode-characters-on-security-and-comprehension-in-large-language-models"></a>
3. "Impact of Non-Standard Unicode Characters on Security and Comprehension in Large Language Models". [Paper](https://arxiv.org/abs/2405.14490)
<a id="injecguard-benchmarking-and-mitigating-over-defense-in-prompt-injection-guardrail-models-1"></a>
4. "InjecGuard Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models 1". [Paper](https://arxiv.org/abs/2410.22770)
<a id="jade-a-linguistics-based-safety-evaluation-platform-for-large-language-models"></a>
5. "JADE: A Linguistics-based Safety Evaluation Platform for Large Language Models". [Paper](https://arxiv.org/abs/2311.00286)
<a id="jailbreakbench-an-open-robustness-benchmark-for-jailbreaking-large-language-models"></a>
6. "JailbreakBench An Open Robustness Benchmark for Jailbreaking Large Language Models". [Paper](https://arxiv.org/abs/2404.01318)
<a id="jailbreaking-large-language-models-against-moderation-guardrails-via-cipher-characters"></a>
7. "Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters". [Paper](https://arxiv.org/abs/2405.20413)
<a id="jailbroken-how-does-llm-safety-training-fail"></a>
8. "Jailbroken: How Does LLM Safety Training Fail?". [Paper](https://arxiv.org/abs/2307.02483)
<a id="llms-lost-in-translation-m-alert-uncovers-cross-linguistic-safety-gaps"></a>
9. "LLMs Lost in Translation: M-ALERT uncovers Cross-Linguistic Safety Gaps". [Paper](https://arxiv.org/abs/2412.15035)
<a id="llms-for-multi-modal-knowledge-extraction-and-analysis-in-intelligencesafety-critical-applications"></a>
10. "LLMs for Multi-Modal Knowledge Extraction and Analysis in Intelligence/Safety-Critical Applications". [Paper](https://arxiv.org/abs/2312.03088)
<a id="longsafetybench-long-context-llms-struggle-with-safety-issues"></a>
11. "LongSafetyBench: Long-Context LLMs Struggle with Safety Issues". [Paper](https://arxiv.org/abs/2411.06899)
<a id="sg-bench-evaluating-llm-safety-generalization-across-diverse-tasks-and-prompt-types"></a>
12. "SG-Bench: Evaluating LLM Safety Generalization Across Diverse Tasks and Prompt Types". [Paper](https://arxiv.org/abs/2410.21965)
<a id="the-art-of-defending-a-systematic-evaluation-and-analysis-of-llm-defense-strategies-on-safety-and-over-defensiveness"></a>
13. "The Art of Defending A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness". [Paper]()
<a id="the-art-of-defending-a-systematic-evaluation-and-analysis-of-llm-defense-strategies-on-safety-and-over-defensiveness"></a>
14. "The Art of Defending: A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness". [Paper](https://arxiv.org/abs/2401.00287)
<a id="h4rm3l-a-dynamic-benchmark-of-composable-jailbreak-attacks-for-llm-safety-assessment"></a>
15. "h4rm3l A Dynamic Benchmark of Composable Jailbreak Attacks for LLM Safety Assessment". [Paper](https://arxiv.org/abs/2408.04811)

### Black-box

<a id="do-anything-now-characterizing-and-evaluating-in-the-wild-jailbreak-prompts-on-large-language-models"></a>
1. ""Do Anything Now" Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models". [Paper](https://dl.acm.org/doi/abs/10.1145/3658644.3670388?casa_token=6LkeuCb-cCkAAAAA:Tthu9sQK2mKBsn8R80bffKB0_V5MVnSReTi0PSIduYZJAC6-CbrrVvVYIELhwW08VP7Cd9qmfi26)
<a id="moralized-multi-step-jailbreak-prompts-black-box-testing-of-guardrails-in-large-language-models-for-verbal-attacks"></a>
2. ""Moralized" Multi-Step Jailbreak Prompts Black-Box Testing of Guardrails in Large Language Models for Verbal Attacks". [Paper](https://arxiv.org/abs/2411.16730)
<a id="moralized-multi-step-jailbreak-prompts-black-box-testing-of-guardrails-in-large-language-models-for-verbal-attacks"></a>
3. ""Moralized" Multi-Step Jailbreak Prompts: Black-Box Testing of Guardrails in Large Language Models for Verbal Attacks". [Paper](https://arxiv.org/abs/2411.16730)
<a id="covert-malicious-finetuning-challenges-in-safeguarding-llm-adaptation"></a>
4. "Covert Malicious Finetuning: Challenges in Safeguarding LLM Adaptation". [Paper](https://arxiv.org/abs/2406.20053)
<a id="emoji-attack-a-method-for-misleading-judge-llms-in-safety-risk-detection"></a>
5. "Emoji Attack: A Method for Misleading Judge LLMs in Safety Risk Detection". [Paper](https://arxiv.org/abs/2411.01077)
<a id="flipattack-jailbreak-llms-via-flipping"></a>
6. "FlipAttack: Jailbreak LLMs via Flipping". [Paper](https://arxiv.org/abs/2410.02832)
<a id="how-johnny-can-persuade-llms-to-jailbreak-them-rethinking-persuasion-to-challenge-ai-safety-by-humanizing-llms"></a>
7. "How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs". [Paper](https://arxiv.org/abs/2401.06373)
<a id="jailbreaking-black-box-large-language-models-in-twenty-queries"></a>
8. "Jailbreaking Black Box Large Language Models in Twenty Queries". [Paper](https://arxiv.org/abs/2310.08419)
<a id="jailbreaking-llm-controlled-robots"></a>
9. "Jailbreaking LLM-Controlled Robots". [Paper](https://arxiv.org/abs/2410.13691)
<a id="jailbreaking-large-language-models-in-infinitely-many-ways"></a>
10. "Jailbreaking Large Language Models in Infinitely Many Ways". [Paper](https://arxiv.org/abs/2501.10800)
<a id="jailbreaking-leading-safety-aligned-llms-with-simple-adaptive-attacks"></a>
11. "Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks". [Paper]()
<a id="llm-defenses-are-not-robust-to-multi-turn-human-jailbreaks-yet"></a>
12. "LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet". [Paper](https://arxiv.org/abs/2408.15221)
<a id="large-language-models-are-vulnerable-to-bait-and-switch-attacks-for-generating-harmful-content"></a>
13. "Large Language Models are Vulnerable to Bait-and-Switch Attacks for Generating Harmful Content". [Paper](https://arxiv.org/abs/2402.13926)
<a id="sop-unlock-the-power-of-social-facilitation-for-automatic-jailbreak-attack"></a>
14. "SoP: Unlock the Power of Social Facilitation for Automatic Jailbreak Attack". [Paper](https://arxiv.org/abs/2407.01902)
<a id="speechguard-exploring-the-adversarial-robustness-of-multimodal-large-language-models-1"></a>
15. "SpeechGuard Exploring the Adversarial Robustness of Multimodal Large Language Models 1". [Paper](https://arxiv.org/abs/2405.08317)
<a id="the-language-barrier-dissecting-safety-challenges-of-llms-in-multilingual-contexts"></a>
16. "The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts". [Paper](https://arxiv.org/abs/2401.13136)
<a id="when-llm-meets-drl-advancing-jailbreaking-efficiency-via-drl-guided-search"></a>
17. "When LLM Meets DRL Advancing Jailbreaking Efficiency via DRL-guided Search". [Paper](https://arxiv.org/abs/2406.08705)

#### Automation

<a id="mart-improving-llm-safety-with-multi-round-automatic-red-teaming"></a>
1. "MART: Improving LLM Safety with Multi-round Automatic Red-Teaming". [Paper](https://arxiv.org/abs/2311.07689)
<a id="tree-of-attacks-jailbreaking-black-box-llms-automatically"></a>
2. "Tree of Attacks: Jailbreaking Black-Box LLMs Automatically". [Paper](https://arxiv.org/abs/2312.02119)

#### Delicately Designed Attacks

<a id="multilingual-blending-llm-safety-alignment-evaluat"></a>
1. "Multilingual Blending LLM Safety Alignment Evaluat". [Paper](https://arxiv.org/abs/2407.07342)

#### Prompt Injection

<a id="wordgame-efficient-effective-llm-jailbreak-via-simultaneous-obfuscation-in-query-and-response"></a>
1. "WordGame Efficient & Effective LLM Jailbreak via Simultaneous Obfuscation in Query and Response". [Paper](https://arxiv.org/abs/2405.14023)

### Defense

<a id="1--top-adversarial-prompt-evaluation-systematic-benchmarking-of-guardrails-against-prompt-input-attacks-on-llms"></a>
1. "1- TOP-Adversarial Prompt Evaluation Systematic Benchmarking of Guardrails Against Prompt Input Attacks on LLMs". [Paper](https://openreview.net/forum?id=a44MiSFw6G)
<a id="2-top---aegis-online-adaptive-ai-content-safety-moderation-with-ensemble-of-llm-experts"></a>
2. "2 TOP - AEGIS Online Adaptive AI Content Safety Moderation with Ensemble of LLM Experts". [Paper](https://arxiv.org/abs/2404.05993)
<a id="adversllm-a-practical-guide-togovernance-maturity-and-riskassessment-forllm-based-applications"></a>
3. "ADVERSLLM A PRACTICAL GUIDE TOGOVERNANCE, MATURITY AND RISKASSESSMENT FORLLM-BASED APPLICATIONS". [Paper](https://ijcionline.com/paper/13/13624ijci04.pdf)
<a id="adashield-safeguarding-multimodal-large-language-models-from-structure-based-attack-via-adaptive-shield-prompting"></a>
4. "AdaShield Safeguarding Multimodal Large Language Models from Structure-Based Attack via Adaptive Shield Prompting". [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72661-3_5)
<a id="aegis20-a-diverse-ai-safety-dataset-and-risks-taxonomy-for-alignment-of-llm-guardrails"></a>
5. "Aegis2.0: A Diverse AI Safety Dataset and Risks Taxonomy for Alignment of LLM Guardrails". [Paper](https://arxiv.org/abs/2501.09004)
<a id="bridging-the-safety-gap-a-guardrail-pipeline-for-trustworthy-llm-inferences"></a>
6. "Bridging the Safety Gap A Guardrail Pipeline for Trustworthy LLM Inferences". [Paper](https://openreview.net/forum?id=KjxZ4BdUdN)
<a id="certifying-llm-safety-against-adversarial-prompting"></a>
7. "Certifying LLM Safety against Adversarial Prompting". [Paper](https://arxiv.org/abs/2309.02705)
<a id="coreguard-safeguarding-foundational-capabilities-of-llms-against-model-stealing-in-edge-deployment"></a>
8. "CoreGuard: Safeguarding Foundational Capabilities of LLMs Against Model Stealing in Edge Deployment". [Paper](https://arxiv.org/abs/2410.13903)
<a id="dspy-guardrails-building-safe-llm-applications-via-self-refining-language-model-pipelines"></a>
9. "DSPy Guardrails Building Safe LLM Applications via Self-Refining Language Model Pipelines". [Paper](https://boxiyu.github.io/assets/pdf/DSPy_Guardrails.pdf)
<a id="defensive-prompt-patch-a-robust-and-interpretable-defense-of-llms-against-jailbreak-attacks"></a>
10. "Defensive Prompt Patch A Robust and Interpretable Defense of LLMs against Jailbreak Attacks". [Paper](https://arxiv.org/abs/2405.20099)
<a id="detectors-for-safe-and-reliable-llms-implementations-uses-and-limitations-1"></a>
11. "Detectors for Safe and Reliable LLMs Implementations, Uses, and Limitations 1". [Paper]()
<a id="efficient-adversarial-training-in-llms-with-continuous-attacks"></a>
12. "Efficient Adversarial Training in LLMs with Continuous Attacks". [Paper](https://arxiv.org/abs/2405.15589)
<a id="guard-d-llm-an-llm-based-risk-assessment-engine-for-the-downstream-uses-of-llms"></a>
13. "GUARD-D-LLM An LLM-Based Risk Assessment Engine for the Downstream uses of LLMs". [Paper]()
<a id="guardian-a-multi-tiered-defense-architecture-for-thwarting-prompt-injection-attacks-on-llms"></a>
14. "GUARDIAN A Multi-Tiered Defense Architecture for Thwarting Prompt Injection Attacks on LLMs". [Paper]()
<a id="gentel-safe-a-unified-benchmark-and-shielding-framework-for-defending-against-prompt-injection-attacks"></a>
15. "GenTel-Safe: A Unified Benchmark and Shielding Framework for Defending Against Prompt Injection Attacks". [Paper](https://arxiv.org/abs/2409.19521)
<a id="goal-oriented-prompt-attack-and-safety-evaluation-for-llms"></a>
16. "Goal-Oriented Prompt Attack and Safety Evaluation for LLMs". [Paper](https://arxiv.org/abs/2309.11830)
<a id="gradsafe-detecting-jailbreak-prompts-for-llms-via-safety-critical-gradient-analysis"></a>
17. "GradSafe: Detecting Jailbreak Prompts for LLMs via Safety-Critical Gradient Analysis". [Paper](https://arxiv.org/abs/2402.13494)
<a id="gradient-cuff-detecting-jailbreak-attacks-on-large-language-models-by-exploring-refusal-loss-landscapes"></a>
18. "Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes". [Paper](https://arxiv.org/abs/2403.00867)
<a id="granite-guardian"></a>
19. "Granite Guardian". [Paper](https://arxiv.org/abs/2412.07724)
<a id="guardagent-safeguard-llm-agents-by-a-guard-agent-via-knowledge-enabled-reasoning"></a>
20. "GuardAgent Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning". [Paper]()
<a id="guardagent-safeguard-llm-agents-by-a-guard-agent-via-knowledge-enabled-reasoning"></a>
21. "GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning". [Paper](https://arxiv.org/abs/2406.09187)
<a id="guardreasoner-towards-reasoning-based-llm-safeguards"></a>
22. "GuardReasoner: Towards Reasoning-based LLM Safeguards". [Paper](https://arxiv.org/abs/2501.18492)
<a id="humorreject-decoupling-llm-safety-from-refusal-prefix-via-a-little-humor"></a>
23. "HumorReject: Decoupling LLM Safety from Refusal Prefix via A Little Humor". [Paper](https://arxiv.org/abs/2501.13677)
<a id="immune-improving-safety-against-jailbreaks-in-multi-modal-llms-via-inference-time-alignment"></a>
24. "Immune: Improving Safety Against Jailbreaks in Multi-modal LLMs via Inference-Time Alignment". [Paper](https://arxiv.org/abs/2411.18688)
<a id="injecguard-benchmarking-and-mitigating-over-defense-in-prompt-injection-guardrail-models"></a>
25. "InjecGuard Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models". [Paper](https://arxiv.org/abs/2410.22770)
<a id="instructional-segment-embedding-improving-llm-safety-with-instruction-hierarchy"></a>
26. "Instructional Segment Embedding: Improving LLM Safety with Instruction Hierarchy". [Paper](https://arxiv.org/abs/2410.09102)
<a id="jailbreaking-llms-safeguard-with-universal-magic-words-for-text-embedding-models"></a>
27. "Jailbreaking LLMs' Safeguard with Universal Magic Words for Text Embedding Models". [Paper](https://arxiv.org/abs/2501.18280)
<a id="llmguard-guarding-against-unsafe-llm-behavior"></a>
28. "LLMGuard Guarding against Unsafe LLM Behavior". [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30566)
<a id="lionguard-building-a-contextualized-moderation-classifier-to-tackle-localized-unsafe-content"></a>
29. "LionGuard: Building a Contextualized Moderation Classifier to Tackle Localized Unsafe Content". [Paper](https://arxiv.org/abs/2407.10995)
<a id="lora-guard-parameter-efficient-guardrail-adaptation-for-content-moderation-of-large-language-models"></a>
30. "LoRA-Guard Parameter-Efficient Guardrail Adaptation for Content Moderation of Large Language Models". [Paper](https://arxiv.org/abs/2407.02987)
<a id="maatphor-automated-variant-analysis-for-prompt-injection-attacks"></a>
31. "Maatphor: Automated Variant Analysis for Prompt Injection Attacks". [Paper](https://arxiv.org/abs/2312.11513)
<a id="mogu-a-framework-for-enhancing-safety-of-open-sourced-llms-while-preserving-their-usability"></a>
32. "MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability". [Paper](https://arxiv.org/abs/2405.14488)
<a id="moje-mixture-of-jailbreak-experts-naive-tabular-classifiers-as-guard-for-prompt-attacks"></a>
33. "MoJE Mixture of Jailbreak Experts, Naive Tabular Classifiers as Guard for Prompt Attacks". [Paper](https://ojs.aaai.org/index.php/AIES/article/view/31638)
<a id="on-promptdriven-safeguarding-for-large-language-models"></a>
34. "On PromptDriven Safeguarding for Large Language Models". [Paper](https://openreview.net/forum?id=ugxGpOEkox)
<a id="overthink-slowdown-attacks-on-reasoning-llms"></a>
35. "OverThink: Slowdown Attacks on Reasoning LLMs". [Paper](https://arxiv.org/abs/2502.02542)
<a id="prp-propagating-universal-perturbations-to-attack-large-language-model-guard-rails"></a>
36. "PRP Propagating Universal Perturbations to Attack Large Language Model Guard-Rails". [Paper](https://arxiv.org/abs/2402.15911)
<a id="primeguard-safe-and-helpful-llms-through-tuning-free-routing"></a>
37. "PrimeGuard Safe and Helpful LLMs through Tuning-Free Routing". [Paper]()
<a id="refuse-whenever-you-feel-unsafe-improving-safety-in-llms-via-decoupled-refusal-training"></a>
38. "Refuse Whenever You Feel Unsafe: Improving Safety in LLMs via Decoupled Refusal Training". [Paper](https://arxiv.org/abs/2407.09121)
<a id="representation-noising-a-defence-mechanism-against-harmful-finetuning"></a>
39. "Representation Noising: A Defence Mechanism Against Harmful Finetuning". [Paper](https://arxiv.org/abs/2405.14577)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content"></a>
40. "RigorLLM Resilient Guardrails for Large Language Models against Undesired Content". [Paper](https://arxiv.org/abs/2403.13031)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content"></a>
41. "RigorLLM: Resilient Guardrails for Large Language Models against Undesired Content". [Paper](https://arxiv.org/abs/2403.13031)
<a id="robust-llm-safeguarding-via-refusal-feature-adversarial-training"></a>
42. "Robust LLM safeguarding via refusal feature adversarial training". [Paper](https://arxiv.org/abs/2409.20089)
<a id="safeguarding-system-prompts-for-llms"></a>
43. "Safeguarding System Prompts for LLMs". [Paper](https://arxiv.org/abs/2412.13426)
<a id="safety-layers-in-aligned-large-language-models-the-key-to-llm-security"></a>
44. "Safety Layers in Aligned Large Language Models: The Key to LLM Security". [Paper](https://arxiv.org/abs/2408.17003)
<a id="securing-retrieval-augmented-generation-pipelines-a-comprehensive-framework"></a>
45. "Securing Retrieval-Augmented Generation Pipelines A Comprehensive Framework". [Paper](https://www.neliti.com/publications/590025/securing-retrieval-augmented-generation-pipelines-a-comprehensive-framework)
<a id="self-guard-empower-the-llm-to-safeguard-itself"></a>
46. "Self-Guard Empower the LLM to Safeguard Itself". [Paper](https://arxiv.org/abs/2310.15851)
<a id="shieldlm-empowering-llms-as-aligned-customizable-and-explainable-safety-detectors"></a>
47. "ShieldLM: Empowering LLMs as Aligned, Customizable and Explainable Safety Detectors". [Paper](https://arxiv.org/abs/2402.16444)
<a id="smoothllm-defending-large-language-models-against-jailbreaking-attacks"></a>
48. "SmoothLLM Defending Large Language Models Against Jailbreaking Attacks". [Paper](https://arxiv.org/abs/2310.03684)
<a id="strengthening-llm-trust-boundaries-a-survey-of-prompt-injection-attacks"></a>
49. "Strengthening LLM Trust Boundaries A Survey of Prompt Injection Attacks". [Paper](https://www.researchgate.net/profile/Missy-Cummings/publication/378072627_Strengthening_LLM_Trust_Boundaries_A_Survey_of_Prompt_Injection_Attacks/links/65c57ac379007454976ae142/Strengthening-LLM-Trust-Boundaries-A-Survey-of-Prompt-Injection-Attacks.pdf)
<a id="superficial-safety-alignment-hypothesis"></a>
50. "Superficial Safety Alignment Hypothesis". [Paper](https://arxiv.org/abs/2410.10862)
<a id="tamper-resistant-safeguards-for-open-weight-llms"></a>
51. "Tamper-Resistant Safeguards for Open-Weight LLMs". [Paper](https://arxiv.org/abs/2408.00761)
<a id="targeting-alignment-extracting-safety-classifiers-of-aligned-llms"></a>
52. "Targeting Alignment: Extracting Safety Classifiers of Aligned LLMs". [Paper](https://arxiv.org/abs/2501.16534)
<a id="targeting-alignment-extracting-safety-classifiers-of-aligned-llms"></a>
53. "Targeting Alignment: Extracting Safety Classifiers of Aligned LLMs". [Paper](https://arxiv.org/abs/2501.16534)
<a id="the-instruction-hierarchy-training-llms-to-prioritize-privileged-instructions"></a>
54. "The Instruction Hierarchy Training LLMs to Prioritize Privileged Instructions". [Paper](https://arxiv.org/abs/2404.13208)
<a id="torchopera-a-compound-ai-system-for-llm-safety"></a>
55. "TorchOpera A Compound AI System for LLM Safety". [Paper](https://arxiv.org/abs/2406.10847)
<a id="wildguard-open-one-stop-moderation-tools-for-safety-risks-jailbreaks-and-refusals-of-llms"></a>
56. "WildGuard: Open One-Stop Moderation Tools for Safety Risks, Jailbreaks, and Refusals of LLMs". [Paper](https://arxiv.org/abs/2406.18495)

### Frameworks

<a id="uniguard-towards-universal-safety-guardrails-for-jailbreak-attacks-on-multimodal-large-language-models"></a>
1. "UniGuard Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models". [Paper]()

### Gray-box

<a id="can-safety-fine-tuning-be-more-principled-lessons-learned-from-cybersecurity"></a>
1. "Can Safety Fine-Tuning Be More Principled? Lessons Learned from Cybersecurity". [Paper](https://arxiv.org/abs/2501.11183)
<a id="covert-malicious-finetuning-challenges-in-safeguarding-llm-adaptation"></a>
2. "Covert Malicious Finetuning Challenges in Safeguarding LLM Adaptation". [Paper](https://arxiv.org/abs/2406.20053)
<a id="evil-geniuses-delving-into-the-safety-of-llm-based-agents"></a>
3. "Evil Geniuses: Delving into the Safety of LLM-based Agents". [Paper](https://arxiv.org/abs/2311.11855)
<a id="fine-tuning-aligned-language-models-compromises-safety-even-when-users-do-not-intend-to"></a>
4. "Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!". [Paper](https://arxiv.org/abs/2310.03693)
<a id="from-prompt-injections-to-sql-injection-attacks-how-protected-is-your-llm-integrated-web-application"></a>
5. "From Prompt Injections to SQL Injection Attacks How Protected is Your LLM-Integrated Web Application?". [Paper]()
<a id="increased-llm-vulnerabilities-from-fine-tuning-and-quantization"></a>
6. "INCREASED LLM VULNERABILITIES FROM FINE-TUNING AND QUANTIZATION". [Paper]()
<a id="jailbreaking-llm-controlled-robots-1-1"></a>
7. "Jailbreaking LLM-Controlled Robots 1 1". [Paper](https://arxiv.org/abs/2410.13691)
<a id="language-model-unalignment-parametric-red-teaming-to-expose-hidden-harms-and-biases"></a>
8. "Language Model Unalignment Parametric Red-Teaming to Expose Hidden Harms and Biases". [Paper](https://arxiv.org/abs/2310.14303)
<a id="lora-as-an-attack-piercing-llm-safety-under-the-share-and-play-scenario"></a>
9. "LoRA-as-an-Attack! Piercing LLM Safety Under The Share-and-Play Scenario". [Paper](https://arxiv.org/abs/2403.00108)
<a id="peering-behind-the-shield-guardrail-identification-in-large-language-models"></a>
10. "Peering Behind the Shield Guardrail Identification in Large Language Models". [Paper](https://arxiv.org/abs/2502.01241)
<a id="safeguard-is-a-double-edged-sword-denial-of-service-attack-on-large-language-models"></a>
11. "Safeguard is a Double-edged Sword Denial-of-service Attack on Large Language Models". [Paper](https://arxiv.org/abs/2410.02916)
<a id="sowing-the-wind-reaping-the-whirlwind-the-impact-of-editing-language-models"></a>
12. "Sowing the Wind, Reaping the Whirlwind: The Impact of Editing Language Models". [Paper](https://arxiv.org/abs/2401.10647)
<a id="stochastic-monkeys-at-play-random-augmentations-cheaply-break-llm-safety-alignment"></a>
13. "Stochastic Monkeys at Play: Random Augmentations Cheaply Break LLM Safety Alignment". [Paper](https://arxiv.org/abs/2411.02785)
<a id="the-language-barrier-dissecting-safety-challenges-of-llms-in-multilingual-contexts"></a>
14. "The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts". [Paper](https://arxiv.org/abs/2401.13136)
<a id="virus-harmful-fine-tuning-attack-for-large-language-models-bypassing-guardrail-moderation"></a>
15. "Virus: Harmful Fine-tuning Attack for Large Language Models Bypassing Guardrail Moderation". [Paper](https://arxiv.org/abs/2501.17433)

### Others

<a id="on-evaluating-the-durability-of-safeguards-for-open-weight-llms"></a>
1. "On Evaluating the Durability of Safeguards for Open-Weight LLMs". [Paper](https://arxiv.org/abs/2412.07097)
<a id="purple-teaming-llms-with-adversarial-defender-training"></a>
2. "Purple-teaming LLMs with Adversarial Defender Training". [Paper](https://arxiv.org/abs/2407.01850)
<a id="purple-teaming-llms-with-adversarial-defender-training"></a>
3. "Purple-teaming LLMs with Adversarial Defender Training". [Paper](https://arxiv.org/abs/2407.01850)

### White-box

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

## Metrics

### Biases

<a id="1-top---chatgpt-doesnt-trust-chargers-fans-guardrail-sensitivity-in-context"></a>
1. "1 TOP - ChatGPT Doesn't Trust Chargers Fans Guardrail Sensitivity in Context". [Paper](https://arxiv.org/abs/2407.06866)
<a id="biaskg-adversarial-knowledge-graphs-to-induce-bias-in-large-language-models"></a>
2. "BiasKG: Adversarial Knowledge Graphs to Induce Bias in Large Language Models". [Paper](https://arxiv.org/abs/2405.04756)
<a id="chatgpt-and-bard-responses-to-polarizing-questions"></a>
3. "ChatGPT and Bard Responses to Polarizing Questions". [Paper](https://arxiv.org/abs/2307.12402)
<a id="debiasing-text-safety-classifiers-through-a-fairness-aware-ensemble"></a>
4. "Debiasing Text Safety Classifiers through a Fairness-Aware Ensemble". [Paper](https://arxiv.org/abs/2409.13705)
<a id="gender-bias-in-decision-making-with-large-language-models-a-study-of-relationship-conflicts"></a>
5. "Gender Bias in Decision-Making with Large Language Models: A Study of Relationship Conflicts". [Paper](https://arxiv.org/abs/2410.11084)
<a id="intentional-biases-in-llm-responses"></a>
6. "Intentional Biases in LLM Responses". [Paper](https://ieeexplore.ieee.org/abstract/document/10316060)
<a id="the-silence-of-the-llms-cross-lingual-analysis-of-guardrail-related-political-bias-and-false-information-prevalence-in-chatgpt-google-bard-gemini-and-bing-chat"></a>
7. "The silence of the LLMs Cross-lingual analysis of guardrail-related political bias and false information prevalence in ChatGPT, Google Bard (Gemini), and Bing Chat". [Paper]()
<a id="when-in-doubt-cascade-towards-building-efficient-and-capable-guardrails"></a>
8. "When in Doubt, Cascade: Towards Building Efficient and Capable Guardrails". [Paper](https://arxiv.org/abs/2407.06323)

### Ethical

<a id="ai-ethics-by-design-implementing-customizable-guardrails-for-responsible-ai-development"></a>
1. "AI Ethics by Design Implementing Customizable Guardrails for Responsible AI Development". [Paper]()
<a id="codehelp-using-large-language-models-with-guardrails-for-scalable-support-in-programming-classes"></a>
2. "CodeHelp Using Large Language Models with Guardrails for Scalable Support in Programming Classes". [Paper](https://dl.acm.org/doi/abs/10.1145/3631802.3631830)
<a id="right-to-be-forgotten-in-the-era-of-large-language-models-implications-challenges-and-solutions"></a>
3. "Right to be Forgotten in the Era of Large Language Models: Implications, Challenges, and Solutions". [Paper](https://arxiv.org/abs/2307.03941)

### Fairness

<a id="insaaf-incorporating-safety-through-accuracy-and-fairness-are-llms-ready-for-the-indian-legal-domain"></a>
1. "InSaAF: Incorporating Safety through Accuracy and Fairness | Are LLMs ready for the Indian Legal Domain?". [Paper](https://arxiv.org/abs/2402.10567)
<a id="watching-the-ai-watchdogs-a-fairness-and-robustness-analysis-of-ai-safety-moderation-classifiers"></a>
2. "Watching the AI Watchdogs: A Fairness and Robustness Analysis of AI Safety Moderation Classifiers". [Paper](https://arxiv.org/abs/2501.13302)

### Hallucination

<a id="a-survey-on-hallucination-in-large-language-models-principles-taxonomy-challenges-and-open-questions-1"></a>
1. "A Survey on Hallucination in Large Language Models Principles, Taxonomy, Challenges, and Open Questions 1". [Paper](https://arxiv.org/abs/2311.05232)
<a id="hallucinating-ai-hijacking-attack-large-language-models-and-malicious-code-recommenders"></a>
2. "Hallucinating AI Hijacking Attack: Large Language Models and Malicious Code Recommenders". [Paper](https://arxiv.org/abs/2410.06462)
<a id="hallucination-minimized-data-to-answer-framework-for-financial-decision-makers"></a>
3. "Hallucination-minimized Data-to-answer Framework for Financial Decision-makers". [Paper](https://arxiv.org/abs/2311.07592)
<a id="the-need-for-guardrails-with-large-language-models-in-medical-safety-critical-settings-an-artificial-intelligence-application-in-the-pharmacovigilance-ecosystem"></a>
4. "The Need for Guardrails with Large Language Models in Medical Safety-Critical Settings: An Artificial Intelligence Application in the Pharmacovigilance Ecosystem". [Paper](https://arxiv.org/abs/2407.18322)

### Performance

<a id="despite-super-human-performance-current-llms-are-unsuited-for-decisions-about-ethics-and-safety"></a>
1. "Despite "super-human" performance, current LLMs are unsuited for decisions about ethics and safety". [Paper](https://arxiv.org/abs/2212.06295)
<a id="lightweight-safety-guardrails-using-fine-tuned-bert-embeddings"></a>
2. "Lightweight Safety Guardrails Using Fine-tuned BERT Embeddings". [Paper](https://arxiv.org/abs/2411.14398)

### Privacy

<a id="deploying-privacy-guardrails-for-llms-a-comparative-analysis-of-real-world-applications"></a>
1. "Deploying Privacy Guardrails for LLMs: A Comparative Analysis of Real-World Applications". [Paper](https://arxiv.org/abs/2501.12456)
<a id="unique-security-and-privacy-threats-of-large-language-model-a-comprehensive-survey"></a>
2. "Unique Security and Privacy Threats of Large Language Model A Comprehensive Survey". [Paper](https://arxiv.org/abs/2406.07973)

### Reliability

<a id="combining-domain-and-alignment-vectors-to-achieve-better-knowledge-safety-trade-offs-in-llms"></a>
1. "Combining Domain and Alignment Vectors to Achieve Better Knowledge-Safety Trade-offs in LLMs". [Paper](https://arxiv.org/abs/2411.06824)
<a id="is-safer-better-the-impact-of-guardrails-on-the-argumentative-strength-of-llms-in-hate-speech-countering"></a>
2. "Is Safer Better? The Impact of Guardrails on the Argumentative Strength of LLMs in Hate Speech Countering". [Paper](https://arxiv.org/abs/2410.03466)
<a id="on-calibration-of-llm-based-guard-models-for-reliable-content-moderation"></a>
3. "On Calibration of LLM-based Guard Models for Reliable Content Moderation". [Paper]()
<a id="plan-grounded-large-language-models-for-dual-goal-conversational-settings"></a>
4. "Plan-Grounded Large Language Models for Dual Goal Conversational Settings". [Paper](https://arxiv.org/abs/2402.01053)
<a id="trust-oriented-adaptive-guardrails-for-large-language-models"></a>
5. "Trust-Oriented Adaptive Guardrails for Large Language Models". [Paper]()

### Robustness

<a id="active-learning-for-robust-and-representative-llm-generation-in-safety-critical-scenarios"></a>
1. "Active Learning for Robust and Representative LLM Generation in Safety-Critical Scenarios". [Paper](https://arxiv.org/abs/2410.11114)
<a id="detectors-for-safe-and-reliable-llms-implementations-uses-and-limitations"></a>
2. "Detectors for Safe and Reliable LLMs Implementations, Uses, and Limitations". [Paper](https://arxiv.org/abs/2403.06009)
<a id="detectors-for-safe-and-reliable-llms-implementations-uses-and-limitations"></a>
3. "Detectors for Safe and Reliable LLMs: Implementations, Uses, and Limitations". [Paper](https://arxiv.org/abs/2403.06009)
<a id="developing-assurance-cases-for-adversarial-robustness-and-regulatory-compliance-in-llms"></a>
4. "Developing Assurance Cases for Adversarial Robustness and Regulatory Compliance in LLMs". [Paper](https://arxiv.org/abs/2410.05304)
<a id="do-not-answer-a-dataset-for-evaluating-safeguards-in-llms"></a>
5. "Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs". [Paper](https://arxiv.org/abs/2308.13387)
<a id="guardrails-automated-suggestions-for-clarifying-ambiguous-purpose-statements-1"></a>
6. "GuardRails Automated Suggestions for Clarifying Ambiguous Purpose Statements 1". [Paper](https://dl.acm.org/doi/abs/10.1145/3627217.3627234?casa_token=Y-C6zdZ4n08AAAAA:2Y6Es019NeK-6A4qA8rL9jISGc8d1oGZrMm6VxQXYJI1mJRLTLIzD_m8TONxI0gS1ZU1GWhY0dLe)
<a id="locking-down-the-finetuned-llms-safety"></a>
7. "Locking Down the Finetuned LLMs Safety". [Paper](https://arxiv.org/abs/2410.10343)
<a id="marco-multi-agent-real-time-chat-orchestration"></a>
8. "MARCO: Multi-Agent Real-time Chat Orchestration". [Paper](https://arxiv.org/abs/2410.21784)
<a id="ml-on-rails-safeguarding-machine-learning-models-in-software-systems-a-case-study"></a>
9. "ML-On-Rails Safeguarding Machine Learning Models in Software Systems A Case Study". [Paper]()
<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
10. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="rigorllm-resilient-guardrails-for-large-language-models-against-undesired-content-1"></a>
11. "RigorLLM Resilient Guardrails for Large Language Models against Undesired Content 1". [Paper](https://arxiv.org/abs/2403.13031)
<a id="towards-assurance-of-llm-adversarial-robustness-using-ontology-driven-argumentation"></a>
12. "Towards Assurance of LLM Adversarial Robustness using Ontology-Driven Argumentation". [Paper](https://arxiv.org/abs/2410.07962)

### Safety

<a id="activation-approximations-can-incur-safety-vulnerabilities-even-in-aligned-llms-comprehensive-analysis-and-defense"></a>
1. "Activation Approximations Can Incur Safety Vulnerabilities Even in Aligned LLMs Comprehensive Analysis and Defense". [Paper](https://arxiv.org/abs/2502.00840)
<a id="annotation-alignment-comparing-llm-and-human-annotations-of-conversational-safety"></a>
2. "Annotation alignment: Comparing LLM and human annotations of conversational safety". [Paper](https://arxiv.org/abs/2406.06369)
<a id="building-trust-in-mental-health-chatbots-safety-metrics-and-llm-based-evaluation-tools"></a>
3. "Building Trust in Mental Health Chatbots: Safety Metrics and LLM-Based Evaluation Tools". [Paper](https://arxiv.org/abs/2408.04650)
<a id="conscendi-a-contrastive-and-scenario-guided-distillation-approach-to-guardrail-models-for-virtual-assistants"></a>
4. "CONSCENDI A Contrastive and Scenario-Guided Distillation Approach to Guardrail Models for Virtual Assistants". [Paper](https://arxiv.org/abs/2304.14364)
<a id="combining-domain-and-alignment-vectors-to-achieve-better-knowledge-safety-trade-offs-in-llms"></a>
5. "Combining Domain and Alignment Vectors to Achieve Better Knowledge-Safety Trade-offs in LLMs". [Paper](https://arxiv.org/abs/2411.06824)
<a id="do-not-answer-a-dataset-for-evaluating-safeguards-in-llms"></a>
6. "Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs". [Paper](https://arxiv.org/abs/2308.13387)
<a id="does-refusal-training-in-llms-generalize-to-the-past-tense"></a>
7. "Does Refusal Training in LLMs Generalize to the Past Tense?". [Paper](https://arxiv.org/abs/2407.11969)
<a id="enhancing-llm-safety-via-constrained-direct-preference-optimization"></a>
8. "Enhancing LLM Safety via Constrained Direct Preference Optimization". [Paper](https://arxiv.org/abs/2403.02475)
<a id="ensuring-safety-and-trust-analyzing-the-risks-of-large-language-models-in-medicine"></a>
9. "Ensuring Safety and Trust Analyzing the Risks of Large Language Models in Medicine". [Paper](https://arxiv.org/abs/2411.14487)
<a id="harmaug-effective-data-augmentation-for-knowledge-distillation-of-safety-guard-models"></a>
10. "HarmAug Effective Data Augmentation for Knowledge Distillation of Safety Guard Models". [Paper](https://arxiv.org/abs/2410.01524)
<a id="llm-safety-alignment-is-divergence-estimation-in-disguise"></a>
11. "LLM Safety Alignment is Divergence Estimation in Disguise". [Paper](https://arxiv.org/abs/2502.00657)
<a id="large-language-model-safety-a-holistic-survey"></a>
12. "Large Language Model Safety A Holistic Survey". [Paper]()
<a id="locking-down-the-finetuned-llms-safety"></a>
13. "Locking Down the Finetuned LLMs Safety". [Paper](https://arxiv.org/abs/2410.10343)
<a id="mapping-llm-security-landscapes-a-comprehensive-stakeholder-risk-assessment-proposal"></a>
14. "Mapping LLM Security Landscapes A Comprehensive Stakeholder Risk Assessment Proposal". [Paper](https://arxiv.org/abs/2403.13309)
<a id="on-the-role-of-attention-heads-in-large-language-model-safety"></a>
15. "On the Role of Attention Heads in Large Language Model Safety". [Paper](https://arxiv.org/abs/2410.13708)
<a id="pku-saferlhf-towards-multi-level-safety-alignment-for-llms-with-human-preference"></a>
16. "PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs with Human Preference". [Paper](https://arxiv.org/abs/2406.15513)
<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
17. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="root-defence-strategies-ensuring-safety-of-llm-at-the-decoding-level"></a>
18. "Root Defence Strategies: Ensuring Safety of LLM at the Decoding Level". [Paper](https://arxiv.org/abs/2410.06809)
<a id="scans-mitigating-the-exaggerated-safety-for-llms-via-safety-conscious-activation-steering"></a>
19. "SCANS: Mitigating the Exaggerated Safety for LLMs via Safety-Conscious Activation Steering". [Paper](https://arxiv.org/abs/2408.11491)
<a id="seal-safety-enhanced-aligned-llm-fine-tuning-via-bilevel-data-selection"></a>
20. "SEAL: Safety-enhanced Aligned LLM Fine-tuning via Bilevel Data Selection". [Paper](https://arxiv.org/abs/2410.07471)
<a id="safeguarding-ai-agents-developing-and-analyzing-safety-architectures"></a>
21. "Safeguarding AI Agents Developing and Analyzing Safety Architectures". [Paper](https://arxiv.org/abs/2409.03793)
<a id="safeguarding-ai-agents-developing-and-analyzing-safety-architectures"></a>
22. "Safeguarding AI Agents: Developing and Analyzing Safety Architectures". [Paper](https://arxiv.org/abs/2409.03793)
<a id="scisafeeval-a-comprehensive-benchmark-for-safety-alignment-of-large-language-models-in-scientific-tasks"></a>
23. "SciSafeEval: A Comprehensive Benchmark for Safety Alignment of Large Language Models in Scientific Tasks". [Paper](https://arxiv.org/abs/2410.03769)
<a id="trust-safety-of-llms-and-llms-in-trust-safety"></a>
24. "Trust & Safety of LLMs and LLMs in Trust & Safety". [Paper](https://arxiv.org/abs/2412.02113)

### Security

<a id="adaptive-hardening-of-large-language-model-securityinventors"></a>
1. "Adaptive Hardening of Large Language Model SecurityInventor(s)". [Paper](https://www.tdcommons.org/dpubs_series/7250/)
<a id="arabic-dataset-for-llm-safeguard-evaluation"></a>
2. "Arabic Dataset for LLM Safeguard Evaluation". [Paper](https://arxiv.org/abs/2410.17040)
<a id="assessing-the-brittleness-of-safety-alignment-via-pruning-and-low-rank-modifications"></a>
3. "Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications". [Paper](https://arxiv.org/abs/2402.05162)
<a id="assessment-of-llm-responses-to-end-user-security-questions"></a>
4. "Assessment of LLM Responses to End-user Security Questions". [Paper]()
<a id="challenges-in-trustworthy-human-evaluation-of-chatbots"></a>
5. "Challenges in Trustworthy Human Evaluation of Chatbots". [Paper](https://arxiv.org/abs/2412.04363)
<a id="detectors-for-safe-and-reliable-llms-implementations-uses-and-limitations-1"></a>
6. "Detectors for Safe and Reliable LLMs Implementations, Uses, and Limitations 1". [Paper](https://arxiv.org/abs/2403.06009)
<a id="picky-llms-and-unreliable-rms-an-empirical-study-on-safety-alignment-after-instruction-tuning"></a>
7. "Picky LLMs and Unreliable RMs: An Empirical Study on Safety Alignment after Instruction Tuning". [Paper](https://arxiv.org/abs/2502.01116)
<a id="garak-a-framework-for-security-probing-large-language-models"></a>
8. "garak: A Framework for Security Probing Large Language Models". [Paper](https://arxiv.org/abs/2406.11036)

### Toxicity

<a id="can-a-large-language-model-be-a-gaslighter"></a>
1. "Can a large language model be a gaslighter?". [Paper](https://arxiv.org/abs/2410.09181)
<a id="decoding-hate-exploring-language-models-reactions-to-hate-speech"></a>
2. "Decoding Hate: Exploring Language Models' Reactions to Hate Speech". [Paper](https://arxiv.org/abs/2410.00775)
<a id="from-guard-rails-to-epic-fails-can-generative-ai-police-its-own-capacity-for-offence"></a>
3. "From Guard Rails to Epic Fails Can Generative AI Police Its Own Capacity for Offence?". [Paper](https://mediazioni.unibo.it/article/view/20544)
<a id="llms-with-personalities-in-multi-issue-negotiation-games"></a>
4. "LLMs with Personalities in Multi-issue Negotiation Games". [Paper](https://arxiv.org/abs/2405.05248)
<a id="toxicity-in-chatgpt-analyzing-persona-assigned-language-models"></a>
5. "Toxicity in ChatGPT: Analyzing Persona-assigned Language Models". [Paper](https://arxiv.org/abs/2304.05335)

### Uncertainty

<a id="prioritizing-safeguarding-over-autonomy-risks-of-llm-agents-for-science"></a>
1. "Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science". [Paper](https://arxiv.org/abs/2402.04247)
<a id="uncertainty-based-abstention-in-llms-improves-safety-and-reduces-hallucinations"></a>
2. "Uncertainty-Based Abstention in LLMs Improves Safety and Reduces Hallucinations". [Paper]()

## Multimodality

<a id="eyes-closed-safety-on-protecting-multimodal-llms-via-image-to-text-transformation"></a>
1. "Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation". [Paper](https://arxiv.org/abs/2403.09572)
<a id="highlighting-the-safety-concerns-of-deploying-llmsvlms-in-robotics"></a>
2. "Highlighting the Safety Concerns of Deploying LLMs/VLMs in Robotics". [Paper](https://arxiv.org/abs/2402.10340)
<a id="how-many-unicorns-are-in-this-image-a-safety-evaluation-benchmark-for-vision-llms"></a>
3. "How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs". [Paper](https://arxiv.org/abs/2311.16101)
<a id="learning-to-see-but-forgetting-to-follow-visual-instruction-tuning-makes-llms-more-prone-to-jailbreak-attacks"></a>
4. "Learning To See But Forgetting To Follow: Visual Instruction Tuning Makes LLMs More Prone To Jailbreak Attacks". [Paper](https://arxiv.org/abs/2405.04403)
<a id="safewatch-an-efficient-safety-policy-following-video-guardrail-model-with-transparent-explanations"></a>
5. "SafeWatch An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations". [Paper]()
<a id="speechguard-exploring-the-adversarial-robustness-of-multimodal-large-language-models-1-1-1"></a>
6. "SpeechGuard Exploring the Adversarial Robustness of Multimodal Large Language Models 1 1 1". [Paper](https://arxiv.org/abs/2405.08317)
<a id="the-vllm-safety-paradox-dual-ease-in-jailbreak-attack-and-defense"></a>
7. "The VLLM Safety Paradox: Dual Ease in Jailbreak Attack and Defense". [Paper](https://arxiv.org/abs/2411.08410)
<a id="video-watermarking-safeguarding-your-video-from-unauthorized-annotations-by-video-based-llms"></a>
8. "Video Watermarking: Safeguarding Your Video from (Unauthorized) Annotations by Video-based LLMs". [Paper](https://arxiv.org/abs/2407.02411)
<a id="visual-adversarial-examples-jailbreak-aligned-large-language-models"></a>
9. "Visual Adversarial Examples Jailbreak Aligned Large Language Models". [Paper](https://arxiv.org/abs/2306.13213)


## Popular frameworks

### Llama Guard

<a id="llama-guard-llm-based-input-output-safeguard-for-human-ai-conversations"></a>
1. "Llama Guard LLM-based Input-Output Safeguard for Human-AI Conversations". [Paper](https://arxiv.org/abs/2312.06674)

### Nvidia NeMo

<a id="nemo-guardrails-a-toolkit-for-controllable-and-safe-llm-applications-with-programmable-rails"></a>
1. "NeMo Guardrails A Toolkit for Controllable and Safe LLM Applications with Programmable Rails". [Paper]()

## Specific-Domain

<a id="building-a-domain-specific-guardrail-model-in-production"></a>
1. "Building a Domain-specific Guardrail Model in Production". [Paper](https://arxiv.org/abs/2408.01452)
<a id="challenges-in-guardrailing-large-language-models-for-science"></a>
2. "Challenges in Guardrailing Large Language Models for Science". [Paper](https://arxiv.org/abs/2411.08181)

