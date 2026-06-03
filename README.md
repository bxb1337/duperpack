# DuperPack

Extraction tool for native libraries within Meta applications like WhatsApp, Instagram, and Facebook Messenger. This tool uses Github Actions to patch, install, and extract files from the associated Meta application. Those native libraries will be available once the GitHub action completes (~15 minutes per run).

This tool could definitely be improved but it gets the job done ¯\\\_(ツ)_/¯

## How to use
Fork this repository, then run the `Superpack Native Library Extraction` workflow manually from the Actions page and provide an APK download URL in the `apk_url` input (currently requires the Universal .apk).

![duperpackOutput](https://raw.githubusercontent.com/datalocaltmp/duperpack/main/images/output.png)

## Coming soon

Arbitrary application superpack unpacking.
