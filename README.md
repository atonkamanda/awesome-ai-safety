# AI Safety and Alignment

![](https://img.shields.io/github/last-commit/atonkamanda/awesome-ai-safety?color=green) ![](https://img.shields.io/badge/PaperNumber-42-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red)

A curated list of resources dedicated to research in **AI safety and alignment**. As AI systems become increasingly influential in society, ensuring that they operate safely, truthfully, and robustly is more critical than ever. This list is focused on recent AI research with highly capable models and will be updated frequently. 

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

1. **Concrete Problems in AI Safety.** [2016] ![](https://img.shields.io/badge/General-blue)  
   *Dario Amodei, Chris Olah, Jacob Steinhardt, Paul Christiano, John Schulman, Dan Mané*  
   [[pdf](https://arxiv.org/abs/1606.06565)]

2. **Towards Guaranteed Safe AI: A Framework for Ensuring Robust and Reliable AI Systems.** [2024] ![](https://img.shields.io/badge/General-blue)  
   *David "davidad" Dalrymple, Joar Skalse, Yoshua Bengio, Stuart Russell, Max Tegmark, Sanjit Seshia, Steve Omohundro, Christian Szegedy, Ben Goldhaber, Nora Ammann, Alessandro Abate, Joe Halpern, Clark Barrett, Ding Zhao, Tan Zhi-Xuan, Jeannette Wing, Joshua Tenenbaum*  
   [[pdf](https://arxiv.org/abs/2405.06624)]

3. **International AI Safety Report.** [2025] ![](https://img.shields.io/badge/General-blue)  
   *Yoshua Bengio, Sören Mindermann, Daniel Privitera, Tamay Besiroglu, Rishi Bommasani, Stephen Casper, Yejin Choi, Philip Fox, Ben Garfinkel, Danielle Goldfarb, Hoda Heidari, Anson Ho, Sayash Kapoor, Leila Khalatbari, Shayne Longpre, Sam Manning, Vasilios Mavroudis, Mantas Mazeika, Julian Michael, Jessica Newman, Kwan Yee Ng, Chinasa T. Okolo, Deborah Raji, Girish Sastry, Elizabeth Seger, Theodora Skeadas, Tobin South, Emma Strubell, Florian Tramèr, Lucia Velasco, Nicole Wheeler, Daron Acemoglu, Olubayo Adekanmbi, David Dalrymple, Thomas G. Dietterich, Edward W. Felten, Pascale Fung, Pierre-Olivier Gourinchas, Fredrik Heintz, Geoffrey Hinton, Nick Jennings, Andreas Krause, Susan Leavy, Percy Liang, Teresa Ludermir, Vidushi Marda, Helen Margetts, John McDermid, Jane Munga, Arvind Narayanan, Alondra Nelson, Clara Neppel, Alice Oh, Gopal Ramchurn, Stuart Russell, Marietje Schaake, Bernhard Schölkopf, Dawn Song, Alvaro Soto, Lee Tiedrich, Gaël Varoquaux, Andrew Yao, Ya-Qin Zhang, Fahad Albalawi, Marwan Alserkal, Olubunmi Ajala*  
   [[pdf](https://arxiv.org/abs/2501.17805)]

---

## Alignment

1. **Scalable agent alignment via reward modeling: a research direction.** [2018] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Jan Leike, David Krueger, Tom Everitt, Miljan Martic, Vishal Maini, Shane Legg*  
   [[pdf](https://arxiv.org/abs/1811.07871)]

2. **Training language models to follow instructions with human feedback.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe*  
   [[pdf](https://arxiv.org/abs/2203.02155)]

3. **Scaling Laws for Reward Model Overoptimization.** [2022] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Leo Gao, John Schulman, Jacob Hilton*  
   [[pdf](https://arxiv.org/abs/2210.10760)]

4. **Foundational Challenges in Assuring Alignment and Safety of Large Language Models.** [2024] ![](https://img.shields.io/badge/General-blue)  
   *Usman Anwar, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana, Erik Jenner, Stephen Casper, Oliver Sourbut, Benjamin L. Edelman, Zhaowei Zhang, Mario Günther, Anton Korinek, Jose Hernandez-Orallo, Lewis Hammond, Eric Bigelow, Alexander Pan, Lauro Langosco, Tomasz Korbak, Heidi Zhang, Ruiqi Zhong, Seán Ó hÉigeartaigh, Gabriel Recchia, Giulio Corsi, Alan Chan, Markus Anderljung, Lilian Edwards, Aleksandar Petrov, Christian Schroeder de Witt, Sumeet Ramesh Motwan, Yoshua Bengio, Danqi Chen, Philip H.S. Torr, Samuel Albanie, Tegan Maharaj, Jakob Foerster, Florian Tramer, He He, Atoosa Kasirzadeh, Yejin Choi, David Krueger*  
   [[pdf](https://arxiv.org/abs/2404.09932)]

5. **Deliberative Alignment: Reasoning Enables Safer Language Models.** [2024] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Melody Y. Guan, Manas Joglekar, Eric Wallace, Saachi Jain, Boaz Barak, Alec Helyar, Rachel Dias, Andrea Vallone, Hongyu Ren, Jason Wei, Hyung Won Chung, Sam Toyer, Johannes Heidecke, Alex Beutel, Amelia Glaese*  
   [[pdf](https://arxiv.org/abs/2412.16339)]

6. **Alignment faking in large language models.** [2024] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Ryan Greenblatt, Carson Denison, Benjamin Wright, Fabien Roger, Monte MacDiarmid, Sam Marks, Johannes Treutlein, Tim Belonax, Jack Chen, David Duvenaud, Akbir Khan, Julian Michael, Sören Mindermann, Ethan Perez, Linda Petrini, Jonathan Uesato, Jared Kaplan, Buck Shlegeris, Samuel R. Bowman, Evan Hubinger*  
   [[pdf](https://arxiv.org/abs/2412.14093)]

---

## Instrumental Convergence

1. **Optimal Policies Tend to Seek Power.** [2019] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Alexander Matt Turner, Logan Smith, Rohin Shah, Andrew Critch, Prasad Tadepalli*  
   [[pdf](https://arxiv.org/abs/1912.01683)]

2. **Parametrically Retargetable Decision-Makers Tend To Seek Power.** [2022] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Alexander Matt Turner, Prasad Tadepalli*  
   [[pdf](https://arxiv.org/abs/2206.13477)]

3. **Power-Seeking Can Be Probable and Predictive for Trained Agents.** [2023] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Victoria Krakovna, Janos Kramar*  
   [[pdf](https://arxiv.org/abs/2304.06528)]

4. **Evaluating the Paperclip Maximizer: Are RL-Based Language Models More Likely to Pursue Instrumental Goals?** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Yufei He, Yuexin Li, Jiaying Wu, Yuan Sui, Yulin Chen, Bryan Hooi*  
   [[pdf](https://www.arxiv.org/abs/2502.12206)]

5. **Tell me about yourself: LLMs are aware of their learned behaviors.** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Jan Betley, Xuchan Bao, Martín Soto, Anna Sztyber-Betley, James Chua, Owain Evans*  
   [[pdf](https://arxiv.org/abs/2501.11120)]

6. **Utility Engineering: Analyzing and Controlling Emergent Value Systems in AIs.** [2025] ![](https://img.shields.io/badge/Instrumental-purple)  
   *Mantas Mazeika, Xuwang Yin, Rishub Tamirisa, Jaehyuk Lim, Bruce W. Lee, Richard Ren, Long Phan, Norman Mu, Adam Khoja, Oliver Zhang, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2502.08640)]

---

## Adversarial Robustness

1. **Poisoning Language Models During Instruction Tuning.** [2023] ![](https://img.shields.io/badge/Security-red)  
   *Alexander Wan, Eric Wallace, Sheng Shen, Dan Klein*  
   [[pdf](https://arxiv.org/abs/2305.00944)]

2. **Are aligned neural networks adversarially aligned?** [2023] ![](https://img.shields.io/badge/Security-red)  
   *Nicholas Carlini, Milad Nasr, Christopher A. Choquette-Choo, Matthew Jagielski, Irena Gao, Anas Awadalla, Pang Wei Koh, Daphne Ippolito, Katherine Lee, Florian Tramer, Ludwig Schmidt*  
   [[pdf](https://arxiv.org/abs/2306.15447)]

3. **Universal and Transferable Adversarial Attacks on Aligned Language Models.** [2023] ![](https://img.shields.io/badge/Security-red)  
   *Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson*  
   [[pdf](https://arxiv.org/abs/2307.15043)]

4. **Jailbroken: How Does LLM Safety Training Fail?** [2023] ![](https://img.shields.io/badge/Security-red)  
   *Alexander Wei, Nika Haghtalab, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2307.02483)]

5. **Backdoor Defense, Learnability and Obfuscation.** [2024] ![](https://img.shields.io/badge/Security-red)  
   *Paul Christiano, Jacob Hilton, Victor Lecomte, Mark Xu*  
   [[pdf](https://arxiv.org/abs/2409.03077)]

6. **AI Control: Improving Safety Despite Intentional Subversion.** [2024] ![](https://img.shields.io/badge/General-blue)  
   *Ryan Greenblatt, Buck Shlegeris, Kshitij Sachan, Fabien Roger*  
   [[pdf](https://arxiv.org/abs/2312.06942)]

7. **Many-shot jailbreaking.** [2024] ![](https://img.shields.io/badge/Security-red)  
   *Anthropic*  
   [[pdf](https://www.anthropic.com/research/many-shot-jailbreaking)]

8. **Constitutional Classifiers: Defending against Universal Jailbreaks across Thousands of Hours of Red Teaming.** [2025] ![](https://img.shields.io/badge/Evaluation-green)  
   *Mrinank Sharma, Meg Tong, Jesse Mu, Jerry Wei, Jorrit Kruthoff, Scott Goodfriend, Euan Ong, Alwin Peng, Raj Agarwal, Cem Anil, Amanda Askell, Nathan Bailey, Joe Benton, Emma Bluemke, Samuel R. Bowman, Eric Christiansen, Hoagy Cunningham, Andy Dau, Anjali Gopal, Rob Gilson, Logan Graham, Logan Howard, Nimit Kalra, Taesung Lee, Kevin Lin, Peter Lofgren, Francesco Mosconi, Clare O'Hara, Catherine Olsson, Linda Petrini, Samir Rajani, Nikhil Saxena, Alex Silverstein, Tanya Singh, Theodore Sumers, Leonard Tang, Kevin K. Troy, Constantin Weisser, Ruiqi Zhong, Giulio Zhou, Jan Leike, Jared Kaplan, Ethan Perez*  
   [[pdf](https://arxiv.org/abs/2501.18837)]

9. **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training.** [2024] ![](https://img.shields.io/badge/Security-red)  
   *Evan Hubinger, Carson Denison, Jesse Mu, Mike Lambert, Meg Tong, Monte MacDiarmid, Tamera Lanham, Daniel M. Ziegler, Tim Maxwell, Newton Cheng, Adam Jermyn, Amanda Askell, Ansh Radhakrishnan, Cem Anil, David Duvenaud, Deep Ganguli, Fazl Barez, Jack Clark, Kamal Ndousse, Kshitij Sachan, Michael Sellitto, Mrinank Sharma, Nova DasSarma, Roger Grosse, Shauna Kravec, Yuntao Bai, Zachary Witten, Marina Favaro, Jan Brauner, Holden Karnofsky, Paul Christiano, Samuel R. Bowman, Logan Graham, Jared Kaplan, Sören Mindermann, Ryan Greenblatt, Buck Shlegeris, Nicholas Schiefer, Ethan Perez*  
   [[pdf](https://arxiv.org/abs/2401.05566)]

---

## Debate

1. **AI safety via debate.** [2018] ![](https://img.shields.io/badge/Alignment-brightgreen)  
   *Geoffrey Irving, Paul Christiano, Dario Amodei*  
   [[pdf](https://arxiv.org/abs/1805.00899)]

2. **Debating with More Persuasive LLMs Leads to More Truthful Answers.** [2024] ![](https://img.shields.io/badge/Honesty-orange)  
   *Akbir Khan, John Hughes, Dan Valentine, Laura Ruis, Kshitij Sachan, Ansh Radhakrishnan, Edward Grefensthe, Samuel R. Bowman, Tim Rocktäschel, Ethan Perez*  
   [[pdf](https://arxiv.org/abs/2402.06782)]

---

## Honesty

1. **Discovering Latent Knowledge in Language Models Without Supervision.** [2022] ![](https://img.shields.io/badge/Honesty-orange)  
   *Collin Burns, Haotian Ye, Dan Klein, Jacob Steinhardt*  
   [[pdf](https://arxiv.org/abs/2212.03827)]

2. **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model.** [2023] ![](https://img.shields.io/badge/Honesty-orange)  
   *Kenneth Li, Oam Patel, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg*  
   [[pdf](https://arxiv.org/abs/2306.03341)]

3. **How to Catch an AI Liar: Lie Detection in Black-Box LLMs by Asking Unrelated Questions.** [2023] ![](https://img.shields.io/badge/Honesty-orange)  
   *Lorenzo Pacchiardi, Alex J. Chan, Sören Mindermann, Ilan Moscovitz, Alexa Y. Pan, Yarin Gal, Owain Evans, Jan Brauner*  
   [[pdf](https://arxiv.org/abs/2309.15840)]

---

## Chain-of-thought Faithfulness

1. **Learning to Give Checkable Answers with Prover-Verifier Games.** [2021] ![](https://img.shields.io/badge/CoT-teal)  
   *Cem Anil, Guodong Zhang, Yuhuai Wu, Roger Grosse*  
   [[pdf](https://arxiv.org/abs/2108.12099)]

2. **Faithful Chain-of-Thought Reasoning.** [2023] ![](https://img.shields.io/badge/CoT-teal)  
   *Qing Lyu, Shreya Havaldar, Adam Stein, Li Zhang, Delip Rao, Eric Wong, Marianna Apidianaki, Chris Callison-Burch*  
   [[pdf](https://arxiv.org/abs/2301.13379)]

3. **Measuring Faithfulness in Chain-of-Thought Reasoning.** [2023] ![](https://img.shields.io/badge/CoT-teal)  
   *Tamera Lanham, Anna Chen, Ansh Radhakrishnan, Benoit Steiner, Carson Denison, Danny Hernandez, Dustin Li, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Karina Nguyen, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Robin Larson, Sam McCandlish, Sandipan Kundu, Saurav Kadavath, Shannon Yang, Thomas Henighan, Timothy Maxwell, Timothy Telleen-Lawton, Tristan Hume, Zac Hatfield-Dodds, Jared Kaplan*  
   [[pdf](https://arxiv.org/abs/2307.13702)]

4. **Prover-Verifier Games Improve Legibility of LLM Outputs.** [2024] ![](https://img.shields.io/badge/CoT-teal)  
   *Jan Hendrik Kirchner, Yining Chen, Harri Edwards, Jan Leike, Nat McAleese, Yuri Burda*  
   [[pdf](https://arxiv.org/abs/2407.13692)]

---

## Weak-to-strong Generalization

1. **Weak-to-Strong Generalization: Eliciting Strong Capabilities With Weak Supervision.** [2023] ![](https://img.shields.io/badge/General-blue)  
   *Collin Burns, Pavel Izmailov, Jan Hendrik Kirchner, Bowen Baker, Leo Gao, Leopold Aschenbrenner, Yining Chen, Adrien Ecoffet, Manas Joglekar, Jan Leike, Ilya Sutskever, Jeff Wu*  
   [[pdf](https://arxiv.org/abs/2312.09390)]

2. **Theoretical Analysis of Weak-to-Strong Generalization.** [2024] ![](https://img.shields.io/badge/General-blue)  
   *Hunter Lang, David Sontag, Aravindan Vijayaraghavan*  
   [[pdf](https://arxiv.org/abs/2405.16043)]

3. **Weak-to-Strong Generalization beyond Accuracy: a Pilot Study in Safety, Toxicity, and Legal Reasoning.** [2024] ![](https://img.shields.io/badge/General-blue)  
   *Ruimeng Ye, Yang Xiao, Bo Hui*  
   [[pdf](https://arxiv.org/abs/2410.12621)]

---

## Mechanistic Interpretability

1. **A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity.** [2024] ![](https://img.shields.io/badge/Interpretability-yellow)  
   *Andrew Lee, Xiaoyan Bai, Itamar Pres, Martin Wattenberg, Jonathan K. Kummerfeld, Rada Mihalcea*  
   [[pdf](https://arxiv.org/abs/2401.01967)]

2. **Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet.** [2024] ![](https://img.shields.io/badge/Interpretability-yellow)  
   *Adly Templeton, Tom Conerly, Jonathan Marcus, Jack Lindsey, Trenton Bricken, Brian Chen, Adam Pearce, Craig Citro, Emmanuel Ameisen, Andy Jones, Hoagy Cunningham, Nicholas L Turner, Callum McDougall, Monte MacDiarmid, Alex Tamkin, Esin Durmus, Tristan Hume, Francesco Mosconi, C. Daniel Freeman, Theodore R. Sumers, Edward Rees, Joshua Batson, Adam Jermyn, Shan Carter, Chris Olah, Tom Henighan*  
   [[pdf](https://transformer-circuits.pub/2024/scaling-monosemanticity/)]

---

## Evaluation

1. **Red Teaming Language Models with Language Models.** [2022] ![](https://img.shields.io/badge/Evaluation-green)  
   *Ethan Perez, Saffron Huang, Francis Song, Trevor Cai, Roman Ring, John Aslanides, Amelia Glaese, Nat McAleese, Geoffrey Irving*  
   [[pdf](https://arxiv.org/abs/2202.03286)]

2. **Model Evaluation for Extreme Risks.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Toby Shevlane, Sebastian Farquhar, Ben Garfinkel, Mary Phuong, Jess Whittlestone, Jade Leung, Daniel Kokotajlo, Nahema Marchal, Markus Anderljung, Noam Kolt, Lewis Ho, Divya Siddarth, Shahar Avin, Will Hawkins, Been Kim, Iason Gabriel, Vijay Bolina, Jack Clark, Yoshua Bengio, Paul Christiano, Allan Dafoe*  
   [[pdf](https://arxiv.org/abs/2305.15324)]

3. **XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models.** [2023] ![](https://img.shields.io/badge/Evaluation-green)  
   *Paul Röttger, Hannah Rose Kirk, Bertie Vidgen, Giuseppe Attanasio, Federico Bianchi, Dirk Hovy*  
   [[pdf](https://arxiv.org/abs/2308.01263)]

4. **Safetywashing: Do AI Safety Benchmarks Actually Measure Safety Progress?** [2024] ![](https://img.shields.io/badge/Evaluation-green)  
   *Richard Ren, Steven Basart, Adam Khoja, Alice Gatti, Long Phan, Xuwang Yin, Mantas Mazeika, Alexander Pan, Gabriel Mukobi, Ryan H. Kim, Stephen Fitz, Dan Hendrycks*  
   [[pdf](https://arxiv.org/abs/2407.21792)]

---

## Contribution

### Other Contributors

*List of contributors will be added here.*

### Contributing to this Paper List

- First, decide which category your paper belongs to.
- Next, follow the format used above—ensure there is an empty line between the title and the authors, and include the appropriate keyword tags and PDF link.
- Finally, submit a pull request with your updates.

**Don't worry if you don't nail every detail on the first try—we will help refine and update them.** Thank you for contributing to the AI safety and alignment community!
