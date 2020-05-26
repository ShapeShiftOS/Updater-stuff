

>> The OTA updater requires a json file like below:

```bash
{
  "response": [
    {
      "datetime": 1590123226,
      "filename": "LineageOS-14.1-begonia-20200522-0455-OFFICIAL.zip",
      "id": "c3ae825794d977d42c856212f0aa806b",
      "romtype": "OFFICIAL",
      "size": 726564073,
      "url": "https://sourceforge.net/projects/LineageOS/files/begonia/LineageOS-14.1-begonia-20200522-0455-OFFICIAL.zip.zip/download",
      "version": "14"
    }
  ]
}
```

>> This has to be named according to your codename. For example: begonia.json


>> To add a changelog, simply create a changelog file with the first two lines empty. This file name should also be according to the device's codename.
For example: begonia.md

>> All these files can be found in the out directory after a successful build. You have to simply rename them, adapt them to our order, and then pull request the files. Once they are in this repository, devices will receive an update through the OTA Updater.
