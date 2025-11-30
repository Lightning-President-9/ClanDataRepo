# Project Overview
This repository is committed to gathering and holding files containing Clan Members data, Former Clan Members data, and Top Contributors data. The files are supported in four file formats: PDF, JSON, CSV, and Excel. From June 2024, fresh files are uploaded every month, subject to time availability.

## Important Update
Up to June 2024, there was a significant upgrade of the database and the JavaScript employed in file exporting. The column name 'clancapitalattack' has been updated to 'clancapital'. Furthermore, headers in all file types, except PDF, have been sanitized for simpler handling in future use.

## Note
`-1` indicates the member was not in the clan during that period – see data in [JSON](https://github.com/Lightning-President-9/ClanDataRepo/tree/main/Clan%20Members/Clan%20Monthly%20Performance%20JSON) or [CSV](https://github.com/Lightning-President-9/ClanDataRepo/tree/main/Clan%20Members/Clan%20Monthly%20Performance) formats.

## Unique ID Corrections – July 2025 Update

While compiling and updating member data from both active and former clan member APIs, I encountered inconsistencies in the `uniqueid` field — specifically, some entries were missing, and others were duplicated.

### The Problem

- A few `uniqueid` values (like `COCAR#100`, `COCAR#101`, etc.) were missing entirely from the database.
- Some IDs were accidentally duplicated (for instance, both **"its a smurf"** and another member had `COCAR#106`).
- A couple of members had no assigned ID or were mistakenly assigned an ID that was already in use.

### Corrections Completed

The following updates were made after manual review and reassignment:

- `COCAR#106` (duplicate) → reassigned to `COCAR#100` for **"its a smurf"**
- `COCAR#107` (duplicate) → reassigned to `COCAR#101` for **"Laza"**
- `COCAR#166` → now correctly assigned to **"tấn lộc"** (was previously missing)
- `COCAR#182` → now correctly assigned to **"***Ravi•••??"** (was previously missing)
- **"NeptuneDiver"** was listed under `COCAR#180` → now reassigned to `COCAR#113`
- `COCAR#180` is now correctly assigned to **"***Ravi•••??"**

All of the above corrections have been reflected in the following API endpoints:

- https://coc-ancient-ruins-website.onrender.com/api/mem  
- https://coc-ancient-ruins-website.onrender.com/api/fmem

### Top Clan Contributors Clan Score Update
- `30/11/25` Clan Score from `>75` -> `>200`
