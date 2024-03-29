#Ecosystem Change log

###0.4.2
**New:** [Snipt](https://snipt.net/) online repository initiative for simple scripts and easier publishing for contributors  

**Improvement:** Renamed "github" UI button "Preview" to be agnostic to the source itself.  
**Improvement:** Disclaimer page now features github and snipt links to inform people where content is pooled from 

**Fix:** *Server side*: Unity version tag for items, now content from Unity 5 online rep are tagged "Unity 5" properly

###0.4.1

**New:** Added "Github" button to open an item on Github. Very handy to reference and access content source.
**Fix:** Support for Unity 5 context. Warning some content will be obsolete nonnettes, especially physics based samples

###0.4.0
**Note:** **_Breaking Build_**. The "net.fabrejean" or the "jf_plugins" folder **MUST** be deleted first

**New:** MetaData download for documentation   
**New:** Youtube Link in Documentation when defined in metaData   
**New:** Youtube link on the disclaimer page  
**New:** Soft Integration of PlayMaker version check, to not throw error if PlayMaker not installed  
**New:** Visual feedback if PlayMaker is not installed, with button to open the asset store   
**New:** Version Type to match Unity and PlayMaker version info.  
**New:** Interactive versioning with Build being representative of the number of compilation.   
This is based on [InControl](https://github.com/pbhogan/InControl) by Patrick Hogan   
**New:** ChangeLog based on MarkDown. Ain't that funky, hyperlinks in regular Unity GUI!!! never seen that before :)  
**New:** Documentation of items using a png image, using PlayMaker documentation tool for actions and up to the discretion of publishers for other content  
( like screenshot of the component inspector, or even the game view or anything)   
 Dark and Light skin of Unity are supported with explicit path convention,   
 so the file path for doc images must be respected or it will not be found.   
**New:** IsDebugOn static public bool for surrounding classes to follow debug convention   
**New:** UI Update prompter and menus, currently only redirecting to the wiki page.

**Fix:** Fixed Editor Prefs, and improve prefs handling   
**Fix:** Fixed search errors and interface being locked when error is shown in interface.  
**Fix:** Fixed Server side search filtering when no filter is selected  
**Fix:** Fixed Guiskin for better alignment   
 
**Improvement:** Improved code base, make use of namespace to avoid potential conflict   
**Improvement:** started moving item based code into its own class to free up the browser class itself, make sense and will scale better  
**Improvement:** Dedicated [Trello board](https://trello.com/b/U0AH0SHy/ecosystem) to keep track of this overwhelming project :)   
**Improvement:** code is now using a repository for security   
**Improvement:** remove discrete bar glitch when recompiling   
**Improvement:** MarkDownGUI allow for custom guiskin and style   
**Improvement:** Ecosystem disclaimer uses MarkDown now   
**Improvement:** made the license text in small to gain space   


###0.3.0
**New:**	Package Item   


###0.2.0
**New:**	Template and Sample  
**New:**	Filtering of items

**Improvement:** custom search bar, to match the UI skin   
**Improvement:** better handling of debug logs with a proper settings to turn it on and off


###0.1.0
**Note:**	Initial Public Release 