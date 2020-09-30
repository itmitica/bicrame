## Existing bookmarks

### Export links from existing bookmarks to a text file.

#### Chrome

Open bookmarks page `chrome://bookmarks`, select all `Ctrl+A`, copy `Ctrl+C` and paste `Ctrl+P` to a `bookmarks.txt` text file.

### Sort and remove duplicates

#### Linux

`sort bookmarks.txt | uniq -u > prepared-bookmarks.txt`.

## Product preparation process

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```

