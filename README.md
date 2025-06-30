# cmatrix-hsp
Emulates cmatrix with [OpenHSP/Hot Soup Processor(HSP3)](https://github.com/onitama/OpenHSP)
# Screenshot
[!image](img/screenshot.png)
# Environment
Confirmed working with:
- HSP3.7beta10 at [9553278](https://github.com/onitama/OpenHSP/tree/9553278dde6659bc980721729971bde0e143bffa) on Ubuntu22.04.5 LTS.
- HSP3.6 at [3a3d192](https://github.com/OmeSatoFoundation/OpenHSP/tree/3a3d1928ac0776a759be6fc2c4acc3fe8c06e075) on [2025v1.0](https://github.com/OmeSatoFoundation/ome2023/releases/tag/2025v1.0)
# Tips
|instructions/functions|description|
|:---:|:---|
|sdim|defines string dimentional array|
|redraw|changes drawing mode|
|for|configurable repeat|
|rnd|generates a random number|
|poke|writes a data into a buffer|
|color|set color|
|boxf|draw a box on screen|
|pos|set position on screen|
|font|set font|
|peek|get a data from a buffer|
|strf|convert data to formatted string|
|wait|pause a program|
|goto|jump to flag|
