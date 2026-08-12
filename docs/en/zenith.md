# Zenith

<!-- brief intro -->

Sushi: Zenith entered open beta on July 19, 2026. It is a laid-back modpack focused on **survival, exploration, and building**. The server is still under active development.

---

## Joining Guide {#guide-join}

> This guide helps you install the Sushi: Zenith modpack and configure the necessary settings.

### Installing the Modpack

First, join the Sushi QQ group: **`1045084460`**

In the group files, find the modpack folder, locate "Zenith", and **download the latest version**.

Then, **install the modpack into your Minecraft launcher**. Generally, you can drag the modpack file into your launcher window.

The installation **requires an internet connection**. If you have trouble downloading game files or mods, try again a few times.

!!! note "About Launchers"

    The official Minecraft launcher cannot install third-party modpacks. We recommend using a third-party launcher.

### Configuring the Modpack

After installation, go to the modpack's **settings**, find `JVM arguments`, and enter:

```JVM
-javaagent:patch.jar
```

For specific launcher setting guide, please refer to the launcher's official docs.

!!! note "Why there's no image guide?"
    
    We re sorry but our development team have no experience of using a non-Chinese Minecraft launcher. If you're interested in contributing image guide, please contact us via QQ.
    
!!! warning "Important Notes"
    1. Make sure to set the JVM parameter in the **modpack's version settings**, not the global launcher settings. If you put it in the global settings, you won't be able to play other Minecraft versions normally.
    2. On **Windows**, the modpack installation path must contain **only ASCII characters**. If your `.minecraft` folder path contains non-ASCII characters (e.g., your Windows username contains Japanese Kana characters), see the [Services](#update-service) section below for help.

This parameter connects your game to the SushiMC update service and keeps your client on the latest version.

### Login methods

For safety and compatibility, Sushi: Zenith only allow players to log in through [LittleSkin](https://littleskin.cn).

If you had bought Minecraft, you can link your LittleSkin account with your Microsoft account and go on.

If you hadn't, you can still use LittleSkin to login without purchasing Minecraft.

Once configured, you can launch the Sushi: Zenith modpack!

---

## Services

> Public services available for Sushi: Zenith players.

### Auto-Update Service {#update-service}

If you set the JVM parameter as described in the [Joining Guide](#guide-join), your client will **check for updates automatically** on launch. No need to reinstall the modpack for every update.

!!! warning "Update Issues"

    If you see an error window on launch, something is wrong with the update service. Please ask politely in the QQ group for help.
    
    If your .minecraft path contains **non-ASCII characters**, you may fail to use update service throuogh JVM arguments. For this, please direct to version folder and run `update.exe` to update manually.

### Web Map

You can visit the [web map](https://zenith.map.sushimc.top) to view the survival server's real-time map.
The creative server does not have a map available yet.

---

## Quick Navigation

> Click the links below to view other related guides for Sushi: Zenith.

[Basic Gameplay Guide](zenith-game.md)

[Advanced Options](zenith-advanced.md)

[Known Bugs and Issues (worth a read!)](zenith-known-bugs.md)

[Frequently Asked Questions](zenith-faqs.md)
