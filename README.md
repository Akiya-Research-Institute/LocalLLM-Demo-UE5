# UE5.4 demo project for Local LLM plugin

This is a UE5.4 project for demonstration of [Local LLM plugin](https://www.unrealengine.com/marketplace/product/b349cc8c5ef840ac90cd08d0ee59a89d).

Local LLM plugin allows to load a large language model (LLM) of GGUF format and run it on Unreal Engine.

<!-- [![Youtube demo](http://img.youtube.com/vi/mmMDhH0ueyI/0.jpg)](https://www.youtube.com/watch?v=mmMDhH0ueyI) -->

## Download packaged build

You can download packaged build of this demo project from [here](https://taguchishouji-my.sharepoint.com/:u:/g/personal/kasa_taguchishouji_onmicrosoft_com/ESClVDJjABVLiLirpkfZtq8BWPnXzVzDzFgBdWiZQ4B5FQ?e=TNJBQW).

## System Requirements

- Windows 64bit
- Unreal Engine 5.4.2
- Local LLM plugin v1.0 or above

If you want to run with a GPU,

- CUDA: 12.2.0

## How to use this demo

1. Clone this repo <!-- : `git clone git@github.com:Akiya-Research-Institute/WhisperRealtime-Demo.git` -->
2. Open `LocalLLM_Demo/LocalLLM_Demo.uproject`
3. Click `Content Drawer > Add > Add Feature or Content Pack...` 
4. Select `Third Person` on Blueprint tab and click `Add to Project`
5. Restart Unreal Editor.
6. Click `Play` on Unreal Editor.

![DemoSetup](https://user-images.githubusercontent.com/89242761/210740516-161fd325-3f75-41dd-8f34-77f6e1942c53.gif)

Demo project contains 2 maps.

- /Content/LocalLLMDemo/Map/ChatDemo_One
  Demonstration of conversation with one NPC

- /Content/LocalLLMDemo/Map/ChatDemo_Multi
  Demonstration of conversation with two NPC

When you reach to the characters, the dialogue UI automatically appears.
