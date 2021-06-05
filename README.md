# GoogleDriveMigrator
a note/script to help automate the tiresome and frustrating process of moving from one google account to the other

[Link to full Google CoLab sheet.](https://colab.research.google.com/drive/1-ROiF2AmBJkHbFmADSMJxWNfRchATZZf?usp=sharing)

The full details are in the .ipynb file, but note that there are 3 things that must be done before being able to migrate the files:

1. Get the folder IDs for both the source and destination folder.
2. If not using the name "drive_download" for the name of the destination folder it will need to be changed.
3. \[optionally\] add any folders you want to skip to the "skipFolderList".

# Thanks
This script was mostly adapted from the amazing work by [wenkesj's](https://stackoverflow.com/users/9252356/wenkesj) in [this StackOverflow answer](https://stackoverflow.com/questions/48376580/google-colab-how-to-read-data-from-my-google-drive).
