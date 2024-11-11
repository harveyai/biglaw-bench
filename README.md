# BigLaw Bench
A new standard for evaluating AI on legal & professional tasks.

## Overview
BigLaw Bench is a comprehensive framework for evaluating the performance of large language models (LLMs) on complex, real-world legal tasks. Developed by Harvey's legal research team, BigLaw Bench aims to supplement existing benchmarks by focusing on tasks that mirror actual billable work performed by lawyers, providing a more accurate measure of an AI model's utility in professional legal settings.

## Benchmarks

### 1. BigLaw Bench — Core
BigLaw Bench Core is a set of core tasks for benchmarking baseline legal problem-solving. Core tasks are organized into two primary categories, each encompassing several specific sub-task types:

#### Transactional Task Categories
- Corporate Strategy & Advising
- Drafting
- Legal Research
- Due Diligence
- Risk Assessment & Compliance
- Negotiation Strategy
- Deal Management
- Transaction Structuring
- Regulatory & Advising

#### Litigation Task Categories
- Analysis of Litigation Filings
- Case Management
- Drafting
- Case Law Research
- Transcript Analysis
- Document Review and Analysis
- Trial Preparations & Oral Argument

### 2. BigLaw Bench — Workflows
BigLaw Bench Workflows represent a set of composite legal tasks that are used to evaluate agentic systems. We currently provide benchmarks for:

- **SPA Deal Points:** Evaluates the ability of LLM agents to extract a variety of standard deal points from a dataset of Share Purchase Agreements (SPAs). 

### 3. BigLaw Bench — Retrieval
BigLaw Bench Retrieval is a set of datasets and tasks for benchmarking the quality of retrieval systems. We currently provide benchmarks for:

- **Contracts:** Complex documents (e.g., hundreds of pages and potentially hundreds of thousands of tokens of text) with cross-references and defined terms which must be tracked to effectively contextualize relevant text. We currently support two types of contracts -- Merger Agreements and SPAs. 

- **Discovery Emails:** Relatively short documents that come in high-volume and have complex relationships (e.g., email threads) and rich metadata (sender, recipient, attachments) essential to identifying relevant messages.

## Evaluation Methodology
Each task in BigLaw Bench is assessed using custom-designed rubrics that measure:
- **Answer Quality**: Evaluates the completeness, accuracy, and appropriateness of the model's response based on specific criteria essential for effective task completion.
- **Source Reliability**: Assesses the model's ability to provide verifiable and correctly cited sources for its assertions, enhancing trust and facilitating validation.

Scores are calculated by combining positive points for meeting task requirements and negative points for errors or missteps (e.g. hallucinations). The final answer score represents: *What % of a lawyer-quality work product does the model complete for the user?*

## Data Samples
Sample tasks and grading rubrics can be found at the links below.

1. BLB-core: [here](blb-core)
2. BLB-workflows-spa: [here](blb-workflows/spa)
3. BLB-retrieval: [here](blb-workflows/retrieval)

For access to the full dataset and additional resources, please contact Harvey directly.

## Credits
[Julio Pereyra](https://www.linkedin.com/in/julio-pereyra-411738147), [Elizabeth Lebens](https://www.linkedin.com/in/beth-lebens-777847263), [Matthew Guillod](https://www.linkedin.com/in/matthew-guillod-284671116), [Laura Toulme](https://www.linkedin.com/in/laura-toulme-a6b66182), [Cameron MacGregor](https://www.linkedin.com/in/cameron-macgregor-396580164), [David Murdter](https://www.linkedin.com/in/davidmurdter), [Karl de la Roche](https://www.linkedin.com/in/karldelaroche), [Emilie McConnachie](https://www.linkedin.com/in/emilie-mcconnachie), [Jeremy Pushkin](https://www.linkedin.com/in/jeremypushkin), [Rina Kim](https://www.linkedin.com/in/rinakime), [Aaron Chan](https://www.linkedin.com/in/aaron-y-chan), [Jenny Pan](https://www.linkedin.com/in/jennyypan), [Boling Yang](https://www.linkedin.com/in/boling-yang-104534123), [Nan Wu](https://www.linkedin.com/in/nan-wu-41895bb7), [Niko Grupen](https://www.linkedin.com/in/nikogrupen), [Lauren Oh](https://www.linkedin.com/in/lauren-dayoun-oh), [Aatish Nayak](https://www.linkedin.com/in/aatishn), [Gabriel Pereyra](https://www.linkedin.com/in/gabepereyra)
