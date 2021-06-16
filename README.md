# Rasa Helm Charts

Official Helm charts for Rasa products:

- [Rasa Bot (Rasa Open Source Server)](charts/rasa-bot)
- [Rasa Action Server](charts/rasa-action-server)

Helm charts for components used by Rasa:

- [Duckling](charts/duckling)

## Prerequisites

- [Helm 3](https://helm.sh/) (>= 3.5 )
- Kubernetes 1.10+

## How to use Rasa Helm repository?

You need to add this repository to your Helm repositories:

```shell
helm repo add rasa https://helm.rasa.com
helm repo update
```

## Where to get help

- If you encounter bugs or have suggestions for this Helm chart, please create an issue in this repository.
- If you have general questions about usage, please create a thread in the [Rasa Forum](https://forum.rasa.com/).

## How to contribute

We are very happy to receive and merge your contributions. You can
find more information about how to contribute to Rasa (in lots of
different ways!) [here](http://rasa.com/community/contribute).

To contribute via pull request, follow these steps:

1. Create an issue describing the feature you want to work on
2. Create a pull request describing your changes

## License

Licensed under the Apache License, Version 2.0. Copyright 2021 Rasa Technologies GmbH. Copy of the license.
