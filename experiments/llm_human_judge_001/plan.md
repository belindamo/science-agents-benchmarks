# Experiment Plan: LLM-Human Judge Correlation Analysis for Scientific Evaluation

## Experiment Idea
### Title
LLM-Human Judge Correlation Analysis for Scientific Evaluation

### Bit (Problem)
LLM judges can effectively substitute for human experts across all dimensions of scientific evaluation

### Flip (Solution)
LLM judges excel at certain structured aspects but require human collaboration for subjective scientific judgments

### Hypothesis
- H1: LLM judges will achieve >0.7 Pearson correlation with human experts on structured evaluation tasks
- H2: LLM judges will achieve <0.5 correlation on subjective evaluation tasks  
- H3: Ensemble LLM+human judge rankings will outperform either alone by >15%

## Evaluation Plan
### Metrics
- Primary metric: Pearson correlation coefficient between LLM and human expert ratings
- Secondary metrics: Intraclass correlation coefficient (ICC), bootstrapped confidence intervals, mean absolute error

### Baseline
Human expert panel ratings serving as ground truth across multiple evaluation dimensions

### Data Collection
- Dataset: 50 research papers from ML conferences (ICML, NeurIPS, ICLR)
- Human Expert Panel: 5 ML researchers (PhD-level) for ground truth ratings
- LLM Judges: GPT-4, Claude-3.5-Sonnet, Gemini-Pro
- Evaluation Protocol: PaperBench-inspired hierarchical rubrics with 5-point Likert scales

### Analysis Method
- Statistical correlation analysis using Pearson correlation
- ICC calculations for inter-rater reliability
- Bootstrapped confidence intervals for robustness
- Effect size calculations using Cohen's d

### Success Criteria
- H1 Success: r > 0.7 for structured dimensions (methodology, reproducibility)
- H2 Success: r < 0.5 for subjective dimensions (novelty, significance)
- H3 Success: Ensemble method shows >15% improvement in correlation over individual judges

## Implications
### If Successful
- Validates the hypothesis that LLMs excel at structured evaluation but struggle with subjective assessment
- Suggests optimal human-AI collaboration frameworks for scientific peer review
- Provides empirical evidence for task-specific AI deployment in research evaluation

### If Failed
- Would indicate either LLMs are better at subjective evaluation than expected, or structured evaluation is more complex than anticipated
- Could reveal limitations in current evaluation frameworks or the need for better LLM fine-tuning

### Future Work
- Develop hybrid evaluation systems that leverage both LLM and human strengths
- Investigate domain-specific evaluation performance across different scientific fields
- Design training protocols to improve LLM performance on subjective dimensions

## Related Works
### Nearest Neighbor Paper
PaperBench (Starace et al., 2025) - provides framework for automated research paper evaluation

### Key Differences
- Focus on correlation analysis between LLM and human judges rather than just performance metrics
- Explicit testing of structured vs subjective evaluation dimensions
- Investigation of ensemble methods for optimal human-AI collaboration

### Literature Gap
Limited empirical analysis of where LLMs excel vs struggle in scientific evaluation tasks

## Vectors (Risk Dimensions)
### Technical Risk
- LLM API reliability and consistency across evaluation sessions
- Prompt engineering challenges for consistent evaluation criteria

### Methodological Risk
- Selection bias in paper choice affecting generalizability
- Expert fatigue leading to inconsistent human ratings
- Evaluation rubric design influencing correlation results

### Resource Risk
- Cost of LLM API calls for comprehensive evaluation
- Availability and time commitment of human expert panel
- Access to sufficient high-quality research papers

### Priority
Rating: 8/10 - High priority due to relevance to current AI evaluation challenges and clear experimental design