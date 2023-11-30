---
layout: intro
theme: bricks
mdc: true
highlighter: prism
---

# Welcome to the coderetreat

---
layout: section
---

# Agenda

::right::

**16:00** - Intro to coderetreat and the Game of Life

**16:30** - Session 1 - Pairing

**17:30** - Intro to TDD

**18:00** - Session 2 - Ping Pong

**19:00** - Session 3 - The Lazy Coder

**20:00** - Retrospective

---
layout: items
---
# 4 Rules of Simple Design
*by Kent Beck*

::items::

<Polygon7 w="20" h="20" m="auto"/>
<Polygon2 w="20" h="20" m="auto"/>
<Polygon3 w="20" h="20" m="auto"/>
<Polygon4 w="20" h="20" m="auto"/>

Passes the tests

Reveals intention

No duplication

Fewest elements

---
layout: section
---

![](/img/driver_navigator.png)

::right::

# Pair Programming

- Talk before you start coding, discuss, and get a common understanding of the system and tasks ahead.
- **Driver** communicates while typing and changing code.
- **Navigator** supports the driver and keeps an eye on the codebase fit of the current changes.

---
layout: section
---

#  Conway's Game of Life

::right::

![](https://upload.wikimedia.org/wikipedia/commons/3/30/John_H_Conway_2005.jpg)

---

# The Rules

Conway's Game of Life is a cellular automaton with simple rules

- Each cell can be either "alive" or "dead."
- The game is played on a grid of cells.
- A cell's next state depends on its current state and its neighbors.

<iframe width="560" height="315" src="https://www.youtube.com/embed/C2vgICfQawE?si=uZg8RpCDSX8YwTny&amp;start=79" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
layout: section
---

1. **Underpopulation**: Any alive cell with fewer than two alive neighbors dies.
2. **Survival**: Any alive cell with two or three alive neighbors alives on.
3. **Overcrowding**: Any alive cell with more than three alive neighbors dies.
4. **Reproduction**: Any dead cell with exactly three alive neighbors becomes a alive cell.

::right::

<img src="https://github.com/marcoemrich/game-of-life-rules/blob/master/gol_rules_accessible.png?raw=true" style="width: 350px" />

---
layout: section
---

# Clone the repo

`git clone https://github.com/swkBerlin/kata-bootstraps.git`

::right::

![](/img/qr-code.svg)

---
layout: fact
---

# Session 1
## Pairing

Grap a partner, checkout the repo and choose the programming language of your choice.

Develop the Game of Life! Apply the principles of Pair Programming.

---
layout: section
---


![](/img/tdd.png)

::right::

# Test-Driven Development

1. **Write a Test**: Start by writing a failing test case.
2. **Let It Fail**: Run the test, and it should fail as expected.
3. **Write Minimal Code**: Write the minimal code needed to make the test pass.
4. **Test Pass**: Rerun the test, and it should pass now.
5. **Refactor**: If necessary, refactor your code to improve design while keeping the tests passing.
6. **Repeat**: Write more tests, and continue the cycle.

---
layout: fact
---

# Session 2
## Ping Pong

<img src="/img/tdd-ping-pong-pairing.png" style="margin: 0 auto; width: 500px"/>


---
layout: fact
---

# Session 3
## The Lazy Coder

Ping-Pong as before, but actively try to use the least amount of code to make a test pass.
> **IMPORTANT:** It is not necessary, that the code makes sense at all, als long as the test passes.

---
layout: fact
---

# Session 4
## The Evil Coder

Ping-Pong as before, but antagonistic: Introduce as much complexity into the code as you wish or choose an obscure implementation strategy.
