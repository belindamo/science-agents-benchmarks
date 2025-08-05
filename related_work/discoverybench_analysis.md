# DiscoveryBench: Towards Data-Driven Discovery with Large Language Models

**Authors:** Bodhisattwa Prasad Majumder, Harshit Surana, Dhruv Agarwal, Bhavana Dalvi Mishra, et al. (Allen Institute for AI)  
**Venue:** arXiv:2407.01725  
**Year:** 2024  
**URL:** https://arxiv.org/abs/2407.01725

## CS197 Analysis Framework

### Problem
- **Core Problem:** Unclear whether LLMs can automate hypothesis search and verification purely from provided datasets
- **Why it Matters:** Recent advances in code generation, function calling, and data analysis suggest potential for automated data-driven discovery
- **Gap:** No comprehensive benchmark formalizes the multi-step process of data-driven discovery for systematic evaluation

### Assumption in Prior Work
- **Prior Assumption:** LLM capabilities in coding and analysis naturally translate to scientific discovery
- **Inadequacy:** 
  - Existing benchmarks focus on reasoning without data or data analysis with predefined answers
  - Missing realistic evaluation of hypothesis generation and verification from raw datasets
  - No systematic assessment of discovery workflow capabilities

### Insight
- **Novel Contribution:** **Multi-step discovery process formalization** with systematic evaluation framework
- **Key Innovation:** Tasks derived from real published research workflows across diverse domains
- **Breakthrough:** Combines dataset provision with natural language discovery goals to approximate real research challenges

### Technical Overview
- **Benchmark Structure:**
  - **Real Tasks:** 264 tasks across 6 domains (sociology, engineering, etc.)
  - **Synthetic Tasks:** 903 controlled evaluation tasks across complexity levels
  - **Task Definition:** Dataset + metadata + natural language discovery goal
- **Discovery Workflow:**
  - Dataset exploration and understanding
  - Hypothesis generation
  - Statistical analysis and verification
  - Result interpretation and validation
- **Evaluation Framework:**
  - Facet-based assessment revealing different failure modes
  - Structured formalism enables systematic comparison
  - Controlled complexity variation for targeted evaluation

### Proof
- **Model Evaluation:** Several popular LLM-based reasoning frameworks tested
- **Performance Results:** Best system achieves only 25% success rate
- **Failure Analysis:** Systematic identification of different failure modes through facet-based evaluation
- **Validation:** Tasks manually derived from published papers ensure realistic challenge level

### Impact
- **Benchmark Contribution:** First comprehensive data-driven discovery evaluation framework
- **Research Direction:** Highlights substantial gap between current capabilities and autonomous discovery
- **Methodology Innovation:** Structured formalism enables systematic capability assessment
- **Community Resource:** Provides foundation for developing more capable discovery systems
- **Reality Check:** Demonstrates significant challenges in autonomous scientific discovery

## Key Takeaways
1. **Bit Flip:** From static data analysis → dynamic hypothesis discovery and verification
2. **Multi-Step Process:** Discovery requires orchestrating multiple reasoning and analysis steps
3. **Real-World Grounding:** Tasks derived from actual research workflows ensure realistic evaluation
4. **Systematic Gaps:** Even best systems struggle with comprehensive discovery tasks
5. **Faceted Evaluation:** Structured assessment reveals specific failure modes for targeted improvement
6. **Domain Diversity:** Cross-domain evaluation ensures generalization assessment
7. **Community Benchmark:** Provides shared evaluation framework for discovery system development