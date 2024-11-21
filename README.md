# Postman API Finder Utility

The `api_finder` python utility allows a user the ability to find all API specifications that are being managed within all availabel team workspaces .

## Prerequisites

**Python Requirements**

The required python modules can be installed with the use of the [requirements.txt](requirements.txt) file which can be loaded via.

    pip(3) install -r requirements.txt    


## Usage

python(3) findit.py

This script currently expects the user's Postman API key to be set as an enviroment variable name postman_apikey.  

Line 26 of findit.py can be updated as required to set the API key differently until the script is updated to allow for the key to be passed via the command line.
  

## License

[MIT](LICENSE.txt)