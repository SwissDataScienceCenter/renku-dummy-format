# A dummy Renku workflow converter plugin implementation

This repository contains a simple workflow converter implementation that will extend your renku installation
with a format type called `dummy`. Namely, after the successful installation of the plugin one will be
able to use this plugin to export a given workflow

```
$ renku workflow export --format dummy <my_workflow>
```

Note, because of the actual implementation this will not generate any output, only an error will be raised by renku.
