# Command-Line-notes-app
The app is completly build no nodeJS using some npm packages
In this app user can do the folllowing functionality.
1) add the notes using title (node app.js add --title="your note title" --body="body of the notes" ).
2) read the notes using title (node app.js read --title="your note title").
3) list all the notes with title (node app.js list).
4) remove the note using title (remove app.js --title="your note title").

all added notes save in text file called notes.json.

npm package.
1) file system=fs
2) chalk
3) yargs
