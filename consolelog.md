# could-not-find-main-class:
ERROR]: Could not load 'plugins\RandomLocationv_4.79.jar' in folder 'plugins'
org.bukkit.plugin.InvalidPluginException: Cannot find main class `me.xADudex.java.JavaProject.Main'
        at org.bukkit.plugin.java.PluginClassLoader.<init>(PluginClassLoader.java:66) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        at org.bukkit.plugin.java.JavaPluginLoader.loadPlugin(JavaPluginLoader.java:129) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        at org.bukkit.plugin.SimplePluginManager.loadPlugin(SimplePluginManager.java:326) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        at org.bukkit.plugin.SimplePluginManager.loadPlugins(SimplePluginManager.java:248) [spigot.jar:git-Spigot-5695bca-53fccdf]
        at org.bukkit.craftbukkit.v1_12_R1.CraftServer.loadPlugins(CraftServer.java:308) [spigot.jar:git-Spigot-5695bca-53fccdf]
        at net.minecraft.server.v1_12_R1.DedicatedServer.init(DedicatedServer.java:205) [spigot.jar:git-Spigot-5695bca-53fccdf]
        at net.minecraft.server.v1_12_R1.MinecraftServer.run(MinecraftServer.java:545) [spigot.jar:git-Spigot-5695bca-53fccdf]
        at java.lang.Thread.run(Unknown Source) [?:1.8.0_144]
Caused by: java.lang.ClassNotFoundException: me.xADudex.java.JavaProject.Main
        at java.net.URLClassLoader.findClass(Unknown Source) ~[?:1.8.0_144]
        at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:101) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:86) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_144]
        at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_144]
        at java.lang.Class.forName0(Native Method) ~[?:1.8.0_144]
        at java.lang.Class.forName(Unknown Source) ~[?:1.8.0_144]
        at org.bukkit.plugin.java.PluginClassLoader.<init>(PluginClassLoader.java:64) ~[spigot.jar:git-Spigot-5695bca-53fccdf]
        ... 7 more
