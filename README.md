Zoom-Red
=======

A controller for ZoomOSC V4. 

### About

[ZoomOSC v4](https://www.liminalet.com/zoomosc-4-0) is an alternate zoom client which enables independent control of the client via the [OSC](https://en.wikipedia.org/wiki/Open_Sound_Control) protocol.

To use Zoom-Red you need the following pre-requisites:
 * Install node-red - see their [getting started guide](https://nodered.org/docs/getting-started/).
 * Install required node packages - the easiest way is via the node-red 'Manage Palette' dialog.
     + [node-red-contrib-osc](https://flows.nodered.org/node/node-red-contrib-osc)
     + [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)
     + [node-red-node-ui-table](https://flows.nodered.org/node/node-red-node-ui-table)
 * Start node-red 
 * Go to the main UI webpage - the default is [http://127.0.0.1:1880/ui](http://127.0.0.1:1880/ui)
 
**Note**: By default a node-red installation does not require authentication or authorization. So anybody who has access to the network it is running on could take control of your zoom meeting. It is highly recommended that you secure your install. See [Securing node-red](https://nodered.org/docs/user-guide/runtime/securing-node-red) for more info. 