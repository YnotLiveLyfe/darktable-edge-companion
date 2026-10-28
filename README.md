# darktable EDGE Companion

The free Windows program behind the **DarktableEdge** iCUE widget for the Corsair XENEON EDGE. The widget (sold on the Elgato Marketplace) can only carry web files, so the part that talks to darktable is this program. It runs on your own PC and answers the widget on `127.0.0.1:47630`. No internet, no account, no telemetry.

**Download and setup guide:** https://pathfinderprototyping.com/support/darktable-edge/

This repository holds the releases only. Each release carries `DarktableEdgeCompanion.exe` and its SHA-256. Double-click the exe once: it installs itself under your local AppData `Programs\DarktableEdge` folder, registers a sign-in task so it starts with every sign-in, puts its small Lua script in darktable's configuration folder (darktable loads it at its next start), and lists itself under Settings, Apps for removal. Removing it there also takes the script back out of darktable's configuration.

Support: tony@pathfinderprototyping.com
