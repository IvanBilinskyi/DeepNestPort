# DeepNestPort
DeepNest C# Port (https://github.com/Jack000/Deepnest)

DXF Import/Export: https://github.com/IxMilia/Dxf

Also take a look at the WPF Net.Core version: https://github.com/9swampy/DeepNestSharp 

<img src="imgs/2.png"/>
<img src="imgs/3.png"/>


## Compiling minkowski.dll (optional)
1. Replace <boost_1.62_path> with your real BOOST (1.62) path in compile.bat

Example:
```
cl /Ox ..... -I "C:\boost_1_62_0" /LD minkowski.cc
```
2. Run compile.bat using Developer Command Prompt for Visual Studio
3. Copy minkowski.dll to DeepNestPort.exe folder

## Contributors
* https://github.com/Daniel-t-1/DeepNestPort (dxf export)
* https://github.com/9swampy/DeepNestPort (simplification features)
