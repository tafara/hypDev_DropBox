#!python3.5

# Prerequisites :
# 1.SetUp dropbox sdk to be able to use Dropbox Api's
# $ sudo pip install dropbox

# By default python dropbox sdk is based on python version 3.5
#
# 2. Create an App from the dropbox console (https://www.dropbox.com/developers/apps) which will be used and validated to do
# the file upload and restore using dropbox api. You will need an access token to connect to Dropbox before actual file/folder operations.
#
# 3. Once done with code, you can run the script

# $ python main.py // if python3.5 is default

# The script works like this..
# a. Local folder path and destination filename are hardcoded
# b. The script then checks if the given access token is valid
# c. If it is valid, it lists files in the destination folder

# d. It then uploads the local file on dropbox

