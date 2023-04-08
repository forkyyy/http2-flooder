## HTTP/2 Flooder in NodeJS (outdated)

This is a NodeJS-based HTTP/2 flooder script that can be used to DDoS websites. Note that this script is outdated and may not work as expected.

### Installation

Before you can use the script, you'll need to install Node.js on your system

```shell
curl -sL https://deb.nodesource.com/setup_16.x | sudo bash -
sudo apt -y install nodejs
npm i http http2 crypto tls
```

### Usage

To use the script, run the following command in your terminal:

```shell
node tls.js https://website.com 120
```

You can update HTTP proxies and user agents to use in the attack by adding them to the `proxy.txt` and `ua.txt` files, respectively.
