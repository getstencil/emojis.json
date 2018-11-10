# emojis.json
Tagged document for the `2,666` emojis we currently use in [Stencil](https://getstencil.com/). Lots of emoji JSON documents scattered around the web, but they were all missing different properties (and structure) that we needed.

Here's the breakdown of what's included in this document:
- `category` the category the emoji is part of
- `codes` an array of codes that apps may use, including `short`, `simple` and `standard`
- `name` the name of the emoji
- `skinTone` the skin tone of the emoji, or `false` if skin tone isn't relevant
- `tags` an array of tags for the emoji

## Note
I've since stumbled on [Cal Henderson](https://github.com/iamcal)'s amazing [emoji-data](https://github.com/iamcal/emoji-data) library. Will likely use it to consolidate the data I want, and keep this one going so that it's in the format [Stencil](https://getstencil.com/) likes :)
