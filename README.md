![minimal-theme](https://github.com/user-attachments/assets/75df90f3-4bf6-464c-b59b-5a8a169cfa7b)
![minimal-theme-window](https://github.com/user-attachments/assets/55f548fc-8942-401a-970b-9869150ca9f8)


_Demo scene credit: https://github.com/Jamsers/Bistro-Demo-Tweaked_

---


# Godot Minimal Theme

## Versions

- For Godot **4.4** and newer use version [1.7.0](https://github.com/passivestar/godot-minimal-theme/releases/tag/1.7.0)
- For Godot **4.3** use version [1.6.0](https://github.com/passivestar/godot-minimal-theme/releases/tag/1.6.0)
- For Godot **4.2** use version [1.2.1](https://github.com/passivestar/godot-minimal-theme/releases/tag/1.2.1)

## Installation

1. Go to [Releases](https://github.com/passivestar/godot-minimal-theme/releases) and download the `.tres` file for your version. Use the high ppi file if you're using in-engine display scale of over **100%** (for example if you're using a laptop with a high pixel density display)
2.  In Godot open `Editor Settings -> Interface -> Theme`, and choose the downloaded theme in the `Custom Theme` field
3.  Set the theme settings like in the [Recommended settings](https://github.com/passivestar/godot-minimal-theme?tab=readme-ov-file#recommended-settings) below
4. Click `Save & Restart`

## Recommended settings

`Editor Settings -> Interface -> Theme`:

- Base Color: `#252525`
- Accent Color: `#569eff`
- Contrast: `0.3`
- Icon Saturation: `2`
- Corner Radius: `4`

`Editor Settings -> Interface -> Editor`:

- Main Font: [Inter](https://rsms.me/inter/)

> [!IMPORTANT]  
> You can experiment with different values but keep in mind that some UI elements will look out of place if you use a different `Base Color`, especially a non-monochrome one. `Accent Color`, `Icon Saturation` and `Font` are safe to change to any value. `Corner Radius` needs to be set to `4` for the nested resources to match the corner radius of the theme. It's not customizable. This is a limitation of Godot theming capabilities.

## Overview

You can watch a short [overview video](https://youtu.be/WmZq3UgOGKY) of this theme made by **Gamefromscratch**.
