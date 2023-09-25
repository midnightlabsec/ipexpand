# IP Expand

IP Expand (ipexpand) is a tool to list all IP addresses within a specified range.
When you have a list of IP ranges and want to list their individual IP addresses, it is time to ``expand`` them.

## Install

```shell
sudo sh ./setup.sh
```
Once the installation finishes, the ``ipexpand`` command will be globally available on the cli.

## Usage

```shell
ipexpand -t targets.txt -e exclusions.txt -o result.txt
```
Where:
- ``targets.txt`` file should contain all IP ranges that you want to expand.
- ``exclusions.txt`` file should contain any IP address that, after the expansion, you don't want to be on the final list.
- ``result.txt`` file will contain the list of expanded IPs except the ones listed on the ``exclusions.txt`` file.

