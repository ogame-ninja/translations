# Community effort

This repository is meant to bring the community together and create a high quality translation of the Nja app for all the languages.

Make pull requests / issues !

# Instructions

Create a new file for your language eg: `es.yaml` based on `sample.yaml`.  
Translate all the values  
To test the result, place the file in `~/.ogame/locals/es.yaml`  
Then restart the app with the `./nja --lang=es` flag (if your browser default lang is `es`, then the flag is not needed)

You can reload the changes without restarting the app by loading this url: http://127.0.0.1:8080/api/v1/reload-locals
