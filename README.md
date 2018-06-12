# i18next-translate

This repository is a fork of i18n-translate but for use with i18next

All credit goes to https://github.com/thomasbrueggemann/i18n-translate


## Installation

```
npm install -g i18next-translate
```

## Usage

You need a [Google Translate API Key](https://cloud.google.com/translate/).

```
i18n-translate apiKey startDir sourceLang targetLang1,targetLang2,.. (file1,file2,..)
```

e.g.

```
i18n-translate iuOHAEbo9H788d34h93h4diouehIUHI test/data/ de en,fr
```

This would translate all the *.js files in test/data (relative to current folder in the shell) to translate from German to English and French, based on the Google Translate API language codes.

The *file filter* for specific file names is optional. You can specify files in the target folder that you exclusively want to be translated.
