# home-assistant-face-mask-tracker
Simple HA config to rotate and keep track of multiple face masks during the SARS-CoV-2 Covid19 pandemic

Requirements:
* https://github.com/custom-cards/button-card (install via HACS)

![Frontend](https://raw.githubusercontent.com/jhein05/home-assistant-face-mask-tracker/main/screenshots/frontend.jpg)

The large icon tells you what color face mask to wear when you leave the house. Once you come back, you log the amount of time you used the mask and the color changes to the next mask. Once a mask has been used for 8 hours, it becomes EOL (end-of-life) and you can press the small button to reset the counter after you discarded the mask and replaced it with a new one.

The colors in the frontend match the colors of the masks we are using:
![Masks](https://raw.githubusercontent.com/jhein05/home-assistant-face-mask-tracker/main/screenshots/masks.jpg)
