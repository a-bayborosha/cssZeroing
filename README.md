# cssZeroing
# for the "Live Sass Compiller" extension: a style.css if you want it to be added to a separate folder
# add next code to the settings.json in VS Code
"liveSassCompile.settings.generateMap": false,
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "autoprefix": "last 5 versions",
            "extensionName": ".css",
            "savePath": "css"
        }
    ],
