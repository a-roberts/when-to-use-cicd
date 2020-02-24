# when-to-use-cicd

Area with goodies to be used for Adam and Christie's talk at the CDF Summit Amsterdam!

## Use cases to analyse

- Webhook creating: https://github.com/tektoncd/experimental/pull/351/files#diff-81839688376118b428411615f27235e1 ?
- Kube resource creating (like Ingresses, ConfigMaps): https://github.com/tektoncd/experimental/pull/347/files#diff-ef45590478431d372675ceede718827a ?
- Image scanning - how about https://github.com/garethr/snyk-tekton ? Requires a Snyk token though
- Building apps (let’s say a massive Java one) with big images referenced in the Task: https://github.com/tektoncd/catalog/tree/86e603cb107dddf4f83c33962983f39c2b4b851f/maven ?
- Doing performance tests: make ourselves? Running stuff in a bash loop?
- Doing unit tests: make ourselves? Augment https://github.com/tektoncd/catalog/tree/86e603cb107dddf4f83c33962983f39c2b4b851f/maven to do mvn test? But there’s nothing nice to get the output results out to visualise

## Results

## Analysis (why they're good/bad with Tekton)

## Flow diagram

## All the Pipelines/Tasks/Resources etc (cheatsheet)
