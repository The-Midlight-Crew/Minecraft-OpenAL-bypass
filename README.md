# Minecraft-OpenAL-bypass
This is a modified version of Prism Launcher that bypasses the issues that some anti-viruses have with OpenAL. 

## Wait, what do you mean a modified version?

It's literally just Prism Launcher but with one setting changed and a different audio library. In fact, you can check for yourself. All that should be different is prismlauncher.config file, soft_oal.dll, and maybe the accounts.json file and logs folder because I didn't want to give my Minecraft account away.

## What's OpenAL?
It's an audio library that supports surround sound and various other audio related things. For some reason, some anti-viruses flag it, so we swapped it out with Soft OpenAL, and then changed the setting in Prism Launcher that checks what folder to get the audio library from. :D

## Why is it the portable version of Prism Launcher?

Because if you can install normal Prism Launcher, then the chances that your computer has issues with OpenAL are low.

## Can I do this myself if I don't trust you?

Yup. It's just compicated.
1. Download the Portable version of Prism Launcher from [here](https://prismlauncher.org/)
2. Download the top file on the list from [here](https://github.com/kcat/openal-soft/releases/tag/1.24.2). This is the Audio Library. 
3. Hit extract all, then move the folder from Downloads to This PC (C:\). Your screen should look kind of like this: ![image](https://github.com/user-attachments/assets/591b0c54-febf-4e7b-9cef-60269f88688c)
4. Open Prism Launcher.
5. Go to Settings > Minecraft > Tweaks. Tick "Use system installation of OpenAL". Copy this into the text box: C:\openal-soft-1.24.2-bin\openal-soft-1.24.2-bin\bin\Win64\soft_oal.dll
![image](https://github.com/user-attachments/assets/ff15e2e8-ab29-4899-9581-7a7889927329)

And then enjoy playing Minecraft. Or, you could just download this version, since we pretty much did all of that for you.

