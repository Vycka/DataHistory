# DataHistory 

This is a PoC project to have alternative to windows FileHistory feature.

Due to Wonky behaviour of Windows FileHistory and no obvious good alternatives to it out there. A decision was made to follow good old saying "If want something done right, do it your self."

Expectations:
 * This is not gonna be quickly developer product! But unless FileHistory gets better, or good alternative is found. This project has a high chance of eventually being completed.
 * Take advantage of NTFS API to efficiently enumerate whole disk or parts of it in milliseconds.
 * Support long-paths.
 * Clean but detailed verbose.
 * Sort-of event-store db. (also take advantage of file system it self.)
 * Custom Schedule intervals, include/exclude paths. (More or less same as in FileHistory)
 * UI for configuration is not a target. But probably some kind of UI will be needed to browse history easier.
 * Bleeding edge .NET Core version (Cuz why not)
