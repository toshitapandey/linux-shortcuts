### The Grep way

#### 1. Find a string/text through command line

##### 1.1 - Find a text recursively

```
grep -R 'the text I want to search'
```

##### 1.2 - Find a text recursively but exclude a folder

```
grep -R 'the text I want to search' --exclude-dir='folderToExclude'
```

##### 1.3 - Find a text recursively, and include line numbers of file in the output 

```
grep -nR 'the text I want to search' --exclude-dir='folderToExclude'
```
