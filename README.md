# HW1
DATA 515 Homework 1: Command line and submitting homework

Instructions for the homework:
* Create a `download_pronto.sh` script that does the following things: (1pt)
  * Makes a directory called `pronto_data` and does all the other steps from inside this directory (1pt)
  * Uses `curl` to download the Pronto bike data from `https://s3.amazonaws.com/pronto-data/open_data_year_one.zip`, saving the file as `pronto.zip` (1pt)
  * Unzips the archive with `unzip` (1pt)
  * Uses `head` to show the first few lines of `2015_trip_data.csv` to the user' (1pt)
  * Make sure your script is executable - ie you can run it with the command `./download_pronto.sh` (1pt)
    * In particular, if you are using Windows, this is slightly more complicated due to how Windows permissions interact with git. Check out [this guide](https://www.scivision.dev/git-windows-chmod-executable/) for making files executable with git on Windows.
    * If you're not sure if it worked, remember that you can use the `ls -l` command to view the permissions. In addition, in GitHub, if you view the file itself, you should see a label "Executable File" in the header for the file.
* The script should be present at the top level in your HW1 GitLab repository, and you should NOT upload `pronto.zip` or `pronto_data` (1pt)
* Submit your homework using GitLab/Gradescope (1pt)
