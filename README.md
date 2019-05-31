# Lit Master Node Demo Project

**Read the official [Blog Post](https://blogs.unity3d.com/2018/12/19/unity-2018-3-shader-graph-update-lit-master-node/).**

**This Project is intended to work with Unity release [2013.3](https://unity3d.com/get-unity/update).**

With the release of 2018.3, Shader Graph introduces a new Master Node for the High Definition Render Pipeline. 
This new Master Node (called Lit Master) makes many of the advanced shading features found in HDRP accessible in Shader Graph!

This demo project makes use of Shader Graph and the High Definition Render Pipeline. It contains a bonsai tree and butterfly to showcase using iridescence 
and translucency with shadergraph.

For additional example projects check out Andy Touch’s [Shader Graph Example Library](https://github.com/UnityTechnologies/ShaderGraph_ExampleLibrary)!

If you want to talk to us about the Shader Graph, check out the [forums](https://forum.unity.com/threads/feedback-wanted-shader-graph.511960/) and stay tuned to the blog for more exciting updates!

**Bugs**: If when first launching shaders look incorrect (such as the butterfly being flat blue) open the associated Shader Graph (all shader graphs in the folder ShaderGraphShaders) and click the **Save Asset** button in the top left of the Shader Graph Window.

**Note**: this project demos multiple features that are still in Preview, meaning they introduce brand new features and workflows. As such, some of these features may be subject to change (API, UX, scope, etc.) and aren’t covered by traditional Unity support. 
You can, however, report issues with Preview features on our [forum](https://forum.unity.com/forums/graphics-experimental-previews.110/?_ga=2.75910933.1446511377.1522795261-1647295365.1509665782) page.

Instructions
------------
**Important! This Project uses git-lfs to store large file types!**

Quick instructions for people familiar with Git
1. Install [Git LFS](https://git-lfs.github.com/)
2. Clone this repository somewhere to disk
3. run `git lfs install` to initialize Git LFS
4. Launch with Unity version [2018.3](https://unity3d.com/get-unity/update)

Longer instructions for people new to Git
1. Locate the green button that says **Clone or Download**. Select it.
2. Select **Open in Desktop.** That will launch https://desktop.github.com/. 
3. Locate the Purple **Download** button, select it. This will download GitHubDesktopSetup.exe, launch that exe after it downloads.
4. Once it installs, launch it or allow it to auto launch. You should see three buttons in the middle of the GitHub Desktop Window. Select the third button, **Clone a repository**.
5. This will bring up a popup window, select the third tab **URL**.
6. Where is says *URL or username/repository* add https://github.com/natalieburke/ShaderGraphFeatureDemo_LitMasterNode.
7. **Choose** a Local path or use the auto created one.
8. Select **Clone**. Wait a little.
9. When this finishes another popup will appear that says Initialize Git LFS. This is important, make sure you select **Initialize Git LFS** (Blue button).
10. The project is now on your machine at the location selected as the Local path from step 7.
11. Launch the project with Unity version [2018.3](https://unity3d.com/get-unity/update)


Acknowledgement
---------------

The textures on the butterfly are created based on photogtraphs by Didier Descouens and are under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.en) license (CC BY-SA 4.0).

Please see the following page for further details.

https://commons.wikimedia.org/wiki/File:Morpho_didius_Male_Dos_MHNT.jpg
