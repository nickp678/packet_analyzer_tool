# Packet_Analyzer_Tool


## Introduction

This is a HTTP packet capture and analyzer made with Python. It will first sniff and capture any HTTP packets going from and to the local machine. From there, it will analyze each packet and print out metadata such as timestamp, MAC & IP addresses of both the source and destination, source and destination port, etc. It even provides additional information based on whether the packet is a HTTP request or response.

## Prerequisites

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Scapy.

```bash
pip install scapy
```

Download the packet_analyzer.py file from github

## Usage

To run the Packet Analyzer, use the following command:

```bash
python3 inputaggregator.py
```

Have fun!
