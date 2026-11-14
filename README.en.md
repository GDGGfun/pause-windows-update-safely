# Pause Windows Update Safely

## Introduction

Pause Windows updates (almost) permanently with a minimal tweak — without disabling
or otherwise affecting the Windows Update service.

## How It Works

- Import registry entries to change the values that cap the maximum pause duration.
- On 26H2: import registry entries to change the pause deadline (the expiration date
  of the pause) instead.

## Installation

1. Download the appropriate `.reg` file from the Releases page.
2. Double-click the `.reg` file and confirm the dialogs (Yes / OK).
3. Enjoy!

## Usage

- Windows 10, and Windows 11 25H2 or earlier: download
  `延长更新暂停时间10年.reg` ("Extend update pause to 10 years") from Releases.
- Windows 11 26H2: download `26H2延长更新暂停至2066.reg`
  ("26H2: extend update pause to 2066") from Releases.
