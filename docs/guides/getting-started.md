# Getting Started

## Install Assetto Corsa

Assetto Corsa must be purchased and installed via [Steam](https://store.steampowered.com/):

```txt
https://store.steampowered.com/app/244210/Assetto_Corsa/
```

We recommend buying the **Ultimate Edition Bundle** — it includes all the official DLC. Many online servers require at least some of these DLC's to join. The game is frequently on [sale](https://steamdb.info/app/244210/), so it's worth waiting for a discount if you're not in a rush.

::: tip TIP
After installation, launch the game once. It's not strictly required, but doing so ensures that all folders and config files are created. You can then close the game after reaching the main menu.
:::

## Install Content Manager

<!-- TODO: ADD REFERENCES TO ILJA'S CREATOR PROFILE FOR THIS SECTION -->

Content Manager (CM) is a third-party launcher developed by [Ilja Jusupov](../creators/ilja-jusupov). It replaces the original Assetto Corsa launcher and is considered essential for anyone using mods or joining online servers.

Download it from:

```txt
https://acstuff.ru/app/
```

To install:

- Extract `ContentManager.exe` somewhere you can easily access it, like your desktop
- Launch `ContentManager.exe`
- Set the path to the Assetto Corsa installation directory when prompted

This path would usually be at:

```ps
C:\Program Files (x86)\Steam\steamapps\common\assettocorsa
```

::: info NOTE
If this is not the case for you, for any reason, you can instead find Assetto Corsa in your Steam library, then navigate to `Settings -> Manage -> Browse Local Files` and the root directory will be opened in file explorer.
:::

## Install Custom Shaders Patch (CSP)

Custom Shaders Patch (CSP) is an essential extension that adds advanced graphic rendering, lighting, physics interaction, weather support, and other under-the-hood improvements. It is developed by the [same creator as CM](../creators/ilja-jusupov).

To install:

- Open Content Manager
- Navigate to `Settings -> Custom Shaders Patch`
- If this is your first time, you will be prompted to install some version of CSP, usually the most recent stable build

The recommended version is enough for most users. To access experimental builds and features like rain, you’ll need to support the project on Patreon:

```txt
http://www.patreon.com/x4fab
```

::: info NOTE
If you're working with a version of CSP downloaded separately (not through CM, such as the Patreon prerelease versions), do the following:

- Download the archive
- Place the required folders into the Assetto Corsa root directory
- Overwrite existing files if prompted

You can usually drag and drop the archive into CM, but it's worth knowing how to install things manually — especially if you plan on modding later.
:::

## Install Pure

Pure is a comprehensive weather and lighting framework developed by [Peter Boese](../creators/peter-boese). It replaces older systems like SOL, and is the current standard for enhanced visuals and weather control in Assetto Corsa.

Pure is only available through Boese's Patreon:

```txt
https://www.patreon.com/peterboese
```

To install:

- Download the archive
- Place the folders into the Assetto Corsa root directory
- Replace any old files when prompted

### Making sure it works

Getting Pure to fully work can be a bit inconsistent, especially if you're not used to it. Even if it installs without errors, that doesn't always mean it's set up properly.

Here are some ways to check:

<!-- !!: for CM versions post v0..34.34 or whatever -->

- **Drive Tab**: Make sure Pure is selected under the `Weather` dropdown before launching a session (for recent CM versions)
- **CSP Settings**: In `Settings -> Custom Shaders Patch -> Extensions -> Weather FX`, Pure should be selected under the `Weather style` dropdown (either `Pure Gamma` or `Pure LCS`, for versions of Pure post v2.38) <!-- MAKE SURE THIS IS RIGHT -->
- **In-game Apps**: Join a session and open the Pure apps (`Pure Config`, `Pure Planner`). If they don't appear in the app shelf or throw errors, the install is likely broken
- **Post-Processing Filters**: Some PPFilters made for Pure won't work right unless Pure is actually functioning. If visuals look wrong or a black screen appears, it will most likely be an issue with the Pure installation

If any of these don't behave as expected, try reinstalling Pure manually. It may take a bit of back and forth to get it working cleanly.

<!-- TODO: FINISH THIS -->
<!-- TODO: ADD PICTURES, VIDEO, MEDIA -->

## Full Setup Walkthrough (Video)

If you want a more in-depth guide that covers everything in one go, including steps not covered above, this video walks through:

- Installing Assetto Corsa, CM, CSP, and Pure
- Mod installation guide
- CSP configuration and feature highlights
- Visual examples of how things should look once it's all set up

It's a useful reference, especially if you prefer video guides or want to see how everything connects in context.

<!-- YOUTUBE VIDEO WILL GO HERE -->

<div class="video-container">
  <iframe src="https://www.youtube.com/embed/eour5cDFF84" frameborder="0" allowfullscreen></iframe>
</div>
