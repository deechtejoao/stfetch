# stfetch 

**stfetch** is a Bash script that retrieves Steam game details by App ID or game name — using the Steam API. It outputs the game's title, release date, price, and Metacritic score (if available), all from your terminal.

---

## Features

- Resolve by **App ID** or **game name**  
- Scrape Steam search results to find App IDs  
- Fetch game metadata via Steam Store API  
- Display title, release date, price, and Metacritic score  

---

## Requirements

- **Bash** (version 4+)  
- **curl**  
- **jq**  
- Standard Unix utilities: `grep`, `sed`, `head`  

---

## Usage 
```bash
$ stfetch silksong

Steam App ID: 1030300
Title       : Hollow Knight: Silksong
Release Date: Sep 4, 2025
Price       : $19.99
Reviews     : No Metacritic data
```

## Installation

```bash 
git clone https://github.com/deechtejoao/stfetch
```
Make it executable:
```bash 
chmod +x stfetch
```
