﻿# Wardenx-cli

 the official wardenx CLI version
- that's a showcase project, don't tend to use any sensitive data

### run the CLI

in your terminal run this command:

```./wardenx-cli init```

it will setup a new profile for you to use it

### how to use the CLI

run this command to show the CLI guide:

```./wardenx-cli help```

### the available commands

- init => create tables, and username, password, recovery_key
- add *label* *passowrd*
- del -s *label*
- del -h
- edit -u *new username*
- edit -p *old password* *new passowrd*
- edit -k *password* *new key*
- edit -l *old label* *new label*
- edit -s *label* *new passowrd*
- get -h => shows logs
- get -s *label*
- get -a
- help
- recover
- generate
- hash
