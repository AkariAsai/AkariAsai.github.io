---
layout: about
title: About
permalink: /
subtitle: Ph.D. student @ <a href='https://www.cs.washington.edu/'>Paul G. Allen School of Computer Science & Engineering, University of Washington</a><br>Visiting Student Researcher @ <a href='https://ai.meta.com/'>Meta AI</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>

news: true # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->

I am in the final year of my Ph.D. in NLP at Paul G. Allen School of Computer Science & Engineering, University of Washington. I am fortunate to be advised by [Prof. Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/index.html). I am also spending time at [Meta AI Research](https://ai.meta.com/research/) as a visiting student researcher, under the supervision of [Dr. Wen-tau Yih](https://scottyih.org/). Prior to joining UW, I obtained a B.E. in [Electrical Engineering and Computer Science](https://www.ee.t.u-tokyo.ac.jp/en/) from The University of Tokyo, Japan. 

My research focuses on natural language processing and machine learning, with a particular emphasis on large language models (LLMs). I investigate the core limitations of LLMs---such as hallucinations---that cannot be overcome by scaling alone. To address these challenges, I pioneered [**Retrieval-Augmented LMs**](https://acl2023-retrieval-lm.github.io/), a novel class of LLMs that integrate large-scale text data via retrieval during inference. More specifically,

- **Establishing the Necessity of Retrieval-Augmented LMs** -- I have systematically researched the failure modes of LLMs, and am among the first to develop retrieval-augmented approaches as a solution. My work has shown their effectiveness for (1) reducing hallucinations e.g.,  [Adaptive Retrieval-Augmented LM (ACL 2023 Oral, Best Video Award)](https://arxiv.org/abs/2212.10511), (2) achieving more compute-efficient scaling e.g., [MassiveDS (NeurIPS 2024)](https://huggingface.co/papers/2407.12854); (3) staying updated with real-time knowledge changes e.g., [Real-time QA (NeurIPS D&B 2023)](https://arxiv.org/abs/2207.13332). I've taught [the first tutorial of retrieval-augmented LMs](https://acl2023-retrieval-lm.github.io/) at ACL 2023.

- **Building the Foundations of Retrieval-Augmented LMs** -- I have established the foundational components of Retrieval-Augmented LMs, developing better architectures, training strategies, and inference techniques like [Self-RAG (ICLR Oral-Top 1%, 2024)](https://arxiv.org/abs/2310.11511), [Evidentiality-guided RAG (NAACL Oral, 2022)](https://arxiv.org/abs/2112.08688) and [FAVA (COLM 2024)](https://arxiv.org/abs/2401.06855). I’ve advanced retrieval systems to be more versatile, following diverse user instructions [(TART, Findings of ACL 2023)](https://arxiv.org/abs/2211.09260), more robust to complex queries [(Path Retriever, ICLR 2020)](https://openreview.net/forum?id=SJgVHkrYDH) [(LUKE, EMNLP 2020; 1.5 million downloads on HF)](https://arxiv.org/abs/2010.01057), and more efficient [(Binary Passage Retriever, ACL 2021)](https://arxiv.org/abs/2106.00882).


- **Making Real-world Impacts through Retrieval-Augmented LMs** -- I advance the frontiers of Retrieval-Augmented LMs by addressing critical real-world challenges, particularly in contexts where information is scarce or fragmented. My work focuses on: (1) Developing reliable LMs for expert domain tasks, such as scientific research [(Open Scholar, 2024)](https://allenai.org/blog/openscholar) or code generation ([CodeRAG-Bench, Findings of NAACL 2024](https://code-rag-bench.github.io/)), and (2) improving information access across world languages (e.g., [CORA, NeurIPS 2021](https://arxiv.org/abs/2107.11976); [XOR QA, NAACL 2021](https://arxiv.org/abs/2010.11856); [AfriQA, Findings of EMNLP, 2022](https://arxiv.org/abs/2305.06897)), to help linguistic minorities to access the information they need.


**Awards and Recognitions:** My work has received multiple paper awards at conferences like ACL and NeurIPS workshop, and has been featured in major media outlets such as [Forbes](https://www.forbes.com/councils/forbestechcouncil/2024/07/30/how-rag-powered-ai-applications-have-a-positive-impact-on-businesses/) and [MIT Technology Review](https://www.technologyreview.com/2018/02/05/145813/100000-happy-moments/). I'm honored to be named among the [Forbes 30 Under 30 Asia in Science ](https://www.forbes.com/30-under-30/2025/asia/healthcare-science), [MIT Technology Review Innovators Under 35 from Japan (2024)](https://www.technologyreview.jp/l/innovators_jp/348573/akari-asai/), [EECS Rising Stars (2022)](https://risingstars.utexas.edu/profiles/akari-asai), and the [IBM Global Ph.D. Fellows (2022-2023)](https://news.cs.washington.edu/2022/10/20/lost-in-translation-no-more-ibm-fellowship-winner-akari-asai-asks-and-answers-big-questions-in-nlp-to-expand-information-access-to-all/). My work is now integrated into major libraries like [Hugging Face](https://huggingface.co/docs/transformers/en/model_doc/luke), [LlamaIndex](https://docs.llamaindex.ai/en/stable/api_reference/packs/self_rag/) and [LangChain](https://blog.langchain.dev/agentic-rag-with-langgraph/), and used in multiple real-world systems, such as [COVID-19 Research Search](https://www.salesforce.com/news/stories/salesforce-research-develops-new-search-engine-to-support-the-fight-against-covid-19/). Most recently, we released [Ai2 OpenScholar Public Demo](https://openscholar.allen.ai/), assisting more than 30k scientists across scientific disciplines to synthesize scientific literature more effectively and efficiently. 

**Teaching, Mentoring and Services:** I am also passionate about teaching, mentoring and helping students to learn research, especially students from underrepresented groups.
I have been the Head TA for [CSE473: Intro to AI (undergrad)](https://courses.cs.washington.edu/courses/cse473/23au/) and [CSE599J: Data-centric ML (graduate)](https://koh.pw/cse599j/) at UW, and gave 10 invited lectures at multiple universities. I’ve been really fortunate to work with passionate and extremely talented undergraduate and graduate students. 
To reduce barriers to starting research or pursuing a Ph.D. in this area, I am hosting weekly office hours open to everyone (please sign up from [Calendly](https://calendly.com/akari-asai/office-hour)!), and was a mentor for [UW CSE Ph.D. Pre-Application Mentorship Service (PAMS)](https://www.cs.washington.edu/academics/phd/admissions/pams). I've served as an student area chair (NLP) for UW CSE Ph.D. admissions for two years and as a UW CSE DEI student representative, working to foster an inclusive academic environment. 