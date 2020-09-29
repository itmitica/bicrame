# utdk-marks
My own recipe for bookmark preserve.

## Composition
A bookmark is defined by: **u**rl, **t**itle, **d**escription, **k**eywords. The key ingredient: the **u**rl.

## Specimen
### Markdown - extended syntax

```
***

U
: https://github.com/itmitica

T
: itmitica (Mitică) · GitHub

D
: A GitHub repo

K
: `version` `control` `software` `repository` `bookmarks`

***

U
: https://github.com/itmitica

T
: itmitica (Mitică) · GitHub

***
```

<hr>
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
<hr>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>T</dt>
<dd>itmitica (Mitică) · GitHub</dd>
</dl>
<hr>

## Product preparation process

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
