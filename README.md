# _date_lib
a date library for real web programming.

### Step1. Create _Date object

var _D = new _Date()

### Step2. Use intuitive method chaining to get the timestamp you want.

Ex) Use intuitive method chaining to get the timestamp you want.

```_D.lastWeek().start().done().getTime();```

Ex) Do you want to get the last time stamp of today?

``` _D.end().done().getTime()
