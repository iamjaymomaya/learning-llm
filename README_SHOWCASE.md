# LLM Engineering Portfolio Roadmap (Week 1 Day 1 -> Week 8 Day N)

This README is a clean, recruiter-friendly blueprint for structuring your GitHub repository as you complete the Udemy course:

**AI Engineer Core Track: LLM Engineering, RAG, QLoRA, Agents**  
https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models/

Use this as your portfolio operating system: each week and day has clear outputs, so anyone can instantly understand what you learned and built.

## 1) Portfolio Principles

1. One folder per week, one subfolder per day.
2. Each day has a mini README with problem, approach, and result.
3. Keep notebooks and production-style code both (learning + engineering).
4. Save demos/screenshots/audio in `artifacts/` so your work is visible without running code.
5. Add quick reflections: what worked, what failed, what you improved.

## 2) Recommended Root Structure

```text
llm-engineering-portfolio/
  README.md
  LICENSE
  .gitignore
  requirements.txt
  pyproject.toml
  .env.example

  docs/
    learning-journal.md
    architecture-notes.md
    model-comparison-matrix.md
    prompt-patterns.md
    cost-tracking.md

  shared/
    utils/
      io.py
      eval.py
      prompts.py
      logging.py
    datasets/
      README.md
    configs/
      models.yaml
      paths.yaml

  weeks/
    week-01-foundations-first-llm-product/
    week-02-multimodal-chatbot-and-agents/
    week-03-open-source-and-huggingface/
    week-04-llm-evaluation-and-codegen/
    week-05-rag-and-vector-embeddings/
    week-06-frontier-model-finetuning/
    week-07-open-source-qlora-finetuning/
    week-08-autonomous-multi-agent-capstone/

  projects/
    project-01-brochure-generator/
    project-02-airline-multimodal-assistant/
    project-03-meeting-minutes-from-audio/
    project-04-python-to-cpp-optimizer/
    project-05-rag-knowledge-worker/
    project-06-price-prediction-frontier/
    project-07-price-prediction-qlora/
    project-08-autonomous-deals-agent/

  experiments/
    ab-tests/
    model-benchmarks/

  artifacts/
    screenshots/
    demos/
    audio/
    reports/

  tests/
    test_prompts.py
    test_rag_pipeline.py
    test_agents.py

  .github/
    workflows/
      ci.yml
```

## 3) Day Template (Use For Every Day Folder)

Create each day as:

```text
day-XX-topic-name/
  README.md
  notes.md
  tasks.md
  lab.ipynb
  src/
    main.py
    pipeline.py
    prompts.py
  tests/
    test_main.py
  artifacts/
    demo.png
  reflection.md
```

### What each file should contain

- `README.md`: objective, dataset/tools, approach, key output, lessons.
- `notes.md`: concise lecture and concept notes.
- `tasks.md`: checklist of what you implemented.
- `lab.ipynb`: exploratory implementation used during learning.
- `src/`: cleaned implementation extracted from notebook.
- `tests/`: minimal correctness checks.
- `artifacts/`: screenshots, generated outputs, short clips.
- `reflection.md`: mistakes, fixes, next improvements.

## 4) Week-by-Week Topic Map (from course outline)

Note: Week 1 day topics are explicit on the course page. Weeks 2-8 are mapped to official weekly outcomes and projects; use Day N to match your actual lecture sequence.

### Week 1 - Foundations + First Product (Top Models)

```text
weeks/week-01-foundations-first-llm-product/
  day-01-local-llm-setup-and-first-api-call/
  day-02-llm-building-blocks-and-api-clients/
  day-03-frontier-vs-open-source-model-comparison/
  day-04-transformers-tokenization-context-and-cost/
  day-05-project-01-brochure-generator/
```

### Week 2 - Multi-Modal Chatbot, UI, Tools, Agents (Project 2)

```text
weeks/week-02-multimodal-chatbot-and-agents/
  day-01-frontier-api-integration-and-baseline-chat/
  day-02-gradio-ui-and-conversation-state/
  day-03-image-audio-and-multimodal-inputs/
  day-04-tool-calling-and-agentic-workflows/
  day-0N-project-02-airline-customer-support-agent/
```

### Week 3 - Open Source + HuggingFace (Project 3)

```text
weeks/week-03-open-source-and-huggingface/
  day-01-huggingface-pipelines-and-model-selection/
  day-02-open-source-use-cases-translation-summarization/
  day-03-audio-transcription-and-structured-extraction/
  day-04-meeting-minutes-and-action-items-pipeline/
  day-0N-project-03-meeting-minutes-from-audio/
```

### Week 4 - LLM Evaluation + Code Generation (Project 4)

```text
weeks/week-04-llm-evaluation-and-codegen/
  day-01-evaluation-framework-for-business-tasks/
  day-02-model-selection-benchmarking-and-scorecards/
  day-03-code-generation-and-translation-patterns/
  day-0N-project-04-python-to-cpp-optimizer/
```

### Week 5 - RAG + Vector Embeddings (Project 5)

```text
weeks/week-05-rag-and-vector-embeddings/
  day-01-embeddings-chunking-and-retrieval-basics/
  day-02-vector-databases-indexing-and-search/
  day-03-rag-pipeline-query-routing-and-grounding/
  day-04-evaluation-hallucination-control-and-citations/
  day-0N-project-05-rag-knowledge-worker/
```

### Week 6 - From Inference to Training (Project 6)

```text
weeks/week-06-frontier-model-finetuning/
  day-01-training-concepts-datasets-and-label-strategy/
  day-02-frontier-finetuning-workflow/
  day-03-experiment-tracking-and-hyperparameter-tuning/
  day-04-evaluation-vs-baseline-and-error-analysis/
  day-0N-project-06-price-prediction-frontier/
```

### Week 7 - Advanced Fine-Tuning with QLoRA (Project 7)

```text
weeks/week-07-open-source-qlora-finetuning/
  day-01-qlora-theory-and-memory-efficient-training/
  day-02-data-prep-for-open-source-finetuning/
  day-03-training-open-source-model-with-lora-adapters/
  day-04-compare-open-source-vs-frontier-performance/
  day-0N-project-07-price-prediction-qlora/
```

### Week 8 - Autonomous Multi-Agent System + Productionization (Project 8)

```text
weeks/week-08-autonomous-multi-agent-capstone/
  day-01-agent-roles-planning-and-tooling/
  day-02-multi-agent-collaboration-and-orchestration/
  day-03-evaluation-observability-and-guardrails/
  day-04-ui-polish-and-deployment-prep/
  day-0N-project-08-autonomous-deals-agent/
```

## 5) Project Folder Standard (for all 8 projects)

```text
project-XX-name/
  README.md
  app.py
  requirements.txt
  src/
    chains_or_agents.py
    prompts.py
    tools.py
    eval.py
  data/
    raw/
    processed/
  artifacts/
    demo.gif
    architecture.png
  tests/
    test_pipeline.py
  report.md
```

## 6) README Format for Each Week

Use this same structure inside each week and day README:

```md
# Week X Day Y - Topic

## Objective
What I am trying to build/learn.

## Concepts Covered
- Concept 1
- Concept 2

## Implementation
- Stack/tools
- Main design decisions

## Results
- Metrics/output
- Screenshot/demo link

## Challenges and Fixes
- Issue -> Fix -> Learning

## Next Step
What I will do in the next day.
```

## 7) Suggested Git Workflow

1. One branch per day or feature: `feat/week-03-day-02-hf-pipelines`.
2. One clean commit per logical step.
3. Commit message style:
   - `feat(w3d2): add HF translation and summarization pipeline`
   - `fix(w5d3): improve retrieval chunk overlap`
   - `docs(w8): add deployment architecture diagram`

## 8) Portfolio Quality Checklist

- Every day folder has `README.md` and `reflection.md`.
- Every project has a runnable entrypoint and one visual artifact.
- At least one benchmark table exists for model comparison.
- RAG project includes retrieval quality notes and hallucination controls.
- Fine-tuning projects include baseline vs tuned model comparison.
- Week 8 capstone includes architecture diagram + short demo.

## 9) Final Publish Structure (What recruiters should see quickly)

1. Root README with course summary and links to 8 projects.
2. A clear `projects/` folder with business-style problem statements.
3. `artifacts/demos/` with GIFs/screenshots for quick proof.
4. `docs/model-comparison-matrix.md` to show engineering judgment.
5. Clean commit history showing progressive learning.

---

If you follow this structure consistently, your repository will read like an AI engineering journey from fundamentals to production-grade agentic systems.