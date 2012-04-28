# NamedEmoji

Named Emojis for OSX. Emojis are from Campfire and GitHub.

See also: [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/)

## Installation

    $ gem install named_emoji

## Usage

    require 'named_emoji'
    puts NamedEmoji[:smile]
    # => ��

As command line tool:

    $ emoji scream
    ��

List available emojis:

    $ emoji -l

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
