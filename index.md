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
- [VarDial workshops](https://sites.google.com/view/vardial2019) host regular
  shared task related to dialects and closely related languages.
- [SMM4H](https://healthlanguageprocessing.org/smm4h/challenge/)
  is another workshop with regular associated shared tasks.
- [CLPSYCH](http://clpsych.org/) is yet another interesting venue with
  somewhat regular shared tasks..
- IWCS 2019 has  a new
  [shared task](https://competitions.codalab.org/competitions/20220) on semantic parsing.

The above is only a sample. There are more shared tasks you can find
through a search on the Internet. Most of the shared tasks for the
upcoming year may not be yet announced. You are recommended to check
the earlier instances of the shared tasks or the associated workshops.

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
