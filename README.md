MultiLine

This trival project demonstrates using multi-line strings in an iOS app's localizable.strings file.

The contents of localizable.strings is:

```
"foo" = "This
is
a
multi-line
string";
```

The code that uses it, from the single view controller's viewDidLoad, is:

            print(NSLocalizedString("foo", value: "foo", comment: "comment"))


And the output it generates to the console is:

```
This
is
a
multi-line
string
```
