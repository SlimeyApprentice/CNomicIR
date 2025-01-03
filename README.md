# NomiC Initial Ruleset
A C-based code nomic initial "ruleset."

## Explanation
Nomic is a game invented by Peter Suber to analyse self-amending systems, such as governments. Many internet communities have sprung up around this game, and have created quite complicated rulesets. Most of these communities (that I have seen) create laws that are meant to be read by humans. This is an attempt to have the law interpreted by a computer. The program allows players to make editting proposals which change its source code, and in theory allow for an infinitely extensible program.

## Setup
Currently, there is no code. When the program is developed, I would strongly advise against running it on your machine outside of a VM or other sandbox, because if I or any of your players introduce bugs into the system that allow arbitrary code execution then attackers could gain user access to your machine. I plan to have some method of containing it out of the box, perhaps using Docker.

## MetaRuleset


## Todo
- [ ] Initial Makefile
- [ ] Networking Components (decide on an ideal interface)
- [ ] Decide on a win condition
- [ ] Design and implment (initial) UI
- [ ] Design and implement file editing system
- [ ] Design and implement proposal system
- [ ] Design the access control system (think about how to add players)
- [ ] Design and implement voting and quorum
- [ ] Design compilation safeties (kill a proposal if the result would not compile)
- [ ] Design container system
- [ ] ?
