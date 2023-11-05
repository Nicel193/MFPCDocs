# NameSpace: MFPC
## PlayerData
> Stores player config.
##### Inherits from:
 - UnityEngine.ScriptableObject
---
### Properties
|type|name|docs|
|---|---|---|
|PlayerStates|AvailablePlayerStates|Determines available player states.|
##### Move
||||
|---|---|---|
|Vector2|RangeCameraRotationVertical|Range of vertical camera rotation.|
|Single|WalkSpeed|Walk speed of the player.|
|Single|Gravity|Gravity affecting the player.|
|Boolean|AirControl|When AirControl is enabled, then the player can control the direction of flight.|
|Boolean|MoveInertia|When inertia is enabled, the player starts and ends the movement smoothly.|
|Single|Deceleration|The speed at which the player stops.|
|Single|Acceleration|The speed at which the player starts moving.|
##### Run
||||
|---|---|---|
|Single|RunSpeed|Running speed of the player.|
|Boolean|IncreaseFOV|When IncreaseFOV is enabled, the FOV (field of view) is increased while running.|
|Single|RunFOV|FOV value while running.|
|Single|SpeedChangeFOV|Speed of FOV change.|
##### Jump
||||
|---|---|---|
|Single|JumpForce|Jump force applied to the player.|
|AudioClip|JumpSFX|Sound effect played when jumping.|
|Single|UnderRayDistance|Distance of the ray under the player to check ground.|
##### Sit
||||
|---|---|---|
|Single|SitWalkSpeed|Crouch walk speed of the player.|
|Single|SitHeight|CharacterController height when character is crouched.|
|Single|ChangeSitSpeed|Rate of altitude change.|
|Single|RayDistance|Length of the ray checking space above the player.|
|AudioClip|SitSFX|Sound effect played when sitting and standing up.|
##### Ladder
||||
|---|---|---|
|Single|ClimbSpeed|The speed at which a character climbs ladder.|
|Single|NormalizationSpeed|Character movement speed to the center of the ladder.|
|Single|NormalizationRotateSpeed|Character rotate speed to the center of the ladder.|
|Vector2|RangeCameraRotation|Range of camera vertical rotation while climbing the ladder.|
|AudioClip|ClimbSFX|Sound effect played when climbing the ladder.|
##### Lean
||||
|---|---|---|
|Single|LeanAngle|Angle at which the player leans.|
|Single|LeanOffsetPositionX|Position offset while leaning.|
|Single|LeanSpeed|Speed of leaning.|
|Single|LeanMoveSpeed|Speed of player movement while leaning.|

---
### Methods
|type|name|docs|
|---|---|---|
|Boolean|IsAvailableState|Checks if a given player state is available.|

