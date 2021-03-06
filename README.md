# python-twitch-clips

Python script that downloads twitch clips locally.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequirements

* Python 3
* Twitch account 
* Twitch client_id. Read the docs [here](https://dev.twitch.tv/docs/v5/#getting-a-client-id).

### Instructions

1. Clone the repository.
2. Insert the client_id into the script "client_id" variable.
3. Copy the Twitch clip link to clipboard.
4. Execute the script by running the following command:
```console  
python3 dltwitchclips.py --clip <paste_clip_url_here> 
```  
Note: **Make sure to install the Python3 modules before running the script.**  
5. The script will create tmp directory where the file will be saved.

## Known issues
---