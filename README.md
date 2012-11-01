# BsbFontAwesome

BsbFontAwesome is a ZF2 module that helps exposing the awesome font awesome project.



Update your composer.json in your project root to include the following snipped

    "require": {
        "bushbaby/fontawesome" : "dev-master"
    }

Additionally, since font awesome doesn't have a composer.json, add the following snipped to the composer.json in your project root.

    "repositories" : [
        {
            "type": "package",
            "package": {
                "version": "2.0.0",
                "name": "fortawesome/fontawesome",
                "source": {
                    "type": "git",
                    "url": "https://github.com/FortAwesome/Font-Awesome.git",
                    "reference": "2.0.0"
                }
            }
        }
    ],




