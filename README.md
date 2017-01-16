# karmaline

Blames your git repository and genereates HTML representation, where some karma value assigned to every line of code depending on who wrote it and on meta inforamtion from the commit message.

## Usage

```
./karmablame <repo> <config>
```

That will output some stats:

```
Processed 134/134
68/134 files has 100% good karma
27% of lines has good karma 1681/6128
Continuous groups larger that N lines:
	140:    0 groups (      0 lines)
	 70:    2 groups (    166 lines)
	 50:    3 groups (    222 lines)
	 30:   18 groups (    796 lines)
	 15:   45 groups (   1340 lines)
	  7:   66 groups (   1553 lines)
```

And generate HTML representation in `html` folder.

## Configuration

Is a json file, where you can specify which authors should get karma as well as some urls setup for HTML representation. You can use [.karmaline](.karmaline) as an example.
