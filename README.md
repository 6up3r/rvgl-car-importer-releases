<div align="center">

<img src="media/banner.png" alt="RVGL Car Importer: Gran Turismo 2 cars for RVGL" width="100%">

<p>
  <a href="https://github.com/6up3r/rvgl-car-importer-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/6up3r/rvgl-car-importer-releases?label=release&style=for-the-badge&color=f5a623"></a>
  <a href="https://github.com/6up3r/rvgl-car-importer-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/6up3r/rvgl-car-importer-releases/total?style=for-the-badge&color=e8502a"></a>
  <img alt="Windows" src="https://img.shields.io/badge/Windows-x64%20%C2%B7%20x86%20%C2%B7%20ARM64-0078D4?style=for-the-badge&logo=windows&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-Apple%20Silicon%20%C2%B7%20Intel-111111?style=for-the-badge&logo=apple&logoColor=white">
</p>

<b>Your own Gran Turismo 2 disc in, RVGL cars out.</b><br>
Read the disc, browse its cars, see each one exactly as RVGL will draw it, export it in one click.

<p>
  <a href="#-download"><b>Download</b></a> ·
  <a href="#-what-it-does"><b>What it does</b></a> ·
  <a href="#-a-tour-of-the-app"><b>Tour</b></a> ·
  <a href="#-reporting-a-car-or-a-crash"><b>Report</b></a> ·
  <a href="#-faq"><b>FAQ</b></a>
</p>

<img src="media/hero.gif" alt="The white Citroën Saxo 1.6i VTS turning a full circle in the app's viewer, as RVGL draws it" width="800">

</div>

## 🏁 What it does

<table>
  <tr>
    <td align="center" width="33%"><h3>💿 1. Open your disc</h3>A disc image (<code>.cue</code>/<code>.bin</code>, <code>.iso</code>, <code>.img</code>), the CD in the drive or a folder of the disc's files. The app ships no game data.</td>
    <td align="center" width="33%"><h3>🔍 2. Pick a car</h3><b>608 cars</b>, <b>1,022 versions</b> on the PAL disc: road cars, racing modifications, JGTC, Le Mans and rally cars.</td>
    <td align="center" width="33%"><h3>🏎️ 3. Export to RVGL</h3>Body, colours, wheels, handling, engine sound and the car's box in RVGL's menu, straight into its <code>cars</code> folder.</td>
  </tr>
</table>

Today it reads disc 2 of **Gran Turismo 2**: PAL, Japanese, and USA v1.0, v1.1 and v1.2. More games are to come.

<p align="center"><img src="media/overview.png" alt="The app's window: the car list, the viewer, the car's sheet, RVGL's box and the export" width="900"></p>

## 🎬 A tour of the app

<table>
  <tr>
    <td width="50%"><img src="media/find.gif" alt="Searching the car list" width="100%"></td>
    <td width="50%"><h3>Find any car</h3>Search by name, filter by brand, kind or state. Each car lists its versions; race cars carry their badge.</td>
  </tr>
  <tr>
    <td width="50%"><h3>See it as RVGL draws it</h3>A real-time viewer with RVGL's own look: drag to rotate, right-drag to move, wheel to zoom, double-click to reset.</td>
    <td width="50%"><img src="media/viewer.gif" alt="Rotating and zooming a car in the viewer" width="100%"></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/angles.gif" alt="Front, rear, side and top views" width="100%"></td>
    <td width="50%"><h3>Every angle</h3>Three-quarter, front, rear, side and top in one click.</td>
  </tr>
  <tr>
    <td width="50%"><h3>Every colour</h3>All of a car's Gran Turismo 2 colours, with their names from the disc; export them all or just one.</td>
    <td width="50%"><img src="media/colours.gif" alt="Switching between a car's colours" width="100%"></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/wireframe.gif" alt="Wireframe and lighting toggles" width="100%"></td>
    <td width="50%"><h3>Wireframe, lights, wheels</h3>Check every car before it races: wireframe, lighting, wheels, transparent parts, steering, orthographic view.</td>
  </tr>
  <tr>
    <td width="50%"><h3>Race cars too</h3>JGTC GT500, Le Mans and rally cars, each with RVGL's rating and stats bars shown as the game's car selection will show them.</td>
    <td width="50%"><img src="media/racecar.gif" alt="A Le Mans race car in the viewer" width="100%"></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/export.gif" alt="Exporting a car" width="100%"></td>
    <td width="50%"><h3>One-click export</h3>Choose the destination, the colours, the engine sound (from the disc or RVGL's standard), the class and the RC antenna; <b>Export</b> writes the car, the log tells you where.</td>
  </tr>
</table>

## 📦 Download

Grab the file for your system from the [latest release](https://github.com/6up3r/rvgl-car-importer-releases/releases/latest): one file, nothing beside it.

| System | File | Needs |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/-Windows%2011%20%C2%B7%2010%20LTSC%2FEnterprise-0078D4?logo=windows&logoColor=white" alt="Windows"> | `rvgl-car-importer-win-x64.exe`, `rvgl-car-importer-win-x86.exe` | nothing to install |
| <img src="https://img.shields.io/badge/-Windows%2011%20on%20ARM64-0078D4?logo=windows&logoColor=white" alt="Windows ARM64"> | `rvgl-car-importer-win-arm64.exe` | nothing to install |
| <img src="https://img.shields.io/badge/-Linux%20x64-FCC624?logo=linux&logoColor=black" alt="Linux"> | `rvgl-car-importer-linux-x64.AppImage` | the libraries .NET lists for self-contained apps (`libc6`, `libgcc-s1`, `libstdc++6`, `libssl3`, `ca-certificates`, `tzdata`, `zlib1g`, `libgssapi-krb5-2`), X11 and FUSE |
| <img src="https://img.shields.io/badge/-macOS%2014%2B%20Apple%20Silicon-111111?logo=apple&logoColor=white" alt="macOS Apple Silicon"> | `rvgl-car-importer-osx-arm64.zip` (`RVGL Car Importer.app`) | nothing to install; the app is not notarized, so the first start needs «Open Anyway» in System Settings > Privacy & Security |
| <img src="https://img.shields.io/badge/-macOS%2014%2B%20Intel-111111?logo=apple&logoColor=white" alt="macOS Intel"> | `rvgl-car-importer-osx-x64.zip` (`RVGL Car Importer.app`) | the same, on a Mac with an Intel processor |

> [!TIP]
> The app checks this repository for a newer release at start and from **File > Check for updates...**. It installs only a file whose SHA-256 is listed in the release's `release.json`, signed with the authors' key (`release.json.sig`).

## 🛠️ Reporting a car or a crash

<table>
  <tr>
    <td width="50%"><h3>🚗 A car looks or drives wrong</h3>Open the car in the app and press <b>Report a problem...</b> next to its name: it opens the <a href="https://github.com/6up3r/rvgl-car-importer-releases/issues/new?template=car.yml">car report form</a> already filled in with the car, the disc and the app's version. One report per car and per problem, with a screenshot where it shows.</td>
    <td width="50%"><h3>💥 The app closed unexpectedly</h3>The app saves a crash report and, at the next start, tells you where. <b>Report on GitHub</b> opens the <a href="https://github.com/6up3r/rvgl-car-importer-releases/issues/new?template=crash.yml">crash report form</a> and the report's folder: drop the file into the form. The report names no one: your home folder is written <code>~</code>.</td>
  </tr>
</table>

The authors read every report and label the ones they accept; the fix comes in a later release.

## ❓ FAQ

<details>
<summary><b>Does the app contain any game data?</b></summary>
<br>
No. It reads your own copy of the disc, an image or the CD in the drive, and converts the cars on your computer.
</details>

<details>
<summary><b>Which discs does it read?</b></summary>
<br>
Disc 2 of Gran Turismo 2: PAL, Japanese, and USA v1.0, v1.1 and v1.2. «? > Compatible games» in the app lists them with their serials; a disc it does not read is refused with that list.
</details>

<details>
<summary><b>Where does the app keep its settings and crash reports?</b></summary>
<br>
In <code>settings.txt</code> of your application data folder (<code>%APPDATA%\rvgl-car-importer</code> on Windows, <code>~/.config/rvgl-car-importer</code> on Linux), the crash reports in its <code>crash</code> folder, the last 10.
</details>

<details>
<summary><b>Where do the exported cars go?</b></summary>
<br>
Into the <code>cars</code> folder you choose under <b>Export</b>, usually the one of your RVGL. «Delete» removes only cars this app exported.
</details>

<div align="center">
<br>
<sub>Made by <b>6Up3r</b> · an alpha version: more games to come</sub>
</div>
