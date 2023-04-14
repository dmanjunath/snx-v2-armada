### SNX Armada Workflow Demo

[![Publish to Armada](https://github.com/dmanjunath/snx-armada-demo/actions/workflows/build-armada-workflow.yml/badge.svg)](https://github.com/dmanjunath/snx-armada-demo/actions/workflows/build-armada-workflow.yml)

This repo shows a simple github action to build and deploy a site to Armada Network using Github Actions. To see an example of a passing github action go to https://github.com/dmanjunath/snx-armada-demo/actions/runs/4701567587. To see the site go to https://app.guerillaflotilla.com

Note - the site doesn't run with all production env vars injected (eg infura, portis, blocknative) so some trading functionality may not work but the site loads and wallets can be connected and all UI works. If all env vars are injected the site should fully function.