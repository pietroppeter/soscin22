# soscin22

State Of Scientific Computing In Nim 2022 - repo for my upcoming Fosdem presentation: https://fosdem.org/2022/schedule/event/nim_stateofscinim/

⚠️ work in progress ⚠️

## overview

30'+5'Q&A

goals of the talk:
- give an overview of what is currently available in scientific computing with nim
- improve existing documentation by providing some new examples on how to use some of the libraries (and map existing examples)
- have a better idea on where I should concentrate my efforts for 2022 and suggest generally possible directions for evolution

not really a talk focused on nimib, but plan to use nimib to communicate most of the stuff. in particular I plan to use nimislides to create the presentation.

as an additional goal it would be nice to have something that will be able to automate stuff (for discovery of new libs and gathering info about them)

the minimal goal to reach is just to be a startightforward presentation that targets someone who is new to nim and interested in scientific computing and wants to know where to start and what can they expect to accomplish (and maybe where to help). this minimal goal I guess is doable even if I do not complete any of the tasks below.

## slides

- [ ] intro
  - [ ] who am I
  - [ ] goals of the talk
  - [ ] about nimib
- [ ] framework
  - [ ] what is scientific computing
  - [ ] data science as a prominent subfield
  - [ ] scinim as github org
- [ ] survey
  - [ ] criteria to include a lib in the survey
  - [ ] results of the survey...
- [ ] examples
  - [ ] ... selection of examples from tasks and maybe also some existing examples
- [ ] next steps
  - [ ] ...

## tasks

stuff I plan to potentially do for the presentation (far from expecting to do them all, already a small selection will be more than enough for the presentation).

- [ ] complete the refactor nbBlock (useful/required? for nimislides and possibly other notebooks)
- [ ] complete ML tutorial in scinim/getting-started
- [ ] gather a list of "scinim" libraries (multiple source: are we scientists yet, curated packages, ...) and put them in my scinim star list
- _(scinim lib is any lib related in someway to scientific computing with nim however small and even possibly obsolete - will use the most inclusive defintion for what a scinim lib is)_
- [ ] create a nimib notebook that gather stats for all scinim libs (e.g. last commit, last release, contributors, number of commits in 2021, ...) 
- [ ] nimib examples for aymanalbaz's libraries
- [ ] nimib examples for GSL wrapper
- [ ] implement rnad (crypto lock puzzles as featured in HN) with bigints (and bignum?)
- [ ] using plotly in nimib notebook
- [ ] using gnuplot in nimib notebook
- [ ] PR for ggplotnim horizontal lines (it would be nice to have a beginner friendly notebook that explains all steps - including all you have to do with git/github)
- [ ] try out jupyternim
- [ ] a jupyternim backend for nimib
- [ ] blogpost for a poc for deneb (vegalite for nim)
- [ ] experiment interactivity with nimscripter
- [ ] nimib examples of some libs by aferretti?
- [ ] nimib notebook that takes test from a repo and runs them in a nimib notebook (including all outputs). in this way practically most repos would gain some new documentation (easier to read). not sure how feasible/useful this could be
