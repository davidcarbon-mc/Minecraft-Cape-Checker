# Minecraft-Cape-Checker
Minecraft Cape Check Concept

# OptiFine
Use your Minecraft username
```
   url = "http://s.optifine.net/capes/" + username + ".png";
```

# LabyMod
Use UUID with dashes.
```
   url = "http://capes.labymod.net/capes/" + player.aK();
```

# MinecraftCapes.co.uk
Use your Minecraft username
```
   String CapeUrl = "https://minecraftcapes.co.uk/gallery/grab-player-capes/" + username;
```


# 5Zig (Defuct)
Use UUID without dashes.
```
   final MinecraftProfileTexture minecraftProfileTexture = new MinecraftProfileTexture("http://textures.5zig.net/textures/2/" + Utils.getUUIDWithoutDashes(gameProfile.getId()), new HashMap());
```

# Links
- OptiFine: http://s.optifine.net/capes/USERNAME.png
- LabyMod: http://capes.labymod.net/capes/USE-DASHES-UUID.png
- MinecraftCapes.co.uk: https://minecraftcapes.co.uk/gallery/grab-player-capes/USERNAME
- 5Zig: http://textures.5zig.net/textures/2/NODASHESUUID
