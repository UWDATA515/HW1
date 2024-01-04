# HW1
DATA 515 Homework 1: Command line and submitting homework

Instructions for the homework:
* Create a `download_pronto.sh` script that does the following things:
  * Makes a directory called `pronto_data` and does all the other steps from inside this directory.
  * Uses `curl` to download the Pronto bike data in CSV from `https://data.seattle.gov/api/views/tw7j-dfaw/rows.csv?accessType=DOWNLOAD` and save the output to `pronto.csv`
  * Uses `head` to show the first few lines of the CSV to the user.
  * Make sure your script is executable - ie you can run it with the command `./download_pronto.sh`.
    * In particular, if you are using Windows, this is slightly more complicated due to how Windows permissions interact with git. Check out [this guide](https://www.scivision.dev/git-windows-chmod-executable/) for making files executable with git on Windows.
    * If you're not sure if it worked, remember that you can use the `ls -l` command to view the permissions.
* Submit your homework using git/GitHub. The script should be present at the top level in your HW1 GitHub repository, and you should NOT upload `pronto.csv`.
