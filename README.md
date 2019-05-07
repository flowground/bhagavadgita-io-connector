# ![LOGO](logo.png) Bhagavad Gita **flow**ground Connector

## Description

A generated **flow**ground connector for the Bhagavad Gita API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/bhagavadgita.io/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:39:41+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### Get all the 18 Chapters of the Bhagavad Gita.

> Get a list of all the 18 Chapters of the Bhagavad Gita.

*Tags:* `chapter`

#### Input Parameters
* `access_token` - _required_ - Your app's access token.
* `language` - _optional_ - Language to query. Leave blank for english.
    Possible values: hi.

### Get a specific chapter from the Bhagavad Gita.

> Get information about a specific chapter from the Bhagavad Gita.

*Tags:* `chapter`

#### Input Parameters
* `access_token` - _required_ - Your app's access token.
* `chapter_number` - _required_ - Which Chapter Number to filter?
    Possible values: 1, 2, 3.
* `language` - _optional_ - Language to query. Leave blank for english.
    Possible values: hi.

### Get all the Verses from a Chapter.

> Get a list of all Verses from a particular Chapter.

*Tags:* `verse`

#### Input Parameters
* `access_token` - _required_ - Your app's access token.
* `chapter_number` - _required_ - Which Chapter Number to filter?
    Possible values: 1, 2, 3.
* `language` - _optional_ - Language to query. Leave blank for english.
    Possible values: hi.

### Get a particular verse from a chapter.

> Get a specific verse from a specific chapter.

*Tags:* `verse`

#### Input Parameters
* `access_token` - _required_ - Your app's access token.
* `chapter_number` - _required_ - Which Chapter Number to filter?
    Possible values: 1, 2, 3.
* `verse_number` - _required_ - Which Verse Number to filter?
    Possible values: 1, 2, 3.
* `language` - _optional_ - Language to query. Leave blank for english.
    Possible values: hi.

### Get all the Verses.

> Get a list of all Verses.

*Tags:* `verse`

#### Input Parameters
* `access_token` - _required_ - Your app's access token.
* `language` - _optional_ - Language to query. Leave blank for english.
    Possible values: hi.

### Send client credentials and get an access token.

*Tags:* `auth`

## License

**flow**ground :- Telekom iPaaS / bhagavadgita-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
