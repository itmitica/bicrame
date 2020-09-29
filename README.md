# bicrame
bookmarks I can read and modify easily

## Structure
The bookmarks list is a definitions list. A bookmark entry is a definition element.

The definition term is the title. The first definition is a short description. The second definition is the URL. The third definition is a list of keywords, tags.

## Exemplification
### Markdown - extended syntax

```
##
itmitica (Mitică) · GitHub
: A guy's GitHub repo
: https://github.com/itmitica
: version control software repository bookmarks
##
itmitica (Mitică) · GitHub
: A guy's GitHub repo
: https://github.com/itmitica
: version control software repository bookmarks
```

<h2></h2>
<dl>
<dt>itmitica (Mitică) · GitHub</dt>
<dd>A guy’s GitHub repo</dd>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
</dl>
<h2></h2>
<dl>
<dt>itmitica (Mitică) · GitHub</dt>
<dd>A guy’s GitHub repo</dd>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
</dl>

## Meta retrieval

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
