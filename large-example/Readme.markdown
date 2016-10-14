## sensu-plugins-large-example

*Note: all lowercase*

## Functionality

This suite of checks and metrics covers all your needs for technology/vendor Foo.

*Note: Basically a one sentence summary that tells people arriving via search engines if they found what they are looking for.*

## Checks & Metrics

- [check-first.rb][]: Checks the disk capacity of bar.
- [check-second.rb][]: Checks that the bar currently fits X's foo.
- [metrics-third.rb][]: Measures all values of sox in the example.

[check-first.rb]: docs/check-first.markdown
[check-second.rb]: docs/check-second.markdown
[metrics-third.rb]: docs/metrics-third.markdown

*Note: the links go to `docs/CHECK_BASENAME.markdown`.*  
*Note: this replaces the `files` section.*

## Usage

*Note: this section would be moved to the individual check sites.*

## Installation

```plain
sensu-install --plugin sensu-plugins-standard-example
```

Additionally you need to have X, Y and possibly Z installed, depending on your distribution. You might need a C/C++ compiler.

If you wish to use `check-second.rb` you furthermore need to install ABZ.

*Note: Linking to a completely other page should be last resort, but that is only my opinion.*

*Note: clearly state here if some checks/metrics have additional requirements.*

### Configuration

*Note: this section is optional and should be left out if not applicable.*

In order to use the wobbler you need to configure it first by having a section similar to the following in your Sensu configuration, e.g. in `/etc/sensu/conf.d/handlers/wobbler.json`. You can learn more about how Sensu can be configured in the [Sensu Configuration Reference doc][config-doc].

[config-doc]: https://sensuapp.org/docs/latest/reference/configuration.html

```json
{
  "wobbler": {
    "apikey": "1234abcdefg1234abcdefg",
    "apiversion": "v1",
    "room": "Ops",
    "from": "Sensu"
  }
}
```

## Notes

*Note: Put here what* **does not** *fit into other sections. If nothing is here, delete the sections and don't leave other empty sections either.*
