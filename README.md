# CS461-QRDQN-Project
This is the term project for the CS 461 course in bilkent

## Example usage

Run a model on `smallGrid` layout for 6000 episodes, of which 5000 episodes
are used for training.

```
$ python pacman.py -p PacmanDQN -n 6000 -x 5000 -l smallGrid
```

### Layouts
Different layouts can be found and created in the `layouts` directory

## Requirements

- `python==3.5.1`
- `tensorflow==0.8rc`
