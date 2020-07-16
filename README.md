# Intl plugin for Sanity
[![npm version](https://img.shields.io/npm/v/sanity-plugin-intl-input.svg?style=flat)](https://www.npmjs.com/package/sanity-plugin-intl-input)

## Default solution
When you want to create translations in Sanity they suggest [following approach](https://www.sanity.io/docs/localization).  
This definitely works, but makes the UI very clunky as you get more fields that require translations.  

![Default Solution](https://raw.githubusercontent.com/LiamMartens/sanity-plugin-intl-input/master/doc/img/default-solution.gif)  

## With intl-plugin
With the intl plugin you will get a cleaner UI for creating translatable documents as the translation is managed across multiple fields and it is even possible to manage document wide translations.  

| Simple translated object field | Document wide translation |
|-|-|
|![Intl Plugin Input](https://raw.githubusercontent.com/LiamMartens/sanity-plugin-intl-input/master/doc/img/intl-plugin.gif)|![Intl Plugin Document Translation](https://raw.githubusercontent.com/LiamMartens/sanity-plugin-intl-input/master/doc/img/intl-plugin-document.gif)|

### Documentation
1. [Installation Instructions](docs/installation.md)
2. How to use
    - [Intl object input](docs/usage-intl-object.md)
    - [Document wide translation](docs/usage-intl-doc.md)
3. Datastructure
    - [Intl object input](docs/datastructure-intl-object.md)
    - [Document wide translation](docs/datastructure-intl-doc.md)
4. [GraphQL support](docs/graphql-intl-doc.md)
5. [Advanced languages](docs/advanced-languages.md)