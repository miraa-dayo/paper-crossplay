# Custom Pterodactyl Egg
(a mini project by me)

This repository contains a custom Minecraft Pterodactyl egg for setting up your SMPs easily by automatically downloading the required plugins for Crossplay and configs to automatically disable "online-mode".

## Requirements

- Pterodactyl Panel v1.x.x or above
- Debian Docker support enabled on your Pterodactyl node

## Installation

To install the custom egg on your Pterodactyl panel, follow these steps:

1. Download the egg files:
   - Download the "egg-paper-crossplay.json"

   ``` https://github.com/miraa-dayo/paper-crossplay/blob/main/egg-paper-crossplay.json

2. Upload the egg to your Pterodactyl Panel:
   1. Log in to your Pterodactyl panel as an admin.
   2. Navigate to Admin Panel > Nests > Import Egg (Associated Nest must be Minecraft or any nest that you can easily access).
   3. Upload the '.json' egg file and click 'Import'

3. Configure the egg:
   
   - Edit the dockerfile (if required) to specify the game server's base image or settings.
   - Modify the config file to adjust environment variables for the game server (such as ports, memory, etc.).

4. Add the egg to your server:

   - Create a new server and select the newly added egg.

Complete the server setup and start it!
