# hashwords
An experiment to make git commits or any 8 byte hash to 2 words.

## Usage

```
git log --format=%h | while read h
do
  commitwords $h
done | less
```
