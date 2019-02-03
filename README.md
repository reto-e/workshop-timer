# workshop-timer
## What does it do?
Well, it times your workshop. There are two main panels on the page: The planned minutes of the workshop are on the left hand side. On the right hand side there is a timer you can use to time different activities of your workshop.

## How do I use it?
### Download
Download the files, store them somewhere on your computer. the "innoventa_timer.html" is the main file with the page, the "gong.mp3" is the sound file which is played when the timer finishes.

So open your browser and drag the "innoventa_timer.html" file into it and you are ready to go. 

### Set up the minutes
Hit the "edit" button and type in your minutes in csv-style. Example:
```
Intro,5
Activation,3
Describe the problem,15
Collect aspects of the problem,15
```

Save this entries. The entries will get stored to your local storage. I.e. they are available only on the computer where you edited the entries. To share the minutes among different computers you need to copy-paste your minutes and store them again on other computers.

## Used Components
The css is from [w3-css](https://www.w3schools.com/w3css/default.asp).
The nice charts come from [chart.js](https://www.chartjs.org/)
The gong used in thes example is the alien spaceship UFO Sound from [soundbible](http://soundbible.com/2213-Alien-Spaceship-UFO.html)

## Known issues
* After a change of the minutes you have to reload the page (e.g. with F5) to see the changes
* Since the the minutes are stored in the local storage, they are bound to one computer and cannot be easily shared. This is done on purpose, though, because like this I do not need to run a server with user authentication and so on.
* The workshop-timer does not appear to behave very cooperative with Safari browser... 
