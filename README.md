# bicrame
bookmarks I can read and modify easily

## Structure
The bookmarks list is a definitions list. A bookmark entry is a definition element. The definition term is the title as a url link. The first definition is the description. The second definition is a list of keywords.

## Exemplification
### Markdown - extended syntax

```
##
[itmitica (Mitică) · GitHub](https://github.com/itmitica)
: A guy's GitHub repo
: version control software repository bookmarks
##
[itmitica (Mitică) · GitHub](https://github.com/itmitica)
: A guy's GitHub repo
: version control software repository bookmarks
```

<h2></h2>
<dl>
<dt>itmitica (Mitică) · GitHub</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dd>version control software repository bookmarks</dd>
</dl>
<h2></h2>
<dl>
<dt>itmitica (Mitică) · GitHub</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dd>version control software repository bookmarks</dd>
</dl>

## Meta retrieval

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
