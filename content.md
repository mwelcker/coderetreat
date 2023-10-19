# Welcome to Coderetreat

---

## Agenda

* 16:30 - Intro to coderetreat and the Game of Life
* 17:00 - Session 1 - Pairing
* 18:00 - Intro to TDD
* 18:15 - Session 2 - Ping Pong
* 19:15 - Session 3 - The Lazy Coder
* 20:15 - Retrospective

---

## 4 Rules of Simple Design
*by Kent Beck*


1. Passes the tests.
2. Reveals intention.
3. No duplication.
4. Fewest elements.


---

## Pair Programming

- Talk before you start coding, discuss, and get a common understanding of the system and tasks ahead.
- **Driver** communicates while typing and changing code.
- **Navigator** supports the driver and keeps an eye on the codebase fit of the current changes.


---
<h2 class="r-fit-text">Rules of Conway's Game of Life</h2>


Conway's Game of Life is a cellular automaton with simple rules:

- Each cell can be either "alive" or "dead."
- The game is played on a grid of cells.
- A cell's next state depends on its current state and its neighbors.

---

<h2>The Rules</h2>

1. **Underpopulation**: Any alive cell with fewer than two alive neighbors dies.
2. **Survival**: Any alive cell with two or three alive neighbors alives on.
3. **Overcrowding**: Any alive cell with more than three alive neighbors dies.
4. **Reproduction**: Any dead cell with exactly three alive neighbors becomes a alive cell.

---

<img src="https://github.com/marcoemrich/game-of-life-rules/blob/master/gol_rules_accessible.png?raw=true" width="50%">

---
<h2 class="r-fit-text">Just a showcase, on whats possible</h2>

<iframe width="560" height="315" src="https://www.youtube.com/embed/C2vgICfQawE?si=uZg8RpCDSX8YwTny&amp;start=79" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
<img src="img/qr-code.svg" width="50%"/>

```bash
git clone https://github.com/swkBerlin/kata-bootstraps.git
```
---


## Session 1 - Pairing

Grap a partner, checkout the repo and choose the programming language of your choice.
Develop the Game of Life! Apply the principles of Pair Programming.

---

## Test-Driven Development

1. **Write a Test**: Start by writing a failing test case.
2. **Let It Fail**: Run the test, and it should fail as expected.
3. **Write Minimal Code**: Write the minimal code needed to make the test pass.
4. **Test Pass**: Rerun the test, and it should pass now.
5. **Refactor**: If necessary, refactor your code to improve design while keeping the tests passing.
6. **Repeat**: Write more tests, and continue the cycle.

---

## Session 2 - Ping Pong

1. Partner 1 writes a test.
2. Partner 2 implements code to make the test pass and writes another test.
3. Partner 1 implements code to make the test pass and writes another test.
4. ...

---

## Session 3 - The Lazy Coder

Ping-Pong as before, but actively try to use the least amount of code to make a test pass.
> It is not necessary, that the code makes sense at all, als long as the test passes.

---

## Session 4 - The Evil Coder

Ping-Pong as before, but antagonistic: Introduce as much complexity into the code as you wish or choose an obscure implementation strategy.