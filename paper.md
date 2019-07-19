---
title: 'FAUMachine Fault Injection Clusters'
tags:
  - example
  - tags
  - for the paper
authors:
 - name: Tapasweni Pathak
   orcid: 0000-0001-6286-3088
   affiliation: "0"
Date: 19 July 2019
bibliography: paper.bib
---

# Summary

We are showcasing an implementation where FAUMachine clusters are run distributively.
We are publishing a package for implementing FAUMachine clusterts.  FAUMachine
is a linux based fault injection virtual machine, with the package you can run multiple cluster
with the best usage of the memory. The user can inject memory flips in any pid
runningo on top of FAUMachine, say a byte flip. The worst byte flip are those
that go unnoticed until they have corrupted a lot of information. You can take that
whole machine down. Say from sched.c, BUG_ON(in_interrupt()) implemented w/ a
conditional in machine. This is basically generating things with BAD RAM. We have
researched on multiple experiments and exposing using this experimental paper.
