# Create Custome Node for Node-RED

Demonstrating how to write custom nodes for **Node-RED** (Related Link :  https://nodered.org/docs/creating-nodes/)

## Node-RED 

Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways. It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click. _from https://nodered.org/_

## Example : ZeroMQ (ØMQ) Node + Node-RED-Dashbaord

![alt text-1](https://github.com/phyunsj/node-red-custom-node/blob/master/node-red-dashboard-weather.gif "Node-RED-Dashboard Weather")

#### Supported ØMQ Node Types

MQ PUB & MQ SUB : Publish/Subscribe Pattern for distributing data from a single process (e.g. publisher) to multiple recipients (e.g. subscribers) 

![alt text-1](https://github.com/phyunsj/node-red-custom-node/blob/master/node-red-zeromq.png "Node-RED ZeroMQ Node")


**Link Node-RED custome node locally for development**

On Windows, using npm 5.x or greater:

> cd  C:\Users\my_name\.node_red
> npm install C:\Users\my_name\my_project\node-red-zeromq

## Node-RED-Dashboard Flow

![alt text-1](https://github.com/phyunsj/node-red-custom-node/blob/master/node-red-zeromq-dashboard.png "Node-RED-Dashboard ZeroMQ")


## Additional Info

- Node-RED How To: Custom Node Creation https://www.youtube.com/watch?v=TlzqGhfdbEM
- Writing custom add-ons for Node-RED https://opensourceforu.com/2017/07/writing-custom-add-ons-node-red/
