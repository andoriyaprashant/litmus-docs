---
id: installation
title: Litmusctl
sidebar_label: Installation
---

---

The LitmusChaos command-line tool, litmusctl, allows you to manage litmuschaos's infrastructure plane. You can use litmusctl to connect and disconnect chaos infrastructures, create chaos experiments, project, and manage multiple litmuschaos accounts.

## Prerequisites

Litmusctl CLI requires the following things:

- **kubeconfig** - litmusctl needs the kubeconfig of the k8s cluster where we need to connect litmus chaos infrastructures. The CLI currently uses the default path of kubeconfig i.e. `~/.kube/config`.
- **kubectl** - litmusctl is using kubectl under the hood to apply the manifest.
  > To install kubectl, follow: [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl)

## Usage

For more information including a complete list of litmusctl operations, see the litmusctl reference documentation.

- For 0.23.0 or latest: <a href="https://github.com/litmuschaos/litmusctl/blob/master/Usage_0.23.0.md">Click here</a>

## Installation

To install the latest version of litmusctl follow the below steps:

<table>
  <th>Platforms</th>
  <th>1.11.0</th>
  <th>1.10.0</th>
  <th>1.9.0</th>
  <th>1.8.0</th>
  <th>1.7.0</th>
  <th>1.6.0</th>
  <th>1.5.0</th>
  <th>1.4.0</th>
  <th>master(Unreleased)</th>
  <tr>
    <td>litmusctl-darwin-amd64 (MacOS)</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-darwin-amd64-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-linux-386</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-386-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-linux-amd64</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-linux-arm</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-linux-arm64</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-arm64-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-windows-386</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-386-master.tar.gz">Click here</a></td>
  </tr>
   <tr>
    <td>litmusctl-windows-amd64</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-amd64-master.tar.gz">Click here</a></td>
  </tr>
  <tr>
    <td>litmusctl-windows-arm</td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.11.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.10.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.9.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.8.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.7.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.6.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.5.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-1.4.0.tar.gz">Click here</a></td>
    <td><a href="https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-windows-arm-master.tar.gz">Click here</a></td>
  </tr>
</table>

### Linux/MacOS

- Extract the binary

```shell
tar -zxvf litmusctl-<OS>-<ARCH>-<VERSION>.tar.gz
```

- Provide necessary permissions

```shell
chmod +x litmusctl
```

- Move the litmusctl binary to /usr/local/bin/litmusctl. Note: Make sure to use root user or use sudo as a prefix

```shell
mv litmusctl /usr/local/bin/litmusctl
```

- You can run the litmusctl command in Linux/macOS:

```shell
litmusctl <command> <subcommand> <subcommand> [options and parameters]
```

### Windows

- Extract the binary from the zip using WinZip or any other extraction tool.

- You can run the litmusctl command in windows:

```shell
litmusctl.exe <command> <subcommand> <subcommand> [options and parameters]
```

- To check the version of the litmusctl:

```shell
litmusctl version
```

---
