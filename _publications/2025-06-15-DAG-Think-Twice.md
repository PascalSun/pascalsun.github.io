---
title: "DAG-Think-Twice: Causal Structure Guided Elicitation of Causal Reasoning in LLMs"
collection: publications
category: conferences
permalink: /publication/2025-06-15-DAG-Think-Twice
excerpt: 'Reasoning based way to do the finetuning'
date: 2025-06-15
venue: 'Pacific-Asia Conference on Knowledge Discovery and Data Mining'
slidesurl: 'https://link.springer.com/content/pdf/10.1007/978-981-96-8298-0.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-96-8298-0_33'
citation: 'Deng, Z., Sun, Q., Li, J., Liu, W. (2025). DAG-Think-Twice: Causal Structure Guided Elicitation of Causal Reasoning in LLMs. In: Wu, X., et al. Data Science: Foundations and Applications. PAKDD 2025. Lecture Notes in Computer Science(), vol 15876. Springer, Singapore. https://doi.org/10.1007/978-981-96-8298-0_33'
---

With the advent of Large Language Models (LLMs), assessing their causal reasoning capabilities has attracted a rapid growth in research efforts. Much of the existing work, however, mirrors the evaluation of commonsense reasoning, which is a task with overly open-ended questions and lacks distinction from information retrieval. Determining whether LLMs inherently possess causal reasoning capabilities or merely reproduce patterns from training data is the key research question this research is focusing on. First, to produce suitable benchmark datasets, we leverage extensive prior work in causal inference through Directed Acyclic Graphs (DAGs) and develop a Causal Structure-Guided Causal Reasoning Dataset Generation Framework. This framework facilitates the generation of causal reasoning datasets from any existing causal graphs represented as DAGs. Second, a DAG-Think-Twice structured prompting technique is proposed, introducing two structured tags (<thinking> and <reflection>) in the prompts with explicit guidance on the roles of concepts and events played in a causal reasoning task (i.e. confounders, mediators, colliders). This has achieved a remarkable improvement of 40% to 90% in GPT-4o and Gemma2-9B in accuracy. Testing on the existing dataset CLADDER also achieved a marked 30% improvement over the SOTA method CAUSALCOT. The dataset is available at https://github.com/22856226/Research.