google-drive-upload
===================

Command-line utility for uploading files to Google Drive.

Usage
-----

```
usage: google-drive-upload [-h] [-d DIRECTORY] file [file ...]

Upload a file to Google Drive.

positional arguments:
  file                  File to upload

optional arguments:
  -h, --help            show this help message and exit
  -d DIRECTORY, --directory DIRECTORY
                        Target directory
```

Configuration
-------------

`google-drive-upload` expects to find a configuration file at `~/.google-drive-upload/config` containing your Google API keys:


```ini
[default]

client_id = YOUR_CLIENT_ID
client_secret = YOUR_CLIENT_SECRET
```

You can obtain API keys from [Google Developers Console](https://code.google.com/apis/console).