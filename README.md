# UE5.4 demo project for Local LLM plugin

This is a UE5.4 project for demonstration of [Local LLM plugin](https://vrlab.akiya-souken.co.jp/en/products/localllmplugin/).

Local LLM plugin allows to load a large language model (LLM) of GGUF format and run it on Unreal Engine.

<!-- [![Youtube demo](http://img.youtube.com/vi/mmMDhH0ueyI/0.jpg)](https://www.youtube.com/watch?v=mmMDhH0ueyI) -->
![demo](https://github.com/Akiya-Research-Institute/LocalLLM-Demo-UE5/assets/89242761/73055101-19b8-4e32-9cbe-47b8e63def65)

## Download packaged build

You can download packaged build of this demo project from Releases.

## Software Requirements

- Windows 64bit
- Unreal Engine 5.4.2
- Local LLM plugin v1.0 or above

(Optinal) if you want to run with a GPU,

- CUDA: 12.2.0

## Hardware Reauirements

- A CPU that supports AVX, AVX2 and FMA.

  The following CPUs should work.

  - Intel: 4th Generation (Haswell) and above
  - AMD: All Ryzen series

(Optinal) if you want to run with a GPU,

- A NVIDIA GPU that supports CUDA 12.2.0

## How to use this demo

1. Clone this repo `git clone https://github.com/Akiya-Research-Institute/LocalLLM-Demo-UE5` -->
2. Open `LocalLLM_Demo/LocalLLM_Demo.uproject`
3. Click `Content Drawer > Add > Add Feature or Content Pack...` 
4. Select `Third Person` on Blueprint tab and click `Add to Project`
5. Restart Unreal Editor.
6. Click `Play` on Unreal Editor.

![DemoSetup](https://user-images.githubusercontent.com/89242761/210740516-161fd325-3f75-41dd-8f34-77f6e1942c53.gif)

Demo project contains 2 maps.

- /Content/LocalLLMDemo/Map/ChatDemo_One

  Demonstration of conversation with 1 NPC

- /Content/LocalLLMDemo/Map/ChatDemo_Multi

  Demonstration of conversation with 2 NPCs

When you get close to the characters, a dialog UI automatically appears.

