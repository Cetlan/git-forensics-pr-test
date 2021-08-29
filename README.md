This repository is just to experiment with the reference discovery for PR
jobs in Jenkins multibranch pipelines. I suspect there's a bug in discovery
that it won't actually use the most recent build of the merge target, even
though that is the commit that will be used in the merge build.
