![Logo1](/_inc/images/fusion.png)

<h1>Fusion "Slice" Emulationstation Theme for RetroFlag GPI (Retropie)</h1>

Theme elements inspired and sampled from:
 * es-theme-next-pixel by [SamYStudiO](https://github.com/SamYStudiO/es-theme-next-pixel)
 * Basevid Theme from [ES Toolkit](https://github.com/mattrixk/es-toolkit)
 
<h3>Elements</h4>

 * Wallpaper from es-theme-next pixel and Wallhaven (https://wallhaven.cc/)
 * Console logos from [es-theme-next-pixel](https://github.com/SamYStudiO/es-theme-next-pixel) (Because they are really good logos)
 * Fonts in /_inc/media/fonts
 * Original Wallpapers in /_inc/media/og-wallpaper
 * Logo Screensaver images in /_inc/media/screensaver-logo
 * No Logo Screensaver images in /_inc/media/screensaver-nologo
 * Launch Screens in /_inc/media/lanchscreens
 * PNG Logos in /_inc/media/Logo-PNG

<h2>Screenshots</h2>

<h3>Main Screen</h3>
 
| ![Screenshot1](/_inc/media/screenshots/slice.png) | ![Screenshot2](/_inc/media/screenshots/slice2.png)
| ---------- | ------------- |
| ![Screenshot3](/_inc/media/screenshots/slice3.png) | ![Screenshot4](/_inc/media/screenshots/slice4.png)


<h3>Views</h3>
<h5>Note : Recommend 3 Image Mix Scrapes, but looks good with 1, 2, or 4. </h5>
<h5>Also set your scrape dimensions to 320x240 for clearer images in the GPI</h5>

| Detailed View | Basic View |
| --- | --- |
| ![Screenshot10](/_inc/media/screenshots/slice-detailed.png) | ![Screenshot6](/_inc/media/screenshots/slice-basic.png) | 


<h3>Launch Screens</h3>

| SNES | PSX |
| --- | --- |
| ![Screenshot7](/_inc/media/launchscreens/snes/launching.png) | ![Screenshot8](/_inc/media/launchscreens/psx/launching.png) |



<h4>Screensaver Images</h4>

w/Logo | w/o Logo
| --- | ---
| ![Saver20](/_inc/media/screensaver-logo/zelda.png) | ![Saver21](/_inc/media/screensaver-nologo/zelda.png) |


<h3>Supported Retropie Features</h3>

* RetroPie Menu 
* Favorites
* Recent
* All Games
* Collections

<h3>Supported Systems:</h3>

| Atari | Nintendo | Sega | Other 
| :---: | :---: | :---: | :---:
| Atari 2600 |  Nintendo 64 | Sega GameGear | Arcade 
| Atari 5200 |  Nintendo Entertainment System | Sega Genesis / Sega Megadrive | Colecovision 
| Atari 7800 | Nintendo GameBoy | Sega Master System | Mame
| Atari Lynx | Nintendo GameBoy Advance | Sega32x | NeoGeo Pocket Color
| Atari ST  | Nintendo GameBoy Color | SegaCD |  Odyssey 2 / Videopac
|  |  Nintendo VirtualBoy |  | PC Engine 
|  |  |  | SuperGrafx
|  |  |  | TurboGrafx 16
|  |  |  | Sony Playstation
|  |  |  | Sony PSP
|  |  |  | Ports 

Multiple systems have alternate wallpaper/launch screens in their repective folders, labeled as "Alt" or "_1"

<h2>Instructions</h2>

<h2>Warning : Do not do any of this as root! </h2>

<h3>To add theme: </h3>

* `cd /home/pi/.emulationstation/themes`
* `sudo git clone https://github.com/kaleben0/es-fusion-slice`
* The theme will now show as an option in Emulationstation

<h3>To add screensaver images</h3>

* `sudo mkdir /home/pi/.emulationstation/slideshow`
* `sudo mkdir /home/pi/.emulationstation/slideshow/image`
* For images w/ Logo
 * `sudo cp /home/pi/.emulationstation/themes/es-fusion-slice/_inc/media/screensaver-logo/* /home/pi/.emulationstation/slideshow/image/`
* For images w/o Logo
 * `sudo cp /home/pi/.emulationstation/themes/es-fusion-slice/_inc/media/screensaver-nologo/* /home/pi/.emulationstation/slideshow/image/`
* Screensaver Settings are under UI Settings > Screensaver Settings. 
* Set Screensaver Type to Slideshow
* In Emulationstation, Go to UI Settings > Screensaver Settings > Slideshow Screensaver Settings to change options

<h3>To add launch images</h3>

<h2>Warning : Backup up your /opt/retropie/configs dir before doing this!</h2>

* Open RetroPie Setup
* Go to RetroPie Settings > Runcommand Configuration
* Set Launch Menu Art (Option 2) to Enabled
* Exit RetroPie setup
* Copy each of the "launching.png" files from /home/pi/.emulationstation/themes/es-fusion-slice/_inc/media/launchscreens/(system) to the matching folder in /opt/retropie/configs/(system) 
