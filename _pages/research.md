---
layout: page
title: Research
permalink: /projects/
nav: true
nav_order: 2
---

Currently, my work revolves around three interconnected questions. I also take particular interest in education as a domain of application, and I have long-standing interests in incentive-aware machine learning and fairness.

<div class="research-themes">
  <section>
    <h2>Prediction-Driven Decisions and Social Impact</h2>
    <p>How do predictive models influence decision-making in social institutions, and what are the broader consequences for equity and welfare?</p>
  </section>
  <section>
    <h2>Causal Human-AI Decision-Making</h2>
    <p>When do human decision-makers rely on algorithmic recommendations, contribute unique expertise, or improve outcomes through intervention, and can we use causal methods to derive these insights from real world data?</p>
  </section>
  <section>
    <h2>Evaluating Algorithmic Systems</h2>
    <p>How can we design rigorous evaluation frameworks to audit, stress-test, and govern algorithmic interventions?</p>
  </section>
</div>

<nav class="research-jump-nav" aria-label="Research page sections">
  <a href="#manuscripts">Manuscripts</a>
  <a href="#peer-reviewed-publications">Peer-reviewed</a>
  <a href="#technical-reports">Reports</a>
  <a href="#blog-posts">Blog</a>
  <a href="#workshops-co-organized">Workshops</a>
  <a href="#other-links">Other</a>
</nav>

<div class="pub-filter" role="group" aria-label="Filter publications by topic">
  <button type="button" class="active" data-filter="all">All</button>
  <button type="button" data-filter="prediction-social">Prediction & Social Impact</button>
  <button type="button" data-filter="causal-human-ai">Causal Human-AI Decisions</button>
  <button type="button" data-filter="evaluation">Evaluation Methods</button>
  <button type="button" data-filter="incentives">Incentive-Aware ML</button>
  <button type="button" data-filter="fairness">Fairness</button>
  <button type="button" data-filter="education">Education</button>
</div>

<div class="research-publications" markdown="1">

### Manuscripts

- Inioluwa Deborah Raji<sup>*</sup>, Lydia T. Liu<sup>*</sup>, Angela Zhou<sup>*</sup>, et al.<br>
  **Bridging Predictions and Interventions: An Integrated Framework for Automated Decision-Systems.**<br>
  _Pre-print_, 2026. [arxiv](https://arxiv.org/abs/2606.25668)<br>
  A companion perspective article that distills the core framework and motivation of the paper below for a broader audience.

- Lydia T. Liu<sup>*</sup>, Inioluwa Deborah Raji<sup>*</sup>, Angela Zhou<sup>*</sup>, Luke Guerdan,
  Jessica Hullman, Daniel Malinsky, Bryan Wilder, Simone Zhang, Hammaad Adam,
  Amanda Coston, Ben Laufer, Ezinne Nwankwo, Michael Zanger-Tishler, Eli
  Ben-Michael, Solon Barocas, Avi Feller, Marissa Gerchick, Talia Gillis, Shion
  Guha, Daniel Ho, Lily Hu, Kosuke Imai, Sayash Kapoor, Joshua Loftus, Razieh
  Nabi, Arvind Narayanan, Ben Recht, Juan Carlos Perdomo, Matthew Salganik,
  Mark Sendak, Alexander Tolbert, Berk Ustun, Suresh Venkatasubramanian,
  Angelina Wang, Ashia Wilson.  
  **Bridging Prediction and Intervention Problems in Social Systems.**  
  _Working White Paper,_ 2025. [arxiv](https://arxiv.org/abs/2507.05216) <details>
  Many automated decision systems (ADS) are designed to solve prediction problems -- where the goal is to learn patterns from a sample of the population and apply them to individuals from the same population. In reality, these prediction systems operationalize holistic policy interventions in deployment. Once deployed, ADS can shape impacted population outcomes through an effective policy change in how decision-makers operate, while also being defined by past and present interactions between stakeholders and the limitations of existing organizational, as well as societal, infrastructure and context. In this work, we consider the ways in which we must shift from a prediction-focused paradigm to an intervention-oriented paradigm when considering the impact of ADS within social systems. We argue this requires a new default problem setup for ADS beyond prediction, to instead consider predictions as decision support, final decisions, and outcomes. We highlight how this perspective unifies modern statistical frameworks and other tools to study the design, implementation, and evaluation of ADS systems, and point to the research directions necessary to operationalize this paradigm shift. Using these tools, we characterize the limitations of focusing on isolated prediction tasks, and lay the foundation for a more intervention-oriented approach to developing and deploying ADS. </details>

- Kara Schechtman, Benjamin Brandon, Jenise Stafford, Hannah Li<sup>^</sup>, Lydia T. Liu<sup>^</sup>.  
  **Discretion in the Loop: Human Expertise in Algorithm-Assisted College Advising.**  
  _To appear (Non-archival)_, ACM Conference on Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO). [arxiv](https://arxiv.org/abs/2505.13325)  
  A preliminary version was presented at [IC2S2](https://www.ic2s2-2025.org), Norrköping, Sweden, July 2025, and at the [Workshop on AI & Analytics for Social Good](https://www.rhsmith.umd.edu/departments/decision-operations-information-technologies/impact-workshop), College Park, MD, May 2025.

- Mark D. Verhagen, Benedikt Stroebl, Tiffany Liu, Lydia T. Liu, Matthew J. Salganik.  
  **The Book of Life approach: Enabling richness and scale for life course research.**  
  _Working Paper_, 2025. [arxiv](http://arxiv.org/abs/2507.03027) [blogpost](https://blog.ai.princeton.edu/2026/02/20/the-book-of-life-moving-from-a-sociology-of-variables-to-a-sociology-of-events/)

- Romina Mahinpei, Victoria Dean, Ruth Fong, Lydia T. Liu, Manoel Horta Ribeiro.  
  **AI Assistance for Discretionary Work: Increasing Feedback Provision in Higher Education.**  
  _In submission_, 2026. [arxiv](https://arxiv.org/abs/2606.03095)

### Peer-reviewed publications

#### Journal articles

- Joshua Cohen and Lydia T. Liu.  
  **The Reach of Fairness.**  
  _ACM Journal on Responsible Computing_. Just Accepted (February 2025). [eprint](https://dl.acm.org/doi/abs/10.1145/3718989) [preprint](/assets/pdf/acm_submission_final.pdf)

- Lydia T. Liu<sup>\*</sup>, Serena Wang<sup>\*</sup>, Tolani Britton<sup>^</sup>, Rediet Abebe<sup>^</sup>.  
  **Reimagining the Machine Learning Life Cycle to Improve Educational Outcomes of Students.**  
  _Proceedings of the National Academy of Sciences 120.9 (2023): e2204781120._ <!--[arxiv](http://arxiv.org/abs/2209.03929)--> [eprint](https://www.pnas.org/eprint/3RXWD4U8UFVCHHUWGFGY/full) [slides](/assets/pdf/ml4ed-bair-talk.pdf)  
  A preliminary version ("Promises and Pitfalls of Machine Learning in Education") was presented as a poster at the Research Conference on Communications, Information, and Internet Policy [(TPRC 2021)](https://www.tprcweb.com).

- Lydia T. Liu, Feng Ruan, Horia Mania, Michael I. Jordan.  
  **Bandit Learning in Decentralized Matching Markets.**  
  _Journal of Machine Learning Research_, 22(211):1−34, 2021. [journal](https://jmlr.org/papers/v22/20-1429.html) [arxiv](https://arxiv.org/abs/2012.07348)  
  Presented as a [poster](/assets/pdf/decentralizedbandits_poster.pdf) at Workshop on Operations of People-Centric Systems (EC '21)

- Zhizhen Zhao, Lydia T. Liu, Amit Singer.  
  **Steerable *e*PCA: Rotationally Invariant Exponential Family PCA.**  
  _IEEE Transactions on Image Processing, vol. 29, pp. 6069-6081, 2020._ [doi](https://doi.org/10.1109/TIP.2020.2988139) [arxiv](https://arxiv.org/abs/1812.08789)

- Lydia T. Liu<sup>\*</sup>, Edgar Dobriban<sup>\*</sup>, and Amit Singer.  
  **<em>e</em>PCA: High Dimensional Exponential Family PCA.**  
  _Annals of Applied Statistics 2018, Vol. 12, No. 4, 2121-2150._ [doi](https://dx.doi.org/10.1214/18-AOAS1146) [arxiv](https://arxiv.org/abs/1611.05550) [software](http://github.com/lydiatliu/epca/)

#### Conference proceedings

- Amaya Dharmasiri, William Yang, Polina Kirichenko, Lydia T. Liu, Olga Russakovsky.  
  **The Impact of Coreset Selection on Spurious Correlations and Group Robustness**. [poster](https://neurips.cc/virtual/2025/loc/san-diego/poster/121416)  
  Advances in Neural Information Processing Systems (NeurIPS), San Diego, CA, 2025.

- Inioluwa Deborah Raji and Lydia T. Liu.  
  **Evaluating Prediction-based Interventions with Human Decision Makers In Mind.**  
  _Proceedings of The 28th International Conference on Artificial Intelligence and Statistics (AISTATS)_, 2025. [arxiv](https://arxiv.org/abs/2503.05704)  
  A preliminary version was presented as a poster at the ICML 2024 workshop on [Humans, Algorithmic Decision-Making and Society](https://humans-algs-society.github.io/papers/).

- Lydia T. Liu, Solon Barocas, Jon Kleinberg, Karen Levy.  
  **On the Actionability of Outcome Prediction.**  
  _Proceedings of the AAAI conference on Artificial Intelligence_, 2024. [doi](https://doi.org/10.1609/aaai.v38i20.30229) [arxiv](https://arxiv.org/abs/2309.04470)

- Lydia T. Liu, Nikhil Garg, Christian Borgs.  
  **Strategic ranking.**  
  _Proceedings of The 25th International Conference on Artificial Intelligence and Statistics (AISTATS)_, 2022. [arxiv](https://arxiv.org/abs/2109.08240)  
  Presented as a [poster](/assets/pdf/strategic_ranking_poster.pdf) at the ACM conference on Equity and Access in Algorithms, Mechanisms, and Optimization [(EAAMO)](https://eaamo.org/), 2021.

- Esther Rolf, Max Simchowitz, Sarah Dean, Lydia T. Liu, Daniel Björkegren, Moritz Hardt, Joshua Blumenstock.  
  **Balancing Competing Objectives with Noisy Data: Score-Based Classifiers for Welfare-Aware Machine Learning.**  
  _Proceedings of the 37th International Conference on Machine Learning (ICML)_, 2020. [arxiv](https://arxiv.org/abs/2003.06740)

- Lydia T. Liu<sup>\*</sup>, Horia Mania<sup>\*</sup>, Michael I. Jordan.  
  **Competing Bandits in Matching Markets.**  
  _Proceedings of The 23rd International Conference on Artificial Intelligence and Statistics (AISTATS)_, 2020. [arxiv](https://arxiv.org/abs/1906.05363)

- Lydia T. Liu, Ashia Wilson, Nika Haghtalab, Adam Tauman Kalai, Christian Borgs, Jennifer Chayes.  
  **The Disparate Equilibria of Algorithmic Decision Making when Individuals Invest Rationally.**  
  _Proceedings of the ACM Conference on Fairness, Accountability, and Transparency (ACM FAT\*)_, Barcelona, Spain, 2020. [doi](https://dl.acm.org/doi/abs/10.1145/3351095.3372861)
  [arxiv](https://arxiv.org/abs/1910.04123)

- Lydia T. Liu<sup>\*</sup>, Max Simchowitz<sup>\*</sup>, Moritz Hardt.  
  **The Implicit Fairness Criterion of Unconstrained Learning.**  
  _Proceedings of the 36th International Conference on Machine Learning (ICML)_, Long Beach, California, USA, 2019. [arxiv](https://arxiv.org/abs/1808.10013) [code](https://github.com/lydiatliu/unconstrainedml)

- Chi Jin<sup>\*</sup>, Lydia T. Liu<sup>\*</sup>, Rong Ge, Michael I. Jordan.  
  **On the Local Minima of the Empirical Risk.**  
  _Advances in Neural Information Processing Systems (NeurIPS) 32_, Montréal, Canada, 2018. **_Spotlight._** [arxiv](https://arxiv.org/abs/1803.09357)

- Lydia T. Liu, Sarah Dean, Esther Rolf, Max Simchowitz, Moritz Hardt.  
  **Delayed Impact of Fair Machine Learning.**  
  🏆 _Proceedings of the 35th International Conference on Machine Learning (ICML)_, Stockholm, Sweden, 2018. **_Best Paper Award._** [arxiv](https://arxiv.org/abs/1803.04383) [code](https://github.com/lydiatliu/delayedimpact)

#### Workshop proceedings

- Jane Castleman, Nimra Nadeem, Tanvi Namjoshi, Lydia T. Liu.  
  **Rethinking Math Benchmarks: Implications for AI in Education.**  
  _Proceedings of the Innovation and Responsibility in AI-Supported Education Workshop._
  [paper](https://proceedings.mlr.press/v273/castleman25a.html)

- Yuhan Liu, Yuhan Zheng, Siyuan Zhang, Lydia T. Liu.  
  **Evaluating Fairness in Black-box Algorithmic Markets: A Case Study of Ride Sharing in Chicago.**  
  _International Conference on Machine Learning (ICML) Workshop on [Humans, Algorithmic Decision-Making and Society: Modeling Interactions and Impact](https://humans-algs-society.github.io/papers/)._
  [arxiv](http://arxiv.org/abs/2407.20522)

- Benedikt Stroebl, Rajiv Krishna Swamy, Lydia T. Liu.  
  **A Baseline that Matters: Categorical Prioritization as Benchmark for Social Policy Algorithms.**  
  _International Conference on Machine Learning (ICML) Workshop on [Humans, Algorithmic Decision-Making and Society: Modeling Interactions and Impact](https://humans-algs-society.github.io/papers/)._
  [poster](https://drive.google.com/file/d/1zdla_9SCD8tsO07g5aqe34L00G1yGotn/view?usp=sharing)

- Esther Rolf, Max Simchowitz, Sarah Dean, Lydia T. Liu, Daniel Björkegren, Moritz Hardt, Joshua Blumenstock.  
  **Balancing Competing Objectives for Welfare-Aware Machine Learning with Imperfect Data.**  
  🏆 _[NeurIPS Joint Workshop on AI for Social Good](https://aiforsocialgood.github.io/neurips2019/accepted/track1/pdfs/74_aisg_neurips2019.pdf)_, Vancouver, Canada, 2019. **_Best Paper Award._**

- Lydia T. Liu, Urun Dogan, and Katja Hofmann.  
  **Decoding multitask DQN in the world of Minecraft.**  
  _[The 13th European Workshop on Reinforcement Learning](https://ewrl.files.wordpress.com/2016/11/ewrl13-2016-submission-29.pdf)_, Barcelona, Spain, 2016. Also presented at the _11th Women in Machine Learning Workshop_ and [_the Deep Reinforcement Learning Workshop at NeurIPS 2016_](https://drive.google.com/file/d/0B1PUpk7kwWu-bDd2djhqNEx2S2J4UURTUE1sVjVnS2tXZG9r/view).

_<sup>\*</sup> <sup>^</sup> equal contribution_

</div>

<div class="research-supplement" markdown="1">

### Technical reports

- [**Social Dynamics of Machine Learning for Decision Making**](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2022/EECS-2022-41.html).  
  PhD Dissertation, University of California Berkeley, Spring 2022.

<!-- * [**On the two-sample statistic approach to generative adversarial networks.**](http://arks.princeton.edu/ark:/88435/dsp0179408079v)
Undergraduate Senior Thesis, Princeton University, Spring 2017.
-->

### Blog posts

- [**On the Actionability of Outcome Prediction.**](https://montrealethics.ai/on-the-actionability-of-outcome-prediction/) _Montreal AI Ethics Institute, AI Ethics Brief._ Feb 2024.

- [**When bias begets bias: A source of negative feedback loops in AI systems.**](https://www.microsoft.com/en-us/research/blog/when-bias-begets-bias-a-source-of-negative-feedback-loops-in-ai-systems/) _Microsoft Research Blog._ Jan 2020.

- [**Delayed Impact of Fair Machine Learning.**](https://bair.berkeley.edu/blog/2018/05/17/delayed-impact/) Co-authored with Sarah Dean, Esther Rolf, Max Simchowitz, Moritz Hardt. _Berkeley AI Research Blog._ May 2018.

### Workshops co-organized

- Simons Institute workshop on [Bridging Prediction and Intervention Problems in Social Systems](https://simons.berkeley.edu/workshops/bridging-prediction-intervention-problems-social-systems), Jan. 12-16, 2026. Berkeley, CA.

- BIRS workshop on [Bridging Prediction and Intervention Problems in Social Systems](http://www.birs.ca/events/2024/5-day-workshops/24w5283), June 3-7, 2024. Banff, AB, Canada. [Workshop Report](https://www.birs.ca/workshops/2024/24w5283/report24w5283.pdf)

- AAAI 2024 [Workshop on AI for Education: Bridging Innovation and Responsibility](https://ai4ed.cc/workshops/aaai2024), Feb 26-27, 2024. Vancouver, BC, Canada.

- NeurIPS 2020 Workshop on [**Consequential Decision Making
  in Dynamic Environments**](https://dynamicdecisions.github.io/). Virtual.

### Other links

Our work has been featured in:

- Talking Machines podcast, [Long Term Fairness](https://www.thetalkingmachines.com/episodes/long-term-fairness).
- Bloomberg Opinion, [How to Teach a Computer What ‘Fair’ Means](https://www.bloomberg.com/view/articles/2018-03-15/computer-algorithms-need-to-know-what-fair-means).

</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const labels = {
      "prediction-social": "Prediction & Social Impact",
      "causal-human-ai": "Causal Human-AI Decisions",
      evaluation: "Evaluation Methods",
      incentives: "Incentive-Aware ML",
      fairness: "Fairness",
      education: "Education",
    };

    const rules = [
      [
        "prediction-social",
        /Bridging Prediction and Intervention Problems|Bridging Predictions and Interventions|The Book of Life approach|Reimagining the Machine Learning Life Cycle|The Reach of Fairness|On the Actionability of Outcome Prediction|Delayed Impact of Fair Machine Learning|The Disparate Equilibria|Balancing Competing Objectives|A Baseline that Matters/i,
      ],
      [
        "causal-human-ai",
        /Discretion in the Loop|AI Assistance for Discretionary Work|Evaluating Prediction-based Interventions|On the Actionability of Outcome Prediction/i,
      ],
      [
        "evaluation",
        /Bridging Prediction and Intervention Problems|Bridging Predictions and Interventions|Evaluating Prediction-based Interventions|Impact of Coreset Selection|Rethinking Math Benchmarks|Evaluating Fairness in Black-box Algorithmic Markets|A Baseline that Matters/i,
      ],
      [
        "incentives",
        /Strategic ranking|Bandit Learning in Decentralized Matching Markets|Competing Bandits in Matching Markets|The Disparate Equilibria/i,
      ],
      [
        "fairness",
        /The Reach of Fairness|The Impact of Coreset Selection|Balancing Competing Objectives|The Disparate Equilibria|The Implicit Fairness Criterion|Delayed Impact of Fair Machine Learning|Evaluating Fairness in Black-box Algorithmic Markets|A Baseline that Matters|Strategic ranking/i,
      ],
      [
        "education",
        /Discretion in the Loop|AI Assistance for Discretionary Work|Reimagining the Machine Learning Life Cycle|Rethinking Math Benchmarks/i,
      ],
    ];

    const publicationItems = Array.from(document.querySelectorAll(".research-publications li"));
    const resourceLinkLabels = new Set([
      "arxiv",
      "blogpost",
      "code",
      "doi",
      "eprint",
      "journal",
      "paper",
      "poster",
      "preprint",
      "slides",
      "software",
      "video",
    ]);

    document.querySelectorAll(".research-publications li a").forEach((link) => {
      const label = link.textContent.trim().toLowerCase();
      if (resourceLinkLabels.has(label) || label.startsWith("video,")) {
        link.classList.add("pub-link-button");
      }
    });

    publicationItems.forEach((item) => {
      const text = item.textContent;
      const topics = rules.filter(([, pattern]) => pattern.test(text)).map(([topic]) => topic);
      const uniqueTopics = Array.from(new Set(topics));
      item.dataset.topics = uniqueTopics.join(" ");

      if (!uniqueTopics.length) return;

      const topicList = document.createElement("div");
      topicList.className = "pub-topic-list";
      topicList.setAttribute("aria-label", "Publication topics");
      topicList.innerHTML = uniqueTopics.map((topic) => `<span class="topic-${topic}">${labels[topic]}</span>`).join("");
      item.prepend(topicList);
    });

    function applyFilter(topic) {
      publicationItems.forEach((item) => {
        item.hidden = topic !== "all" && !item.dataset.topics.split(" ").includes(topic);
      });

      document.querySelectorAll(".research-publications h3, .research-publications h4").forEach((heading) => {
        let node = heading.nextElementSibling;
        let hasVisibleItem = false;
        const boundary = heading.tagName === "H3" ? /^H3$/ : /^H[34]$/;
        while (node && !boundary.test(node.tagName)) {
          if (node.matches("ul, ol") && Array.from(node.querySelectorAll("li")).some((item) => !item.hidden)) {
            hasVisibleItem = true;
            break;
          }
          node = node.nextElementSibling;
        }
        heading.hidden = topic !== "all" && !hasVisibleItem;
      });
    }

    document.querySelectorAll(".pub-filter button").forEach((button) => {
      button.addEventListener("click", () => {
        document.querySelectorAll(".pub-filter button").forEach((otherButton) => otherButton.classList.remove("active"));
        button.classList.add("active");
        applyFilter(button.dataset.filter);
      });
    });
  });
</script>
