# ssh-completion

Auto-magically add completion on your ssh command

## Installation

Clone ssh-completion repository

```bash
$ git clone git@github.com:ReputationVIP/ssh-completion.git
```

Source `.ssh_completion` dot file in your `.bashrc`

```
if [ -f /path/to/repository/.ssh_completion ]; then
        source /path/to/repository/.ssh_completion
fi
```

Optional add base config file in `/path/to/repository/.ssh_config_shared_files`

Source your `.bashrc` and let the magic begin

```bash
$ source ~/.bahsrc
```

## Documentation

ssh-completion add aliases in your bash environement.

It provide host completion extract from `config-generate` file.

It can concat your `~/.ssh/config` file with others online `config` file in a `config-generate` file use by ssh command.

### External

- [ssh config file](http://nerderati.com/2011/03/17/simplify-your-life-with-an-ssh-config-file)

### Requirements

- ssh.
- bash.

### Submitting bugs and feature requests

Bugs and feature request are tracked on [GitHub](https://github.com/ReputationVIP/ssh-completion/issues)

### Author

[Nicolas Couet](https://github.com/tejerka)
See also the list of [contributors](https://github.com/ReputationVIP/ssh-completion/graphs/contributors) which participated in this project.
