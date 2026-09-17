# DFS & BFS Pacman

## Q1, depth-first search

`SearchAgent` uses DFS by default, so `-a fn=dfs` is optional.

```bash
python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent
```

## Q2, breadth-first search

```bash
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
```
