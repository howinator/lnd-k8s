# How to build
This should be a makefile, but to build, e.g., 0.20.1, do `docker build --build-arg TARGETPLATFORM=linux/amd64 -t howinator/bitcoin-core:0.20.1 -t howinator/bitcoin-core:latest .`

# Resources
* https://medium.com/@Judezhu87/running-bitcoind-node-on-kubernetes-1d833212b1a
* https://medium.com/bleevin/tutorial-of-setting-up-lightning-network-in-a-distributed-way-58b879c6150e
* https://github.com/ruimarinho/docker-bitcoin-core
* https://github.com/lsdopen/k8-bitcoinlnd
* https://www.reddit.com/r/lightningnetwork/comments/izf4v7/kubernetes_bitcoincore_lnd_lndhub_and_a_handy_scb/
