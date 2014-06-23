```
                                                                                                 
 _____       _               _____     _           _     _____                               _   
|   __|_____| |_ ___ ___ ___|  |  |___| |___ ___ _| |___|     |___ _____ ___ ___ ___ ___ ___| |_ 
|   __|     | . | -_|  _|___|  |  | . | | . | .'| . |___|   --| . |     | . | . |   | -_|   |  _|
|_____|_|_|_|___|___|_|     |_____|  _|_|___|__,|___|   |_____|___|_|_|_|  _|___|_|_|___|_|_|_|  
                                  |_|                                   |_|                      
```

This project is currently under heavy/active development and I would not recommend using.

### TODO

* Setup broccoli
* Get tests running
* Rework project structure


### Usage

```handlebars
{{asset-uploader uploadUrl='/files' uploadParams=controller.uploadParams uploadDataName='file' width='300' height='300' action="fileUploaded" attachTo=controller.model.page deleteAction='deleteFile'}}
```