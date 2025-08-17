# LayerManager
A simple python script making you able to automatically download &amp; install all of 7GranDad's Translation Layers.

# Important
### Windows will ask you, if you are sure if you wanna run the application, this is totally normal because it's made by an unknown publisher. The file is safe to run. If you don't trust me, decompile it yourself and check the code.

# Usage Guide:

## 1. Download Node.js
Download Node.js from https://nodejs.org/en/ and install it with it's dependencies.

## 2. Download LayerManager
Go to the lastest release and download the "LayerManager.exe" and run it
If it asks you if you wanna use the default filepath, incase you already have the layers stored somewhere, you can select those paths,
in any other case I'd recommend using the default ones.

## 3. Set up the layers
To set up the layers, first click the "Check/Update" button on the layer you wish to start. As soon as the update is done, click the "Setup" button and wait till it's done.

## 4. Start the layer
To start a layer, simply click the "Start" button. In case of MiniBlox and BloxD,
you need specific things to play, more on that later.
To join the server, simply connect to "localhost" through your multiplayer menu on version 1.8, or use ViaFabricPlus (https://modrinth.com/mod/viafabricplus) for newer version clients.

## 5. How to join MiniBlox
To "join" MiniBlox, the steps are the same as in 4, but since MiniBlox's Prediction AntiCheat came out,
you need to send C0CInput packets along with ticks to be able to move which only a few client's have.
### Clients with MiniBlox MoveFixes:
**Free**: 
- LiquidBounce (https://liquidbounce.net/ - Disabler Mode MiniBlox)

**Paid**:
- Neon (https://neonclient.com/ - MoveFix Mode MiniBlox)
- Augustus (https://discord.gg/FgBMFjanrc/ - Disabler Mode MiniBlox)
- Terminus (https://terminusclient.com/- Disabler Mode Miniblox Input - **HAS A FLY**)

## 6. How to join BloxD
To join BloxD you first need to install Firefox from https://www.firefox.com/en/thanks/ as it's the browser the Layer Manager uses to start the layer.
Once you installed Firefox, install the Tampermonkey Extension from https://www.tampermonkey.net/. After installing it, open up the extension and click "Create a new script...".
Then press Win+R on your keyboard and type "%appdata%\.layermanager\BloxD", then press enter. In the folder, drag n drop the file "tampermonkey.js" onto your "<New userscript>" tab in Firefox.
A new tab should open up asking you if you want to install the userscript, press "Install". Then press the "BloxD" button in the Layer Manager, it should update the layer if it isn't up to date already
and open up "https://bloxd.io/" in your browser. If the captcha doesn't complete automatically, complete it manually. It should then say "Bloxd Communication Script Status: Sent!".
You can now *theoretically* join it using localhost, you won't be able to move since Bloxd uses a different set of physics than normal Minecraft.
### Clients with Scripts for Bloxd Movement (Free):
- Liquidbounce Nextgen (ALSO HAS A MODULE FOR IT NOW - NAMED BLOXD PHYSICS)
- LiquidBounce Legacy
- Scripts at https://discord.gg/3WVeCpshhk in #bloxd-stuff or https://discord.gg/UaUsWSEkyT in #scripts in category minecraft.

### Clients with built-in Modules for Bloxd Movement (Paid):
- Neon (https://neonclient.com/ - 23€) - Enable **MoveFix** and choose **Bloxd** as mode or just load my config from the online configs.
- Rise (https://riseclient.com/ - $34.99) - Just **load the config Bloxd** and you're good to go.
- Astralis (https://discord.gg/Q2QMJPuG6z - 28,99 €) - Enable the module **Bloxd Movement**.
- Terminus (https://terminusclient.com/ - 45€) - Enable Movement Correction and select the mode "**Voxel Game Physics**".
