# udanit-marks
My own recipe for bookmark preserve.

## Composition
A bookmark is essentially defined by the origin: **u**rl, by the **d**ay when it was made, by its **a**uthor, and non-essentially by a **n**ame, an **i**nformational short description and by a few **t**ags.

## Specimen
### Markdown - extended syntax

```
***

U
: https://github.com/itmitica

D
: 2020-09-29

A
: mit

N
: itmitica (Mitică) · GitHub

I
: A GitHub repo

T
: `version` `control` `software` `repository` `bookmarks`

***

U
: https://github.com/itmitica

D
: 2020-09-29

A
: mit

***
```

<hr>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>D</dt>
<dd>2020-09-29</dd>
<dt>A</dt>
<dd>mit</dd>
<dt>N</dt>
<dd>itmitica (Mitică) · GitHub</dd>
<dt>I</dt>
<dd>A GitHub repo</dd>
<dt>T</dt>
<dd><code>version</code> <code>control</code> <code>software</code> <code>repository</code> <code>bookmarks</code></dd>
</dl>
<hr>
<dl>
<dt>U</dt>
<dd><a href="https://github.com/itmitica">https://github.com/itmitica</a></dd>
<dt>D</dt>
<dd>2020-09-29</dd>
<dt>A</dt>
<dd>mit</dd>
</dl>
<hr>

## Product preparation process

```
wget -qO- https://github.com/itmitica | grep -o "<title>[^<]*" | sed -e 's/<[^>]*>//g'
<meta name="description" content="
<meta name="keywords" content="
```
