# Verified Followers
Find your verified Twitter followers using Python!

# Installation
* Get Twitter API keys
  * You will need consumer keys from a developer account and access keys from your target account. These can be from the same account, and will most likely be in your case.
* Clone or download the repo to your computer
* Ensure you have the latest version of Python 3 and pip installed
* In a Terminal, `cd` to the downloaded repo folder
* Install the required packages:
  * `pip3 install -r requirements.txt` will install the latest versions of all required packages and their dependencies
  * Alternatively, install these manually:
    * `pygal`, `tweepy`, `cairosvg`
* Open `verified-followers.py` in any text editor and enter your username at the top, as well as your Twitter API keys
* Either open the file an IDE such as Visual Studio Code and run, or type `python3 verified-followers.py` into a Terminal
* Find your verified followers!

# Important Info and Limitations
The list of followers and the pie chart will be saved to your home folder.

The progam will take quite a while, depending on how many followers you have. This is as it has to run the verification check on every one of your followers.
