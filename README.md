<p align="center">
  <img src="media/icon.png" width="128" alt="Tortuga pirate ship icon">
</p>

<h1 align="center">Tortuga</h1>

<p align="center">
  A modern remake of <em>Sid Meier's Pirates!</em> — sail, trade, fight and plunder the Caribbean, alone or with friends.
</p>

<p align="center">
  <a href="https://github.com/dnldxn/tortuga-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dnldxn/tortuga-releases?label=latest%20build&color=b8860b" alt="Latest build"></a>
  <img src="https://img.shields.io/badge/platforms-Windows%20%C2%B7%20macOS%20%C2%B7%20Linux-2f6f9f" alt="Windows, macOS, Linux">
  <img src="https://img.shields.io/badge/engine-Godot%204.7-478cbf" alt="Godot 4.7">
  <img src="https://img.shields.io/badge/status-test%20builds-8a6d3b" alt="Test builds">
</p>

<p align="center">
  <img src="media/sailing.jpg" width="100%" alt="Sailing a sloop through the channel between Tortuga and Port-de-Paix, with other ships labelled by nation and type">
</p>

## Overview

Tortuga is an open-ended pirate adventure in the spirit of the 2004 *Pirates!*: you are a captain in the Caribbean of the 1660s, free to trade, privateer, hunt rivals, chase treasure and build a career however you like. It plays fully **offline**, and the same campaign also runs as a **shared world** on a dedicated server where up to four captains sail, cooperate and compete in one Caribbean.

The game is built in Godot 4.7 by a solo developer with AI assistance. The source is private; this repository publishes the **test builds**. Expect rough edges, and expect a new campaign to be required between some versions.

## Goals

- **Keep the spirit of *Pirates!*** — a captain's life of short adventures inside a longer career, with readable tactical choices and consequences that connect everything.
- **Classic, modernized** — overhead sailing, top-down naval battles, light swashbuckling tone and modern usability.
- **Fast, small, quick to load** — responsive controls, smooth frame pacing, a tiny download and short waits to the action, on modest hardware.
- **Offline and shared** — a complete single-player game, plus a small-group shared campaign for independent captains.
- **Signature activities, one at a time** — boarding duels and treasure hunting are in; other classic minigames are judged on their merits.

## What you can do today

| | |
|---|---|
| **Sail** | A 3D Caribbean seen from a pitched follow camera, with wind and tacking, 40 ports of four nations, and islands you can go ashore on. Nearby ships are labelled by nation and type, merchants run from pirates, warships give chase, and music plays as you sail. |
| **Fight** | Naval battles with eight hull types and round, chain and grape shot. Enemy captains fire their broadsides as volleys, keep the weather gauge, lead their shots and flee downwind. Boarding ends in a timed 3D sword duel on deck. |
| **Trade & plunder** | Buy low and sell high across port markets with a price book, capture prizes, intercept the Spanish treasure fleet and hunt named rivals in their home waters. |
| **Run a crew** | Hire in taverns, keep them fed and paid, manage morale and wages, check the hold and fleet at sea, repair and refit at the shipyard and store spare ships. |
| **Build a career** | Commissions and standing with four nations, jobs and contracts, treasure maps, skills and titles, retirement and a career book. |
| **Play together** | A persistent shared world on a dedicated server for up to four captains, with a shared pause and server-side saving. |

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="media/battle.jpg" alt="A galleon fires both broadsides"><br><sub>A galleon fires both broadsides.</sub></td>
    <td width="50%"><img src="media/duel.jpg" alt="Crossing swords with a rival captain on deck"><br><sub>Crossing swords with a rival captain.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/port.jpg" alt="Docked at Tortuga"><br><sub>Docked at Tortuga.</sub></td>
    <td width="50%"><img src="media/market.jpg" alt="The market"><br><sub>Buying sugar at the market.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/tavern.jpg" alt="The tavern"><br><sub>Hiring crew in the tavern.</sub></td>
    <td width="50%"><img src="media/shipyard.jpg" alt="The shipyard"><br><sub>Repairs and fittings at the shipyard.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/journal.jpg" alt="The journal, with contracts and a treasure map"><br><sub>Contracts and a half-found treasure map in the journal.</sub></td>
    <td width="50%"><img src="media/ashore.jpg" alt="A landing party ashore"><br><sub>A landing party goes ashore to dig.</sub></td>
  </tr>
</table>

## Download

Grab the latest build from [Releases](https://github.com/dnldxn/tortuga-releases/releases/latest), unpack it and run it. The game itself is about 45 MB; the full archives below also include the engine.

| Platform | File |
|---|---|
| Windows | `Tortuga-0.N-windows.zip` |
| macOS | `Tortuga-0.N-macos.zip` |
| Linux (x86_64) | `Tortuga-0.N-linux.tar.gz` |
| Dedicated server (linux-arm64) | `tortuga-server-linux-arm64.tar.gz` (+ `.sha256`) |

On Linux, unpack the archive into the folder where you want to keep the game, then run `bash install-desktop.sh` to add Tortuga and its icon to your applications menu. Run the installer again if you move that folder.

The game updates itself: **Check for updates** in the main menu downloads and verifies the newer pack, then restarts. The `.pck` files and `update.json` on each release are for that updater. Clients and servers must run the same version to play together.

## Feedback

These are test builds, so saves from older versions may be refused and a fresh campaign asked for; the release notes say when. Found a bug or have an idea? [Open an issue](https://github.com/dnldxn/tortuga-releases/issues).
