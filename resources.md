# RESOURCES

TA: Li Yao <lyao@saic.edu>

# PRESENTATION IDEAS AND TOPICS
To find the article you would like to present, look on the following resources.
* SIGGRAPH
*  Leonardo on line
* Leonardo MIT press
* IEEE VR 2017 - IEEE VR 2016 - IEEE VR 2015 - IEEE VR 2014
* 3DUI 2015 - 3DUI 2014 - 3DUI 2013
* Presence (MIT Press)
* IEEE Xplore
* scholar.google.com


# LEARNING & TUTORIALS
1. Lynda.com
Maya tutorials once logged into Lynda you can find more tutorials here
https://youtu.be/r_QvUDcsAF0
Unity Tutorials
Substance (youtube and Lynda)


HARDWARE
PC or Mac capable or running Uniity 3D and Maya
3 button mouse

SOFTWARE
You are free to use any tool that best fits your interests and level of comfort, but will cover the topics in class with the following tools:
Maya for Modeling and animation
Photoshop for texture editing
Substance Designer
Audacity for sound
Unity 3D for developing the environments
HTC VIVE & Middle VR or equivalent (TBD) for interaction and tracking

For generation VR objects and models for the class we will be using Maya
http://www.autodesk.com/education/free-software/maya
Free student version
Runs on Mac & WIndows
Need a 3 button mouse
Exports models and animation as fbx format directly to Unity
Many tutorials and documentation are available online

If you know another tool and can generate compatible fbx models then it is fine to use Blender or 3DStudioMax.

There are many different 3D model formats which can be mostly converted to other formats. Autodesk FBX Converter works quite well in converting different model formats to fbx format
http://usa.autodesk.com/adsk/servlet/pc/item?siteID=123112&id=22694909
Command Line and UI versions

Some things to think about when creating your models:
its best to make your models the correct scale within the modelling package. Unity uses 1 unit = 1 meter as its default. You can scale them in software later if you need to but its easier to start with everything at the same scale
Units = Game Units Meters per Game Unit = 1

think about where the 0,0,0 point is (pivot point) for your object since that is where the center of rotation will be, and you also want to make it easy to position objects in the space.

make sure the texture length and width are powers of 2, e.g. 128, 256, 512, 1024 pixels - most apps can handle textures of any size but making the size powers of two ensures you are compatible with a wider range of software

If your project includes free public domain models and textures. jpg and png are probably the safest texture formats. Remember to write down where you took your models and textures from to credit the source in your documentation.

Its highly recommended to test out your models often in Unity and in the CAVE / Oculus. Sometimes you need to turn on two-sided faces for all of the surfaces to show up. Sometimes the colours or textures don't make it through conversion. Often the model or total number of models is too heavy and slows the application down and you need to simplify the models.
Expect to have to make changes. Test in the CAVE or Rift regularly to make sure your final product will work as you expect it to.

For creating the VR worlds for the class we will be using Unity
https://unity3d.com
Free student version
Runs on Mac & Windows
Can develop on a laptop and run on laptop, stereo TV, Oculus Rift, CAVE, etc
Handles fbx (primary format) and obj 3D model formats

There are several online tutorials and great documentation about Unity on the web.

For shader generation we will use Substance Designer
https://www.allegorithmic.com/buy
Students & Teachers: free personal license, valid one year (renewable), for use at home or on a personal machine
Runs on Mac and windows
Node-based non-destructive application for material authoring. Edit complete texture sets fast with the non-linear workflow and see your changes apply simultaneously to all your outputs.
It will be useful for the generation of highly customizable real time Physically Based Rendering (PBR) shaders

For VR integration we will start with the HTC Vive and Middle VR
https://unity3d.com/learn/tutorials/topics/virtual-reality/movement-vr
http://www.middlevr.com/middlevr-for-unity/
https://unity3d.com/learn/tutorials/topics/virtual-reality/vr-overview

PORTING TO CAVE2
https://github.com/uic-evl/omicron-unity/wiki/Guide-for-running-Unity-in-CAVE2


Structure from motion software [Recommended by Dan Sandin]
Inexpensive software system
http://ccwu.me/vsfm/install.html
http://www.agisoft.com/buy/online-store/educational-license/

links to the free open source software
http://ccwu.me/vsfm/install.html
http://ccwu.me/vsfm/doc.html


