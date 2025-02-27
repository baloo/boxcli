`box recent-items`
==================

List information about files accessed in the past 90 days up to a 1000 items

* [`box recent-items`](#box-recent-items)

## `box recent-items`

List information about files accessed in the past 90 days up to a 1000 items

```
USAGE
  $ box recent-items

OPTIONS
  -h, --help                             Show CLI help
  -q, --quiet                            Suppress any non-error output to stderr
  -s, --save                             Save report to default reports folder on disk
  -t, --token=token                      Provide a token to perform this call
  -v, --verbose                          Show verbose output, which can be helpful for debugging
  -y, --yes                              Automatically respond yes to all confirmation prompts
  --as-user=as-user                      Provide an ID for a user
  --bulk-file-path=bulk-file-path        File path to bulk .csv or .json objects
  --csv                                  Output formatted CSV
  --fields=fields                        Comma separated list of fields to show
  --json                                 Output formatted JSON

  --max-items=max-items                  A value that indicates the maximum number of results to return. This only
                                         specifies a maximum boundary and will not guarantee the minimum number of
                                         results returned. When the max-items (x) is greater than 1000, then the maximum
                                         ceil(x/1000) requests will be made.

  --no-color                             Turn off colors for logging

  --save-to-file-path=save-to-file-path  Override default file path to save report

EXAMPLE
  box recent-items
```

_See code: [src/commands/recent-items.js](https://github.com/box/boxcli/blob/v3.9.2/src/commands/recent-items.js)_
