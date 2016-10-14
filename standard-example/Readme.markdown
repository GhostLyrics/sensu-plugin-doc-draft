## sensu-plugins-standard-example

*Note: all lowercase*

## Functionality

The standard-example measures your sox and check for bars fitting into foos.

*Note: Basically a one sentence summary that tells people arriving via search engines if they found what they are looking for.*  
*Note: this obsoletes the `files` section.*

### check-first.rb

Check disk capacity and inodes based upon the gem sys-filesystem.

**parameters:** (alphabetic)

- `foo`: limit on which value of bar this and that happens. (default: `777`)

*Note: list all parameters and include default values so people know what can be done without crawling into the code.*

### check-second.rb

Checks that the bar currently fits into the foo.

**parameters:**

- none

### metric-third.rb

Measures all values of sox in the example.

**parameters:**

- `scheme`: The scheme how to label your metrics

**values:**

- `sox.disk_capacity`: How many voxels currently fit into the sandbox. (unit: voxels)
- `sox.radiator_consumption`: How many ions are shot into the radiator per second (unit: ions/second)

*Note: Short descriptions what is measured so that it's easy to understand what is measured if the plugin outputs a high amount of different, complex values*


## Usage

To do example with a and b enabled you would use:

```plain
check-first.rb --pattern "meh" --warning "7" --critical "9"
```

*Note: Prefer long parameters due to readibility*


## Installation

```plain
sensu-install --plugin sensu-plugins-standard-example
```

Additionally you need to have X, Y and possibly Z installed, depending on your distribution. You might need a C/C++ compiler.

*Note: Linking to a completely other page should be last resort, but that is only my opinion.*

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
