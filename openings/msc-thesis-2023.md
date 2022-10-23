---
layout: page
description: >
  Opening for one self-funded thesis-based MSc student
  to conduct research in algorithms 
  for parallel accelerators with Dr. Sean Chester at the
  University of Victoria (UVic) in Victoria, BC, Canada. 
heading: One Self-funded Thesis-Based MSc Position, Fall 2023
permalink: /openings/msc-thesis-fall-2023
seo:
  name: Sean Chester
  links: ["https://plus.google.com/+SeanChester",
  "https://www.linkedin.com/in/seanchester/",
  "https://www.uvic.ca/ecs/computerscience/people/faculty/profiles/chester-sean.php"]
---

_We have one opening for a self-funded thesis-based MSc candidate to begin by September 2023. Applications will be reviewed in early December 2022._

### Parallel Algorithms for Developing Word Representations

In junior-level Computer Science, we learn that a string of text can be represented by an array of characters and rendered into text based on an encoding, such as ASCII or UTF8. This is a bit limited, however, because the similarity of text is modelled only by the length of the common prefix: i.e., "dog" is more like "dogmatic" than it is like "puppy". The field of Natural Language Processing (NLP) has done much better at coming up with numeric representations of words, such as the recent innovation of [word embeddings](https://arxiv.org/abs/1310.4546) or [Brown clustering](https://sean-chester.github.io/assets/preprints/generalised-brown.pdf). Rather than represent a word with a single id, it is represented with a vector, trained by an unsupervised machine learning algorithm, such that words with similar semantics and syntactic function have similar vector representations. As a result, words that are very similar will be nearby in (say, three-hundred-dimensional) space.

Meanwhile, many matrix-based algorithms are quite amenable to parallelisation with [general purpose computing on a graphics processing card (GPGPU)](https://developer.nvidia.com/gpugems/gpugems2/part-iv-general-purpose-computation-gpus-primer). The Brown clustering work of Dr. Chester and colleagues does not take advantage of a GPU during the training phase, nor some as-yet-unpublished algorithmic ideas. In this project, you would try to develop a novel parallel algorithm for a GPU architecture to expose massive data-level parallelism and dramatically improve training time for this particular task.

### Candidate Profile

If you apply to this position, please try to position your strengths and/or interests with respect to the following:

 * Can you explain clearly what challenges confront developers who want to design parallel algorithms?
 * Can you develop software that manages memory resources effectively?
 * Can you design algorithms to solve a problem and prove that they are correct?


### Application Process

Formally, you must follow [the process outlined on the department website](https://www.uvic.ca/ecs/computerscience/graduate/applying/index.php).

Informally, you should also:
  - contact me directly by email, positioning yourself with respect to the three questions above that characterise a successful candidate for this position
  - in the first full week of December (week number 49), I will contact shortlisted candidates who have the strongest evidence that they fit the profile above and meet the formal requirements of the university
  - in the second full week of December (week number 50), we will conduct technical interviews with the shortlisted candidates
  - in the third full week of December (week number 51), we will conduct second round interviews and extend an offer

### What is a Thesis-Based MSc?

It is important to note that at the University of Victoria, we have [two options for master's degrees](https://www.uvic.ca/ecs/computerscience/graduate/masters/msc-programs/index.php): a _thesis_ option and a _project_ option.

The _thesis_ option is focused on a novel two-year scientific research investigation that culminates in a thesis that you must defend in front of a committee to graduate. The coursework is auxiliary and consists of only five courses that are complementary to your concurrent research. The thesis option is necessary if you intend to pursue further graduate studies, such as a PhD, and _highly_ advised if you wish to pursue a career in research and development (R&D).

The _project_ option requires eight graduate-level courses and a lighter one- or two-semester research project. Generally, it involves less interaction with the supervisor as less research guidance and mentorship is required until the final two semesters.

Students in both options are encouraged to spend one or two four-month semesters in paid research internships or work placements to improve post-graduation employment prospects and to earn income to help cover study expenses. They are also encouraged to take part-time positions as teaching assistants to provide additional income.
