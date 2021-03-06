# MyAgent
A Minecraft agent generator & controller written in node.js

[![MyAgent v4](https://github.com/mcpews/MyAgent/raw/master/images/myagent4.png)](https://github.com/mcpews/MyAgent)

[![MyAgent NPM](https://img.shields.io/badge/npm-myagent-blue.svg)](https://www.npmjs.com/myagent)
[![MyAgent Version](https://img.shields.io/badge/dynamic/json.svg?label=myagent%20version&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmcpews%2FMyAgent%2Fmaster%2Fpackage.json&query=%24.version&colorB=yellowgreen)](https://github.com/mcpews/MyAgent)
## Considerations
Agent Commands doesn't work in Minecraft Bedrock 1.7 ~ 1.8beta(1.8 is supported), that means you can't create or control Agent in these versions.
And the latest version of iOS platform's MC China Edition doesn't compatible with myagent too.
## Available Minecraft Versions
All MCPE Bedrock Embedded Build (version: 1.2+ but not 1.7 ~ 1.8b)
(Note: 0.16 ~ 1.1 used another commandRequest packet format,so not compatible.)  
MyAgent also compatible with Minecraft China Edition and Minecraft Education Edition.
## [MyAgent Server Commands](https://github.com/mcpews/MyAgent/wiki/server-commands)
## Loops
Syntax: `[:/!]/<command>~<loop count>`  
Examples:
 - Move agent up for 10 times : `:/move up~10`
 - Say `oh` for 5 times : `!/say oh~5`
## Fast install (Unrecommended!)
Execute `npm i myagent -g` to install myagent.  
Then execute `myagent` command to start myagent.  
## MyAgent Control
MyAgent Control can set the config of myagent.  
`myagent control set <config> <value>` to set a config.  
`myagent control rmconf` to remove config file of myagent (reset to default configs)
## Execute myagent
First,Clone a copy of myagent  
And then,please execute following command:
```
npm install
```
At last,execute command:`node myagent.js`
## Connect
type command in game:
`/connect [ip]:[port]`  
`[ip]` is IP of the server where you hosting myagent.  
`[port]` is the IP address of myagent. Default value is 19131.
## Report bug
Submit an issue to report bug.
## LICENSE
[GNU GPL v3](LICENSE)
## Maintainers
[LNSSPsd](https://github.com/LNSSPsd)
[CAIMEO](https://github.com/CAIMEOX)
[Torrekie](https://github.com/Torrekie)
[許嘉鋅](https://github.com/TheXuJiaXin)
## See also
[MyAgent++](https://github.com/mcpews/MyAgentPP)
## More
For verbose help or info,please see [MyAgent Wiki](https://github.com/mcpews/MyAgent/wiki).

