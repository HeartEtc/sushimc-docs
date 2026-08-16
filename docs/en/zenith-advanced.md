# Advanced Tips

> These tips can improve your experience but are entirely optional.
>
> They may require some technical knowledge. Don't worry if you can't follow — you **don't need** to do any of this to enjoy Sushi: Zenith.

## Voxy Mod

The Sushi: Zenith modpack comes with the **Voxy** distance extension mod by default. You can adjust your desired render distance in the video settings.

![Voxy settings](/images/zh-CN/voxy-settings.png)

The server provides a maximum render distance of **16 chunks** and sends up to **256 chunks** of Voxy scenery. You can adjust how much Voxy data you want to receive in the Voxy Server Side mod settings.

![Voxy Server Side settings](/images/zh-CN/voxy-settings2.png)

Voxy supports shaders on Sushi: Zenith. We recommend [**Complementary**](https://modrinth.com/shader/complementary-unbound) shaders with the [**Euphoria Patches**](https://modrinth.com/mod/euphoria-patches) mod for great performance and visuals.

!!! warning "Voxy Performance"

    Voxy is well-optimized, but some devices may still struggle. If you experience performance issues, you can disable **Enable Voxy** and **Receive Server-Side Scenery** in the video settings.

## Colorful Tooltips {#colortooltips}

If you don't like the visual effects of colorful tooltips, consider disabling or removing mod [ColorTooltips](https://www.mcmod.cn/class/25915.html) to disable these effects.

The rarity of items are provided by rarity core engine and cannot be removed from client.

## Syncing Xaero Maps Across Lines {#data-sync}

If you frequently switch network lines, your **Xaero map** data will be separate for each line, because the game treats each line as a different server. You can work around this with a bit of effort.

??? tip "Data Sync (for advanced users)"

    1. Open your version folder and find the `xaero` directory, containing `minimap` (minimap) and `world-map` (fullscreen map) subdirectories
    2. **Keep** one line's map folders, **delete** the others
    3. Create **shortcuts** (Windows) or **symlinks** (Linux/macOS) pointing to the kept folders

    All lines will now share the same map data — set it and forget it.

## Syncing Voxy Chunk Cache Across Lines

Similar to above, you may notice that after switching lines, your **Voxy chunk cache** is gone and needs to reload. You can apply the same [Data Sync](#data-sync) approach to the `.voxy` directory in your version folder — create shortcuts or symlinks so the chunk cache is shared across lines. The final folder structure might look like this:

![Data sync example](/images/zh-CN/data-sync.png)

---
