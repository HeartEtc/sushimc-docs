# Advanced Tips

> These tips can improve your experience but are entirely optional.
>
> They may require some technical knowledge. Don't worry if you can't follow — you **don't need** to do any of this to enjoy Sushi: Zenith.

## Syncing Xaero Maps Across Lines {#data-sync}

If you frequently switch network lines, your **Xaero map** data will be separate for each line, because the game treats each line as a different server. You can work around this with a bit of effort.

??? tip "Data Sync (for advanced users)"

    1. Open your version folder and find the `xaero` directory, containing `minimap` (minimap) and `world-map` (fullscreen map) subdirectories
    2. **Keep** one line's map folders, **delete** the others
    3. Create **shortcuts** (Windows) or **symlinks** (Linux/macOS) pointing to the kept folders

    All lines will now share the same map data — set it and forget it.

## Syncing Voxy Chunk Cache Across Lines

Similar to above, you may notice that after switching lines, your **Voxy chunk cache** is gone and needs to reload. You can apply the same [Data Sync](#data-sync) approach to the `.voxy` directory in your version folder — create shortcuts or symlinks so the chunk cache is shared across lines. The final folder structure might look like this:

![Data sync example](../images/zh-CN/data-sync.png)

---
