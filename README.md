# TwitchOBS

## An OBS add-on that displays a user's info.

### How To Setup

Download the file, and open it in any text editor (e.g. Notepad). <br>
Scroll down until you see the line in the image below, and replace `YOUR CLIENT ID HERE` with your Twitch Client ID.

![Image](https://cdn.discordapp.com/attachments/906301382347358252/916760004151877673/unknown.png)

Once that is done, save the file and open it (it should open up in your default browser). <br>
In the search bar, it should show a similar URL as the one below.

![Image](https://cdn.discordapp.com/attachments/906301382347358252/916761316063051846/unknown.png)

In order to modify what streamer this displays, add `?user=streamer_name` to the end of the URL. <br>
Now that you have the URL, copy it or save it somewhere so you can begin to use the add-on in OBS

### How To Use#

Once you have opened OBS, add a browser source to whatever scene you want this added to. <br>
Click `OK`, and then in the `URL` section paste in the URL you copied earlier. Click `OK` again, and it should be added to your stream! <br>
However, the bright green background is still there. To remove this, first select the source and click `Filters`. <br>
Then add an Effect Filter and select `Chroma Key`. To get the best results, change the setting to the image below.

![Image](https://cdn.discordapp.com/attachments/912689470988496926/916753220959879188/unknown.png)

After that, click `Close` and you're done! <br>
If you ever want to edit the streamer it shows, click on the source and then click `Properties` and edit the URL.
