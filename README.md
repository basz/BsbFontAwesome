# BsbFontAwesome

BsbFontAwesome is a ZF2 module that helps exposing the awesome font awesome project.



Update your composer.json in your project root to include the following snipped

    "require": {
        "bushbaby/fontawesome" : "1.*"
    }

Additionally, since font awesome doesn't have a composer.json, add the following snipped to the composer.json in your project root.

    "repositories" : [
        {
            "type": "package",
            "package": {
                "version": "3.0.0",
                "name": "fortawesome/fontawesome",
                "source": {
                    "type": "git",
                    "url": "https://github.com/FortAwesome/Font-Awesome.git",
                    "reference": "3.0.0"
                }
            }
        }
    ],




