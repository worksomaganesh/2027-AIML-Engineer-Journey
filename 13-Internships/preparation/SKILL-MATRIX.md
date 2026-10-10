# Internship Skill Matrix — 202X

**Mission:** secure one genuine first-year internship by **31 March 2027**.  
**Study capacity:** about 2 hours Monday–Friday and 5–6 hours each Saturday and Sunday (roughly 20–22 hours/week).  
**Preparation begins:** 1 November 2026, after first-semester mid-examinations.

This is a priority map, not a claim that these skills are already learned. Hours are estimates for a beginner who codes while learning (not just watches videos); expect roughly ±30% variation. The goal is practical competence that can be demonstrated, not mastery of every topic.

## The four categories

- **Category 1 — Easy and important:** learn first; these unlock most entry-level technical work.
- **Category 2 — Easy, lower priority but useful:** learn only the practical slice needed for projects and applications.
- **Category 3 — Hard and important:** learn enough to explain, implement, test and demonstrate.
- **Category 4 — Hard, lower priority for this deadline:** defer unless a real target job description explicitly requires it.

“Lower priority” does not mean useless. It means it should not displace core skills or project completion before 7 February.

## Estimated learning budget

| Category | Skills and estimated focused hours | Budget |
|---|---|---:|
| 1. Easy + important | Python 18h; Git/GitHub 3h; Linux/terminal 3h; SQL core 9h; NumPy/pandas starter skills 9h; errors/files/debugging 5h; HTTP/JSON basics 3h | **50h** |
| 2. Easy + useful, lower priority | Excel/Sheets 2h; charts 3h; Postman 2h; Streamlit 4h; minimal HTML/CSS 3h; resume/LinkedIn/communication 5h; documentation habits 2h | **21h** |
| 3. Hard + important | DSA patterns 20h; statistics/probability 7h; data cleaning/EDA 5h; scikit-learn and evaluation 15h; FastAPI/Pydantic/REST/SQL database integration 10h; pytest and edge cases 5h; LLM API/prompting/structured output 7h; basic embeddings/RAG 6h; deployment/config/secrets 3h | **78h** |
| **Core skill budget** | Estimates overlap slightly because concepts are reused across projects. | **149h** |

Allow another **40–50 hours for the four repository projects** and around **15–20 hours for interview practice and application admin**. Applications begin before the syllabus is finished. With college work and setbacks, the realistic portfolio-ready target is **1–7 February 2027**; **18–24 January is a stretch checkpoint**, not a promise.

## Category 1 — Easy and important

### 1. Python foundations — 18 hours

**Must learn**
- Variables, primitive types, type conversion, operators and comparisons.
- Strings, lists, tuples, sets and dictionaries; indexing, slicing and common methods.
- if/elif/else, for/while loops, break/continue, nested loops where needed.
- Functions, arguments, return values, scope and basic reusable design.
- Imports, standard library, virtual environments, pip and requirements files.
- Read/write text, CSV and JSON files; pathlib; exceptions and useful error messages.
- Basic classes/objects, attributes, methods and when a simple function is better.
- Debug with print/debugger, tracebacks and minimal reproducible examples.

**Practise by writing:** a log parser, a CSV summarizer, a JSON reader, a small command-line utility, and 20–30 short exercises.

**Defer:** metaclasses, advanced decorators, complex async programming, obscure language internals and elaborate design patterns.

### 2. Git and GitHub — 3 hours

**Must learn:** init/clone, status, add, commit, push, pull, branches at a basic level, .gitignore, README, meaningful commits, repository navigation, issues and pull-request vocabulary.

**Defer:** advanced rebasing, bisect, submodules and complicated release automation.

### 3. Linux and terminal — 3 hours

**Must learn:** pwd, ls, cd, mkdir, cp, mv, rm carefully, cat, less, grep, find, pipes, redirection, process exit status, environment variables and running Python from a terminal.

**Defer:** kernel internals, shell scripting at scale and system administration.

### 4. SQL core — 9 hours

**Must learn:** SELECT, WHERE, ORDER BY, LIMIT, NULL, DISTINCT, CASE, aggregates, GROUP BY, HAVING, INNER/LEFT JOIN, simple subqueries, basic CTEs, primary/foreign keys and reading a simple schema.

**Practise:** write 25–40 queries on a small business dataset.

**Defer:** deep query-plan tuning, stored-procedure programming, advanced recursive CTEs and vendor-specific features. Learn window functions if time remains or a target role asks for them.

### 5. NumPy and pandas starter skills — 9 hours

**Must learn:** arrays and shapes; Series/DataFrame; read CSV; inspect dtypes and missing values; select/filter rows; sort; groupby/aggregation; merge/join; create columns; duplicates; basic datetime parsing; export CSV.

**Defer:** advanced broadcasting tricks, complex MultiIndex operations, performance micro-optimisation and distributed dataframe tools.

### 6. File handling, exceptions and debugging — 5 hours

**Must learn:** pathlib, context managers, CSV/JSON, try/except, specific exceptions, logging basics, input validation and explaining a traceback.

**Defer:** building a logging framework or custom exception hierarchy for its own sake.

### 7. HTTP and JSON — 3 hours

**Must learn:** request/response, URL, method, status codes, headers, JSON request/response bodies, GET/POST, 2xx/4xx/5xx, and why API keys must not be placed in source code.

**Defer:** deep network protocol internals and advanced OAuth flows.

## Category 2 — Easy, useful, but lower priority

### 1. Excel or Google Sheets — 2 hours
**Must learn:** sort/filter, basic formulas, SUM/AVERAGE/COUNTIF, simple pivot table, clean column names and CSV export.  
**Defer:** macros, VBA and complex financial modelling.

### 2. Matplotlib and clear charts — 3 hours
**Must learn:** bar, line, histogram and scatter plots; labels, title, legend; select chart type to match question.  
**Defer:** animation, elaborate styling and publication-grade chart design.

### 3. Postman — 2 hours
**Must learn:** send GET/POST requests, JSON body, headers, view status code, save a small collection.  
**Defer:** complex enterprise collections and advanced automation.

### 4. Streamlit — 4 hours
**Must learn:** simple inputs, buttons, tables, charts, session basics and turning a Python script into a usable demo.  
**Defer:** advanced custom components and production-grade frontend work.

### 5. Minimal HTML/CSS — 3 hours
**Must learn:** headings, links, forms, labels, basic layout and responsive-awareness only if a project needs a web page.  
**Defer:** React, complex CSS frameworks and animation.

### 6. Resume, LinkedIn and communication — 5 hours initially, then ongoing
**Must learn:** one-page student resume, accurate skills, project bullets describing action and evidence, concise outreach, explaining a project in 60–90 seconds, reading a job description for eligibility and keywords.  
**Never do:** claim skills not demonstrated, invent metrics, or list unfinished projects as completed.

### 7. Documentation — 2 hours setup, then ongoing
Every project README should state problem, features, setup, sample input/output, tests, limitations and what you personally built. Screenshots or a demo link help but do not replace runnable instructions.

## Category 3 — Hard and important

### 1. DSA patterns — 20 hours for the first pass

**Must learn:** time/space complexity; arrays and strings; hash maps/sets; sorting; binary search; two pointers; sliding window; stacks/queues; linked-list concepts; recursion basics; tree traversal and BFS/DFS concepts.

**Target:** around 25–35 carefully understood easy/selected-medium problems, with explanations and tests. Practise a little each week.

**Defer until after the deadline:** hard dynamic programming, advanced graph algorithms, competitive-programming tricks and grinding hundreds of copied solutions. If a role has a strict coding screen, increase DSA time and reduce optional GenAI scope.

### 2. Statistics and probability — 7 hours

**Must learn:** mean/median/mode, variance and standard deviation, percentiles, distributions at an intuitive level, conditional probability, sampling, correlation vs causation, train/test split intuition and data leakage.

**Defer:** proof-heavy probability, advanced inference and measure theory.

### 3. Data cleaning and EDA — 5 hours

**Must learn:** data dictionary, missing values, duplicates, invalid ranges, outliers, class imbalance awareness, distributions, feature relationships, leakage checks and writing 3–5 evidence-backed findings.

**Defer:** advanced causal inference and large-scale data engineering.

### 4. Machine learning with scikit-learn — 15 hours

**Must learn:** supervised vs unsupervised learning; baseline model; regression vs classification; train/validation/test; preprocessing; pipelines at a basic level; linear/logistic regression; decision tree and random forest; fit/predict; cross-validation concept; reproducible random state; compare models fairly.

**Evaluation must include:** MAE/RMSE for regression as appropriate; precision, recall, F1, confusion matrix and accuracy limitations for classification; model errors and dataset limitations.

**Defer:** deriving every algorithm from scratch, advanced boosting, hyperparameter-search grids at scale, deep learning and training large models.

### 5. FastAPI, Pydantic, REST and database integration — 10 hours

**Must learn:** simple GET/POST endpoints, request validation, response models, status codes, CRUD concepts, connect to SQLite or PostgreSQL, basic SQL parameterisation, environment config and useful error responses.

**Defer:** microservices, queues, complex authentication systems and high-scale architecture. For a demo, keep scope small and do not store real users' sensitive information.

### 6. pytest and edge cases — 5 hours

**Must learn:** assertions, test functions, fixtures at a basic level, test happy path plus invalid input/empty file/missing field, regression tests for bugs, API endpoint test basics.

**Defer:** mutation testing, complex mocking architectures and a perfect arbitrary coverage percentage.

### 7. LLM API, prompting and structured output — 7 hours

**Must learn:** call one hosted LLM API; read provider documentation; keep keys in environment variables; write prompts with clear task/context/constraints; handle timeouts and API errors; request and validate JSON/schema-shaped output; distinguish model-generated claims from extracted evidence; track token/cost limits.

**Defer:** training an LLM, fine-tuning, multi-agent orchestration and switching across many frameworks.

### 8. Embeddings, retrieval and basic RAG — 6 hours

**Must learn:** what an embedding represents; chunk documents; embed and retrieve relevant chunks; top-k similarity search; show source snippets; test a few questions and unanswerable questions; understand that retrieval does not guarantee truth.

**Defer:** building a vector database from scratch, complex reranking, multimodal RAG and production-scale evaluation infrastructure. A simple local implementation is enough for this deadline.

### 9. Deployment, configuration and secrets — 3 hours

**Must learn:** environment variables, .env excluded by .gitignore, dependency list, startup commands, basic deployment or reproducible local demo, log errors and state limitations. Rotate any secret accidentally committed; deleting it from the latest file is not always sufficient.

**Defer:** Kubernetes, complex cloud architecture and multi-region deployment.

## Category 4 — Hard and lower priority for this deadline

These can be valuable later but are not prerequisites for the initial internship search unless a specific job description demands them.

| Topic | What to do before March | Defer |
|---|---|---|
| Deep learning / PyTorch / TensorFlow | Understand what they are; learn only if the target ML role requires them | Large model training, custom architectures, advanced GPU workflows |
| Transformer internals and LLM fine-tuning | High-level awareness | Implement transformer from scratch, fine-tuning large models |
| CUDA / GPU kernels | No required work for general Python/data/AI-app roles | CUDA C++, kernel profiling, GPU architecture deep dives |
| Advanced DSA | Know when to revisit | Hard DP, advanced graph theory, competitive programming |
| Docker / Kubernetes / DevOps | Docker basics only if deployment requires it | Kubernetes clusters, CI/CD platform engineering |
| Cloud certifications | Use a simple free/low-cost deployment if helpful | Collect certifications without project evidence |
| React / full-stack frontend | Minimal HTML/CSS or Streamlit demo | Building a full frontend framework from scratch |
| System design / distributed systems | HTTP, API and database basics | Senior-level architecture and distributed systems deep dives |
| Advanced SQL / big data | Joins, grouping and basic schema skills | Spark clusters, Kafka, database query-plan tuning |

## What does “ready” mean?

By 7 February, aim to demonstrate:
- [ ] Write basic-to-intermediate Python without copying every line.
- [ ] Use Git/GitHub and explain a clean commit history.
- [ ] Query and join tables in SQL.
- [ ] Clean and analyse a dataset with pandas; explain useful charts/findings.
- [ ] Train and fairly evaluate a simple ML model.
- [ ] Build and test a small API or usable application.
- [ ] Explain one LLM feature and test its failure cases if targeting AI-app roles.
- [ ] Present at least **three finished, documented projects** (the fourth can be smaller).
- [ ] Explain design choices, limitations and what you personally wrote.
- [ ] Apply based on actual eligibility, not just company fame.

**Time rule:** each hour of video should be accompanied by coding, testing or explaining. If behind schedule, cut Category 4 first, then reduce RAG/visual polish; do not cut Python practice, core project completion, honest documentation or applications.
