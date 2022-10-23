To get this into a usable state in the Unity editor:

You'll need Unity 2019.4.31f1 installed with android build tools (Quest VR headset is an android based platform).
Then download and install the VRC creator companion https://vrchat.com/download/vcc

Once that finishes and loads up, create a new project on the left side (world). And put that in your main Github 
directory (usually C:\users\<username>\Documents\GitHub) Name the project (in this instance) 
"MarsExplorer-VRE-Freestyle", and make sure it is being created in a folder of the same name right below the project. 

Now let it do its thing , and when it finishes on the right side there's a menu, scroll down til you see "UdonSharp". 
Add it to the project and wait a bit. When done, open the project from roughly the centre of the window. 
It'll take a little while to compile the scripts on the first-time run. 

In the meantime, open Github Desktop and clone https://github.com/FoxinTale/MarsExplorer-VRE-Freestyle into a folder, 
but remove the Freestyle leaving just "MarsExplorer-VRE". And now we wait for Unity to finish compiling. 
Once it does and the main window is visible with an empty scene, close both Unity and Github Desktop.
Now, copy and replace the contents of "MarsExplorer-VRE" into the other folder "MarsExplorer-VRE-Freestyle". 

Then delete the whole "MarsExplorer-VRE" folder and reopen Github Desktop. It'll complain about not being able to find the folder anymore, 
but just use the "locate" button to point it towards the "MarsExplorer-VRE-Freestyle" folder. 

Re-open Unity now via opening the project in VCC. Once it loads up, at the bottom bar should be a file window like thing with the contents of the assets folder visible.
Double click the scenes folder and drag the "SampleScene" over to the Heirarchy window on the left. Right click the "Untitled Scene" and remove it. 

The final step is, on the top look for a "VR Chat SDK" section on the ribbon. Click it and go down to "show control panel" click and drag this to the 
right side of the Unity window next to the Inspector tab and then sign in to VR Chat there. 

Hopefully, that is it. 



