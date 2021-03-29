<h1 align="center">hasanpy</h1>
<p align="center">
A Python implementation of the <a href="https://esolangs.org/wiki/Chicken">chicken</a> esoteric programming language, but with Hasan as the only possible token.
</p>

## What's Hasan?
A Hasan program only contains the tokens `"hasan"`, `" "` and `"\n"`. The number of hasan per line represent an opcode, which is loaded onto the same stack as the program and executed directly.

For more details, view the [original implementation and spec here](https://web.archive.org/web/20180816190122/http://torso.me/chicken), or view the [Esolang page for chicken](https://esolangs.org/wiki/Chicken).

## Installation
```
$ pip install hasanpy
$ hasanpy --help
```

## Manual Installation
### Requirements
- Python 3.8+
- [Poetry](https://github.com/python-poetry/poetry)

### Steps
1. Click the **Clone or download** button in the top right corner.
2. Either clone the repository or download the ZIP file and extract.
3. Change directory and install dependencies.
```
$ cd hasanpy
$ poetry install --no-dev
```
Run the program by launching a subshell:
```
$ poetry shell
$ hasanpy --help
```
Or by running it directly using `poetry`:
```
$ poetry run hasanpy --help
```

### Dependencies
- [Click](https://github.com/pallets/click)

## Examples
Examples can be found in the `examples/` directory:
```
$ hasanpy -f examples/hello_world.chn
```

## License
This project is licensed under MIT. For more information see the [LICENSE](https://github.com/mdibaiee/hasanpy/blob/master/LICENSE) file.
