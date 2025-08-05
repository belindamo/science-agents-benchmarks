# Auto-Bench: An Automated Benchmark for Scientific Discovery in LLMs

**Authors:** Tingting Chen, Srinivas Anumasa, Beibei Lin, Vedant Shah, Anirudh Goyal, Dianbo Liu  
**Venue:** arXiv:2502.15224  
**Year:** 2025  
**URL:** https://arxiv.org/abs/2502.15224

## CS197 Analysis Framework

### Problem
- **Core Problem:** No standardized benchmark exists to evaluate LLMs' capability for autonomous scientific discovery
- **Why it Matters:** Given LLMs' remarkable performance, there's critical need to assess whether they can conduct human-like scientific research and discover new knowledge as "AI scientists"
- **Gap:** Scientific discovery requires iterative knowledge updating, environment understanding, hypothesis identification, and action reasoning - capabilities not systematically evaluated

### Assumption in Prior Work
- **Prior Assumption:** Scientific discovery capability can be assessed through general language tasks or domain-specific problem solving
- **Inadequacy:** Existing benchmarks fail to capture the interactive, iterative nature of scientific discovery where agents must:
  - Engage with experimental environments
  - Refine understanding through strategic interventions  
  - Uncover hidden causal structures
  - Generate valid justifications for hypotheses

### Insight
- **Novel Contribution:** Scientific discovery evaluation should be based on **causal graph discovery principles**
- **Key Innovation:** Interactive oracle-based framework where models iteratively refine understanding through strategic interventions
- **Breakthrough:** Challenges models to uncover hidden structures and make optimal decisions across both natural and social sciences

### Technical Overview
- **Framework:** Autonomous Cycle with interactive oracle
- **Methodology:** 
  - Models receive task descriptions and previous intervention/observation history
  - Generate adjacency matrices representing causal relationships
  - Propose new interventions to gather additional data
  - Loop continues until generated graph matches underlying causal structure
- **Domains:** Chemistry and social networks as experimental settings
- **Evaluation:** Performance measured by ability to discover true causal graph structure

### Proof
- **Evaluation Setup:** State-of-the-art LLMs tested (GPT-4, Gemini, Qwen, Claude, Llama)
- **Key Finding:** Significant performance drop as problem complexity increases
- **Results:** Models struggle with complex causal discovery tasks
- **Validation:** Demonstrates gap between machine and human intelligence in scientific reasoning

### Impact
- **Field Impact:** First standardized benchmark specifically designed for scientific discovery in LLM agents
- **Methodological Contribution:** Establishes causal graph discovery as core evaluation paradigm
- **Future Direction:** Provides foundation for developing more capable AI scientists
- **Research Acceleration:** Enables systematic comparison of different approaches to automated scientific discovery

## Key Takeaways
1. **Bit Flip:** From general language evaluation → causal discovery-based scientific evaluation
2. **Critical Gap:** Current LLMs fail at complex scientific reasoning despite general capabilities
3. **Benchmark Innovation:** Interactive, iterative evaluation more realistic than static tasks
4. **Research Priority:** Need for specialized architectures for scientific discovery vs. general language models