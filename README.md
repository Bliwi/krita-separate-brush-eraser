# Krita Separate Brush and Eraser

![](icon.jpg)

Makes Krita treat the brush and eraser as if they’re separate tools. The brush and eraser keep track of presets, size, opacity, flow, etc separately. All added functions can be found under `Tools > Separate Brush and Eraser` in the shortcuts menu.
- `Switch to Freehand Brush`: Switches to the freehand brush tool in brush mode and activates the current brush preset
- `Switch to Freehand Eraser`: Switches to the freehand brush tool in erase mode and activates the current eraser preset
- `Activate Eraser Preset for Current Tool`: Activates eraser preset without switching tools.
- `Activate Brush Preset for Current Tool`: Activates brush preset without switching tools
- `Toggle Eraser Preset for Current Tool`: Toggles between brush and eraser presets without switching tools


I’d suggest binding hotkeys to `Switch to Freehand Brush` / `Switch to Freehand Eraser`, they most closely mimic the behavior of other painting programs.

If you click the eraser in the top bar, the eraser will toggle on/off for the current tool without changing presets (ie. what Krita does by default). This is useful if you find yourself wanting to swap your current brush into erase mode in the normal Krita way.

**Uses input adapter library from [shortcuts composer](https://github.com/wojtryb/Shortcut-Composer)**

## Installation

Download [separatebrusheraser.zip](http://github.com/dninosores/Bliwi/krita-separate-brush-eraser/latest/download/separatebrusheraser.zip) and install by going to `Tools > Scripts > Import Python Plugin From File...` in Krita and selecting the zip file.

If you're having issues, more information on plugin installation can be found [here](https://docs.krita.org/en/user_manual/python_scripting/install_custom_python_plugin.html).

# Brush preset tag linking

This is meant to emulate the functionality of the tool preset panel from Photoshop and how clip studio handles brushes.

This option can be enabled by navigating to the settings panels `Tools > Scripts > Brush Eraser Settings` and enabling the checkbox `Link a brush preset tag with the brush and eraser`.
The Dropdown options below allow you to select which preset tag will be linked with the brush and eraser respectively.

<img width="321" height="175" alt="image" src="https://github.com/user-attachments/assets/d56cfa55-8317-4d74-a1b9-9a887aa4ef85" />
