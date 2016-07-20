Contact info for Meghan Maloy

To replicate:
    -make new directory
    -npm init
    -add index.js and info.json files (can copy after installing this package)
    -edit package.json "scripts" to include the following line in the array:
          "postinstall":"cat info.json"
    -npm publish
    -to test, go to another directory and npm install the package