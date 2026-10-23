# TGH ED Staffing Planner

Password-protected staffing planner for USF Emergency Medicine and TGH Emergency Services.

- index.html is the whole app (no build step).
- data.enc holds all roster, contract, shift and schedule data, encrypted with AES-256-GCM using a key derived from the site password (PBKDF2, 200,000 iterations). Names and hours are not readable in this repository without the password.
- To publish edits made in the site, use Data, then Download updated data file, then replace data.enc here.
