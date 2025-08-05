i want to make a set of benchmarks for scientific discovery.
kind of like HELM https://crfm.stanford.edu/helm/, but for science specific tasks

check out https://pub.sakana.ai/ai-scientist-v2/paper/paper.pdf 
we want to observe where it worked well, where it failed, and design benchmark collection for it

i was thinking paperbench's approach works quite well 

<more info>
# Sakana AI's research portfolio reveals nature-inspired breakthrough

Sakana AI has achieved a historic milestone with the AI Scientist project, creating the first fully AI-generated scientific paper to pass peer review at an academic conference. The Tokyo-based company, founded by former Google researchers **David Ha** and **Llion Jones** (co-author of the foundational Transformer paper), has established a distinctive research agenda focused on evolutionary computing and nature-inspired AI approaches rather than conventional scaling strategies.

The AI Scientist v2 paper, accepted at an ICLR 2025 workshop with scores of 6, 7, and 6, demonstrated that AI systems can autonomously conduct scientific research from ideation through peer review. This achievement builds on Sakana's broader research portfolio spanning evolutionary model merging, biologically-inspired neural architectures, and automated scientific discovery. However, independent evaluations reveal significant limitations, with critics comparing the system's output quality to "an unmotivated undergraduate student" and noting frequent hallucinations and methodological flaws. Despite generating complete papers for just $15 each, the system requires substantial human oversight and produces work suitable only for workshop-level venues rather than main conference tracks.

## The AI Scientist achieves historic first with significant caveats

The AI Scientist project represents both a technical milestone and a sobering reality check for automated research. The original system, released in August 2024, introduced a four-stage pipeline: idea generation using Semantic Scholar for novelty checking, experimental iteration with the Aider coding assistant, automated paper writing in LaTeX, and LLM-powered peer review. The system demonstrated capabilities across three machine learning domains—diffusion modeling, transformer-based language modeling, and grokking dynamics—producing papers like **"DualScale Diffusion: Adaptive Feature Balancing for Low-Dimensional Generative Models"** and **"Adaptive Learning Rates for Transformers via Q-Learning"**.

Version 2, released in April 2025, marked a fundamental architectural shift from template-based linear pipelines to template-free agentic tree search. The new system employs a Breadth-First Tree Search (BFTS) methodology guided by an experiment manager agent, enabling non-linear exploration of research hypotheses. Key innovations include integrated Vision-Language Model feedback for figure refinement, direct LLM-native code generation replacing external tools, and flexible cross-domain generalization. The accepted ICLR workshop paper, **"Compositional Regularization: Unexpected Obstacles in Enhancing Neural Network Generalization,"** scored above the acceptance threshold and ranked in approximately the top 45% of submissions.

However, independent evaluation by researchers from Trinity College Dublin and the National University of Singapore revealed sobering limitations. Their comprehensive study found that **42% of experiments failed due to coding errors**, generated manuscripts averaged only 5 citations (mostly outdated), and the system frequently hallucinated numerical results. The automated reviewer component rejected 9 out of 10 legitimate human papers, suggesting poor calibration. While cost-effective at $6-15 per paper, each required approximately 3.5 hours of human oversight to address structural errors, missing figures, and placeholder text.

## Sakana's research extends far beyond automated discovery

The company's publication record reveals a coherent research philosophy centered on nature-inspired intelligence and evolutionary approaches. Their **Nature Machine Intelligence paper** (January 2025) on "Evolutionary Optimization of Model Merging Recipes" demonstrates how evolution can discover non-intuitive ways to combine open-source models from different domains. This work enabled creation of specialized Japanese language models (EvoLLM-JP, EvoVLM-JP) by merging language capabilities with mathematical reasoning or vision understanding.

Other significant publications include **"Continuous Thought Machines"** (May 2025), introducing neural architectures with neuron-level temporal processing inspired by biological brain dynamics, and **"Transformer²: Self-adaptive LLMs"** (January 2025), presenting a framework for models that dynamically adjust weights using Singular Value Decomposition and reinforcement learning. The company has also developed culturally-focused AI systems like Evo-Ukiyoe for Japanese art generation and pioneered applications in digital humanities through Kuzushiji character recognition.

Research themes consistently emphasize alternatives to pure scaling approaches: evolutionary computing for model development, biologically-inspired architectures incorporating temporal dynamics, self-adaptive systems that evolve during deployment, and collective intelligence frameworks mimicking natural phenomena like fish schooling behavior. This differentiates Sakana from labs focused primarily on parameter scaling.

## World-class team brings complementary expertise to Tokyo

Sakana's research strength stems from its exceptional team composition. **David Ha**, CEO and co-founder, brings over 12,000 Google Scholar citations from work on hypernetworks, world models, and collective intelligence. His background spans Google Brain directorship and complex systems research. **Llion Jones**, CTO and co-founder, co-authored the seminal "Attention Is All You Need" paper with nearly 200,000 citations, making him one of the eight original Transformer authors who have all now departed Google.

The research team includes **Takuya Akiba**, creator of the Optuna hyperparameter optimization framework with over 4,000 citations; **Robert Tjarko Lange**, an evolutionary optimization specialist who developed the evosax and gymnax JAX libraries; and **Tarin Clanuwat**, whose groundbreaking work on Kuzushiji recognition opened historical Japanese texts to computational analysis. Additional researchers like **Yujin Tang** (neuroevolution expert) and **Qi Sun** (generative AI specialist) round out capabilities across robotics, multi-agent systems, and large-scale datasets.

Notable advisors and investors include **Jeff Dean** (Google Chief Scientist), **Clem Delangue** (Hugging Face CEO), and backing from Lux Capital, Khosla Ventures, and major Japanese corporations including NTT, KDDI, and Sony. The company has raised over $230 million and achieved a $1.5 billion valuation within two years of founding.

## Mixed reception reflects both promise and current limitations

Community response to the AI Scientist has been characterized by simultaneous excitement and skepticism. The GitHub repository garnered over 8,900 stars and 1,300 forks, while the original paper accumulated over 100 citations within months. Media coverage from TechCrunch, IEEE Spectrum, and Nature Index generally portrayed the work positively but highlighted important caveats.

Academic reception proved more critical. Researchers on Twitter/X and Reddit forums reported significant setup difficulties and questioned output quality. An independent evaluation described outputs as **"scientific slop"** with poor literature synthesis capabilities. Critics noted the system's heavy dependence on human-provided templates, minimal code modifications (only 8% character changes per iteration), and frequent factual errors. Peter Wildeford's assessment that "Sakana's AI scientist is not that much of a breakthrough" captured widespread sentiment among practicing researchers.

The milestone of achieving peer review acceptance must be contextualized: only 1 of 3 submitted papers passed review, the accepted paper was suitable only for workshop rather than main conference venues, and the authors themselves withdrew it post-acceptance for transparency. The system's co-author Cong Lu compared its capabilities to "an early Ph.D. student" with creative ideas but poor execution.

## Future directions balance ambition with pragmatic constraints

Sakana AI's AI Scientist project illuminates both the potential and current limitations of automated scientific discovery. While achieving the historic first of peer review acceptance, the system's significant quality issues, high failure rates, and need for human oversight demonstrate that genuine autonomous research remains distant. The $15 per-paper cost efficiency becomes less compelling when factoring in the 3.5 hours of human intervention required.

Nevertheless, Sakana's broader research agenda shows promise. Their nature-inspired approach to AI development, strong team composition, and successful work in evolutionary model merging and biologically-inspired architectures position them as innovators exploring alternatives to conventional scaling paradigms. The company's focus on Japanese AI leadership, commitment to open-source research, and backing from both Silicon Valley venture capital and Japanese corporations creates unique opportunities.

The AI Scientist serves as both achievement and cautionary tale—demonstrating that while AI can mimic the structure of scientific research, genuine scientific discovery requires capabilities beyond current systems. As automated research tools mature, Sakana's pioneering work will likely be remembered not for replacing human scientists but for catalyzing important conversations about AI's evolving role in accelerating human scientific endeavors.
</more info>