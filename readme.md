# Consul SE Demos

The intent for this is to create a single dashboard for Consul Demos.

Content inspired and largely copied from [hashicorp/consul-demo-traffic-splitting](https://github.com/hashicorp/consul-demo-traffic-splitting)

## Prerequisites

- Docker
- Bash

## Setup

Clone this repo

``` bash
git clone https://github.com/grove-mountain/consul-se-demos.git
cd consul-se-demos
```

In one window run Docker Compose

``` bash
docker-compose up
```

## Run the demo scripts

All scripts use a tool called demo-magic which allows you to step through each command that's being run and pause where necessary.

When running the script, follow the directions in the script at each step and then hit `return` to move to the next one.

Run these in a separate window

### Consul Template Demo

Run the following script:

``` bash
1_consul_template_demo.sh
```

### Consul Layer 7 Demo

Run the following script:

``` bash
2_l7_demo.sh
```

## Cleanup

In the Docker Compose window:

``` bash
ctrl-c
docker-compose down
```
