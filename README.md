# GIFLIB for UE4 Plugin.

## In Develop...

### How to build giflib.

#### Windows 10 64bit

1. `git clone https://github.com/ryugibo/UEgiflib.git` in your plugin directory.
2. `git submodule init ;git submodule update`
3. `cd Plugins/UEgiflib/Source/ThirdParty/Giflib/giflib`
4. `cmake -G "Visual Studio 15 2017 Win64" ./`
5. `cmake --build ./ --config Release`

#### MacOS 10.13.2

1. `git clone https://github.com/ryugibo/UEgiflib.git` in your plugin directory.
2. `git submodule init ;git submodule update`
3. `cd Plugins/UEgiflib/Source/ThirdParty/Giflib/giflib`
4. `cmake -G "Xcode" ./`
5. `cmake --build ./ --config Release`

### Reference Sites.

1. https://sourceforge.net/projects/giflib/
1. https://github.com/aseprite/giflib
1. http://dlib.net/dlib/image_loader/load_image.h.html
1. https://luapower.com/giflib
