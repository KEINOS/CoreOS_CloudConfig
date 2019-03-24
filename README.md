# Sample Configuration file for CoreOS Container Linux

- Repo: https://github.com/KEINOS/CoreOS_CloudConfig.git

## Ignition Config

Ignition file which was transpiled from the Container Linux Config.

- File: [ignition.json](ignition.json)
- Download: https://keinos.github.io/CoreOS_CloudConfig/ignition.json

```shellsession
$ curl -O https://keinos.github.io/CoreOS_CloudConfig/ignition.json
```

## Container Linux Config

Configuration file to be transpiled to `ignition.json`.

- File: [cloud-config.yml](cloud-config.yml)
- Download: https://keinos.github.io/CoreOS_CloudConfig/cloud-config.yml

```shellsession
$ curl -O https://keinos.github.io/CoreOS_CloudConfig/cloud-config.yml
```

## Config transpiler

Bash script to transpile. An alias of `ct` (the [Config Transpiler](https://github.com/coreos/container-linux-config-transpiler/)) command.

- File: [transpile](transpile)
- Download: https://keinos.github.io/CoreOS_CloudConfig/transpile

```shellsession
$ curl -O https://keinos.github.io/CoreOS_CloudConfig/transpile
```

