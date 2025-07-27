# mkpass
Rudimentary command-line password generator.

## Usage

By default, invoking mkpass will generate a single 10-character password:

```
$ mkpass
T8aExxlC89
$ 
```

Use the `-n` flag to control how many passwords are generated:

```
$ mkpass -n 5
NY26BCQ8gn
ACdNYEzAQ4
YlCXkT1GRn
9f2aJnu9FR
nJGmUaml6G
$ 
```

Use the `-l` flag to control the length of the generated passwords:

```
$ mkpass -l 20
dFsVHalFJEcriN7S3Hfh
$
```

You can combine these two flags if you want to control the length and number of passwords simultaneously.
