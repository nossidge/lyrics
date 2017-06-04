# Lyrics

by Paul Thompson - nossidge@gmail.com

A tiny, simple CLI script to get lyrics from genius.com.


## Installation

This isn't a gem, it's just a simple one-file script.


### Gem dependencies

    $ gem install genius
    $ gem install nokogiri


### Genius API
Go to https://genius.com/developers and create a new API client.

Create an environment variable called `GENIUS_ACCESS_TOKEN` and put your access token in there.


## Usage

From the command line:

    $ lyrics "the monkees" "i'm a believer"
    $ lyrics "the beatles" "yellow submarine"
    $ lyrics "carly rae jepsen" "call me maybe"

You need the artist, then the song.

If it fails it will fail silently.


## Licence

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
