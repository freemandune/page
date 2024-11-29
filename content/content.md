+++
date = '2024-10-21T23:14:02+02:00'
draft = false
menus = ['main', 'footer']
title = 'Content'
+++

{{< highlight go >}} A bunch of code here {{< /highlight >}}
{{< figure src="elephant.jpg" title="An elephant at sunset" >}}

<b>rwarawr</b>
- test1
- test2
- test3

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).


{{< highlight go-html-template >}}
{{ range .Pages }}
  <h2><a href="{{ .RelPermalink }}">{{ .LinkTitle }}</a></h2>
{{ end }}
{{< /highlight >}}

[Post 1]({{% relref "/posts/my-first-post.md#foo" %}})

{{< youtube 0RKpf3rK57I >}}
