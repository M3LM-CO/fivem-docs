---
title: TriggerEvent
---

The TriggerEvent function triggers the specified event with optional data. This function can be used between client and client-side scripts or between server and server-side scripts.

Syntax
------

```lua
TriggerEvent(string eventName[, ...])
```

### Required arguments
- **eventName**: A string representing the event name to trigger.

### Optional arguments
- **...**: Any additional data that should be passed along.

Usage
--------

You can use the TriggerEvent function to trigger events on the client or server side of your FiveM resource.
If you want to trigger a client-side event from the server, you should use the [TriggerClientEvent][]! function. 
If you want to trigger a server-side event from the client, you should use the [TriggerServerEvent][]! function.

Examples
--------

Here's an example of how to use the TriggerEvent function to trigger an event:

```lua
TriggerEvent('eventName', arg1, arg2 ...)
```

In this example, eventName is the name of the event you want to trigger, and arg1, arg2, and so on are optional data that you want to pass along with the event.

[TriggerServerEvent]: /docs/scripting-reference/runtimes/lua/functions/TriggerServerEvent/
[TriggerClientEvent]: /docs/scripting-reference/runtimes/lua/functions/TriggerClientEvent/
