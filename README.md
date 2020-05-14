# layout

The basic file structure for Rainfusion

## File Structure

---

### ``manifest.json``

This file represents the fields that will be displayed on the main Rainfusion website.

```jsonc
{
    // The name of your mod.
    // This name MUST be the same name as the mod directory.
    "name": "Example Mod",
    // A simple short summary of the mod.
    "summary": "Example mod for RoRML",
    // The version of your mod.
    // This version must follow semantic versioning.
    "version": "1.0.0",
    // The dependencies your mod requires.
    "dependencies": [
        [
            // The ID of the dependency.
            "00000000-0000-0000-0000-000000000000",
            {
                // The version of the dependency required.
                "version": "= 1.0.0",
                // If the dependency is optional or not.
                "optional": true
            }
        ]
    ]
}
```

---

### ``DESCRIPTION.md``

This file contains the description for the mod.
This file is rendered into the main description tab on the Rainfusion website.

---

### ``icon.png``

The icon must be 100x100px and must be under the format of **.png**.

---