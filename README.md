Suppress UDFs
----------------------------------------------

This plugin suppresses fields identified by the best practices group in 2016.

## User Defined [AS-128](https://issues.library.jhu.edu/browse/AS-128)

- Boolean 1
- Boolean 2
- Boolean 3
- Integer 1
- Integer 2
- Integer 3
- Real 2
- Real 3
- Date 1
- Date 2
- Date 3
- Controlled Value 1 *Skipped because this is being used for accession status*
- Controlled Value 2
- Controlled Value 3
- Controlled Value 4

## Installation

To install, just activate the plugin in your config/config.rb file by
including an entry such as:

     AppConfig[:plugins] = ['jhu-suppress']

Then restart ArchivesSpace.
