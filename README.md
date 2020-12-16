# Project Manager

Are you having problems organizing-, developing- or maintaining your projects? Would you like to edit one copy of a file and have that shared across all projects? Then this is for you.

## Table of Contents

- [Project Manager](#project-manager)
  - [Table of Contents](#table-of-contents)
  - [Why Use It?](#why-use-it)
  - [Benefits](#benefits)
    - [Files](#files)
    - [Automation](#automation)
    - [UI](#ui)
  - [Requirements](#requirements)
  - [How To Use](#how-to-use)
    - [Setup](#setup)
    - [Projects](#projects)
  - [FAQ](#faq)
    - [Supported Operating Systems?](#supported-operating-systems)
    - [Can I Lose Data?](#can-i-lose-data)
    - [Who Is The Target Audience?](#who-is-the-target-audience)
  - [Todo](#todo)

## Why Use It?

Organizing and maintenance of projects should be simple. However, the larger a project gets, the harder it is to be consistent in design and other shared files, a project manager solves this problem by keeping a single file in the root sharing this across the multiple projects.

## Benefits

### Files

- Single file as source of truth.
- Automatic versioning of files.
- Global files.
- Secret files (.env, .conf and other secret files) stored on-device and imported automatically.

### Automation

- Check for changes in files across all projects with one command.
- Deploying and testing can be done automatically.
- Commiting changes and pushing to remote repo can be done automatically.

### UI

- Web interface for managing projects.
- User friendly command line tool.

## Requirements

You need to have [**Git**](https://git-scm.com/), [**NodeJS**](https://nodejs.org) and [**Python**](https://python.org) installed on your computer.

## How To Use

### Setup

**Description:** This is a combination of most of the other scripts. It will also ask for configs if they do not already exist.

```bash
python setup.py
```

### Projects

**Description:** Downloads and manages the "projects" folder.

```bash
python projects.py
```

## FAQ

### Supported Operating Systems?

Windows, Mac and Linux are all supported.

### Can I Lose Data?

It is **built to keep data intact** and will warn you whenever data could potentially be lost.

### Who Is The Target Audience?

The target audience is the person with larger projects with multiple sub-projects that share the same data. This could be projects which make use of brand colors, brand assets and/or other data which should be consistent across multiple projects.

## Todo

- [ ] Setup scripts.
- [ ] User config.
- [ ] Project scripts.
- [ ] Backup scripts.
- [ ] Git scripts.
- [ ] Global file scripts.
- [ ] Secret file scripts.
- [ ] Update script.
- [ ] Add Web Interface
- [ ] Build CLI
