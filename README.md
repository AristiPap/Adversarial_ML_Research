# Adversarial Attacks and Defences: Threats and Prospects Analysis 
Undergraduate Thesis on Adversarial Attacks and Defences. This repo is consisted of 
- Research papers
- Coding implementation of various attack and defence methods described in the thesis
- Results documented during the execution of some of the attacks/defences
- Thesis document describing the research process and findings along with experimental results

## General 
Data in the 21st Century is like Oil in the 18th Century: an immensely, untapped valuable asset. Like oil, for those who see Data’s fundamental value and learn to extract and use it there will be huge rewards. We’re in a digital economy where data is more valuable than ever. It’s the key to the smooth functionality of everything from the government to local companies. Without it, progress would halt. According to estimates, all data in 2022 could
reach 44 zettabytes. Nowadays, machine learning models in computer vision are used
in many real-world applications, like self-driving cars, face recognition, cancer diagnosis,
or even in next-generation shops in order to track which products customers take off the
shelf so their credit card can be charged when leaving.The increasing accuracy of these
machine learning systems is quite impressive, so it naturally led to a veritable flood of ap-
plications using them. Although the mathematical foundations behind them were already
studied a few decades ago, the relatively recent advent of powerful GPUs gave research-
ers the computing power necessary to experiment and build complex machine learning
systems. Today, state-of-the art models for computer vision are based on deep neural
networks with up to several million parameters, and they rely on hardware that was not
available just a decade ago.\\
One of the ways privacy could be breached, is by exploiting inherit vulnerabilities found
in the structure and nature of many ML models a, deployed in public. This massive data
evolution, has created many data breaches and security issues that have not yet been re-
solved. Example (and point of the whole thesis) of such exploitations are the adversarial
attacks.As of today, attacking a machine learning model is easier than defending it. State-
of-the art models deployed in real-world applications are easily fooled by adversarial ex-
amples if no defense strategy is employed, opening the door to potentially critical security
issues. For example, Deep neural networks (DNN) have achieved state of the art perform-
ance for image classification tasks. However, state of the art DNNs have vulnerabilities
to adversarial attacks. They are susceptible to small perturbations that are made in a
meaningful way, which is not random noise.
Due to this gap in DNNs and inherited the risk of breaching privacy has motivated many
senior coders and scientists to try and come up with new defences.The attacker crafts the
attack, exploiting all the information they have about the model.So how a hybrid type of
training or having more robust models could help defend our networks? How easily can
we generate hybrid attacks and is it possible to defend against them all?
These are some of the questions, we are trying to answer in this Thesis.

## Source Code
 It provides basic implementations of adversarial attacks and defences using python classes (keras and tesorflow used for multiple of the attacks).
 Also you will find the implementation of the hybrid version of the boundary attack that we created using keras Resnet model (also implemented with cnn class)

### TODO
- [ ] Optimize code ,check the accuracy and success rate of our attacks if we add bias
- [ ] Further research on defence methods and work on improving existing version of defence algorithm in the thesis code

## Links:
- Thesis Publication: https://pergamos.lib.uoa.gr/uoa/dl/frontend/el/browse/3232946

## Contributors
- Supervisor: [Kostas Chatzikokolakis](https://www.chatzi.org/)
