# Delicious Library XML2JSON

XML to JSON converter for Delicious Library exports.

## Getting Started

These instructions will help you generate a JSON file from your Delicious Library export.

### Prerequisites

Node

### Installing

Open terminal and cd to your desired working folder.

Clone this repo to your local system

```
git clone git@github.com:pgraci/delicious-library-xml2json.git
```

Then cd into the new folder that is created

```
cd delicious-library-xml2json
```

Run npm to install package dependencies

```
npm install
```

Run the node script

```
node index.js
```

This should complete immediately, but may take longer depending on the size of your XML file.

Once completed, there will now be a library.json file in this folder.

Replace the sample library.xml file with one that you export. However you need to edit the xml file and delete the following line:

`<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">`

Save the file, and run the node script again.

## Authors

* **Phil Graci** http://philgraci.com

## Acknowledgments

Forked from https://github.com/marcghorayeb/delicious-library-xml2json

Sample library.xml file included is courtesy of Mark Hines @Realeyz for Likkle Shop NYC.
