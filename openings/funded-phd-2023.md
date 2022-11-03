---
layout: page
description: >
  Opening for one PhD student to conduct research in algorithms 
  for parallel accelerators with Dr. Sean Chester at the
  University of Victoria (UVic) in Victoria, BC, Canada. 
heading: One Funded PhD Position, Fall 2023
permalink: /openings/funded-phd-fall-2023
seo:
  name: Sean Chester
  links: ["https://plus.google.com/+SeanChester",
  "https://www.linkedin.com/in/seanchester/",
  "https://www.uvic.ca/ecs/computerscience/people/faculty/profiles/chester-sean.php"]
---

_We have one opening for a PhD candidate to begin by September 2023. Applications will be reviewed in early December 2022._

### Designing Algorithms for In-Memory Processing

The year 2003 marked a critical pivot in computing: processor clock speeds stopped accelerating at the exponential pace that had been observed since the 70's. Heat dissipation, power consumption, and current leakage all transpired to make it uneconomical to continue increasing processor frequencies, leading chip manufacturers to focus on concurrency [(Sutter, 2005)](http://www.gotw.ca/publications/concurrency-ddj.htm). However, by that time, compute speed had already far outstripped the speed of memory by a factor of about 240×; most applications therefore are throttled by stalls waiting for memory accesses in what has become known as the "Memory Wall" [(Drepper, 2007)](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf). Efficient applications today, therefore, need to both leverage concurrency and minimise memory stalls in order to keep energy consumption low and performance high.

A recent innovation is _in-memory processing_, such as [the UPMEM DRAM Processing Unit (DPU)](https://www.upmem.com/technology/) and [Samsung AXDIMM](https://youtu.be/gzrWlAYOIu0), where some arithmetic logic is moved directly into the memory controller to limit data movement. Done well, this can avoid altogether many data transfers between the DRAM circuit and the processor. The implications for application design of such an architecture are obviously not yet well understood, but they clearly stress standard assumptions like the RAM model of computation.

In this position, you will explore memory-centric computing architectures from an algorithm design perspective. Through the process of designing novel, competitive algorithms for in-memory processing, you will try to identify themes that could inform a new model of computation that reflects the uniqueness of these modern accelerators.

### Candidate Profile

If you apply to this position, please try to position your strengths and/or interests with respect to the following:

 * Can you explain clearly why we need in-memory processors?
 * Can you develop software that manages memory resources effectively?
 * Can you design novel parallel algorithms for environments with asynchronicity or concurrency and prove that they are correct?

Remember, I do not expect that anyone is an expert on this topic yet; that's why the research is needed! Just put your best foot forward. Applicants without a master's degree are also invited to apply, but need to present a particularly strong case for being able to generate new scientific knowledge within this field and may be offered a position as a thesis-based master's student instead.

### Application Process

Formally, you must follow [the process outlined on the department website](https://www.uvic.ca/ecs/computerscience/graduate/applying/index.php).

Informally, you should also:
  - contact me directly by email, positioning yourself with respect to the three questions above that characterise a successful candidate for this position
  - in the first full week of December (week number 49), I will contact shortlisted candidates who have the strongest evidence that they fit the profile above and meet the formal requirements of the university
  - in the second full week of December (week number 50), we will conduct technical interviews with the shortlisted candidates
  - in the third full week of December (week number 51), we will conduct second round interviews and extend an offer
