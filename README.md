# Perfer

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

<files+> are a set of benchmark files

Common options:
    -t TIME                          Minimal time for to run (greater usually improve accuracy)
    -m N                             Numbers of measurements per job
    -h, --help                       Show this help
```

A benchmark tool for all rubies!

See [The GSoC proposal](http://www.google-melange.com/gsoc/proposal/review/google/gsoc2012/eregon/1) for more details.

And the [Wiki](https://github.com/jruby/perfer/wiki).
