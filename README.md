# Note_Taker
Note Taker

## Note Taker

- My motivation in building a SVG Logo Maker is to get better at JavaScripting.
- I built this SVG Logo Maker to allow someone to quickly create a logo using different shapes, text and colors.
- I learned a little JavaScripting.

## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

## Usage

Use the Note Taker to take notes daily to help you not to forget things.
```
https://github.com/Kimberlyc1904/Note_Taker
https://note-taker-kc-7b30231ce7da.herokuapp.com/
```
## Deployment to Heroku steps
```
git init
heroku git:remote -a note-taker-kc
set git remote heroku to https://git.heroku.com/note-taker-kc.git
git add .
git commit -am "make it better"
git push heroku main
```

## Tests
```
Once deployed I tested that the app would open correctly in Heroku. Checked logs to see erors and used google to try to resolve.
First error I was able to resolve by moving the package.json file to the root.
Second error I had to change the PORT coding in the server.js file to allow the app to open correctly.
```

![screenshot](images/ScreenShot.png)

## Credits

```
Erwin Jocosing Student. @ github.com/ej619
W3 Schools https://www.w3schools.com/
ChatGPT https://chat.openai.com/
Nick TA
youtube
```
