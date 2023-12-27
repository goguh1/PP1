# PP1

Project: Overview
Project 1: import/export script
- Import file created from baselight (Baselight_export.txt)
- Import xytech work order (Xytech.txt)
- Script will parse data
- Computation done to match shareholder request, to replace file system from local baselight to facility
storage (remember color correcter's prefer local storage for bandwidth issues)
- Export CSV file ('/' indicates columns):
- Line 1: Producer / Operator / job /notes
- Line 4: show location / frames to fix
- Frames in consecutive order shown as ranges


Project: example
Xytech:
/ddnsan2/avengers/reel1/1920x1080
Baselight_export:
/images1/avengers/reel1/1920x1080 10 11 12 13 19 23 24
/ddnsan2/avengers/reel1/1920x1080 10-13
/ddnsan2/avengers/reel1/1920x1080 19
/ddnsan2/avengers/reel1/1920x1080 23-24
