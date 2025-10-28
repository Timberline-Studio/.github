# 🌟Welcome to Timberline Studio!🌟

For Beastro, we had our own homebrew [coding standard](https://github.com/Timberline-Studio/TimberlineStandard), but will swap to the [Unreal Coding Standard](https://dev.epicgames.com/documentation/en-us/unreal-engine/epic-cplusplus-coding-standard-for-unreal-engine?application_version=5.6) for future projects.

The purpose of creating this Github org is to keep our modular code maintainable outside of a specific project's perforce stream depot. For our **proprietary plugins**, this will allow us to keep a good history of changes, mark up releases for certain projects, etc. For **Unreal Engine** code, it will simplify our merging/update process by helping us merge our custom changes a little bit faster.

## 🗄️Repositories 

### 🚙 Engine 
* Beastro's UE 5.6.1 - In Perforce
* [Unreal AngelScript](https://github.com/Timberline-Studio/Timberline-UE-AS) (Timberline Fork)

### 📐 Projects
**These projects are not meant to be tied to any in-development IP**. They are for discovery and ideation only. Official Projects will exist solely on Timberline Studio's perforce server.

* AS Sandbox
  * Sandbox project for tinkering with AngelScript in Unreal Engine

### 🔌 Plugins
#### 🌲 TS
* [Flume](https://github.com/Timberline-Studio/Flume)
  * Timberline's proprietary Narrative System, made for Unreal Engine.
* [Story Director](https://github.com/Timberline-Studio/StoryDirector)
* [Timberline Utilities](https://github.com/Timberline-Studio/TimberlineUtilities)
* [Timberline Gameplay Effect](https://github.com/Timberline-Studio/TimberlineGameplayEffect)
  * Gameplay Effect system created for Beastro's turn-based combat system.

#### 🛍️ Marketplace
* [RMA ImGui](https://github.com/Timberline-Studio/TS-RMA-ImGui)
  * Imgui plugin that is maintained and updated.
  * [We used a different plugin for Beastro](https://github.com/segross/UnrealImGui). It is very stale and gross.
