---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.PistonActivateEventSignal Class
description: Contents of the mojang-minecraft.PistonActivateEventSignal class.
---
# PistonActivateEventSignal Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

Manages callbacks that are connected to piston activations.


## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)
  
### **subscribe**
`
subscribe(callback: (arg: PistonActivateEvent) => undefined): (arg: PistonActivateEvent) => undefined
`

Adds a callback that will be called when a piston expands or retracts.
#### **Parameters**
- **callback**: (arg: [*PistonActivateEvent*](PistonActivateEvent.md)) => undefined

#### **Returns** (arg: [*PistonActivateEvent*](PistonActivateEvent.md)) => undefined


### **unsubscribe**
`
unsubscribe(callback: (arg: PistonActivateEvent) => undefined): void
`

Removes a callback from being called when a piston expands or retracts.
#### **Parameters**
- **callback**: (arg: [*PistonActivateEvent*](PistonActivateEvent.md)) => undefined


> [!WARNING]
> This function can throw errors.


