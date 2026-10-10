> **Archived (2026-10-10).** This fork is no longer used. NibePi was split into
> an RS485/MQTT gateway ([nibepi-backend](https://github.com/greberg/nibepi-backend),
> image `ghcr.io/greberg/nibepi-gateway`) and a Home Assistant component that
> holds all control logic ([nibepi-ha](https://github.com/greberg/nibepi-ha)).
> The last Node-RED based version is the tag
> [`nodered-final`](https://github.com/greberg/nibepi-flow/tree/nodered-final).

# nibepi-flow
Flows.json for NibePi nodes in Node-RED

This fork carries the VV-AI hot water dashboard from
[pizzihelmet/nibepi-flow](https://github.com/pizzihelmet/nibepi-flow), imported
node by node rather than merged, so it does not appear under its author's name
in the git history.

These flows need the matching nodes from
[fnordpojk/node-red-contrib-nibepi](https://github.com/fnordpojk/node-red-contrib-nibepi),
where the upstream authors are credited in full. The price tab still works
because of Martin Åhsberg's fixes.

Original NibePi by [anerdins](https://github.com/anerdins/nibepi-flow).
