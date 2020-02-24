# experiments

This is where the experiments sit that you can run yourself

## Apply the definitions

`kubectl apply -f experiments/pipelines`

`kubectl apply -f experiments/tasks`

`kubectl apply -f experiments/resources`

## Run the Pipelines

### Webhooks: `tkn run ...`

Params: secret name that can create webhooks, GitHub repo URL

### Create Ingress: `tkn run ...`

Params: callback URL

### Scan image: `tkn run ...`

Params: image to scan, optionally a pull secret

### Build app: `tkn run ...`

Params: Git repo to build

### Performance test: `tkn run ...`

Params: number of iterations

### Unit test: `tkn run ...`