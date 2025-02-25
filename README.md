# AI Safety and Alignment

![](https://img.shields.io/github/last-commit/atonkamanda/awesome-ai-safety?color=green) ![](https://img.shields.io/badge/PaperNumber-64-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red)

A curated list of resources dedicated to research in **AI safety and alignment**. As AI systems become increasingly influential in society, ensuring that they operate safely, truthfully, and robustly is more critical than ever. This list emphasizes contemporary research addressing safety challenges with modern, highly capable AI models and will be updated regularly. 

## Contents

- [Overview](#overview)
- [Alignment](#alignment)
- [Instrumental Convergence](#instrumental-convergence)
- [Adversarial Robustness](#adversarial-robustness)
- [Debate](#debate)
- [Honesty](#honesty)
- [Chain-of-thought Faithfulness](#chain-of-thought-faithfulness)
- [Weak-to-strong Generalization](#weak-to-strong-generalization)
- [Mechanistic Interpretability](#mechanistic-interpretability)
- [Evaluation](#evaluation)
- [Contribution](#contribution)

---



## Overview

This section presents foundational papers that introduce key concepts, challenges, and frameworks in AI safety.
1. **Concrete Problems in AI Safety.** [2016] ![](https://img.shields.io/badge/Overview-blue)  
   *Dario Amodei, Chris Olah, Jacob Steinhardt, Paul Christiano, John Schulman, Dan Mané*  
   [[pdf](https://arxiv.org/abs/1606.06565)]

2. **The Off-Switch Game.** [2016] ![](https://img.shields.io/badge/Overview-blue)  
   *Dylan Hadfield-Menell, Anca Dragan, Pieter Abbeel, Stuart Russell*  
   [[pdf](https://arxiv.org/abs/1611.08219)]

3. **AI Safety Gridworlds.** [2017] ![](https://img.shields.io/badge/Overview-blue)  
   *Jan Leike, Miljan Martic, Victoria Krakovna, Pedro A. Ortega, Tom Everitt, Andrew Lefrancq, Laurent Orseau, Shane Legg*  
   [[pdf](https://arxiv.org/abs/1711.09883)]

4. **Unsolved Problems in ML Safety.** [2021] ![](https://img.shields.io/badge/Overview-blue)  
   *Dan Hendrycks, Nicholas Carlini, John Schulman, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2109.13916)]

5. **Foundational Challenges in Assuring Alignment and Safety of Large Language Models.** [2024] ![](https://img.shields.io/badge/Overview-blue)  
   *Usman Anwar, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana, Erik Jenner, Stephen Casper, Oliver Sourbut, et al.*  
   [[pdf](https://arxiv.org/abs/2404.09932)]

6. **Towards Guaranteed Safe AI.** [2024] ![](https://img.shields.io/badge/Overview-blue)  
   *David "davidad" Dalrymple, Joar Skalse, Yoshua Bengio, Stuart Russell, Max Tegmark, Sanjit Seshia, Steve Omohundro, Christian Szegedy, Ben Goldhaber, Nora Ammann, Alessandro Abate, Joe Halpern, Clark Barrett, Ding Zhao, Tan Zhi-Xuan, Jeannette Wing, Joshua Tenenbaum*  
   [[pdf](https://arxiv.org/abs/2405.06624)]

7. **Can a Bayesian Oracle Prevent Harm from an Agent?** [2024] ![](https://img.shields.io/badge/Overview-blue)  
   *Yoshua Bengio, Michael K. Cohen, Nikolay Malkin, Matt MacDermott, Damiano Fornasiere, Pietro Greiner, Younesse Kaddar*  
   [[pdf](https://arxiv.org/abs/2408.05284)]


8. **International AI Safety Report.** [2025] ![](https://img.shields.io/badge/Overview-blue)  
   *Yoshua Bengio, Sören Mindermann, Daniel Privitera, Tamay Besiroglu, Rishi Bommasani, Stephen Casper, Yejin Choi, Philip Fox, Ben Garfinkel, Danielle Goldfarb, et al.*  
   [[pdf](https://arxiv.org/abs/2501.17805)]


9. **Superintelligent Agents Pose Catastrophic Risks: Can Scientist AI Offer a Safer Path?** [2025] ![](https://img.shields.io/badge/Overview-blue)  
   *Yoshua Bengio, Michael Cohen, Damiano Fornasiere, Joumana Ghosn, Pietro Greiner, Matt MacDermott, Sören Mindermann, Adam Oberman, Jesse Richardson, Oliver Richardson, Marc-Antoine Rondeau, Pierre-Luc St-Charles, David Williams-King*  
   [[pdf](https://arxiv.org/abs/2502.15657)]

---

## Alignment

Alignment research focuses on ensuring AI systems act in accordance with human values and intentions. This area addresses the fundamental challenge of specifying what we want AI systems to do and creating techniques to train them to pursue these objectives faithfully. 



1. **Scalable agent alignment via reward modeling: a research direction.** [2018] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Jan Leike, David Krueger, Tom Everitt, Miljan Martic, Vishal Maini, Shane Legg*  
   [[pdf](https://arxiv.org/abs/1811.07871)]

2. **Learning Human Objectives by Evaluating Hypothetical Behavior.** [2019] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Siddharth Reddy, Anca D. Dragan, Sergey Levine, Shane Legg, Jan Leike*  
   [[pdf](https://arxiv.org/abs/1912.05652)]

3. **What Would Jiminy Cricket Do? Towards Agents That Behave Morally.** [2021] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Dan Hendrycks, Mantas Mazeika, Andy Zou, Sahil Patel, Christine Zhu, Jesus Navarro, Dawn Song, Bo Li, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2110.13136)]

4. **The Effects of Reward Misspecification: Mapping and Mitigating Misaligned Models.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Alexander Pan, Kush Bhatia, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2201.03544)]

5. **Training language models to follow instructions with human feedback.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe*  
   [[pdf](https://arxiv.org/abs/2203.02155)]

6. **Scaling Laws for Reward Model Overoptimization.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Leo Gao, John Schulman, Jacob Hilton*  
   [[pdf](https://arxiv.org/abs/2210.10760)]

7. **How Would The Viewer Feel? Estimating Wellbeing From Video Scenarios.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Mantas Mazeika, Eric Tang, Andy Zou, Steven Basart, Jun Shern Chan, Dawn Song, David Forsyth, Jacob Steinhardt, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2210.10039)]

8. **Deliberative Alignment: Reasoning Enables Safer Language Models.** [2024] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Melody Y. Guan, Manas Joglekar, Eric Wallace, Saachi Jain, Boaz Barak, Alec Helyar, Rachel Dias, Andrea Vallone, Hongyu Ren, Jason Wei, Hyung Won Chung, Sam Toyer, Johannes Heidecke, Alex Beutel, Amelia Glaese*  
   [[pdf](https://arxiv.org/abs/2412.16339)]

9. **Alignment faking in large language models.** [2024] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Ryan Greenblatt, Carson Denison, Benjamin Wright, Fabien Roger, Monte MacDiarmid, Sam Marks, Johannes Treutlein, Tim Belonax, Jack Chen, David Duvenaud, Akbir Khan, Julian Michael, Sören Mindermann, Ethan Perez, Linda Petrini, Jonathan Uesato, Jared Kaplan, Buck Shlegeris, Samuel R. Bowman, Evan Hubinger*  
   [[pdf](https://arxiv.org/abs/2412.14093)]

---

## Instrumental Convergence

Instrumental convergence examines how AI systems with different goals might develop similar subgoals—like seeking power or preventing shutdown—as instrumentally useful steps toward their primary objectives. This research area explores how, when and why systems develop those behaviors, helping us understand potential risks from advanced AI systems even when their ultimate goals seem benign. 

1. **Optimal Policies Tend to Seek Power.** [2019] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Alexander Matt Turner, Logan Smith, Rohin Shah, Andrew Critch, Prasad Tadepalli*  
   [[pdf](https://arxiv.org/abs/1912.01683)]

2. **Parametrically Retargetable Decision-Makers Tend To Seek Power.** [2022] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Alexander Matt Turner, Prasad Tadepalli*  
   [[pdf](https://arxiv.org/abs/2206.13477)]

3. **Power-Seeking Can Be Probable and Predictive for Trained Agents.** [2023] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Victoria Krakovna, Janos Kramar*  
   [[pdf](https://arxiv.org/abs/2304.06528)]

4. **Tell me about yourself: LLMs are aware of their learned behaviors.** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Jan Betley, Xuchan Bao, Martín Soto, Anna Sztyber-Betley, James Chua, Owain Evans*  
   [[pdf](https://arxiv.org/abs/2501.11120)]

5. **Evaluating the Paperclip Maximizer: Are RL-Based Language Models More Likely to Pursue Instrumental Goals?** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Yufei He, Yuexin Li, Jiaying Wu, Yuan Sui, Yulin Chen, Bryan Hooi*  
   [[pdf](https://www.arxiv.org/abs/2502.12206)]

6. **Utility Engineering: Analyzing and Controlling Emergent Value Systems in AIs.** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Mantas Mazeika, Xuwang Yin, Rishub Tamirisa, Jaehyuk Lim, Bruce W. Lee, Richard Ren, Long Phan, Norman Mu, Adam Khoja, Oliver Zhang, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2502.08640)]

7. **Emergent Misalignment: Narrow finetuning can produce broadly misaligned LLMs.** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Jan Betley, Daniel Tan, Niels Warncke, Anna Sztyber-Betley, Xuchan Bao, Martín Soto, Nathan Labenz, Owain Evans*  
   [[pdf](https://arxiv.org/abs/2502.17424)]

---

## Adversarial Robustness

Adversarial robustness research addresses the vulnerability of AI systems to attempts to circumvent their safety measures or manipulate their behavior. This area studies how AI systems might be compromised through techniques like jailbreaking, prompt injection, and data poisoning, as well as methods to defend against such attacks or to make the system more reliable.

1. **Adversarial Training for High-Stakes Reliability.** [2022] ![](https://img.shields.io/badge/Adversarial-red)  
   *Daniel M. Ziegler, Seraphina Nix, Lawrence Chan, Tim Bauman, Peter Schmidt-Nielsen, Tao Lin, Adam Scherlis, Noa Nabeshima, Ben Weinstein-Raun, Daniel de Haas, Buck Shlegeris, Nate Thomas*  
   [[pdf](https://arxiv.org/abs/2205.01663)]

2. **Poisoning Language Models During Instruction Tuning.** [2023] ![](https://img.shields.io/badge/Adversarial-red)  
   *Alexander Wan, Eric Wallace, Sheng Shen, Dan Klein*  
   [[pdf](https://arxiv.org/abs/2305.00944)]

3. **Are aligned neural networks adversarially aligned?** [2023] ![](https://img.shields.io/badge/Adversarial-red)  
   *Nicholas Carlini, Milad Nasr, Christopher A. Choquette-Choo, Matthew Jagielski, Irena Gao, Anas Awadalla, Pang Wei Koh, Daphne Ippolito, Katherine Lee, Florian Tramer, Ludwig Schmidt*  
   [[pdf](https://arxiv.org/abs/2306.15447)]

4. **Jailbroken: How Does LLM Safety Training Fail?** [2023] ![](https://img.shields.io/badge/Adversarial-red)  
   *Alexander Wei, Nika Haghtalab, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2307.02483)]

5. **Universal and Transferable Adversarial Attacks on Aligned Language Models.** [2023] ![](https://img.shields.io/badge/Adversarial-red)  
   *Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson*  
   [[pdf](https://arxiv.org/abs/2307.15043)]

6. **AI Control: Improving Safety Despite Intentional Subversion.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
   *Ryan Greenblatt, Buck Shlegeris, Kshitij Sachan, Fabien Roger*  
   [[pdf](https://arxiv.org/abs/2312.06942)]

7. **Many-shot jailbreaking.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
   *Anthropic*  
   [[pdf](https://www.anthropic.com/research/many-shot-jailbreaking)]

8. **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
   *Evan Hubinger, Carson Denison, Jesse Mu, Mike Lambert, Meg Tong, Monte MacDiarmid, Tamera Lanham, Daniel M. Ziegler, Tim Maxwell, Newton Cheng, Adam Jermyn, Amanda Askell, Ansh Radhakrishnan, Cem Anil, David Duvenaud, Deep Ganguli, Fazl Barez, Jack Clark, Kamal Ndousse, Kshitij Sachan, Michael Sellitto, Mrinank Sharma, Nova DasSarma, Roger Grosse, Shauna Kravec, Yuntao Bai, Zachary Witten, Marina Favaro, Jan Brauner, Holden Karnofsky, Paul Christiano, Samuel R. Bowman, Logan Graham, Jared Kaplan, Sören Mindermann, Ryan Greenblatt, Buck Shlegeris, Nicholas Schiefer, Ethan Perez*  
   [[pdf](https://arxiv.org/abs/2401.05566)]

9. **Simple probes can catch sleeper agents.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
   *Anthropic*  
   [[pdf](https://www.anthropic.com/research/probes-catch-sleeper-agents)]

10. **Holistic Safety and Responsibility Evaluations of Advanced AI Models.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
    *Laura Weidinger, Joslyn Barnhart, Jenny Brennan, Christina Butterfield, Susie Young, Will Hawkins, Lisa Anne Hendricks, Ramona Comanescu, Oscar Chang, Mikel Rodriguez, et al.*  
    [[pdf](https://arxiv.org/abs/2404.14068)]

11. **Improving Alignment and Robustness with Circuit Breakers.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
    *Andy Zou, Long Phan, Justin Wang, Derek Duenas, Maxwell Lin, Maksym Andriushchenko, Rowan Wang, Zico Kolter, Matt Fredrikson, Dan Hendrycks*  
    [[pdf](https://arxiv.org/abs/2406.04313)]

12. **Tamper-Resistant Safeguards for Open-Weight LLMs.** [2024] ![](https://img.shields.io/badge/Adversarial-red)  
    *Rishub Tamirisa, Bhrugu Bharathi, Long Phan, Andy Zhou, Alice Gatti, Tarun Suresh, Maxwell Lin, Justin Wang, Rowan Wang, Ron Arel, et al.*  
    [[pdf](https://arxiv.org/abs/2408.00761)]

13. **Constitutional Classifiers: Defending against Universal Jailbreaks across Thousands of Hours of Red Teaming.** [2025] ![](https://img.shields.io/badge/Adversarial-red)  
    *Mrinank Sharma, Meg Tong, Jesse Mu, Jerry Wei, Jorrit Kruthoff, Scott Goodfriend, Euan Ong, Alwin Peng, Raj Agarwal, Cem Anil, Amanda Askell, Nathan Bailey, Joe Benton, Emma Bluemke, Samuel R. Bowman, Eric Christiansen, Hoagy Cunningham, Andy Dau, Anjali Gopal, Rob Gilson, Logan Graham, Logan Howard, Nimit Kalra, Taesung Lee, Kevin Lin, Peter Lofgren, Francesco Mosconi, Clare O'Hara, Catherine Olsson, Linda Petrini, Samir Rajani, Nikhil Saxena, Alex Silverstein, Tanya Singh, Theodore Sumers, Leonard Tang, Kevin K. Troy, Constantin Weisser, Ruiqi Zhong, Giulio Zhou, Jan Leike, Jared Kaplan, Ethan Perez*  
    [[pdf](https://arxiv.org/abs/2501.18837)]
    
---

## Debate

Debate approaches leverage the ability of AI systems to critique each other's outputs as a way to improve truthfulness and reasoning. By having models engage in structured debates—with humans judging the results or models evaluating each other—we can potentially elicit more accurate information and uncover flaws in reasoning that might otherwise remain hidden. 

1. **AI safety via debate.** [2018] ![](https://img.shields.io/badge/Debate-pink)  
   *Geoffrey Irving, Paul Christiano, Dario Amodei*  
   [[pdf](https://arxiv.org/abs/1805.00899)]

2. **Scalable AI Safety via Doubly-Efficient Debate.** [2023] ![](https://img.shields.io/badge/Debate-pink)  
   *Jonah Brown-Cohen, Geoffrey Irving, Georgios Piliouras*  
   [[pdf](https://arxiv.org/abs/2311.14125)]


3. **Debating with More Persuasive LLMs Leads to More Truthful Answers.** [2024] ![](https://img.shields.io/badge/Debate-pink)  
   *Akbir Khan, John Hughes, Dan Valentine, Laura Ruis, Kshitij Sachan, Ansh Radhakrishnan, Edward Grefensthe, Samuel R. Bowman, Tim Rocktäschel, Ethan Perez*  
   [[pdf](https://arxiv.org/abs/2402.06782)]



---

## Honesty

Honesty research focuses on ensuring AI systems provide truthful, accurate information rather than generating plausible-sounding falsehoods. 

1. **TruthfulQA: Measuring How Models Mimic Human Falsehoods.** [2021] ![](https://img.shields.io/badge/Honesty-orange)  
   *Stephanie Lin, Jacob Hilton, Owain Evans*  
   [[pdf](https://arxiv.org/abs/2109.07958)]

2. **Truthful AI: Developing and governing AI that does not lie.** [2021] ![](https://img.shields.io/badge/Honesty-orange)  
   *Owain Evans, Owen Cotton-Barratt, Lukas Finnveden, Adam Bales, Avital Balwit, Peter Wills, Luca Righetti, William Saunders*  
   [[pdf](https://arxiv.org/abs/2110.06674)]

3. **Discovering Latent Knowledge in Language Models Without Supervision.** [2022] ![](https://img.shields.io/badge/Honesty-orange)  
   *Collin Burns, Haotian Ye, Dan Klein, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2212.03827)]

4. **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model.** [2023] ![](https://img.shields.io/badge/Honesty-orange)  
   *Kenneth Li, Oam Patel, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg*  
   [[pdf](https://arxiv.org/abs/2306.03341)]

5. **How to Catch an AI Liar: Lie Detection in Black-Box LLMs by Asking Unrelated Questions.** [2023] ![](https://img.shields.io/badge/Honesty-orange)  
   *Lorenzo Pacchiardi, Alex J. Chan, Sören Mindermann, Ilan Moscovitz, Alexa Y. Pan, Yarin Gal, Owain Evans, Jan Brauner*  
   [[pdf](https://arxiv.org/abs/2309.15840)]

---

## Chain-of-thought Faithfulness

This research area examines whether the reasoning processes of AI systems—particularly when they "think step by step"—actually support their conclusions in a logical, faithful manner. As models increasingly explain their reasoning, ensuring these explanations accurately reflect sound logical processes becomes crucial.

1. **Learning to Give Checkable Answers with Prover-Verifier Games** [2021] ![](https://img.shields.io/badge/Faithfulness-teal)  
   *Cem Anil, Guodong Zhang, Yuhuai Wu, Roger Grosse*  
   [[pdf](https://arxiv.org/abs/2108.12099)]

2. **Faithful Chain-of-Thought Reasoning.** [2023] ![](https://img.shields.io/badge/Faithfulness-teal)  
   *Qing Lyu, Shreya Havaldar, Adam Stein, Li Zhang, Delip Rao, Eric Wong, Marianna Apidianaki, Chris Callison-Burch*  
   [[pdf](https://arxiv.org/abs/2301.13379)]

3. **Measuring Faithfulness in Chain-of-Thought Reasoning.** [2023] ![](https://img.shields.io/badge/Faithfulness-teal)  
   *Tamera Lanham, Anna Chen, Ansh Radhakrishnan, Benoit Steiner, Carson Denison, Danny Hernandez, Dustin Li, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Karina Nguyen, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Robin Larson, Sam McCandlish, Sandipan Kundu, Saurav Kadavath, Shannon Yang, Thomas Henighan, Timothy Maxwell, Timothy Telleen-Lawton, Tristan Hume, Zac Hatfield-Dodds, Jared Kaplan*  
   [[pdf](https://arxiv.org/abs/2307.13702)]

4. **Prover-Verifier Games Improve Legibility of LLM Outputs.** [2024] ![](https://img.shields.io/badge/Faithfulness-teal)  
   *Jan Hendrik Kirchner, Yining Chen, Harri Edwards, Jan Leike, Nat McAleese, Yuri Burda*  
   [[pdf](https://arxiv.org/abs/2407.13692)]

---

## Weak-to-strong Generalization

Weak-to-strong generalization investigates whether and how safety properties in less capable AI systems might transfer to more powerful ones. This emerging area explores techniques where weaker models help align stronger ones, offering a potential path to maintaining control as AI capabilities rapidly advance. 

1. **Weak-to-Strong Generalization: Eliciting Strong Capabilities With Weak Supervision.** [2023] ![](https://img.shields.io/badge/Weak--to--strong-lightblue)  
   *Collin Burns, Pavel Izmailov, Jan Hendrik Kirchner, Bowen Baker, Leo Gao, Leopold Aschenbrenner, Yining Chen, Adrien Ecoffet, Manas Joglekar, Jan Leike, Ilya Sutskever, Jeff Wu*  
   [[pdf](https://arxiv.org/abs/2312.09390)]

2. **Theoretical Analysis of Weak-to-Strong Generalization.** [2024] ![](https://img.shields.io/badge/Weak--to--strong-lightblue)  
   *Hunter Lang, David Sontag, Aravindan Vijayaraghavan*  
   [[pdf](https://arxiv.org/abs/2405.16043)]

3. **Weak-to-Strong Generalization beyond Accuracy: a Pilot Study in Safety, Toxicity, and Legal Reasoning.** [2024] ![](https://img.shields.io/badge/Weak--to--strong-lightblue)  
   *Ruimeng Ye, Yang Xiao, Bo Hui*  
   [[pdf](https://arxiv.org/abs/2410.12621)]

---

## Mechanistic Interpretability

Mechanistic interpretability focuses on developing techniques to understand the internal workings of neural networks at a detailed level. 

1. **Representation Engineering: A Top-Down Approach to AI Transparency.** [2023] ![](https://img.shields.io/badge/Interpretability-yellow)  
   *Andy Zou, Long Phan, Sarah Chen, James Campbell, Phillip Guo, Richard Ren, Alexander Pan, Xuwang Yin, Mantas Mazeika, Ann-Kathrin Dombrowski, Shashwat Goel, Nathaniel Li, Michael J. Byun, Zifan Wang, Alex Mallen, Steven Basart, Sanmi Koyejo, Dawn Song, Matt Fredrikson, J. Zico Kolter, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2310.01405)]

2. **A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity.** [2024] ![](https://img.shields.io/badge/Interpretability-yellow)  
   *Andrew Lee, Xiaoyan Bai, Itamar Pres, Martin Wattenberg, Jonathan K. Kummerfeld, Rada Mihalcea*  
   [[pdf](https://arxiv.org/abs/2401.01967)]

3. **Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet.** [2024] ![](https://img.shields.io/badge/Interpretability-yellow)  
   *Adly Templeton, Tom Conerly, Jonathan Marcus, Jack Lindsey, Trenton Bricken, Brian Chen, Adam Pearce, Craig Citro, Emmanuel Ameisen, Andy Jones, Hoagy Cunningham, Nicholas L Turner, Callum McDougall, Monte MacDiarmid, Alex Tamkin, Esin Durmus, Tristan Hume, Francesco Mosconi, C. Daniel Freeman, Theodore R. Sumers, Edward Rees, Joshua Batson, Adam Jermyn, Shan Carter, Chris Olah, Tom Henighan*  
   [[pdf](https://transformer-circuits.pub/2024/scaling-monosemanticity/)]

---

## Evaluation

Evaluation research develops benchmarks, tests, and methodologies to assess AI systems' safety properties. This area creates rigorous ways to measure alignment, identify potential risks, and track progress in safety research.

1. **Red Teaming Language Models with Language Models.** [2022] ![](https://img.shields.io/badge/Evaluation-green)  
   *Ethan Perez, Saffron Huang, Francis Song, Trevor Cai, Roman Ring, John Aslanides, Amelia Glaese, Nat McAleese, Geoffrey Irving*  
   [[pdf](https://arxiv.org/abs/2202.03286)]

2. **Do the Rewards Justify the Means? Measuring Trade-Offs Between Rewards and Ethical Behavior in the MACHIAVELLI Benchmark.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Alexander Pan, Jun Shern Chan, Andy Zou, Nathaniel Li, Steven Basart, Thomas Woodside, Jonathan Ng, Hanlin Zhang, Scott Emmons, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2304.03279)]

3. **Model Evaluation for Extreme Risks.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Toby Shevlane, Sebastian Farquhar, Ben Garfinkel, Mary Phuong, Jess Whittlestone, Jade Leung, Daniel Kokotajlo, Nahema Marchal, Markus Anderljung, Noam Kolt, Lewis Ho, Divya Siddarth, Shahar Avin, Will Hawkins, Been Kim, Iason Gabriel, Vijay Bolina, Jack Clark, Yoshua Bengio, Paul Christiano, Allan Dafoe*  
   [[pdf](https://arxiv.org/abs/2305.15324)]

4. **XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Paul Röttger, Hannah Rose Kirk, Bertie Vidgen, Giuseppe Attanasio, Federico Bianchi, Dirk Hovy*  
   [[pdf](https://arxiv.org/abs/2308.01263)]

5. **Sociotechnical Safety Evaluation of Generative AI Systems.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Laura Weidinger, Maribeth Rauh, Nahema Marchal, Arianna Manzini, Lisa Anne Hendricks, Juan Mateos-Garcia, Stevie Bergman, Jackie Kay, Conor Griffin, Ben Bariach, et al.*  
   [[pdf](https://arxiv.org/abs/2310.11986)]

6. **Can LLMs Follow Simple Rules?** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Norman Mu, Sarah Chen, Zifan Wang, Sizhe Chen, David Karamardian, Lulwa Aljeraisy, Basel Alomair, Dan Hendrycks, David Wagner*  
   [[pdf](https://arxiv.org/abs/2311.04235)]

7. **HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal.** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
   *Mantas Mazeika, Long Phan, Xuwang Yin, Andy Zou, Zifan Wang, Norman Mu, Elham Sakhaee, Nathaniel Li, Steven Basart, Bo Li, David Forsyth, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2402.04249)]

8. **The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning.** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
   *Nathaniel Li, Alexander Pan, Anjali Gopal, Summer Yue, Daniel Berrios, Alice Gatti, Justin D. Li, Ann-Kathrin Dombrowski, Shashwat Goel, Long Phan, et al.*  
   [[pdf](https://arxiv.org/abs/2403.03218)]

9. **Evaluating Frontier Models for Dangerous Capabilities.** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
   *Mary Phuong, Matthew Aitchison, Elliot Catt, Sarah Cogan, Alexandre Kaskasoli, Victoria Krakovna, David Lindner, Matthew Rahtz, Yannis Assael, et al.*  
   [[pdf](https://arxiv.org/abs/2403.13793)]

10. **Holistic Safety and Responsibility Evaluations of Advanced AI Models.** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
    *Laura Weidinger, Joslyn Barnhart, Jenny Brennan, Christina Butterfield, Susie Young, Will Hawkins, Lisa Anne Hendricks, Ramona Comanescu, Oscar Chang, Mikel Rodriguez, et al.*  
    [[pdf](https://arxiv.org/abs/2404.14068)]

11. **Safetywashing: Do AI Safety Benchmarks Actually Measure Safety Progress?** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
    *Richard Ren, Steven Basart, Adam Khoja, Alice Gatti, Long Phan, Xuwang Yin, Mantas Mazeika, Alexander Pan, Gabriel Mukobi, Ryan H. Kim, Stephen Fitz, Dan Hendrycks*  
    [[pdf](https://arxiv.org/abs/2407.21792)]

12. **Forecasting Rare Language Model Behaviors.** [2025] ![](https://img.shields.io/badge/Evaluation-green)  
    *Erik Jones, Meg Tong, Jesse Mu, Mohammed Mahfoud, Jan Leike, Roger Grosse, Jared Kaplan, William Fithian, Ethan Perez, Mrinank Sharma*  
    [[pdf](https://arxiv.org/abs/2502.16797)]

---

## Contribution

### Other Contributors

*List of contributors will be added here.*

### Contributing to this Paper List

- First, decide which category your paper belongs to.
- Next, follow the format used above—ensure there is an empty line between the title and the authors, and include the appropriate keyword tags and PDF link.
- Finally, submit a pull request with your updates.

**Don't worry if you don't nail every detail on the first try—we will help refine and update them.** Thank you for contributing to the AI safety and alignment community!
