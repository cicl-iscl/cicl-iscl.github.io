---
layout: default
---

This is the course page
for the seminar course
_Challenges in Computational Linguistics_
at the [Department of Linguistics](http://sfs.uni-tuebingen.de),
[University of Tübingen](http://uni-tuebingen.de).

The filed of computational linguistics has a well-established
tradition of "shared tasks" or "challenges" where the participants try
to solve a current problem in the field using a common data set and
a well-defined metric of success. Participation in these tasks is fun
and highly educational as it requires the participants to put all
their knowledge into practice, as well as learning and applying new
methods to the task at hand. The comparison of the participating
systems at the end of the shared task is also a valuable learning
experience, both for the participating individuals and the whole
field.

This course takes its title literally. The students taking the course
are required to participate in a shared task in the field, and solve
it as best as they can. The requirement of the course include
developing a system to solve the problem defined by the shared task,
submitting the results and writing a paper describing the system.

## Requirements

The course requires good programming skills, a working knowledge of
machine learning and NLP, and strong (self) motivation. This typically
means a highly motivated Mater's or advanced Bachelor's student
in computational linguistics or related departments (e.g., computer
science, artificial intelligence, cognitive science). If  you are
unsure, please contact the instructor.

## Shared tasks

In principle, any shared task related to computational linguistics is
acceptable. Here are a few pointers (some point to earlier events):

- [SemEval](http://alt.qcri.org/semeval2020/index.php?id=tasks)
  competitions include a wide range of shared tasks.
- [CoNLL](http://www.conll.org/) hosts regular high-profile shared
  tasks.
- [CLEF](https://clef2020.clef-initiative.eu/) also includes CL/NLP
  related tasks
- [Germeval](https://projects.fzai.h-da.de/iggsa/) shared tasks
  are another option, particularly if you'd like to work on German.
- [VarDial workshops](https://sites.google.com/view/vardial2020) host regular
  shared task related to dialects and closely related languages.
- [NIPS competition track](https://nips.cc/Conferences/2019/CompetitionTrack)
    sometimes include NLP/CL related competitions.

The following workshops hosted (or plan to host) shared tasks.

- [SIGMORPHON](https://sigmorphon.github.io/workshops/)
- [Universal Dependencies Workshop](https://universaldependencies.org/udw20/)
- [Social Media Mining for Health Applications (SMM4H) workshop](https://healthlanguageprocessing.org/smm4h/challenge/)
- [Computational Linguistics and Clinical Psychology Workshop (CLPSYCH)](http://clpsych.org/)
- [FinTOC-2019 Shared Task](http://wp.lancs.ac.uk/cfie/shared-task/)
- [BioNLP workshop](https://aclweb.org/aclwiki/BioNLP_Workshop)
- [Workshop on Noisy User-generated Text](http://noisy-text.github.io/)
- [TextGraphs workshop](https://sites.google.com/view/textgraphs2020)
- [Workshop on Gender Bias for Natural Language Processing](https://genderbiasnlp.talp.cat/shared-task/)
- [Workshop on Neural Generation and Translation](https://sites.google.com/view/wngt20/home)
- [Arabic Natural Language Processing Workshop](https://sites.google.com/view/wanlp-2020/home)
- [Workshop on Fact Extraction and Verification](http://fever.ai/)
- [Workshop on Multilingual Surface Realization](http://taln.upf.edu/pages/msr2019-ws/)
- [Workshop on Rumours and Deception in Social Media](https://www.pheme.eu/rdsm2020/)
- [Joint Workshop on Multiword Expressions and Electronic Lexicons](http://multiword.sourceforge.net/PHITE.php?sitesig=CONF&page=CONF_02_MWE-LEX_2020___lb__COLING__rb__&subpage=CONF_40_Shared_Task)
- [Conference on Machine Translation](http://www.statmt.org/wmt20/)
- [Workshop on Technologies for MT of Low Resource Languages](https://sites.google.com/view/loresmt/)
- [Workshop on Simple and Efficient Natural Language Processing](https://sites.google.com/view/sustainlp2019)
- [Workshop on Abusive Language Online](https://sites.google.com/view/alw4/)
- [Second Workshop on Figurative Language Processing](https://sites.google.com/view/figlang2020/)
- [Workshop on Scholarly Document Processing](https://ornlcda.github.io/SDProc/)
- [Workshop on NLP4IF: censorship, disinformation, and propaganda](http://www.netcopia.net/nlp4if/)
- [Workshop on Trolling, Aggression and Cyberbullying](https://sites.google.com/view/trac-2/home)
- [Workshop on Natural Language Processing for Social Media](https://sites.google.com/site/socialnlp2019/)
- [NLP Techniques for Educational Applications](http://www.nlptea.org/)
- [Grand Challenge and Workshop on Human Multimodal Language](http://multicomp.cs.cmu.edu/acl2018multimodalchallenge/)

This is only a sample. Most of the shared tasks for the
upcoming year may not yet be announced. You are recommended to check
the earlier instances of the shared tasks and keep an eye
on the workshop pages for the upcoming shared tasks announcements.

For the purposes of the class, we prefer a shared task where you
finalize your work with a system description paper. If all else fails,
or if you have a strong preference, a CL-related
[Kaggle](https://www.kaggle.com/) competition may also be an option
(you are still required to write a system description paper).

## Earlier instances of the course

The following are the pointers to the papers the participants have
published.


<table rules="groups" style="width:100%;border-collapse: collapse;">
  <thead style="border-bottom: 1px solid #000;">
    <tr>
      <th style="text-align:left;" width="50%">Paper</th>
      <th style="text-align:left;" width="50%">Shared task</th>
    </tr>
  </thead>
  <tbody style="border-bottom: 1px solid #000;">
{% for paper in site.data.papers %}
    <tr style="border-bottom: 1px solid #000;">
    <td style="text-align:left;">
        <a href="{{ paper.url}}">{{ paper.authors }}</a>
    </td>
    <td style="text-align:left;">
        <a href="{{ paper.taskurl}}">{{ paper.task }}</a>
    </td>
    </tr>
{% endfor %}
    <tr>
    </tr>
  </tbody>
</table>
&nbsp;

## Contact

- Instructor: [Çağrı Çöltekin](http://coltekin.net/cagri/)
    <ccoltekin**@**sfs.uni-tuebingen.de>  
    Office hours: Monday 14:00 - 15:00
    (Wilhelmstr. 19, room 1.09)
