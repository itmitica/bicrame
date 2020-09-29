# bicrame
bookmarks I can read and modify easily

## Structure
A bookmark is defined by: URL, title, description, keywords. Only the URL is mandatory.

## Exemplification
### Markdown - extended syntax

```
*U*
: https://github.com/itmitica

*T*
: itmitica (Mitică) · GitHub

*D*
: A GitHub repo

*K*
: `version` `control` `software` `repository` `bookmarks`

***

*U*
: https://github.com/itmitica

*T*
: itmitica (Mitică) · GitHub
```

<dl>
<dt><em>U</em></dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt><em>T</em></dt>
<dd>itmitica (Mitică) · GitHub</dd>
<dt><em>D</em></dt>
<dd>A GitHub repo</dd>
<dt><em>K</em></dt>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
</dl>
<hr>
<dl>
<dt><em>U</em></dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt><em>T</em></dt>
<dd>itmitica (Mitică) · GitHub</dd>
</dl>

## Meta retrieval

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
