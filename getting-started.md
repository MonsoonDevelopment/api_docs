---
description: How to create a base module, and get it showing up in Monsoon!
---

# Getting Started

Navigate to your `/.minecraft/` directory. In there, assuming you have run Monsoon already (which you should have), you will see a directory named 'monsoon'. Navigate into here, and you should see a 'scripts' directory. Navigate once more into this 'scripts' folder, and make a new file.

Name this file "\[name of module].monsoon.lua". This will mark it as a Monsoon script.

Open this file in a text editor of your choice. I recommend Visual Studio Code (with appropriate plugins), but others, such as Notepad++ and Sublime will probably work fine.

To start, we need to register the module. This can be done like so:

```lua
manager:registerModule('TestModule', 'Description', newModule({
    
    })
}
```

If you now launch Monsoon, you should see this module appear under the scripting category!
