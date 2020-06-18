

>> The OTA updater requires a json file like below:

```bash
{
   "datetime": 1592474685,
   "filehash": "c90df85ba2c3fb5c9cd35a1b6281bd37",
   "filename": "ShapeShiftOS_Magikarp-1.0.3_laurel_sprout-10.0-20200618-1006-OFFICIAL.zip",
   "id": "2e43d9a7957bd920eb49a6eff70d79d0a400b5c6dfcfc3c4dc3179d09942a25c",
   "size": 1392972233,
   "url": "https://mega.nz/file/zugE1CxK#DtZLEYdrJL_U_QCVyUNwno64cAZbpxboHMUIcMdk1uw"
}
```
>> The json file with this data will be created in the out folder after a successful build.

>> If your device codename in lunch command has a capital letter, as in Plate2, the changelog and json should be written similarly. 

>> This has to be named according to your codename. For example: begonia.json


>> To add a changelog, simply create a changelog file with the first two lines empty. This file name should also be according to the device's codename.
For example: begonia.md

>> All these files can be found in the out directory after a successful build. You have to simply rename them, adapt them to our order, add the download link, and then pull request the files. Once they are in this repository, devices will receive an update through the OTA Updater.
