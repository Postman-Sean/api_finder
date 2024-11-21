# Postman API Finder Utility

The `api_finder` python utility allows a user the ability to find all API specifications that are being managed within all availabel team workspaces .

## Prerequisites

**Python Requirements**

The required python modules can be installed with the use of the [requirements.txt](requirements.txt) file which can be loaded via.

    pip(3) install -r requirements.txt    


## Usage

python(3) findit.py [-apikey POSTMAN_APIKEY]

If the Postman API key is not provided via the commandline the script will attempt to pull the value from the user's environment via a variable named postman_apikey.

  

## License

[MIT](LICENSE.txt)