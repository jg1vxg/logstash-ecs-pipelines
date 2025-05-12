# Logstash Pipeline Configurations

This repository contains Logstash configurations that are compatible with the Elastic Common Schema (ECS). We welcome Pull Requests from to improve our operation and security. If you find these configurations useful, feel free to buy me a coffee.

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [Vendor Support](#vendor-support)
- [Disclaimer](#disclaimer)
- [License](#license)

## Overview
We've kindly tested these configurations, and they seem well with Logstash 1:8.17.3-1.

Our goal is to provide a comprehensive set of Logstash pipelines that support a wide variety of data sources while following ECS guidelines to maintain consistency across the Elastic Stack.

## Getting Started
1. Clone or download this repository.
2. Ensure you have [Logstash](https://www.elastic.co/logstash) installed.
3. Copy or link these .conf files into your Logstash conf.d directory (or specify them under your pipelines.yml file).

## Folder Structure
- **conf.d/**: Contains pipeline configuration files for different data sources or output types.
- **pipelines.yml**: Defines multiple pipelines and references the relevant configuration files under conf.d.

## Usage
Once the files are in place, start Logstash using:
```
bin/logstash -f pipelines.yml
```
Alternatively, use the appropriate service or systemd commands to manage Logstash on your environment.

## Contributing
Contributions are welcome and encouraged! Open a Pull Requests, feedback and suggestions are appreciated.

## Vendor Support
If you are a vendor or supporter interested in adding configurations for your devices or enabling deeper integration, please contact me. We look forward to collaborating with you on extending the capabilities of this repository.

## Disclaimer
We assume no responsibility for the use of these configurations. Please review them for your environment and security standards before deployment.

## License
This project is licensed under the Apache License 2.0. Please see [LICENSE](LICENSE) for more details.
