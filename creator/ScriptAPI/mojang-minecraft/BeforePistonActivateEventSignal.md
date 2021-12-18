---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.BeforePistonActivateEventSignal Class
description: Contents of the mojang-minecraft.BeforePistonActivateEventSignal class.
---
# BeforePistonActivateEventSignal Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

Manages callbacks that are connected to an event that fires before a piston is activated.


## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)
  
### **subscribe**
`
subscribe(callback: (arg: BeforePistonActivateEvent) => undefined): (arg: BeforePistonActivateEvent) => undefined
`

Adds a callback that will be called before a piston expands or retracts.
#### **Parameters**
- **callback**: (arg: [*BeforePistonActivateEvent*](BeforePistonActivateEvent.md)) => undefined

#### **Returns** (arg: [*BeforePistonActivateEvent*](BeforePistonActivateEvent.md)) => undefined


### **unsubscribe**
`
unsubscribe(callback: (arg: BeforePistonActivateEvent) => undefined): void
`

Removes a callback from being called before a piston expands or retracts.
#### **Parameters**
- **callback**: (arg: [*BeforePistonActivateEvent*](BeforePistonActivateEvent.md)) => undefined


> [!WARNING]
> This function can throw errors.


