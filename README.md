# chess-board 

## **Live PR URL** [link1](https://github.com/BasharTaamneh/chess_board/pull/1)


## Description
* This programe is to render out chess boards with red and blue queens on them.
 * Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

Each board will have one red and one blue queen at different coordinates. and identifyer to tell if the queens are “under attack” based on their coordinates.

## Feature Tasks

>  add_red method that accepts a row and column as input which colors corresponding cell.

>  add_blue method that accepts a row and column as input which colors corresponding cell.

>  render method that displays the chess board on screen with red and blue shown in correct locations

>  is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## Requirment

```javascript
poetry
python 3.9.7
numpy 
matplotlib 
jupyterlab
```

## Getting started

```bash
poytry install
poetry shell

poetry add numpy matplotlib jupyterlab
```
## User Acceptance Tests

> [x] queens on same row should be “under attack”

> [x] queens on same column should be “under attack”

> [x] queens on same diagonal should be “under attack”

> [x] queens with any other coordinates should NOT be “under attack”


**Collaboratores:**

* Bashar Taamneh

## Change log
chess-board v1  `completed class11 24-10-2021`