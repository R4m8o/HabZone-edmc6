📦 HabZone – EDMC 6.x Compatibility Update
This plugin helps explorers find high-value planets. It displays the "habitable-zone" (i.e. the range of distances in which you might find an Earth-Like World) when you scan the primary star in a system with a Detailed Surface Scanner.

Version: 1.22-edmc6 Status: Stable Tested with: EDMarketConnector 6.1.1, Python 3.13
Changes:
HabZone v1.22-edmc6-slim

A streamlined EDMC 6.x–compatible update of HabZone, focused on reliability and maintainability.
Automatically restores habitable zone distances after EDMC restart
Uses Elite Dangerous journal files to detect the current system on startup
Optional k/M distance abbreviation and exact-value tooltips
Manual Recalc button included
Optional verbose logging for troubleshooting
Refactored and cleaned-up codebase (no legacy Python 2 support)
➡️ No system jump required after restart – values appear instantly.

Installation
On EDMC's Plugins settings tab press the “Open” button. This reveals the plugins folder where EDMC looks for plugins.
Download the latest release.
Open the .zip archive that you downloaded and move the HabZone folder contained inside into the plugins folder.
You will need to re-start EDMC for it to notice the new plugin.

ℹ️ Notes
This update is a maintenance / compatibility fix only

Original functionality and UI layout are unchanged

Safe drop-in replacement for the original HabZone-master/load.py

----- Original - by Marginal -----

Screenshot

Optionally, you can choose to display the ranges in which you might find other high-value planets - Metal-Rich, Water and/or Ammonia Worlds.

Optionally, you can choose to display the high-value planets known to Elite Dangerous Star Map.

Acknowledgements
Calculations taken from Jackie Silver's Hab-Zone Calculator.

License
Copyright © 2017 Jonathan Harris.

Licensed under the GNU Public License (GPL) version 2 or later.
