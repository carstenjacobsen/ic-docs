author: DFINITY
summary: Deploy a Dapp to the Internet Computer
id: deploy_to_ic
categories: codelab,markdown
environments: Web
status: Published
feedback link: https://github.com/dfinity/docs

# Deploy to IC

## Introduction
Duration: 0:01:00

This CodeLab shows how to deploy a dapp to the Internet Computer. Deploying to the mainnet is very similar to deploying a dapp locally. The main difference is that the wallet canister has to be setup with cycles for deployment on the IC, where locally the wallet canister is automatically generated with test cycles. 

This CodeLab covers:

- Get principle ID
- Get ledger account ID
- Add ICP to ledger
- Create canister with an initial amount of ICP
- Deploy wallet with cycles
- Deploy dapp to the IC 

The flow looks like this:

![Deployment Flow](images/deploy.png)

## Create New Project
Duration: 0:03:00

Run this command to create project:

```bash
$ dfx new minimal_dapp
```


# 

sdf
