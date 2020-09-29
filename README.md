# BUTDK marks
Bookmarks, my way.

## Structure
A **B**ookmark is defined by: **U**RL, **T**itle, **D**escription, **K**eywords. Only the URL is a must.

## Exemplification
### Markdown - extended syntax

```
#### B

U
: https://github.com/itmitica

T
: itmitica (Mitică) · GitHub

D
: A GitHub repo

K
: `version` `control` `software` `repository` `bookmarks`

#### B

U
: https://github.com/itmitica

T
: itmitica (Mitică) · GitHub
```

<h4>B</h4>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>T</dt>
<dd>itmitica (Mitică) · GitHub</dd>
<dt>D</dt>
<dd>A GitHub repo</dd>
<dt>K</dt>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
</dl>
<h4>B</h4>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>T</dt>
<dd>itmitica (Mitică) · GitHub</dd>
</dl>

## Meta retrieval

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
