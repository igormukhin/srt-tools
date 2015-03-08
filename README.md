# srt-tools
Some useful tools to work with SRT files content especially for preparing voice-over texts.

To run it, browse to
http://igormukhin.github.io/srt-tools/

### Help

**Left panel**
- **Fix line numbers**: Use this if you manually removed or added lines in the srt files
- **SRT to TXT**: Strips all the control lines line title numbers and timestamps and show the text in the right panel
- **Create roles table**: If you have subtitles with multiple roles (where each role marked with [rolename] at the beginning of the line) then this button will create a nice table which you can copy to Excel file and use auto-filters to find only sayings of a particular person.

**Right panel**
- **TXT to SRT**: Only works with one-lines subtitles! After you did "SRT to TXT" and edited the text on the right, you can merge you changes to the left panel
- **Strip line breaks**: Removes all line breaks

### Publishing updates

If you want to publish just pushed master commits to public: 
1. switch to `gh-pages` branch
2. merge from `master` branch
3. push to GitHub
4. switch back to `master` branch
