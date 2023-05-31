---
layout: page
permalink: /research/
title: research
nav: false
---

I'm currently employed on the research project [TAIGER: Training and Guiding AI Agents with Ethical Rules](https://taiger.logic.at/), funded by the Vienna Science and Technology Fund WWTF.

My current interests lie broadly in hybrid AI; that is, the integration of logic with machine learning. Most of my work so far has involved developing methods for combining reinforcement learning with reasoning engines for deontic logic, and I have a continued interest in using logics for normative reasoning for implementing normative behaviour in reinforcement learning agents. My interests extend more generally to constrained reinforcement learning, logics for normative reasoning, explainable AI, and ethical AI.

### the normative supervisor

In most of my papers I have made use of a module I call the 'normative supervisor'; it is a normative reasoning module that can interface with reinforcement learning agents, taking environmental data from an agent, along with a set of norms, and using a theorem prover (the defeasible logic theorem prover [SPINdle](http://www.governatori.net/papers/2009/ruleml09spindle.pdf)) to determine which actions in the agent's arsenal are compliant. 

You can find an implementation of the normative supervisor [here](https://github.com/lexeree/normative-player-characters), along with an implementation of a DDL-to-LTL synthesis algorithm that utilizes it. Please note that the module is still under active development.
