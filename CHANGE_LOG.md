# Active Texture Management :: Change Log

* 2014-0107: 2-9-aggressive (rbray89) for KSP 0.7.3
	+ Fixed TGA reading.
	+ Added PorkWorks
	+ Contains a config file for aggressive texture reduction (halve all textures, compress all non-normalmaps, and don't generate mip-maps for normalmaps)
* 2014-0105: 2-8-aggressive (rbray89) for KSP 0.7.3
	+ Moved to new config mechanism
	+ Fixed minor *_NRM.tga file issue.
	+ Contains a config file for aggressive texture reduction (halve all textures, compress all non-normalmaps, and don't generate mip-maps for normalmaps)
* 2014-0102: 2-7-aggressive (rbray89) for KSP 0.7.3
	+ Changes to handle normal maps properly.
	+ Contains a config for aggressive texture resizing/compression.
* 2013-1231: 2-6-aggressive (rbray89) for KSP 0.7.3
	+ Added code to protect small textures.
	+ Aggressive configuration.
* 2013-1231: 2-5-aggressive (rbray89) for KSP 0.7.3
	+ Moved to a method that does NOT generate files on disk. Should automatically revert mbmbs back.
	+ Automatically compresses all textures, extra options available if folders are added.
	+ Contains a config for very aggressive texture re-sizing/compression.
* 2013-1229: 2-4 (rbray89) for KSP 0.7.3
	+ Updated config to remove alpha conversion.
* 2013-1229: 2-3 (rbray89) for KSP 0.7.3
	+ Added code for reversion to mbm and explicit folder includes
	+ Hotfix to remove normalmap converion.
	+ Hotfix to actually apply texture resizing.
	+ Allows users to manage all aspects of texture loading.
	+ Increases start-up considerably in some cases, but allows LOTS of memory to be saved in the process.
	+ Config allows many texture parameters to be controlled.
	+ Log shows the end-state of textures and how much memory is saved.
* 2013-1229: 2-2 (rbray89) for KSP 0.7.3
	+ Hotfix to remove normalmap converion.
	+ Hotfix to actually apply texture resizing.
	+ Allows users to manage all aspects of texture loading.
	+ Increases start-up considerably in some cases, but allows LOTS of memory to be saved in the process.
	+ Config allows many texture parameters to be controlled.
	+ Log shows the end-state of textures and how much memory is saved.
* 2013-1229: 2-1 (rbray89) for KSP 0.7.3
	+ Hotfix to actually apply texture resizing.
	+ Allows users to manage all aspects of texture loading.
	+ Increases start-up considerably in some cases, but allows LOTS of memory to be saved in the process.
	+ Config allows many texture parameters to be controlled.
	+ Log shows the end-state of textures and how much memory is saved.
* 2013-1228: 2-0 (rbray89) for KSP 0.7.3
	+ Allows users to manage all aspects of texture loading.
	+ Increases start-up considerably in some cases, but allows LOTS of memory to be saved in the process.
	+ Config allows many texture parameters to be controlled.
	+ Log shows the end-state of textures and how much memory is saved.
* 2013-1130: 1-1 (rbray89) for KSP 0.7.3
	+ This release includes changes derived from sarbian's commit (f61eb139a4ecd55df2998b8a4ec9205bda66de8d).
* 2013-1120: 1 (rbray89) for KSP 0.7.3
	+ Initial Commit
