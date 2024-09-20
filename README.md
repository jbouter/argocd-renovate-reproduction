# argocd-renovate-reproduction

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

## Current behavior

The Renovate runner seems to match the values files correctly, but the regex doesn't match with the contents of the `values.yaml` and `values.test.yaml` files.

## Expected behavior

Renovate should detect the lines underneath `chart:`, being the `name` of the helm chart, the `repo` where the chart can be found, and the `version` of the currently installed version

## Link to the Renovate issue or Discussion

This issue is discussed [renovate/30683](https://github.com/renovatebot/renovate/discussions/30683)

