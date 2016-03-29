# hashwords
An experiment to make git commits or any 8 byte hash to 2 words.

## Usage

To get the words for a commit:

```
./commitwords <your_7_hex_commit>
# or
git log --format=%h | while read h
do
  ./commitwords $h
done | less
```

To get the commit for words:

```
./wordscommit your.words
```

Output:

```
11bc31a12
```
