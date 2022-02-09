# INTRODUCTION 
cat_tools is a python module made to decompress _tex.sc files of supercell games.
# RESULTS 
- successfully decompressed _tex.sc files in all released versions of brawl stars.
- successfully decompressed _tex.sc files in latest version of: clash of clans, clash royale, clash quest, clash mini, hayday pop, boom beach.
# INSTALLATION
in a terminal, type:
```
pip install cat_tools
```
# USAGE
```
from cat_tools import pycat
pycat.decodeSC(file="loading_tex.sc")
```
there is an option to save decompressed data in disk instead of memory, I really recommend it if you want to decompress large files. it is needed to extract images from it
```
from cat_tools import pycat
pycat.decodeSC(file="loading_tex.sc",use_disk=True)
```
# AUTHORS
- S.B#0056
# SPECIAL THANKS TO
- Selce#4792 for helping me with lzma
- XCoder Authors, I got join_image function from [XCoder](https://github.com/MasterDevX/XCoder), the output images were being wrongly made for some of the images in _tex.sc, so I looked at their code and noticed that they made a function called 'join_image'
# OTHERS
If you have any question, bug, or idea, contact me on discord.
# LICENSE
This tool is licensed under GPLV3
Like the GPL v2, GPL 3 is a strong copyleft license, meaning that any copy or modification of the original code must also be released under the GPL v3. In other words, you can take the GPL 3?d code, add to it or make major changes, then distribute your version. However, your version is subject to the same license requirements, meaning that it must be under GPL v3 as well ? anyone can see your modified code and install it for their own purposes.
