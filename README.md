# NFR Classification Decision Framework

This repository contains the interactive decision framework developed for my thesis. The tool helps in selecting the most appropriate AI classification architecture based on various Non-Functional Requirements (NFRs) and project constraints.

## Overview

When building classification systems, choosing the right approach is just as important as the data itself. This framework allows users to input their specific project constraints to see which classification paradigm is recommended, viable, or eliminated.

The tool evaluates four main approaches:
* Rule-based (Keyword and regex matching)
* Classical ML (SVM, Random Forest)
* Deep Learning (Fine-tuned Transformers)
* LLM-based (Few-shot / zero-shot via large language models)

It filters these approaches based on real-world constraints like data sovereignty, certification criticality, data availability, taxonomy stability, interpretability, and latency.

## How to Run

This is a static web application built with HTML, Vue.js, and Tailwind CSS. It does not require any backend server or build process to run.

1. Clone or download this repository to your local machine.
2. Open the `index.html` file directly in any modern web browser.
3. Toggle the constraint buttons to see how different requirements affect the viability of each AI architecture.

## Repository Files

* `index.html`: The main interactive decision framework application.
* `rule_based_demo.html`: A secondary demonstration page for rule-based classification.
* `vercel.json`: Deployment configuration for hosting the project on Vercel.

## Deployment

The application is configured to be easily deployed on Vercel. Because it consists of static files, you can deploy it by simply linking this repository to a Vercel project.
