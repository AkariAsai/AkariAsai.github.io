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

I am currently in my fnial year of pursuing a Ph.D. in NLP at Paul G. Allen School of Computer Science & Engineering, University of Washington. I am fortunate to be advised by [Prof. Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/index.html). I am also spending some time at [Meta AI Research](https://ai.meta.com/research/) as a visiting student researcher, under the supervision of [Dr. Wen-tau Yih](https://scottyih.org/). Prior to joining UW, I obtained a B.E. in [Electrical Engineering and Computer Science](https://www.ee.t.u-tokyo.ac.jp/en/) from The University of Tokyo, Japan.

**I am on the job market this year! Please feel free to reach out me via email if you would like to share opportunities.**

My primary research interests are centered around natural language processing and machine learning.
While large language models (LLMs) are powerful, they also come with significant limitations, such as hallucinations, which can pose serious risks when applied to real-world applications, especially in safety-critical domains like medicine and science.
My Ph.D. research focuses on [**Retrieval-Augmented Language Models**](https://acl2023-retrieval-lm.github.io/), which address many of these limitations by dynamically retrieving and incorporating external knowledge at inference time. More specifically,

- **Identify key limitations of scaling LLMs and effectiveness of retrieval-augmented LMs** -- I have been extensively studying the failure modes of LLMs and was among the first to develop retrieval-augmented LMs as a solution. For example, [Adaptive Retrieval-augmented LM (ACL 2023 Oral, Best Video Award)](https://arxiv.org/abs/2212.10511) demonstrate that hallucinations often occur in long-tail knowledge, and scaling LLMs alone does not resolve this issue, while retrieval-augmented LMs can effectively mitigate it. We also show that retrieval-augmented LMs can address challenges like obsolete parametric knowledge in [Real-time QA (NeurIPS D & B 2023)](https://arxiv.org/abs/2207.13332), and enable compute-optimal scaling (i.e., achieving higher performance with the same FLOPs) in [MassiveDS, NeurIPS 2024](https://huggingface.co/papers/2407.12854).
I've co-taught [the first tutorial of retrieval-augmented LMs](https://acl2023-retrieval-lm.github.io/). See our latest position paper, [Reliable, Adaptive and Attributable LMs with Retrieval (Asai et al., 2024)](assets/pdf/ralm_position.pdf) on why the community needs to shift towards such augmented LMs, rather than merely scaling up parameters.


- **Develop Foundaitons of modern retrieval-augmented LMs** -- Unlike earlier work that focused on specific tasks like QA, modern retrieval-augmented LMs are now employed in much more diverse and complex setups. I have been working to establish the foundational components of retrieval-augmented LMs that can effectively handle these advanced scenarios. This includes developing better architectures, training strategies, and inference-time techniques, such as [Self-RAG (ICLR Oral-Top 1%, 2024)](https://arxiv.org/abs/2310.11511), [Evidentiality-guided RAG (NAACL Oral, 2022)](https://arxiv.org/abs/2112.08688) and [FAVA (COLM 2024)](https://arxiv.org/abs/2401.06855). I've also focused on advancing retrieval systems that are (a) more versatile like our [TART (Findings of ACL 2023)](https://arxiv.org/abs/2211.09260), the first work to introduce retrieval with instructions; (b) more robust to complex queries, as demonstrated by [Path Retriever (ICLR 2020)](https://openreview.net/forum?id=SJgVHkrYDH) and [LUKE (EMNLP 2020)](https://arxiv.org/abs/2010.01057), and (c) more efficient such as the [Binary Passage Retriever (ACL 2021)](https://arxiv.org/abs/2106.00882). These methods have been integrated into widely used libraries, including [huggingface transformers](https://huggingface.co/docs/transformers/en/model_doc/luke), [LlamaIndex](https://docs.llamaindex.ai/en/stable/api_reference/packs/self_rag/) and [LangChain](https://blog.langchain.dev/agentic-rag-with-langgraph/), and used in multiple real-world systems, such as [COVID-19 Research Search](https://www.salesforce.com/news/stories/salesforce-research-develops-new-search-engine-to-support-the-fight-against-covid-19/)


- **Translate state-of-the-art retrieval-augmented LMs methodologies into real-world applications** -- I also push the boundaries of retrieval-augmented LMs by exploring their effectiveness in addressing real-world challenges, such as inequality in information access across languages and the unreliability of LLMs in expert domains. I developed the first end-to-end multilingual retrieval-augmented LM, [CORA (NeurIPS 2021)](https://arxiv.org/abs/2107.11976), and created multilingual open-retrieval datasets, including [XOR QA (NAACL 2021)](https://arxiv.org/abs/2010.11856) and [AfriQA (Findings of EMNLP)](https://arxiv.org/abs/2305.06897), which cover many underrepresented languages, such as African languages. I was the lead organizer of [Workshop on Multilingual Information Access](https://mia-workshop.github.io/) at NAACL 2022 and hosted the first cross-lingual retrieval and open-domain QA shared task. Recently, I've been working on retrieval-augmented LMs for expert domains, such as code generation with [CodeRAG-Bench (Wang*,Asai* et al., 2024)](https://code-rag-bench.github.io/) and science (stay tuned for our upcoming release!).

I am also passionate about teaching, mentoring and helping students to learn research, especially students from underrepresented groups.
I have been the Head TA for [CSE473: Intro to AI (undergrad)](https://courses.cs.washington.edu/courses/cse473/23au/) and [CSE599J: Data-centric ML (grad)](https://koh.pw/cse599j/) at UW.  To reduce the barrier to start research or Ph.D. in this area, I'm hosting weekly office hours open to everyone (please sign up from [Calendly](https://calendly.com/akari-asai/office-hour)!), and am a mentor for [UW CSE Ph.D. Pre-Application Mentorship Service (PAMS)](https://www.cs.washington.edu/academics/phd/admissions/pams).

*Update (September 2024)*: I'm currently at full capacity and have temporarily paused my public office hours. If you're seeking feedback on your Ph.D. application materials or have questions about the UW CSE Ph.D. program, I highly recommend applying to the [UW CSE Ph.D. Pre-Application Mentorship Service (PAMS)](https://www.cs.washington.edu/academics/phd/admissions/pams), and exploring similar programs at other institutions. Unfortunately, I won't be able to mentor new students during the 2024-2025 academic year. If you're interested in collaborating with students from H2Lab, please submit an inquiry through [our group website's inqury](https://h2lab.cs.washington.edu/).
