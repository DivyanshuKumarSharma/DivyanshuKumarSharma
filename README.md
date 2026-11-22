<h1>Divyanshu Kumar Sharma</h1>

<p>
  <strong>Gameplay &amp; tools programmer</strong> · Unreal Engine 5 · C++ · New Brunswick, Canada
</p>

<p>
  <img alt="Unreal Engine 5" src="https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Unity" src="https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white">
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square">
</p>

<p>
  <a href="https://www.linkedin.com/in/divyanshu-kumar-sharma-789890235"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
</p>

I build the systems underneath a game: replicated gameplay abilities, reusable interaction frameworks, and editor tools that catch content problems before they ship. Most of my recent work is in Unreal Engine 5 with C++. I also work in Unity and C#, and I build small cloud projects when something in everyday life needs automating.

---

## Featured projects

### [Asset Auditor](https://github.com/DivyanshuKumarSharma/AssetAuditor)

An Unreal Engine 5 editor plugin that scans a project for content problems (naming conventions, texture budgets, missing LODs or collision, unused assets) and fixes most of them in one click. The same rules run in a Slate panel, on save through Data Validation, and in CI through a commandlet with a pass/fail exit code. New rules are a single class, discovered by reflection.

`UE 5.6` `C++` `Slate` `Asset Registry` `Data Validation` `Commandlets` `Automation tests`

### [AbilityLab: multiplayer Gameplay Ability System kit](https://github.com/DivyanshuKumarSharma/UE5-Gameplay-Ability-System-Tool)

A network-correct GAS setup written in C++. Health and Stamina attributes, a client-predicted Dash driven by root motion, a server-spawned Projectile that deals damage through Gameplay Effects, replicated death and respawn, and a C++-backed HUD that reacts to GAS delegates. Tested with a listen server and client under network emulation.

`UE 5.6` `C++` `GAS` `Replication` `Client prediction` `Gameplay Tags` `UMG`

### [InteractionLab: drop-in interaction system](https://github.com/DivyanshuKumarSharma/UE5-Interaction-System)

A reusable, server-authoritative interaction plugin. Any actor can become interactable (doors, levers, pickups, Blueprint-only props) with focus detection, outline highlighting, input-aware prompts, and press or hold to interact. The server validates reach, line of sight and hold time, and designers create new interactables in Blueprint without touching C++.

`UE 5.6` `C++` `Plugin architecture` `Server RPCs` `RepNotify` `Slate` `Post-process`

### [Alexa Goal Alert](https://github.com/DivyanshuKumarSharma/Alexa-Goal-Alert)

A serverless app built for the FIFA World Cup 2026 that makes an Echo Dot play a sound whenever a goal is scored. EventBridge runs a Node.js Lambda every minute, DynamoDB stops duplicate alerts, and a Sinric Pro virtual sensor triggers an Alexa Routine.

`AWS Lambda` `Node.js` `DynamoDB` `EventBridge` `AWS SAM`

### More

- [**Hawktober Game Jam 2024**](https://github.com/DivyanshuKumarSharma/Hawktober_Game_Jam_2024): a Unity / C# game made for the Hawktober 2024 game jam.

---

## Toolbox

- **Engines:** Unreal Engine 5, Unity
- **Languages:** C++, C#, JavaScript / Node.js, Python
- **Unreal:** Gameplay Ability System, replication and RPCs, Enhanced Input, Slate, UMG, editor plugins, commandlets
- **Tools and cloud:** Git, Visual Studio, AWS (Lambda, DynamoDB, EventBridge, SAM)

---

## Get in touch

The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/divyanshu-kumar-sharma-789890235).
