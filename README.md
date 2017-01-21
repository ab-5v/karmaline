# karmaline

Blames your git repository and genereates HTML representation, where some karma value assigned to every line of code depending on who wrote it and on meta inforamtion from the commit message.

## Usage

```
./karmablame <repo> <config>
```

That will output some stats:

```
Processed 151/151
42% files have absolutely good karma (64/151)
24% of lines have good karma (1574/6443)
Continuous groups larger that N lines (out of 125):
	140:   0% groups (     0)   0% lines (       0)
	 70:   1% groups (     2)   2% lines (     166)
	 50:   1% groups (     2)   2% lines (     166)
	 30:  11% groups (    14)   9% lines (     643)
	 15:  30% groups (    38)  17% lines (    1123)
	  7:  52% groups (    65)  21% lines (    1380)
	  3:  83% groups (   104)  23% lines (    1542)
```

And generate HTML representation in `html` folder.

## Configuration

Is a json file, where you can specify which authors should get karma as well as some urls setup for HTML representation. You can use [.karmaline](.karmaline) as an example.
