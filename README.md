# EpoxyTransport (But works with TS)

EpoxyTransport is a transport for bare-mux which allows you to use [epoxy-tls](https://github.com/MercuryWorkshop/epoxy-tls) in your bare client.

Usage of this transport is as simple as setting the transport and providing a wisp server. An example is shown below where you get connected to the public testing wisp server.

```js
import { SetTransport } from '@mercuryworkshop/bare-mux';

SetTransport("EpxMod.EpoxyClient", { wisp: "wss://wisp.mercurywork.shop/" });
```
This fork of EpoxyTransport contains typings. A pull request has already been made, however branches have not yet been merged. For the time being, I've just decided to host it myself.
