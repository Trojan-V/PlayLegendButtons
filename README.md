# Widget GUI Resource Pack

This Minecraft resource pack overrides selected vanilla GUI widget sprites (buttons and sliders) and configures them with **nine-slicing** via `.png.mcmeta` files.

## Why this pack exists

On the **playlegend.net** server, button textures are provided through the server resource pack during join.  
To keep the experience as seamless as possible (including before the server pack finishes loading), this resource pack also ships the button textures locally, so the UI already matches right away.
Additionally, the server resource pack does not override slider textures, while this local pack does—so sliders match the same style too, making the overall GUI experience even more seamless.

## Important: Texture ownership / source

**The button textures included in this resource pack are NOT original work created by this project.** 
They were extracted from the **playlegend.net server resource pack** and are bundled here purely to provide the same visual style locally.
All credit/rights for those extracted button textures belong to the owners/authors of the playlegend.net server resource pack (and any upstream authors it may include).

## Included textures

The following vanilla resources are overridden:

### Buttons (from playlegend.net server resource pack)
- `minecraft/textures/gui/sprites/widget/button.png`
- `minecraft/textures/gui/sprites/widget/button_highlighted.png`
- `minecraft/textures/gui/sprites/widget/button_disabled.png`

### Sliders (local overrides)
- `minecraft/textures/gui/sprites/widget/slider.png`
- `minecraft/textures/gui/sprites/widget/slider_handle.png`
- `minecraft/textures/gui/sprites/widget/slider_handle_highlighted.png`

All listed `.png` files have a corresponding `.png.mcmeta` that defines nine-slicing behavior.

## Installation

1. Download the resource pack (ZIP).
2. Put it into your Minecraft resourcepacks directory:
   - Windows: `%APPDATA%\.minecraft\resourcepacks`
   - Linux: `~/.minecraft/resourcepacks`
   - macOS: `~/Library/Application Support/minecraft/resourcepacks`
3. In Minecraft: `Options -> Resource Packs` and enable the pack.

## Notes

- Nine-slicing is used so widgets can scale cleanly across different UI scales and screen resolutions while keeping borders/crisp edges intact.
- If you also want hover/active states to match, make sure all highlighted/disabled variants are present (this pack includes them for buttons and slider handles).

## License

Unless stated otherwise, the license for the artwork and metadata in this pack is defined by the repository/project you obtained it from.

## Trademarks / Disclaimer

“Minecraft” is a trademark of Mojang Synergies AB and/or Microsoft. This resource pack is a third-party project and is not an official Minecraft product.