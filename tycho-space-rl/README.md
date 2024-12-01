### Tycho Space RL: Gymnasium Environment and Stand-alone Pygame

*Tycho Space RL is a simple turn-based game. Each player starts with one star. The winner is the one who captures all of his opponent's stars. This is a turn-based game where players simultaneously enter their moves.*

#### Goals:
- Create a Gymnasium-compliant environment
- Can also be played as a standalone game
- Trying out new Copilot and AI coding tools
- Goal is to have those tools do as much of the work as possible

#### Installation
To install the necessary dependencies, run:

```
pip install -e .
```

#### Usage
To use the Gymnasium environment, you can create an instance of the Tycho Space environment as follows:

```python
import gymnasium
import gymnasium_env

env = gymnasium.make('gymnasium_env/TychoSpace-v0')
```

For the standalone game, run the main script:

```
python src/standalone_game/main.py
```

#### License
This project is licensed under the MIT License. See the LICENSE file for more details.