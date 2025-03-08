# Folder structure & Media Sorting

## References 
The folder structure is based on [johnnydecimal](johnnydecimal.com). With inspiration from Stefan Zweifel articles [Synology NAS Setup (2020)](https://stefanzweifel.dev/posts/2020/08/04/synology-nas-setup-2020/#folder-structure--synology-drive) and the update [An Opinionated Personal Folder Structure](https://stefanzweifel.dev/posts/2023/09/16/an-opinionated-personal-folder-structure/). 

Also some good folder ideas are from [datacurator-filetree](https://github.com/roboyoshi/datacurator-filetree) github.


## Folder Structure

```bash
├── 00-09 BOX
│   ├── 00 - INBOX
│   ├── 01 - FOCUSBOX
│   ├── 02 - WORKBOX
│   ├── 03 - FRIGEBOX
├── 10-19 Personal
│   ├── 11 - General
│   │   ├── 11.01 - Identification
│   │   ├── 11.02 - Recipe
│   │   └── 11.03 …
│   ├── 12 - Health
│   │   ├── 12.01 - Medical History
│   │   └── 12.02 - Health Insurance
│   ├── 13 - Contract
│   │   ├── 13.01 - <Mobile Carrier>
│   │   └── 13.02 - <Home Internet Provider>
│   ├── 14 - Travel
│   │   ├── 14.01 - <Travel A> (YYYY-MM-DD)
│   │   │   ├── 14.01.01 - Organisation
│   │   │   └── 14.01.02 - Pictures
│   │   │       ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │       └── …
│   │   └── 14.02 …
│   ├── 15 - Vehicle
│   │   ├── 15.01 - <Vehicle A> (YYYY-MM-DD)
│   │   │   ├── 15.01.01 - Insurance
│   │   │   └── 15.01.02 - Inspection 
│   │   └── 15.02 …
│   └── 16 - Housing
│       ├── 16.01 - <House A> (YYYY-MM-DD)
│       │   ├── 16.01.01 - Correspondence <Landlord> (by year)
│       │   │   ├── <YYYY>
│       │   │   └── <YYYY>
│       │   ├── 16.01.02 - Energy Bills (by year)
│       │   │   ├── <YYYY>
│       │   │   └── <YYYY>
│       │   ├── 16.01.03 - City Correspondence
│       │   └── 16.01.04 - Rental deposit
│       └── 16.02 …
├── 20-29 Family
│   ├── 21 - <Family Name>
│   │   ├── 21.01 - VHS collection
│   │   ├── 21.02 - <Travel A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   ├── 21.03 - <Event A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   └── 21.04 …
│   ├── 22 - <Partner Surname>
│   │   ├── 22.01 - Health
│   │   ├── 22.02 - <Bank A>
│   │   ├── 22.03 - <Vehicles A> (YYYY-MM-DD)
│   │   └── 22.03 - Other
│   ├── 23 - <Children A>
│   │   ├── 23.01 - Birth
│   │   ├── 23.02 - General
│   │   ├── 23.03 - Health
│   │   ├── 23.04 - Education
│   │   └── 23.05 - Picture
│   └── 24 …
├── 30-39 Friend
│   ├── 31 - <Friend Name>
│   │   ├── 31.01 - <Travel A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   ├── 31.02 - <Event A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   └── 31.03 …
│   ├── 32 - <Friend Group Name>
│   │   ├── 32.01 - <Travel A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   ├── 32.02 - <Event A> (YYYY-MM-DD)
│   │   │   ├── <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
│   │   │   └── …
│   │   └── 32.03 …
│   └── 33 …
├── 40-49 Education
│   ├── 41 - Primary School
│   │   ├── 41.01 - Marks
│   │   ├── 41.02 - 5th Level
│   │   └── 41.03 - …
│   ├── 42 - Secondary School
│   │   ├── 42.01 - Marks
│   │   ├── 42.02 - 7th Level
│   │   └── 42.03 - …
│   ├── 43 - Apprenticeship Information Scientist
│   │   ├── 43.01 - Marks
│   │   ├── 43.02 - IPA
│   │   ├── 43.03 - School
│   │   └── 43.04 - <Company>
│   └── 49 - Course
│       ├── 49.01 - <Course name> (YYYY)
│       └── 49.02 …
├── 50-59 Employment
│   ├── 51 - Summer Job (YYYY-YYYY)
│   ├── 52 - <Company A> (YYYY-YYYY)
│   │   ├── 52.01 - Contract
│   │   ├── 52.02 - Pay check
│   │   ├── 52.03 - Project
│   │   ├── 52.04 - Picture
│   │   └── 52.04 …
│   ├── 53 …
│   ├── 58 - Freelance
│   │   ├── 58.01 - <Project A> (YYYY)
│   │   │   ├── 58.01.01 - Accounting
│   │   │   ├── 58.01.02 - Research
│   │   │   ├── 58.01.03 - Asset
│   │   │   ├── 58.01.04 - Design
│   │   │   ├── 58.01.05 - Presentation
│   │   │   └── 58.01.06 - Deliverable
│   │   └── 58.02 - <Client A> 
│   │       ├── 58.02.01 <Project A> (YYYY)
│   │       └── 58.02.02 …
│   └── 59 - Resumé
│       ├── 59.01 - Archive
│       └── 59.02 - Inspiration
├── 60-69 Project
│   ├── 61 - IT
│   │   ├── 61.01 - <Project A> (YYYY)
│   │   │   ├── Asset
│   │   │   ├── UI
│   │   │   ├── v0.01
│   │   │   ├── …
│   │   │   └── Finished
│   │   └── 61.02 …
│   └── 62 - DIY
│       ├── 62.01 - <Project A> (YYYY)
│       │   ├── Inspiration
│       │   ├── …
│       │   └── Finished
│       └── 62.02 …
├── 70-79 Finance
│   ├── 72 - Accounting (by year) 
│   │   ├── <YYYY>.ext
│   │   ├── <YYYY>.ext
│   │   └── …
│   ├── 72 - Banking 
│   │   ├── 71.01 - Bank A (closed)
│   │   │   ├── 71.01.01 - Cash Account
│   │   │   ├── 71.01.01 - Saving Account
│   │   │   ├── 71.01.02 - Pensing Account
│   │   │   └── 71.01.03 - <Credit Card A>
│   │   ├── 71.02 Bank B
│   │   └── …
│   ├── 73 - Taxe (by Year)
│   │   ├── <YYYY>
│   │   └── …
│   ├── 74 - Purchase (by Year)
│   │   ├── <YYYY>
│   │   │   ├── <YYYY-MM-DD>_<Brand>-<REF>_<Shop>.etx
│   │   │   └── …
│   │   └── …
│   └── 75 - Donations (by Year)
│       ├── <YYYY>
│       │   ├── <YYYY-MM-DD>_<Name>.etx
│       │   └── …
│       └── …
├── 80-89 Media
│   ├── 81 - Audio
│   │   ├── 81.01 - Book
│   │   ├── 81.02 - Music
│   │   │   ├── <Artist A>
│   │   │   │   ├── <Album A> (YYYY) [<AudioFormat>]
│   │   │   │   │   ├── <TrackNumber> - <TrackName>.ext
│   │   │   │   └── …
│   │   │   ├── …
│   │   │   └── Various Artists
│   │   ├── 81.03 - Playlist
│   │   └── 81.04 - Podcast
│   ├── 82 - Game
│   │   ├── 82.01 - Board Game
│   │   ├── 82.02 - Lego Instruction
│   │   ├── 82.03 - Tabletop
│   │   └── 82.04 - Video Game
│   ├── 83 - Image
│   │   ├── 83.01 - Artwork
│   │   ├── 83.02 - Meme
│   │   ├── 83.03 - Screenshot
│   │   └── 83.04 - Wallpaper
│   ├── 84 - Literature & Paper
│   │   ├── 84.01 - Book
│   │   ├── 84.02 - Magazine
│   │   ├── 84.03 - Manual
│   │   │   ├── <Brand>-<REF>-<Name>.etx
│   │   │   └── …
│   │   └── 84.04 - Paper
│   ├── 85 - Software
│   │   ├── 85.01 - Android
│   │   │   ├── <Nane>-<Version>.etx
│   │   │   └── …
│   │   ├── 85.02 - Debian
│   │   │   ├── <Nane>-<Version>.etx
│   │   │   └── …
│   │   ├── 85.03 - Windows
│   │   │   ├── <Nane>-<Version>.etx
│   │   │   └── …
│   │   ├── 85.04 - Script
│   │   └── 85.05 - Typeface
│   └── 86 - Video
│       ├── 86.01 - Movie
│       │   ├── <Nane> (YYYY)
│       │   │   ├── <Nane> (YYYY).<Resolution>.<Format>.<AudioFormat>.etx
│       │   │   ├── <Nane> (YYYY).nfo
│       │   │   └── <Nane> (YYYY).en.txt
│       │   └── …
│       ├── 86.02 - TV Anime
│       │   ├── <Nane> (YYYY)
│       │   │   ├── Season 1
│       │   │   │   ├── <Nane> (YYYY) S01E01.<Resolution>.<Format>.<AudioFormat>.etx
│       │   │   │   └── …
│       │   │   └── …
│       │   └── …
│       ├── 86.03 - TV Show
│       │   ├── <Nane> (YYYY)
│       │   │   ├── Season 1
│       │   │   │   ├── <Nane> (YYYY) S01E01.<Resolution>.<Format>.<AudioFormat>.etx
│       │   │   │   └── …
│       │   │   └── …
│       │   └── …
│       └── 86.04 - Web
│       │   ├── Youtube
│       │   │   ├── <Nane> (YYYY).<Resolution>.etx
│       │   │   └── …
│       │   └── …
└── 90-99 Archive
    ├── 91 - Backup
    │   ├── 91.01 - Vscode Setting
    │   ├── 91.02 - PiHole Setting
    │   └── 91.03 - Photo Library
    └── 92 - Archive
        ├── 92.01 - Google <Account A>
        ├── 92.02 - Reddit <Account A>
        └── 92.03 - mastodon.social Account
```

## Areas

### 00-09 BOX

Folder structure kept on my computer, once finish the files/folder are moved to a categorie 10-99 for archive.

- `00 - INBOX`(Download) : Files on the computer that need to be sorted.
- `01 - FOCUBOX` : Project that need focus to finish.
- `02 - WORKBOX` : Project that are ongoing for the current year (accounting, renovation, ...).
- `03 - FRIDGEBOX` : Projects on hold. (Let's be honest I will never do them)

This folder structure is inspired by an article, I can't find the source. (Will be updated if found)

### 10-19 Personal

All the files related to my self. 

- `11 - General` : Miscellany of documents. 
- `12 - Health` : Self explain.
- `13 - Contract` : Phone carrier, Internet Provider, etc.
- `14 - Travel` : Travel done on my own.
- `15 - Vehicle` : Bike, car, vessel, etc.
- `16 - Housing` : Insurance, floor plan, etc.

### 20-29 Family

Help your family member to keep order in there files.

- `21 - <Family Name>` : All the pictures, videos from childhood with family. 
- `22 - <Partner Surname>` : Follow the same filetree with less areas/categories.
- `23 - <Children A>` : Birth docuement, IDs, Health, Education, Picture. Follow the same filetree with less areas/categories.

### 30-39 Friend

Specific area for family friends or friend groups. It is mostly pictures from travels or events.

- `31 - <Friend Name>` : Self explain
- `32 - <Friend Group Name>` : Self explain

### 40-49 Education

- `41 - Primary School` : Self explain
- `42 - Secondary School` : Self explain
- `43 - <School Name/Degree Name>` : Self explain
- `49 - Course` : Education taken outside of school

### 50-59 Employment

- `51 - Summer Job (20xx-20xx)` : Documents related to small jobs experience.
- `52 - <Company A> (20xx-20xx)` : Documents, projects done during employment.
- `58 - Freelance` : Client or one off paid project.
- `59 - Resumé` : Curation of the CV over the year and the assets/inspirations for each.


### 60-69 Project

Personal project done during free time.

- `61 - IT` : Project related to software development.
- `62 - DIY` : Home improvment, Decoration, etc.

### 70-79 Finance

- `71 - Accounting (by year)ame` : Self-explain
- `72 - Banking` : Self-explain
- `73 - Taxe (by year)` : Self-explain
- `74 - Purchase (by Year)` : Self-explain
- `75 - Donations (by Year)` : Self-explain

### 80-89 Media

- `81 - Audio` :  Self-explain
- `82 - Game` : Self-explain
- `83 - Image` : Self-explain
- `84 - Literature & Paper` : Self-explain
- `85 - Software` : Self-explain
- `86 - Video` : Self-explain

### 90-99 Archive

- `91 - Backup` :  Data ready to be imported or restore in different software (Contact list, configuration, etc.)
- `92 - Archive` : Account exports from various services (Reddit, Spotify, etc.)

## Sorting Media

### Music library

- [ MusicBrainz Picard](picard.musicbrainz.org) : renaming music files and sorting them into a folder structure.

### Movie library

- [FileBot](filebot.net) : tool for renaming and organizing movies, TV shows and Anime.

### Photo library

- [XnView](xnview.com) : batch rename, batch converter, duplicate image finder.
- [pingo](https://css-ig.net/pingo) : pingo is an experimental lossless and lossy image optimizer.

#### Process folder

1. Add all pictures from one event to the same folder.
1. Rename folder : `YYYY-MM-DD_<Name-of-event> [SORTING]`
    > Rule: Date should be creation of first picture
1. Set 2 main Categories.
    > E.g. Who: `Family`, `Friends`, `Work`, `School` E.g. What: `Travel`, `Birthday`, `New Year`, `Daily`


#### Process picture

1. **Batch converter** : Set the right modification date (important when multiple capture device)
1. **Batch rename** : Rename all files.
    ```js
    // input:
    ({Modified Date [Y-m-dTHMS]}${Filename})

    // output:
    <YYYY-MM-DD>T<HHmmss>#<Original-name>.ext
    ```
1. Set rating for each pictures
    > E.g. 1: Trash; 2: Bad; 3: Long diaporama; 4: Short diaporama; 5: Memorable
1. Keep a maximun of pictures, use the previous step to make your choice
     > E.g. 50: Day event (evening); 100: Short event (weekend); 500: Long event (more than a week)
1. Add Categories for each picture
    > E.g. `Portraits`, `Landscapes`, `Animals`, `Flowers` (Including trees), `Groups`, `Funs`
1. Add Categories TOP to the best in order to print them
    > E.g. 5: Day event (evening); 10: Short event (weekend); 25: Long event (more than a week)
1. Compress pictures
    > Rule: ./pingo {{Folder_Name}} -nodate

1. Remove `[SORTING]` from folder name and place it in the right area/category.