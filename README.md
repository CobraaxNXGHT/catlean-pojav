# catlean-pojav

this is how you can run catlean on pojav without crashes

https://www.mediafire.com/file/vwwgne5rzkot335/LTW.New.apk/file This renderer (Large Thin Wrapper OpenGL 4.6 +1.17) will be needed

https://github.com/ZalithLauncher/ZalithLauncher The Pojav you will need.


Install both and open Zalith


Install 1.21.4 Fabric and put:
https://modrinth.com/mod/fabric-api/version/0.119.2+1.21.4 Fabric API
https://modrinth.com/mod/fabric-language-kotlin/version/1.13.2+kotlin.2.1.20 Fabric Language Kotlin
https://catlean.fun/ And obviously catlean.

Put this into your mods folder, select Internal 17, then but the LTW renderer as your main renderer.

If needed, if its crashing when joining a world/server, use this JVM Argument:

-XX:-TieredCompilation -XX:+UseInterpreter
or
-noverify -XX:+DisableAttachMechanism

if all else fails, you can dm

deleteduser72727462873

on discord (my friends user because he knows more then I do 🤷‍♂️)
