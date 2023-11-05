# NameSpace: MFPC.Input
## InputConfig
> 
##### Inherits from:
 - UnityEngine.ScriptableObject
---
### Fields
|type|name|docs|
|---|---|---|
|SensitiveData|initialSensitiveData|Initial Sensitivity settings. On subsequent launches, the settings will be loaded from saves.|
|InputType|initialInputType|Initial InputType settings. On subsequent launches, the settings will be loaded from saves (If this option enabled).|
|Boolean|adaptationInput|Controls adjust depending on what device the game was running on|

---
### Properties
|type|name|docs|
|---|---|---|
|Boolean|DebugMode|Enables display of current input|
|Boolean|AutoInputSwitch|Automatic input switching (From keyboard to gamepad and vice versa)|

---
### Methods
|type|name|docs|
|---|---|---|
|InputType|GetCurrentInputType| - |
|SensitiveData|GetSensitiveDataCopy| - |

