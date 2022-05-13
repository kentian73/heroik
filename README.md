# V2ray Heroku

** To deploy V2Ray Vless, go to [Vless] (https://github.com/kentian73/kennet/Tree/vless) branch. **

## Overview

This item is used to deploy V2RAY Websocket on Heroku. Under the extent to which it is reasonably used, the mirror does not cause the title due to a lot of occupation resources.

After the deployment is complete, running V2Ray will always be the latest version every time you start the app.

## Deployment

### step

1. Fork this item to your own GitHub account (username is `example` is an example
2. Modify the task name, be careful not to include `v2ray` and` heroku` Two keywords (modified item named `Demo`
3. Modify `readme.md`, replace the` bclswl0827/v2ray-heroku`, such as `example/demo`)

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/nixzxl/heroik)

 4. Go back to the project home, click on the link above to deploy V2Ray

### variable

The variable name required to be set is as follows.

| Variable | Default | Description |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | VMess User main ID，For authentication, for uuid format |
| `WSPATH` | `/` | WebSocket, HTTP protocol path used |

## Access CloudFlare

The following two ways can be applied to CloudFlare to increase the speed to a certain extent.

  1. Bind the domain name for the application, and access the domain name to CloudFlare
  2. Reverse proxy by CloudFlare Workers

## Notice

  1. ** Do not abuse this item, similar to the free service of Heroku, less service, and use and cherish **
  2. If you use the domain name to access the CloudFlare, consider the enabled TLS 1.3
  3. Most of the IPv4 address of AWS has been masked by Twitter
