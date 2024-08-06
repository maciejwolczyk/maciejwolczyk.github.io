---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<h1 id="aboutme"> About me </h1>

I'm a postdoc at [IDEAS NCBR](https://ideas-ncbr.pl/en/) in the Sequential Decision Making group led by [Prof. Piotr Miłoś](https://www.mimuw.edu.pl/~pmilos/). I'm interested primarily in:
- Sequential Decision Making -- how to use models such as RNNs, transformers, and state-space models in RL and beyond.
- Fine-tuning RL models -- how to harness the power of foundation models in RL by fine-tuning them online.
- Adaptation in foundation models -- how to use LLMs/VLMs in completely new decision-making scenarios.


<h1 id="news"> News </h1>
- **(July 2024)** - We talked about work on forgetting in RL fine-tuning at UCL Dark seminar. It was a great experience! You can see [the recording here](https://www.youtube.com/watch?v=PzcJeRglfQI).
- **(July 2024)** - Our [paper on Adaptive Visual Exploration](https://arxiv.org/abs/2404.03482) was accepted at ECCV 2024. See you soon in Milan!
- **(June 2024)** - Check out our [workshop paper](https://arxiv.org/abs/2406.08423) on mixing and retrieving states in State-Space Models! To be presented at the Next Generation Sequence Models workshop at ICML 2024.
- **(June 2024)** - Bartek Cupiał's and mine [NetHack bug-hunting story](https://twitter.com/CupiaBart/status/1793930355617259811) went viral on Twitter with over 2M views, got featured on [ArsTechnica](https://arstechnica.com/gaming/2024/06/what-kind-of-bug-would-make-machine-learning-suddenly-40-worse-at-nethack/) and [HackerNews](https://news.ycombinator.com/item?id=40583965), and even [translated into Japanese](https://gigazine.net/news/20240527-bug-by-full-moon/).
- **(May 2024)** I'm very proud to have received the [FNP Start scholarship](https://ideas-ncbr.pl/maciej-wolczyk-i-piotr-kicki-wsrod-najlepszych-mlodych-naukowcow-w-polsce/) for talented young researchers!
- **(May 2024)** Our [paper on the issue of forgetting in RL fine-tuning](https://arxiv.org/abs/2402.02868) was accepted as a spotlight at ICML 2024.
- **(March 2024)** - I'm very proud to co-organize the [workshop on the Next Generation of Sequential Modelling Architectures at ICML 2024](https://sites.google.com/view/ngsmworkshop).
- **(February 2024)** I defended my PhD thesis with distinction! Huge thanks to my supervisor, prof. Jacek Tabor and everyone who helped me along the way.
- **(January 2024)** A [work on compositional generalization and modularity](https://openreview.net/forum?id=H98CVcX1eh) I helped with was accepted at ICLR 2024. Congrats to the whole team!
- **(October 2023)**  Started work as a postdoc at IDEAS NCBR!
- **(January 2023)** I had the chance to present my work on continual reinforcement learning at [the Warsaw.ai meetup](https://youtu.be/p_gHN2cwoYQ?si=d-DzahxY9St2kXN2&t=1540).
- **(December 2022)** I presented our work on [Disentangling Transfer in Continual Reinforcement Learning](https://arxiv.org/abs/2209.13900) at NeurIPS 2022.
- **(July 2022)** [MLSS^N](https://mlss.mlinpl.org/) I co-organized was terrific! Many thanks to all lecturers, co-organizers and participants. Check out [the lectures](https://www.youtube.com/playlist?list=PL3aJIq_dM1xUpQxVgP4AySZAJtdVx-2qI)!
- **(May 2022)** Our paper on [continual learning with weight interval regularization](https://arxiv.org/abs/2206.07996) has been accepted to ICML 2022 as a short presentation.
- **(March 2022)** Our [workshop on Dynamic Neural Networks](https://dynn-icml2022.github.io/) has been accepted to ICML 2022. See you in Baltimore!
- **(March 2022)** Started a research internship with [João Sacramento](http://www.joaosacramento.com/) at ETH Zurich!
- **(December 2021)** [PluGeN](https://arxiv.org/abs/2109.09011), our paper on introducing supervision to pre-trained, was accepted to AAAI 2022.
- **(September 2021)** Two of our papers, [Zero Time Waste](https://arxiv.org/abs/2106.05409) and [Continual World](https://arxiv.org/abs/2105.10919) were accepted to the NeurIPS 2021 conference as poster presentations.
- **(September 2021)** A paper on [closed-loop imitation learning](https://arxiv.org/abs/2109.13333) for self-driving cars, which I worked on during my internship at Woven Planet, was accepted to CORL 2021 conference.
- **(April 2021)** Started my internship at Woven Planet Level-5 (previously Lyft Level-5), working on imitation learning for planning in self-driving cars.


<h1 id="publications"> Selected publications </h1>
<div style="margin-bottom: 1em">
    <img src="/images/finetuning_rl.png" alt="Illustration of forgetting in RL" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>Fine-tuning Reinforcement Learning Models is Secretly a Forgetting Mitigation Problem</strong> <br/>
        <b>Maciej Wołczyk</b>*, Bartłomiej Cupiał*, Mateusz Ostaszewski, Michał Bortkiewicz, Michał Zając, Razvan Pascanu, Łukasz Kuciński, Piotr Miłoś<br/>
        <b>ICML 2024 Spotlight</b> <br/>
        <a href="https://arxiv.org/abs/2402.02868">[Paper]</a><a href="https://github.com/BartekCupial/finetuning-RL-as-CL">[Code]</a><a href="https://sites.google.com/view/finetune-rl-without-forgetting">[Webpage]</a>
    </div>
</div>


<div style="margin-bottom: 1em">
    <img src="/images/adaglimpse.png" alt="Scheme of the AdaGlimpse methods" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>AdaGlimpse: Active Visual Exploration with Arbitrary Glimpse Position and Scale
</strong> <br/>
        Adam Pardyl, Michał Wronka, <b>Maciej Wołczyk</b>, Kamil Adamczewski, Tomasz Trzciński, Bartosz Zieliński <br/>
        <b>ECCV 2024</b> <br/>
        <a href="https://arxiv.org/abs/2404.03482">[Paper]</a><a href="https://github.com/apardyl/AdaGlimpse">[Code]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/disentangling_transfer.png" alt="Example transfer matrix from the paper" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>Disentangling Transfer in Continual Reinforcement Learning</strong> <br/>
        <b>Maciej Wołczyk</b>*, Michał Zając*, Razvan Pascanu, Łukasz Kuciński, Piotr Miłoś<br/>
        <b>NeurIPS 2022</b> <br/>
        <a href="https://arxiv.org/abs/2209.13900">[Paper]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/intercontinet.png" alt="General idea of InterContiNet" style="max-height: 200px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>Continual Learning with Guarantees via Weight Interval Constraints </strong> <br/>
        <b>Maciej Wołczyk</b>*, Karol Piczak*, Bartosz Wójcik, Łukasz Pustelnik, Paweł Morawiecki, Jacek Tabor, Tomasz Trzciński, Przemysław Spurek <br/>
        <b>ICML 2022</b> <br/>
        <a href="https://arxiv.org/abs/2206.07996">[Paper]</a><a href="https://github.com/gmum/InterContiNet">[Code]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/plugen.png" alt="Scheme of PluGeN" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>PluGeN: Multi-Label Conditional Generation From Pre-Trained Models</strong> <br/>
        <b>Maciej Wołczyk</b>*, Magdalena Proszewska*, Łukasz Maziarka, Maciej Zięba, Patryk Wielopolski, Rafał Kurczab, Marek Śmieja <br/>
        <b>AAAI 2022</b> <br/>
        <a href="https://arxiv.org/abs/2109.09011">[Paper]</a><a href="https://github.com/gmum/plugen">[Code]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/ztw.png" alt="Scheme of the Zero Time Waste model" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>Zero Time Waste: Recycling Predictions in Early Exit Neural Networks</strong> <br/>
        <b>Maciej Wołczyk</b>*, Bartosz Wójcik*, Klaudia Bałazy, Igor Podolak, Jacek Tabor, Marek Śmieja, Tomasz Trzciński <br/>
        <b>NeurIPS 2021</b> <br/>
        <a href="https://arxiv.org/abs/2106.05409">[Paper]</a> <a href="https://github.com/gmum/Zero-Time-Waste">[Code]</a>
    </div>
</div>


<div style="margin-bottom: 1em">
    <img src="/images/continual_world.png" alt="CW20 from Continual World" style="max-height: 250px;display: block;vertical-align: middle;padding: 5px;margin-left: auto;margin-right: auto;">
    <div style="display: block; padding: 10px; vertical-align: middle; width: 100%">
        <strong>Continual World: A Robotic Benchmark For Continual Reinforcement Learning</strong> <br/>
        <b>Maciej Wołczyk</b>*, Michał Zając*, Razvan Pascanu, Łukasz Kuciński, Piotr Miłoś <br/>
        <b>NeurIPS 2021</b> <br/>
        <a href="https://github.com/awarelab/continual_world">[Webpage]</a> <a href="https://arxiv.org/abs/2105.10919">[Paper]</a> <a href="https://github.com/awarelab/continual_world">[Code]</a>
    </div>
</div>
