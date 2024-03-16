# How to structure your personal files? 📁 📂 🗂️

By the time I wished I had such a guide, so maybe it's of help to you.

## Structure 🌳

```shell
├──adm # Administration, IT-related, Programming
│  ├──1-Hardware
│  ├──2-Network
│  ├──3-Client
│  ├──3-Server
│  ├──4-Personal
│  ├──5-Coding
│  ├──5-Development
│  ├──5-Virtualization
│  ├──6-Applications
│  └──7-Templates
├──finc # Finance, Health, Contracts, Purchases, Guides/Quickstarts
│  ├──1-Personal
│  ├──2-Banking
│  ├──3-Legal
│  ├──3-Tax
│  ├──4-Insurances
│  ├──4-Medical
│  ├──5-Household
│  ├──6-Contracts
│  ├──7-bigBuys
│  ├──7-Purchases
│  │  └──YYYY-MM-DD_shop_shortdescription.jpg
│  ├──7-Sale
│  └──8-Manuals
├──priv # Personal, Recordings, Hobbies, Vacation
│  ├──1-Organization
│  ├──2-Faith
│  ├──3-Recordings
│  │  ├──YYYY
│  │  │  └──YYYY-MM-DD-hhmmss_Picture.jpg
│  │  ├──Camera
│  │  ├──Portrait
│  │  └──Wallpaper
│  ├──3-Music
│  ├──3-SocialMedia
│  ├──4-Sports
│  ├──5-Projects
│  ├──6-Games
│  └──6-Series
└──work # Life Stages, School, Career, Jobs, Courses, Associations
   ├──01-Kindergarten # Childhood
   ├──02-PreSchool
   ├──11-ElementarySchool # Schooling
   ├──12-MiddleSchool
   ├──13-DrivingSchool
   ├──20-Internships # Further Education
   ├──21-YourPrimaryApprenticeship
   ├──22-YourSecondaryApprenticeship
   ├──23-CertifiedEngineer
   ├──30-JobApplication # Career
   ├──30-Courses
   ├──31-YourFirstJob
   │  ├──adm # Job-specific Administration Files
   │  ├──finc # Job-specific Documents
   │  ├──priv # Private Recordings (e.g., Team Building), Notes
   │  └──work # Work Folders, Projects
   ├──32-YourSecondJob
   ├──41-YourAssociation # Associations
   ├──51-Football # Leisure
   └──52-Gymnastics
```

### Folder Hierarchy 🧅

1. The structure consists of four main folders: **adm**, **finc**, **priv**, and **work**, each serving as a broad category for organizing different aspects of your life.

2. The second level is organized by number. This helps to keep the subtopics in a consistent order, which makes it easier to get used to your structure.

3. The third layer varies depending on the complexity of the topic. For example, a folder like `work/31-job` may have a more detailed structure, while a folder like `finc/7-Purchases` can be used as a simple dumping ground for files. The key is to keep it as simple as possible.

### File Naming 📄

When naming your files, it can be helpful to start with a date in the format `YYYY-MM-DD`. This has the following advantages:

-   Files get automatically sorted.
-   You build a timeline.
-   Easy searching. You mostly always know roughly what date it was. So you can often traverse it like a timeline.
-   You can easily sort out files. For example, I move my files from `finc/7-Purchases` into my Archive if i have done the taxes for one specific year.
-   When combined with a time it always gives a unique filename.

## Implementation

```
~/Sync
```

This folder embodies the explained structure and serves as your short-term memory. If you keep it's size down, it can be easily synchronized across different devices, using tools like [Syncthing](https://syncthing.net/). Additionally, I have set up an [Obsidian](https://obsidian.md/) vault on this folder so my notes and files are seamlessly integrated onto each other.

```
~/Desktop
~/Documents
~/Pictures
~/Videos
~/Templates
```

These standard xdg folders are good for use as your "workspace". Here come your active git, video editing or other active projects and tasks; everything you are currently working on.

```
/Archive
```

Lastly, the "Archive" serves as your long-term memory storage for finished projects and large files. This folder should be a mount to some big hard drives that get backed up regularly. Mine is a ZFS RAID for example.

---

Tags: File Organization, Personal Files, Directory Structure, Structured Approach, Efficiency, Digital Asset Management
