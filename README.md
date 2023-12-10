# Assyrian Dictionary (Desktop)
This is the official desktop app of the AssyrianLanguages [online dictionary](https://assyrianlanguages.org). 

At this time, the only available options are public preview versions. Some of the features are experimental and significant changes may be made in future versions.

An **internet connection is required** to search for words. The only time it's not required is when browsing and/or searching words that have been saved by the user.

## Setup
If you already have an installation and you want to install another version, then you must **uninstall** the current version first.

You can find the latest version at the [releases](https://github.com/AssyrianLanguages/Assyrian-Dictionary-Desktop/releases/) page.

### Windows Setup
1. Download the `.msi` file.
2. Double-click it to open the installation.
3. Follow through the installation.

![Screenshot of the AssyrianLanguages Windows dictionary app.](/assets/images/windows_v1-2-1.png)

### Mac Setup
1. Download the `.dmg` file.
2. Double-click it to open the installation.
3. Once the installation window appears, drag the app's icon unto the Applications folder icon.

Note: If you get a warning dialog about installing an app from an unidentified developer, see [Open a Mac app from an unidentified developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/14.0/mac/14.0).

![Screenshot of the AssyrianLanguages Mac dictionary app.](/assets/images/mac_v1-2-1.png)

### Linux Setup
1. Download the `.deb` file.
2. Open a terminal and navigate to the folder in which the installation file resides.
3. ```sudo dpkg -i assyriandictionary_[VERSION]_amd64.deb```

![Screenshot of the AssyrianLanguages Linux dictionary app.](/assets/images/linux_v1-2-1.png)

### Saved Words & Setting Persistence

When the app runs for the first time, it creates a folder named `.assyriandictionary` in the root user directory on your machine, in which two database files are added. One is named `al.db`, in which saved words are stored, and the other is named `al_settings.db`, where preference settings are stored.

Uninstalling, reinstalling, or updating the app does not remove or affect these files; therefore, **the saved words and settings will be accessed by the new installation** on the same machine — when logged into the machine's user with which the previous installation was made. 

## Features
- dark mode
- saved words (offline & searchable)
- visualized search options
- switching between Eastern & Western dialect **(experimental)**
- auto-transliteration of Assyrian to Latin **(experimental)**
- switching between English & French definitions
- more Latin character options for Assyrian searches (including ones w/ diacritics)

## Planned Features
- in-app Assyrian keyboard
- text size options
- search predictions (where a list drops down as you type, showing you possible Assyrian queries)
- search result filters
- back and forward navigation

## Usage 

### Example
1. Open the app
2. Click the top-left button and choose "Assyrian - With Vowels/Diacritics" 
3. Click into the search box and type: TacmA'
4. Press `Enter` or click the search button on the right

### Latin Characters
You have access to a larger number of Latin characters than available on the website. To see the list, click the information icon in the top-left corner of the app. 

For example, with the same settings as above:

1. Search for: ṭaˁmāˀ

It's the same thing as the previous query, TacmA'.

## Caveat
The auto-transliterator is an experimental feature. It is not perfect. And it may never be possible to make it perfect. Additionally, it has not yet been tested rigorously.

The definition reformatting is also an experimental feature. It is not perfect. And it may never be possible to make it perfect, perhaps unless this part of the dataset, itself, is manually reformatted to fit that format. 

There's nothing necessarily wrong with the original format. It's just, arguably, easier to visually-parse large definitions in the format attempted by this app.

You have the option to **disable these features from the settings** by clicking the button in the top-right corner of the app.

## Safety
This is the official source. Please make sure to always only get the app from here.

If the official source ever changes, then this page will be updated to inform you about it.

If you're not yet aware, then beware: anyone can lace just about any file with malware. So it's wise to only get the installation file from the official source.

Tip: Before installing, for the sake of procedure, one might first drop the downloaded file into a service like VirusTotal.com for a scan.

## Privacy
This app does not collect usage data — not even for improving it. 

The only thing that it does, Internet-wise, is take your search query and try to get search results back from the AssyrianLanguages web service.

If you save any words, then note that it stores them in an unencrypted database on your device. 

Note: It takes some effort to provide encryption and make it user-friendly. So it's not as easy as flipping a switch to make it happen; however, the option will likely be developed eventually.
