[![codebeat badge](https://codebeat.co/badges/05cadbce-cabe-434f-9107-319932900f0a)](https://codebeat.co/projects/github-com-adfleshner-aaronsays-master)

# AaronSays
A simon says kotlin implementation because I was bored.

## Why
Because I was bored and thought it would be fun.

#### Known Issues
* There are times the sound stops working and then continues to not work until app is restarted.
* Some times the background of the button will get stuck in a certain state. (Either never turn on, never turn off, or if one color is selected twice in a row the color may not light up or turn off.)

#### Done
- [x] All buttons.
- [x] Highlight button when selected.
- [x] Play tone when selected.
- [x] Game Logic.
- [x] User interactions.
- [x] Play error if incorrect.
- [x] Add Scoring.
- [x] Add High Scoring.
- [x] Add Restart game if game ends (via Dialog).
- [x] Add Start button. 
- [x] Add new theme
- [x] Add Ad Support (Because I want to learn how it works) + show ad logic

#### TODOs
- [ ] Add custom themes
- [ ] Add custom sounds
- [ ] Add Animations!
- [ ] Add pay support (Because I want to learn how it works)
- [ ] Add New game modes (Maybe something with multiple button at once or simon swipe)
- [ ] Fix Sound and Highlight Issues.

##### 3rd Party Libraries
```gradle 
    implementation 'com.github.mcginty:material-colors:1.1.0'
```
