# Perfer - A benchmark tool for all rubies!

<!-- usage -->
```text
Usage:
  perfer <command> [options] arguments

Commands:
  run files+    - run with current ruby
  report files+ - show the results
  config reset  - reset the configuration file to the defaults (or create it)
  help          - show this help
  results
    path files+      - show the paths to the result files
    rm,delete files+ - remove the result files
    rewrite files+   - rewrite the result files in the latest format

<files+> are a set of benchmark files

Common options:
    -t TIME                          Minimal time to run (greater usually improve accuracy)
    -m N                             Numbers of measurements per job
    -v                               Verbose
    -h, --help                       Show this help
```
<!-- usage -->

See [The GSoC proposal](http://www.google-melange.com/gsoc/proposal/review/google/gsoc2012/eregon/1) for more details.

And the [Wiki](https://github.com/jruby/perfer/wiki).

## Current status

This is a work in progress, 0.1.1 is a preview release.
