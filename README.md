# Project-4-Tracking-in-Pacman
Pacman spends his life running from ghosts, but things were not always so. Legend has it that many years ago, Pacman’s great grandfather Grandpac learned to hunt ghosts for sport. However, he was blinded by his power and could only track ghosts by their banging and
clanging.

In this project, you will design Pacman agents that use sensors to locate and eat invisible ghosts. You’ll advance from locating single, stationary ghosts to hunting packs of multiple moving ghosts with ruthless efficiency.
I can hear you, ghost. Running won't save you from myParticle filter!

This project includes an autograder for you to grade your answers on your machine. This can be run on all questions with the command:
`python autograder.py`.

It can be run for one particular question, such as q2, by:
`python autograder.py -q q2`

It can be run for one particular test by commands of the form:
`python autograder.py -t test_cases/q1/1-ObsProb`

The code for this project contains the following files, available as a zip archive.

| Files you'll edit:       |                                           |
|--------------------------|-------------------------------------------|
| `bustersAgents.py`       | Agents for playing the Ghostbusters variant of Pacman. |
| `inference.py`           | Code for tracking ghosts over time using their sounds. |
| `factorOperations.py`    | Operations to compute new joint or marginalized probability tables. |

| Files you might want to look at: |                                           |
|----------------------------------|-------------------------------------------|
| `bayesNet.py`                    | The BayesNet and Factor classes.          |

| Supporting files you can ignore: |                                           |
|----------------------------------|-------------------------------------------|
| `busters.py`                     | The main entry to Ghostbusters (replacing Pacman.py). |
| `bustersGhostAgents.py`          | New ghost agents for Ghostbusters.         |
| `distanceCalculator.py`          | Computes maze distances, caches results to avoid re-computing. |
| `game.py`                        | Inner workings and helper classes for Pacman. |
| `ghostAgents.py`                 | Agents to control ghosts.                 |
| `graphicsDisplay.py`             | Graphics for Pacman.                      |
| `graphicsUtils.py`               | Support for Pacman graphics.              |
| `keyboardAgents.py`              | Keyboard interfaces to control Pacman.    |
| `layout.py`                      | Code for reading layout files and storing their contents. |
| `util.py`                        | Utility functions.                        |

**Files to Edit and Submit:** You will fill in portions of bustersAgents.py , inference.py , and factorOperations.py during the
assignment. Once you have completed the assignment, you will submit these files to Gradescope (for instance, you can upload all .py files
in the folder). Please do not change the other files in this distribution.

**Evaluation:** Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes
within the code, or you will wreak havoc on the autograder. However, the correctness of your implementation – not the autograder’s
judgements – will be the final judge of your score. If necessary, we will review and grade assignments individually to ensure that you receive
due credit for your work.
