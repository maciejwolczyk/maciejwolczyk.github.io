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

I'm a research engineer at [IDEAS NCBR](https://ideas-ncbr.pl/en/) under supervision of [Prof. Piotr Miłoś](https://www.mimuw.edu.pl/~pmilos/). My main research interests are centered around the issue of efficiency in deep learning, highlighting the following questions in particular:
- Continual Learning -- how to remember the past and reuse it efficiently when learning from a stream of data.
- Reinforcement Learning  -- how to increase the sample efficiency and leverage models pre-trained on offline data.
- Conditional Computation  -- how to adapt the computing power of the model to a given example.
- Generative Models -- how to perform weakly supervised conditional generation and adapt existing models for conditional generation.


<h1 id="news"> News </h1>
- **(October 2023)**  Started work as a research engineer at IDEAS NCBR! Hopefully, the job title will change to "post-doc" soon :)
- **(June 2023)**  Submitted my PhD thesis, awaiting reviews! Went on a break to recharge my batteries.
- **(June 2023)** Our paper on [world models in continual reinforcement learning](https://arxiv.org/abs/2211.15944) was accepted to CoLLAs 2023.
- **(January 2023)** I had the chance to present my work on continual reinforcement learning at [the Warsaw.ai meetup](https://youtu.be/p_gHN2cwoYQ?si=d-DzahxY9St2kXN2&t=1540).
- **(November 2022)** I will be at NeurIPS to present our work on [Disentangling Transfer in Continual Reinforcement Learning](https://arxiv.org/abs/2209.13900). If you'll also be there and you want to grab a coffee together, send me an e-mail or a Twitter DM!
- **(July 2022)** [MLSS^N](https://mlss.mlinpl.org/) was terrific! Many thanks to all lecturers, co-organizers and participants. Check out [the lectures](https://www.youtube.com/playlist?list=PL3aJIq_dM1xUpQxVgP4AySZAJtdVx-2qI)!
- **(May 2022)** Our paper on [continual learning with weight interval regularization](https://arxiv.org/abs/2206.07996) has been accepted to ICML 2022 as a short presentation.
- **(March 2022)** Our [workshop on Dynamic Neural Networks](https://dynn-icml2022.github.io/) has been accepted to ICML 2022. See you in Baltimore!
- **(March 2022)** Started a research internship with [João Sacramento](http://www.joaosacramento.com/) at ETH Zurich!
- **(December 2021)** [PluGeN](https://arxiv.org/abs/2109.09011), our paper on introducing supervision to pre-trained, was accepted to AAAI 2022.
- **(September 2021)** Two of our papers, [Zero Time Waste](https://arxiv.org/abs/2106.05409) and [Continual World](https://arxiv.org/abs/2105.10919) were accepted to the NeurIPS 2021 conference as poster presentations.
- **(September 2021)** A paper on [closed-loop imitation learning](https://arxiv.org/abs/2109.13333) for self-driving cars, which I worked on during my internship at Woven Planet, was accepted to CORL 2021 conference.
- **(April 2021)** Started my internship at Woven Planet Level-5 (previously Lyft Level-5), working on imitation learning for planning in self-driving cars.
- **(August 2020)** Our paper on [conditional semi-supervised generation with mixtures of Gaussians](https://arxiv.org/abs/1906.09333) was published in IEEE Transactions on Neural Networks and Learning Systems. 
- **(July 2020)** Co-organized the [EEML 2020 summer school](https://www.eeml.eu/previous-editions/eeml2020).
- **(October 2019)** Started my PhD at the Jagiellonian University with GMUM.


<h1 id="publications"> Selected publications </h1>
<div style="margin-bottom: 1em">
    <img src="/images/disentangling_transfer.png" alt="Example transfer matrix from the paper" style="width: 30%; display: inline-block; vertical-align: middle; padding: 5px">
    <div style="display: inline-block; padding: 10px; vertical-align: middle; width: 70%">
        <strong>Disentangling Transfer in Continual Reinforcement Learning</strong> <br/>
        <b>Maciej Wołczyk</b>*, Michał Zając*, Razvan Pascanu, Łukasz Kuciński, Piotr Miłoś<br/>
        <b>NeurIPS 2022</b> <br/>
        <a href="https://arxiv.org/abs/2209.13900">[Paper]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/intercontinet.png" alt="General idea of InterContiNet" style="width: 30%; display: inline-block; vertical-align: middle; padding: 5px">
    <div style="display: inline-block; padding: 10px; vertical-align: middle; width: 70%">
        <strong>Continual Learning with Guarantees via Weight Interval Constraints </strong> <br/>
        <b>Maciej Wołczyk</b>*, Karol Piczak*, Bartosz Wójcik, Łukasz Pustelnik, Paweł Morawiecki, Jacek Tabor, Tomasz Trzciński, Przemysław Spurek <br/>
        <b>ICML 2022</b> <br/>
        <a href="https://arxiv.org/abs/2206.07996">[Paper]</a><a href="https://github.com/gmum/InterContiNet">[Code]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/plugen.png" alt="Scheme of PluGeN" style="width: 30%; display: inline-block; vertical-align: middle; padding: 5px">
    <div style="display: inline-block; padding: 10px; vertical-align: middle; width: 70%">
        <strong>PluGeN: Multi-Label Conditional Generation From Pre-Trained Models</strong> <br/>
        <b>Maciej Wołczyk</b>*, Magdalena Proszewska*, Łukasz Maziarka, Maciej Zięba, Patryk Wielopolski, Rafał Kurczab, Marek Śmieja <br/>
        <b>AAAI 2022</b> <br/>
        <a href="https://arxiv.org/abs/2109.09011">[Paper]</a><a href="https://github.com/gmum/plugen">[Code]</a>
    </div>
</div>

<div style="margin-bottom: 1em">
    <img src="/images/ztw.png" alt="Scheme of the Zero Time Waste model" style="width: 30%; display: inline-block; vertical-align: middle; padding: 5px">
    <div style="display: inline-block; padding: 10px; vertical-align: middle; width: 70%">
        <strong>Zero Time Waste: Recycling Predictions in Early Exit Neural Networks</strong> <br/>
        <b>Maciej Wołczyk</b>*, Bartosz Wójcik*, Klaudia Bałazy, Igor Podolak, Jacek Tabor, Marek Śmieja, Tomasz Trzciński <br/>
        <b>NeurIPS 2021</b> <br/>
        <a href="https://arxiv.org/abs/2106.05409">[Paper]</a> <a href="https://github.com/gmum/Zero-Time-Waste">[Code]</a>
    </div>
</div>



<div style="margin-bottom: 1em">
    <img src="/images/continual_world.png" alt="CW20 from Continual World" style="width: 30%; display: inline-block; vertical-align: middle; padding: 5px">
    <div style="display: inline-block; padding: 10px; vertical-align: middle; width: 70%">
        <strong>Continual World: A Robotic Benchmark For Continual Reinforcement Learning</strong> <br/>
        <b>Maciej Wołczyk</b>*, Michał Zając*, Razvan Pascanu, Łukasz Kuciński, Piotr Miłoś <br/>
        <b>NeurIPS 2021</b> <br/>
        <a href="https://github.com/awarelab/continual_world">[Webpage]</a> <a href="https://arxiv.org/abs/2105.10919">[Paper]</a> <a href="https://github.com/awarelab/continual_world">[Code]</a>
    </div>
</div>
