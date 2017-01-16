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
	140:    0 groups (  0%)      0 lines (  0%)
	 70:    2 groups (  2%)    166 lines (  2%)
	 50:    3 groups (  3%)    222 lines (  3%)
	 30:   18 groups ( 18%)    796 lines ( 12%)
	 15:   45 groups ( 45%)   1340 lines ( 21%)
	  7:   66 groups ( 66%)   1553 lines ( 25%)
	  3:   93 groups ( 93%)   1672 lines ( 27%)
```

And generate HTML representation in `html` folder.

## Configuration

Is a json file, where you can specify which authors should get karma as well as some urls setup for HTML representation. You can use [.karmaline](.karmaline) as an example.
