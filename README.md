# anyenv-disable

This is an [anyenv](https://github.com/anyenv/anyenv) plugin to disable a specific \*\*env.
All anyenv subcommands, including `anyenv init`, ignore disabled \*\*envs,
so you can reduce the time of `anyenv init` by disabling \*\*envs infrequently used.


## Installation

```sh
mkdir -p $(anyenv root)/plugins
git clone https://github.com/abicky/anyenv-disable.git $(anyenv root)/plugins/anyenv-disable
```


## Usage

### Disable a specific **env

```sh
anyenv disable <**env>
```

### Enable a specific **env

```sh
anyenv enable <**env>
```

### List disabled **envs

```sh
anyenv envs-disabled <**env>
```


## Author

Takeshi Arabiki (abicky)
