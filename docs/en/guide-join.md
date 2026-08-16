# Joining Guide

> This guide helps you install Sushi modpacks and configure the necessary settings. It is generally applicable to most Sushi modpacks.

## Installing the Modpack

First, join the Sushi QQ group: **`1045084460`**

In the group files, find the modpack folder, locate the modpack you want to play, and **download the latest version**.

Then, **install the modpack into your Minecraft launcher**. For instructions on installing a modpack with your launcher, please consult your launcher's documentation. In general, you can drag the modpack file into your launcher window.

The installation **requires an internet connection**. If you have trouble downloading game files or mods, try again a few times.

!!! note "About Launchers"

    The official Minecraft launcher cannot install third-party modpacks. We recommend using a third-party launcher.

## Setting Up the Updater {#update-setup}

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

## Login Methods

For safety and compatibility, Sushi only supports logging in through [LittleSkin](https://littleskin.cn).

If you had bought Minecraft, you can link your LittleSkin account with your Microsoft account and go on.

If you hadn't, you can still use LittleSkin to login without purchasing Minecraft.

Once configured, you can launch the modpack!

---

## Services

> Public services available for SushiMC players.

### Auto-Update Service {#update-service}

If you set the JVM parameter as described in the [Setting Up the Updater](#update-setup) section, your client will **check for updates automatically** on launch. This keeps your client in sync with the latest version of the modpack — no need to reinstall it for every update.

!!! warning "Update Issues"

    If you see an error window on launch, something is wrong with the update service. Please ask politely in the QQ group for help.
    
    If your .minecraft path contains **non-ASCII characters**, you won't be able to use the auto-update service. In that case, open your version folder and double-click `update.exe` to update manually.

### Web Map

You can visit the web map to view real-time maps of each server. Please refer to each modpack's page for details.

---

## Quick Navigation

Next, you can check out:

[Basic Gameplay Guide](guide-game.md)

[Sushi: Zenith](zenith.md)
