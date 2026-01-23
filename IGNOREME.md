# Shenzhia's In-depth Installation Tutorial


## About

This pack replaces the default TETR.IO sound effects with the ones included here.


## Prerequisites

TETR.IO PLUS is required to customize sound effects (and other features).

Download the version matching your TETR.IO Desktop build using the links below:

- v9: https://gitlab.com/UniQMG/tetrio-plus/-/releases, locate the download link in the **Download** section of the newest release.
- v10: https://gitlab.com/UniQMG/tetrio-plus/-/artifacts, click the download icon of the newest artifact.

Install it by replacing the stock TETR.IO `app.asar` file with the downloaded one. You can find it inside `C:\Users\{user}\AppData\Local\Programs\tetrio-desktop\resources`.


## Get the sound pack

There are two ways to obtain the sound pack. Option 1 is simpler but does not allow modification.


### Option 1 | .TPSE file

A `.tpse` file allows quick importing of TETR.IO PLUS settings and resources.

To obtain it, go to [Releases](https://github.com/bluesnipersguy/bluesspinrotstarterpack/releases) and download the `.tpse` file from the latest release.


### Option 2 | Repository Download

Download the repository to access the `sfx` directory directly. You can then delete/add/modify any files you want before applying them.

To download the repository, head to the main repository page and click the `Code` button, then select `Download ZIP`. The sound files are located in the `sfx` directory inside the archive.

## Apply the sound pack

> [!WARNING]
> Applying the pack overwrites your previous configuration. Make sure you have the files to restore it if you need to.

To apply the sound pack, launch TETR.IO with TETR.IO PLUS installed. If the TETR.IO PLUS window does not open, press `CTRL + T` to open it.

The import process depends on how you obtained the sound pack:

### Import from .TPSE

Open **Data Management**, then select `Import from file`. Select your `.tpse` file and confirm loading it.

### Import from audio files

Open the **SFX Editor**. In the new window that appears select `Choose files` in the `Replace multiple by filename` section next. Navigate to the directory you wish to import from, select all files you wish to import and confirm.

Finally, select `Re-encode and save changes` and wait for the process to complete.

> [!NOTE]
> Once done, restart the game for the changes to take effect.
