# Knowledge sharing - Declarative Data Pipelines

## Table of Content (ToC)

* [Knowledge sharing \- Declarative Data Pipelines](#knowledge-sharing---declarative-data-pipelines)
  * [Table of Content (ToC)](#table-of-content-toc)
  * [Overview](#overview)
  * [References](#references)
    * [Data Engineering helpers](#data-engineering-helpers)
    * [AI helpers skill sets](#ai-helpers-skill-sets)
  * [Articles and projects of interest](#articles-and-projects-of-interest)
    * [Spec\-driven development (SDD)](#spec-driven-development-sdd)
    * [Databricks declarative development](#databricks-declarative-development)
    * [Lakehouse Plumber](#lakehouse-plumber)
    * [Metadata\-Driven Lakehouse Ingestion](#metadata-driven-lakehouse-ingestion)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Overview

[This project](https://github.com/data-engineering-helpers/declarative-data-pipelines)
aims at collecting and sharing reference material about declarative data
pipelines, that is, what they are, how to design and to build them.

That goes without saying that AI agents/assistants will be used wherever
relevant. For instance, to begin with, a starting point/cornerstone is the
[Databricks AI Dev Kit](https://github.com/databricks-solutions/ai-dev-kit)
and related material:

* [Spark Declarative Pipelines (SDP)](https://spark.apache.org/docs/latest/declarative-pipelines-programming-guide.html)
  and
  [Databricks Lakeflow Declarative Pipelines (LDP)](https://docs.databricks.com/aws/en/ldp/)
* [Databricks Asset Bundles (DAB)](https://docs.databricks.com/aws/en/dev-tools/bundles/)

Even though the members of the GitHub organization may be employed by
some companies, they speak on their personal behalf and do not represent
these companies.

## References

### Data Engineering helpers

* [Data Engineering Helpers - Knowledge Sharing - Cheat sheet - Databricks AI Dev Kit](https://github.com/data-engineering-helpers/ks-cheat-sheets/tree/main/ai/databricks-ai-dev-kit)
* [Data Engineering Helpers - Knowledge Sharing - AI Skills](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/ai/rules-skills/)
* [Data Engineering Helpers - Knowledge Sharing - JavaScript (JS) world](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/programming/js-world/)
* [Data Engineering Helpers - Knowledge Sharing - Java](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/programming/java-world/)
* [Data Engineering Helpers - Knowledge Sharing - Python](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/programming/python/)
* [Data Engineering Helpers - Knowledge Sharing - Spark](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/data-processing/spark/)
  * [Data Engineering Helpers - Knowledge Sharing - Spark Declarative pipelines (SDP)](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/data-processing/spark/declarative-pipelines/)
  * [Data Engineering Helpers - Knowledge Sharing - Spark Connect](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/data-processing/spark/spark-connect/)
  * [Data Engineering Helpers - Knowledge Sharing - Delta Lake](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/data-processing/spark/delta/)
  * [Data Engineering Helpers - Knowledge Sharing - Unity Catalog (UC)](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/data-catalogs/unity-catalog/)
* [Data Engineering Helpers - Knowledge Sharing - PostgreSQL](https://github.com/data-engineering-helpers/ks-cheat-sheets/blob/main/db/postgresql/)
* [Data Engineering Helpers - Knowledge Sharing - Modern Data Stack (MDS) in a box](https://github.com/data-engineering-helpers/mds-in-a-box)

### AI helpers skill sets

* [AI Helpers - Knowledge Sharing - AI skills curated](https://github.com/ai-helpers/ai-skills-curated)
* [AI Helpers - Knowledge Sharing - AI skills curated - Overview notebook](https://github.com/ai-helpers/ai-skills-curated/blob/main/notebooks/000%20-%20KS%20-%20Curated%20AI%20Skills%20-%20Overview.ipynb)

## Articles and projects of interest

### Spec-driven development (SDD)

* [GitHub - Spec-kit](https://github.com/github/spec-kit)
  * [GitHub - Spec-kit - Spec-driven development (SDD)](https://github.com/github/spec-kit/blob/main/spec-driven.md)
* [Martin Fowler's blog](https://martinfowler.com/)
  [Understanding Spec-Driven-Development: Kiro, spec-kit, and Tessl](https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html),
  by [Birgitta Böckeler](https://birgitta.info/), Oct. 2025

### Databricks declarative development

* [GitHub - Databricks Solutions - AI Dev Kit](https://github.com/databricks-solutions/ai-dev-kit)
* [Data Engineering Helpers - Knowledge Sharing - Cheat sheet - Databricks AI Dev Kit](https://github.com/data-engineering-helpers/ks-cheat-sheets/tree/main/ai/databricks-ai-dev-kit)
* [Spark Declarative Pipelines (SDP)](https://spark.apache.org/docs/latest/declarative-pipelines-programming-guide.html)
  * [Databricks Lakeflow Declarative Pipelines (LDP)](https://docs.databricks.com/aws/en/ldp/)
* [Databricks Asset Bundles (DAB)](https://docs.databricks.com/aws/en/dev-tools/bundles/)

### Deploy ETLs using Lakeflow Declarative Pipelines

* Title: Deploy streaming incremental and batch processing ETLs using Lakeflow Declarative Pipelines
  in Databricks Lakehouse Medallion Architecture with agentic AI support
* Date: Apr. 2026
* Author: Mikołaj Sędek
  ([Mikołaj Sędek on LinkedIn](https://www.linkedin.com/in/mikolajsedek/),
  [Mikołaj Sędek on Medium](https://medium.com/@mikoajsdek))
* [LinkedIn post](https://www.linkedin.com/posts/mikolajsedek_deploy-streaming-incremental-and-batch-processing-activity-7449383500136271873-OfrG/)
* [GitHub - Lakeflow Declarative Pipelines in Databrick Free Edition](https://github.com/MikolajSedek/lakeflow_declarative_pipelines_demo)

### Lakehouse Plumber

* Overview:

> The Metadata Driven framework for Databricks Lakeflow Declarative Pipelines
> (LDP) (formerly Delta Live Tables (DLT)). Metadata framework that generates
> production ready Pyspark code for Lakeflow Declarative Pipelines

* Authors/main contributors:
  * Mehdi Modarressi
  ([Mehdi Modarressi on LinkedIn](https://www.linkedin.com/in/modarressi/),
  [Mehdi Modarressi on GitHub](https://github.com/Mmodarre))
  * David O'Keefe
  ([David O'Keefe on LinkedIn](https://www.linkedin.com/in/dgokeeffe/),
  [David O'Keefe on GitHub](https://github.com/dgokeeffe),
  [David O'Keefe on Medium](https://medium.com/@davidok7))
* [GitHub - Lakehouse Plumber](https://github.com/Mmodarre/Lakehouse_Plumber)

### Metadata-Driven Lakehouse Ingestion

* Author/main contributor: Yasar Kocyigit
* LinkedIn posts:
  * [Linkedin post - Main features of Metadata-Driven Lakehouse Ingestion](https://www.linkedin.com/posts/yasarkocyigit_databricks-aidevkit-dataengineering-share-7433025769511047168-RoD2/),
  Feb. 2026
  * [LinkedIn post - Introduction to Metadata-Driven Lakehouse Ingestion](https://www.linkedin.com/posts/yasarkocyigit_databricks-lakehouse-dataengineering-activity-7432386473104080897-S-nA/),
  Feb. 2026
* [GitHub - Metadata-Driven Lakehouse Ingestion](https://github.com/yasarkocyigit/daq-databricks-dab)
* Overview:

> In my initial experiments to democratize onboarding in metadata-driven
> development (MDD) architectures, the process has been much easier with
> Databricks AI Dev Kit.
>
> I first built the infra foundation with DAB + MDD, then integrated AI Dev Kit
> and tested it at Databricks app level.
>
> Technically, what we added:
>
> * Chat-based onboarding entrypoint
> * AI Agent runtime for intent-driven orchestration
> * MCP layer for Databricks tool execution
> * Lakebase for conversation and project-state persistence
> * Git-based metadata flow (YAML + DAB)
> * CI/CD gates for validation and controlled deployment
>
> Impact so far:
>
> * Faster source/table onboarding
> * More consistent metadata-driven pipelines
> * Clear path from request -> config -> validation -> deployment
>
> Also, development can be managed via CLI + Claude
> I tested Codex and Gemini Pro 3.1 as well; for this workflow Claude 4.6
> performed best in my experience.
