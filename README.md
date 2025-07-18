<p align="center">
<a href="https://free5gc.org"><img width="40%" src="https://forum.free5gc.org/uploads/default/original/1X/324695bfc6481bd556c11018f2834086cf5ec645.png" alt="free5GC"/></a>
</p>

<p align="center">
<a href="https://github.com/free5gc/free5gc/releases"><img src="https://img.shields.io/github/v/release/free5gc/free5gc?color=orange" alt="Release"/></a>
<a href="https://github.com/free5gc/free5gc/blob/master/LICENSE.txt"><img src="https://img.shields.io/github/license/free5gc/free5gc?color=blue" alt="License"/></a>
<a href="https://forum.free5gc.org"><img src="https://img.shields.io/discourse/topics?server=https%3A%2F%2Fforum.free5gc.org&color=lightblue" alt="Forum"/></a>
<a href="https://www.codefactor.io/repository/github/free5gc/free5gc"><img src="https://www.codefactor.io/repository/github/free5gc/free5gc/badge" alt="CodeFactor" /></a>
<a href="https://goreportcard.com/report/github.com/free5gc/free5gc"><img src="https://goreportcard.com/badge/github.com/free5gc/free5gc" alt="Go Report Card" /></a>
<a href="https://github.com/free5gc/free5gc/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen" alt="PRs Welcome"/></a>
<a href="https://www.bestpractices.dev/projects/9435"><img src="https://www.bestpractices.dev/projects/9435/badge"></a>
</p>

## What is free5GC

The free5GC (a Linux Foundation project) is an open-source project for 5th generation (5G) mobile core networks. The ultimate goal of this project is to implement the 5G core network (5GC) defined in 3GPP Release 15 (R15) and beyond.

For more information, please refer to [free5GC official site](https://free5gc.org/).

## Instructions

The network diagram is as follows:

<p align="center">
  <img src="images/network.png" alt="Network Diagram" width="600"/>
</p>

---

The [run.sh](https://github.com/bilalghani1/free5gc-multi-upfs/blob/main/run.sh) script has been modified — it no longer runs the UPF automatically.  
Please manually start the following components **before** running Free5GC:

- I-UPF  
- PSA-UPF-1  
- PSA-UPF-2  

The configuration of the **SMF** is specified in the YAML file available [here](https://github.com/bilalghani1/free5gc-multi-upfs/blob/main/config/multiUPF/smfcfg_multi.yaml)

## Documentation

For document, please refer to [free5gc.org/guide/](https://free5gc.org/guide/).

## Discussion

For questions and support please use the [official forum](https://forum.free5gc.org). The issue list of this repo is exclusively for bug reports and feature requests.

## Contributing

We welcome you for contribution via [GitHub Pull Request](https://github.com/free5gc/free5gc/pulls).

## Release Note

Detailed changes for each release are documented in the release notes. Detailed changes for each release are documented in the [release notes](https://github.com/free5gc/free5gc/releases).

## License

free5GC is now under [Apache 2.0](https://github.com/free5gc/free5gc/blob/master/LICENSE.txt) license.

