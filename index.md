<p>Here&#39;s how to make a Gorilla Tag Fan Game.</p>
<hr>
<p><strong>#1: Prerequisites</strong></p>
<ul>
<li>Download Unity Hub. Install it.</li>
<li>Download Visual Studio 2022. Install it.</li>
</ul>
<h1 id="section"></h1>
<p><strong>#2: Installing the Unity</strong></p>
<ul>
<li>Install the Unity Editor (Unity version 2021.3.20 or higher is recommended)</li>
</ul>
<h1 id="section-1"></h1>
<p><strong>#3: Creating the Project</strong></p>
<ul>
<li>Click on <strong>New Project</strong> in Unity Hub.</li>
<li>Make sure the <strong>“Editor Version”</strong> is the version you downloaded or the version you choose.</li>
<li>Select the <strong>“3D (Built-In Render Pipeline)” as the template.</strong></li>
<li>In the <strong>“Project Settings,”</strong> choose a name, the location where the project is going to be saved, and choose an <strong>“Unity Organization.”</strong> The check boxes for “Unity Cloud” and “Unity Version Control” are completely optional.</li>
<li>Then, just click on <strong>&quot;Create project&quot;</strong></li>
</ul>
<h1 id="section-2"></h1>
<p><strong>#4: Project Setup</strong></p>
<ul>
<li>
<p>After Unity loads, there might be an “Unity Editor Update Check,” just click on “Skip new version.”</p>
</li>
<li>
<p>In the “Project” tab, go into the “Scenes” folder and Right-Click, “Create” &gt; “Scenes” &gt; “Scene.” I’d recommend naming the Scene “Main Scene.”</p>
</li>
<li>
<p>Double-click on the scene you just created, and it will load into it. Then, delete the “Sample Scene.”</p>
</li>
<li>
<p>Now, go to “Edit” &gt; “Project Settings…”</p>
</li>
<li>
<p>Go down to “XR Plugin Management” and click on it, then click on “Install XR Plugin Management.”</p>
</li>
<li>
<p>After it’s done installing, in the PC tab click on “Open XR.” If it shows a dialog where it tells you to restart Unity, restart Unity.</p>
</li>
<li>
<p>Then, click on the Android tab, and click on “Oculus.”</p>
</li>
<li>
<p>In the dropdown of “XR Plug-in Management,” click on “Oculus.”</p>
</li>
<li>
<p>In the PC tab, for “Stereo Rendering Mode,” set it to “Multi Pass,” and in the Andriod tab, set the “Stereo Rendering Mode” to “Multi Pass.” Also, click on the checkbox for “Low Overhead Mode (GLES).” I would strongly recommend toggling all of the “Target Devices,” or else if you play your game on that device, it will likely not work.</p>
</li>
<li>
<p>In the “OpenXR” dropdown, in the PC tab, set the “Render Mode” to “Multi-pass,” and select the “Interaction Profiles.” I’d <strong>STRONGLY</strong> recommend selecting:</p>
<ul>
<li>HTC Vive Controller Profile</li>
<li>Oculus Touch Controller Profile</li>
<li>Meta Quest Touch Plus Controller Profile</li>
<li>HP Rever G2 Controller Profile</li>
<li>Meta Quest Touch Pro Controller Profile</li>
<li>Valve Index Controller Profile</li>
</ul>
</li>
<li>
<p>In the “Android” tab, set the “Rendering Mode” to “Multi-pass,” and select the following:</p>
<ul>
<li>Oculus Touch Controller Profile</li>
<li>Meta Quest Touch Plus Controller Profile</li>
<li>Meta Quest Touch Pro Controller Profile</li>
</ul>
</li>
<li>
<p>You can then close the “Project Settings” window.</p>
</li>
<li>
<p>Then in the ribbon at the top of the screen, go to “Window” &gt; “Package Manger.”</p>
</li>
<li>
<p>Click on the “Unity Registry,” and search up: “XR Interaction Toolkit.” Click on “Download” then “Install.”</p>
</li>
<li>
<p>Then go to the “Samples” dropdown, then click on: “Starter Assets.” Click on “Import.”</p>
</li>
<li>
<p>Then go to “Assets” &gt; “Samples” &gt; “XR Interaction Toolkit” &gt; <em>Whatever version the toolkit  is for you</em> &gt; “Starter Assets” &gt; “Presets.” Install all of them.</p>
</li>
<li>
<p>Then, go to “Edit” &gt; “Project Settings”, then go to “Preset Manager.”</p>
</li>
<li>
<p>Find “ActionBasedController” (or “ControllerInputActionManager”)</p>
</li>
<li>
<p>In “XRI Default Right Controller,” type in “right”, no capitals.</p>
</li>
<li>
<p>In “XRI Default Left Controller,” type in “left”, no capitals.</p>
</li>
<li>
<p>You can close the “Project Settings” window.</p>
</li>
<li>
<p>Now, download this [Gorilla Tag Locomotion Unity package made by <a href="https://www.youtube.com/channel/UCbDcvzNi48_yY-PnTxSVDuQ">‘GorillaBrian’</a>.(<a href="https://filebin.net/9qdi7172g46v4e2d/Upgraded%20Gorilla%20Locomotion%20V1.unitypackage">https://filebin.net/9qdi7172g46v4e2d/Upgraded Gorilla Locomotion V1.unitypackage</a>)</p>
</li>
<li>
<p>Then in Unity, right-click in the “Assets” window, and click on: “Import Package” &gt; “Custom Package…” Find “Upgraded Gorilla Locomotion V1.unitypackage.”</p>
</li>
<li>
<p>A window should popup, click on “Import.”</p>
</li>
<li>
<p>In the “Heirarchy,” delete the “Main Camera.”</p>
</li>
<li>
<p>In “Assets,” go to “Upgraded Gorilla Locomotion V1” &gt; “Prefabs,” and drag in “Gorilla Rig” into the “Heirarchy.”</p>
</li>
<li>
<p>Click on the “Gorilla Rig” and in the “Inspector,” set the &quot;Position to &quot; <em>0, 0, 0.</em></p>
</li>
<li>
<p>To test the game, Add a “Plane” by right-clicking in the “Heirarchy” &gt; “3D Object” &gt; “Plane.”</p>
</li>
<li>
<p>If you have a Link cable, connect your VR headset to your computer, and click on the Play button in Unity.</p>
</li>
<li>
<p>To build the project to Oculus, go to “File” &gt; “Build Settings.” (or “Build Profiles”)</p>
</li>
<li>
<p>Click on “Android™,” and click on “Switch Platform.”</p>
</li>
<li>
<p>Set the “Texture Compression” to “ATSC.”</p>
</li>
<li>
<p>Set “Run Device” to “All compatible devices.”</p>
</li>
<li>
<p>When ready, click on “Build.”</p>
</li>
</ul>
<h1 id="section-3"></h1>
<p>This concludes the tutorial. You can add additional things like, PhotonVR, horror, and so much more.</p>
