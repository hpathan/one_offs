One Offs
========

Track and manage your one off scripts, in rails applications.

Can be used to move stuff out from your rails migrations that dont belong there. For example data migrations can be moved from schema and into one-offs.

## Installation

Add this line to your application's Gemfile:

    gem 'one_offs'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install one_offs

## Usage

After installing the gem setup a tracker table.


    rake one_offs:generate_tracker_table

Add scripts to `lib/one_offs/`

To run pending one_off scripts.

    rake one_offs:run

To baseline one_offs seed them into to the tracker table.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
