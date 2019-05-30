This guide is if you want to translate Pina in your own language.

The first step is to step and clone this repository.

If your language doesn't exist, you'll need to create a folder with your language 'code' in the Translations directory.<br/>
Language code must be follow [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) (ex: 'fr' for French, 'ja' for Japanese, etc...).

Then inside begin by creating a infos.json file that will contains the 2 following keys:
- **nameEnglish**: The name of the language in the english language
- **nameLanguage**: The name of the language in your language
For example, with french 'nameEnglish' would be 'french' and 'nameLanguage' would be 'français'

Then create a terms.json file and write all your translations here, the easiest way to know the different keys is to take the [english terms.json](Translations/en/terms.json) as an example.

Please make sure to translate "pin" and "Manage Messages" as Discord do.

Either way, once you are done just do a pull request. 
