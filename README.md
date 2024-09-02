# snutil
Back up and operate on my simplenote contents

# Ideas
    - [x] snsync
    - [x] git archive
    - [x] !!ds -> datestamp (e.g., 20240902)
    - [ ] Nightly re-order top list with completed to-do's at bottom (respecting hierarchies!)
    - [ ] s/^- t /- [ ] /
    - [x] add completed date info to items newly marked 
    - [ ] report back actions into simplenote entry, rotated
    - [ ] generate a newsfeed note; update it frequently through the day with headlines, weather, etc.
    - [ ] generate a note with a text version of my calendar, given various ical and caldav feeds

## Ideas that depends on tags

snsync doesn't provide an easy way to see or manipulate tags. Probably they could be sussed out of the .snsync.sqlite.

    - [ ] operate on files according to tag 
    - [ ] sync tags onto last line of file?
    - [ ] !!archive -> mv to archive folder sorted by year

# License
GPL 3.0 or later
This script plays with fire (modifying important files in a chaotic cloud-based data store). Use at your own risk.
