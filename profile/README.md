# TNO MPC Lab

The TNO MPC Lab is a cross-project initiative initiated to improve the overall quality, generality, and reusability in the development of secure Multi-Party Computation (MPC) solutions developed in the numerous (past, ongoing, and future) TNO projects that involve MPC. It consists of generic software components, procedures, and functionalities developed and maintained on a regular basis to facilitate and aid in the development of MPC solutions. The lab strives to boost the development of new protocols and solutions, and decrease time-to-market.

## MPC

[MPC](https://www.tno.nl/en/focus-areas/information-communication-technology/roadmaps/data-sharing/secure-multi-party-computation/) is a subfield of cryptography and an umbrella term consisting of cryptographic techniques that aim to jointly perform computations in a privacy-preserving manner. More precisely, MPC strives to created methods to enable the joint computation of a function over inputs that are distributed among different parties whilst keeping the inputs private. Parties want to ‘learn’ the results of a joint computation without having to share, reveal, or publish, the data that is needed to perform such a computation.

For example, by applying MPC technology, distributed datasets can be securely utilised in the [training](https://github.com/TNO-MPC/mpyc.secure_learning/) and evaluation of [AI](https://appl-ai-tno.nl/technologies/multi-party-computation) and machine learning models.

## Open Source

We believe that opening up the mysteries of advanced cryptography benefits society. Conform the Kerckhoff’s principle the security of the developed MPC solutions does not rely on secrecy but on mathematical principles. The TNO MPC Lab supports Kerckhoff’s principle by publishing open source as a way to validate the theoretical/mathematical correctness of cryptographic protocols as well as their implementations.

The published MPC building blocks and complete solutions can be found on [GitHub](https://github.com/TNO-MPC/) and [PyPI](https://pypi.org/search/?q=%22tno.mpc%22). The mostly used license for TNO MPC lab components is the Apache License, Version 2.0. This allows for easy adoption and flexible usage without enforcing a specific license to (end-)users and contributors of the codebase. We are always open to questions on, suggestions for and contributions to our codebase.

![MPC Lab collaboration](/profile/assets/MPC_Lab_collaboration.svg)