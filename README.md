# Software Engineering Tips

## Writing and Contributing Code

### Git

#### Git Commits
Motivation: Good commit messages matter and Chris Beams [explains](https://chris.beams.io/posts/git-commit/) why:
> it is the best way to communicate context about a change to fellow developers and future selve amd it also empowers other Git commands like `git blame`, `revert`, `rebase`, `log`, `shortlog`

Some tips:
- Write in imperative form
  - Refactor subsystem X for readability
  - Update getting started documentation
  - Remove deprecated methods
  - Release version 1.0.0
- Use the body to explain what changed and why

Benefits as David Thompson [lists](https://dhwthompson.com/2019/my-favourite-git-commit):
- commit message are searchable
- tells a story


## Machine Learning

### Online vs Offline Training

Online training often needs monitoring as the model can be sensitive to new data. Models also need to be re-trained if there are structural changes in the datasets. In other words, models don't decay historical information.

Offline training can deal with this by looking at high leverage.
