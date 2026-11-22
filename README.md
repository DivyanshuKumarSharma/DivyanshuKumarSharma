<h1>Divyanshu Kumar Sharma</h1>

<p>
  <strong>Software engineer</strong> · Game &amp; tools programming · Web development · New Brunswick, Canada
</p>

<p>
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Unreal Engine 5" src="https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white">
  <img alt="Unity" src="https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white">
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-1C1C1C?style=flat-square&logo=supabase&logoColor=3ECF8E">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square">
</p>

<p>
  <a href="https://www.linkedin.com/in/divyanshu-kumar-sharma-789890235"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
</p>

I like building the systems other people build on. In games that means replicated gameplay frameworks, editor tools and a game engine written from scratch in C++. Outside games I build full-stack web apps with React, TypeScript and Supabase, and small serverless projects on AWS. Most of my recent game work is in Unreal Engine 5 with C++, and I also work in Unity and C#.

---

## Software engineering

### [GD-Engine: a game engine and editor in modern C++](https://github.com/DivyanshuKumarSharma/GD-Engine-Proper)

A game engine written from the ground up in C++17, with no engine framework underneath, plus **CourseMaker**, a no-code editor built on it for designing first-person shooting courses. The engine has an OpenGL 3.3 renderer with a render queue and custom shaders, component-based scenes with JSON serialization and prefabs, Bullet physics, audio, FreeType text and glTF model loading. The editor is a docking Dear ImGui app that is linked only into CourseMaker, so the runtime has no dependency on it. The project builds with CMake and has automated tests run through CTest.

`C++17` `OpenGL` `CMake` `CTest` `Bullet Physics` `Dear ImGui` `glTF` `JSON serialization`

### [Asset Auditor](https://github.com/DivyanshuKumarSharma/AssetAuditor)

An Unreal Engine 5 editor plugin that scans a project for content problems (naming conventions, texture budgets, missing LODs or collision, unused assets) and fixes most of them in one click. One core runs behind four front ends: a Slate panel, save-time Data Validation, console commands, and a CI commandlet with a pass/fail exit code. New rules are a single class, discovered by reflection.

`UE 5.6` `C++` `Slate` `Asset Registry` `Data Validation` `CI` `Automation tests`

---

## Web and cloud

### [Game Review Platform](https://github.com/DivyanshuKumarSharma/Game-Review-WebApp)

A web app for reviewing games and finding what to play next, with game detail pages, a review form, a leaderboard, recommendations (top rated, trending and hidden gems) and radar charts of review scores. Built with React and TypeScript on Vite and Tailwind CSS, with a Supabase Postgres back end secured by row-level security policies, plus a Node script that imports game data from the RAWG API.

`React` `TypeScript` `Vite` `Tailwind CSS` `Supabase` `PostgreSQL` `REST APIs`

### [Alexa Goal Alert](https://github.com/DivyanshuKumarSharma/Alexa-Goal-Alert)

A serverless app built for the FIFA World Cup 2026 that makes an Echo Dot play a sound whenever a goal is scored. EventBridge runs a Node.js Lambda every minute, DynamoDB stops duplicate alerts, and a Sinric Pro virtual sensor triggers an Alexa Routine.

`AWS Lambda` `Node.js` `DynamoDB` `EventBridge` `AWS SAM`

---

## Game development

### [AbilityLab: multiplayer Gameplay Ability System kit](https://github.com/DivyanshuKumarSharma/UE5-Gameplay-Ability-System-Tool)

A network-correct GAS setup written in C++. Health and Stamina attributes, a client-predicted Dash driven by root motion, a server-spawned Projectile that deals damage through Gameplay Effects, replicated death and respawn, and a C++-backed HUD that reacts to GAS delegates. Tested with a listen server and client under network emulation.

`UE 5.6` `C++` `GAS` `Replication` `Client prediction` `Gameplay Tags` `UMG`

### [InteractionLab: drop-in interaction system](https://github.com/DivyanshuKumarSharma/UE5-Interaction-System)

A reusable, server-authoritative interaction plugin. Any actor can become interactable (doors, levers, pickups, Blueprint-only props) with focus detection, outline highlighting, input-aware prompts, and press or hold to interact. The server validates reach, line of sight and hold time, and designers create new interactables in Blueprint without touching C++.

`UE 5.6` `C++` `Plugin architecture` `Server RPCs` `RepNotify` `Slate` `Post-process`

### More

- [**Hawktober Game Jam 2024**](https://github.com/DivyanshuKumarSharma/Hawktober_Game_Jam_2024): a Unity / C# game made for the Hawktober 2024 game jam.

---

## Toolbox

- **Languages:** C++, C#, TypeScript, JavaScript / Node.js, Python, SQL
- **Web:** React, Vite, Tailwind CSS, Supabase (PostgreSQL, row-level security), REST APIs
- **Cloud:** AWS (Lambda, DynamoDB, EventBridge, SAM)
- **Engines and graphics:** Unreal Engine 5, Unity, OpenGL, Dear ImGui, Bullet Physics
- **Unreal:** Gameplay Ability System, replication and RPCs, Enhanced Input, Slate, UMG, editor plugins, commandlets
- **Engineering:** Git, CMake, automated testing, CI checks, Visual Studio

---

## Get in touch

The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/divyanshu-kumar-sharma-789890235).
