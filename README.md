# Project Overview
This repository is committed to gathering and holding files containing Clan Members data, Former Clan Members data, and Top Contributors data. The files are supported in four file formats: PDF, JSON, CSV, and Excel. From June 2024, fresh files are uploaded every month, subject to time availability.

## Important Update
Up to June 2024, there was a significant upgrade of the database and the JavaScript employed in file exporting. The column name 'clancapitalattack' has been updated to 'clancapital'. Furthermore, headers in all file types, except PDF, have been sanitized for simpler handling in future use.

## Note
`-1` indicates the member was not in the clan during that period – see data in [JSON](https://github.com/Lightning-President-9/ClanDataRepo/tree/main/Clan%20Members/Clan%20Monthly%20Performance%20JSON) or [CSV](https://github.com/Lightning-President-9/ClanDataRepo/tree/main/Clan%20Members/Clan%20Monthly%20Performance) formats.

## Unique ID Corrections – July 2025 Update

While compiling and updating member data from both active and former clan member APIs, I encountered inconsistencies in the `uniqueid` field — specifically, some entries were missing, and others were duplicated.

#### The Problem

- A few `uniqueid` values (like `COCAR#100`, `COCAR#101`, etc.) were missing entirely from the database.
- Some IDs were accidentally duplicated (for instance, both **"its a smurf"** and another member had `COCAR#106`).
- A couple of members had no assigned ID or were mistakenly assigned an ID that was already in use.

#### Its Solution

I manually reviewed and reassigned the following:

- `COCAR#106` (duplicate) → updated to `COCAR#100` for **"its a smurf"**
- `COCAR#107` (duplicate) → updated to `COCAR#101` for **"Laza"**
- `COCAR#166` was assigned to **"tấn lộc"** (previously missing)
- `COCAR#182` was assigned to **"***Ravi•••??"** (previously missing)

All these updates have been reflected in both [https://coc-ancient-ruins-website.onrender.com/api/mem](https://coc-ancient-ruins-website.onrender.com/api/mem) and [https://coc-ancient-ruins-website.onrender.com/api/fmem](https://coc-ancient-ruins-website.onrender.com/api/fmem).

#### Still Pending

- There is still one known duplicate:
  - **"NeptuneDiver"** currently appears under `COCAR#180` — this will be reassigned to `COCAR#113`.
  - After that, `COCAR#180` will rightfully belong to **"***Ravi•••??"**.

This remaining correction will be completed **after the end of July 2025**.
