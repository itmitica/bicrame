# unitad-marks
My own recipe for bookmark preserve.

## Composition
A bookmark is essentially defined by its origin, the **u**rl, and non-essentially by a **n**ame, an **i**nformational short description, by a few **t**ags, the **d**ay when it was made and by its **a**uthor.

## Specimen
### Markdown - extended syntax

```
***

U
: https://github.com/itmitica

N
: itmitica (Mitică) · GitHub

I
: A GitHub repo

T
: `version` `control` `software` `repository` `bookmarks`

A
: mit

D
: 2020-09-29

***

U
: https://github.com/itmitica

N
: itmitica (Mitică) · GitHub

A
: mit

D
: 2020-09-29

***
```

<hr>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>N</dt>
<dd>itmitica (Mitică) · GitHub</dd>
<dt>I</dt>
<dd>A GitHub repo</dd>
<dt>T</dt>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
<dt>A</dt>
<dd>mit</dd>
<dt>D</dt>
<dd>2020-09-29</dd>
</dl>
<hr>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>N</dt>
<dd>itmitica (Mitică) · GitHub</dd>
<dt>A</dt>
<dd>mit</dd>
<dt>D</dt>
<dd>2020-09-29</dd>
</dl>
<hr>

## Product preparation process

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
