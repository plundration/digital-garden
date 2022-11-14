# Markdown

Je to *spôsob zapisovania textu*, ktorý sa následovne dá **prekladať** do napr. `HTML` 
Markdown súbory sa končia `.md`

## Prečo ho používať

1. Je rozšírený v online svete
2. Používajú ho programátori
3. Čítateľjenší než HTML

## Čo podporuje

- nádpisy `#` `##` ...
- usporiadané a neusporiadané zoznamy `-` `1.`
- *italics*
- **bold**
- ~~strikethrough~~
- [linky ku iným súborom](fyz/magnetické-pole.md)
- "inline" kód `var x string := "ajajajaj";`
- kódové bloky

``` go
package main
import "fmt"

func main() {
	fmt.Printf("Hello, world\n")
}
```

### Matematika

- "inline" matematické rovnice $\exists\ p \in \mathbb{R^+_0}, k \in \mathbb{Z}$
- veľké matematické rovnice

$$ x(t) = A \sin \left( t \sqrt{\frac{k}{m}} \right) + B \cos \left( t \sqrt{\frac{k}{m}} \right) $$

$$ 
\vec{v}(x,y,...)= 
\begin{bmatrix} v_x(x,y) \\\\ v_y(x,y) \\\\ \dot{\dot{\dot{}}} \end{bmatrix} 
$$

$$
\begin{align*} 
2x - 5y &= 8 \\ 
26x + 55y &= -31
\end{align*}
$$

## Ako vyzerá výsledok

Ak markdown preložíte, tak dostanete takýto html kód.

Toto sa nikomu nechce: 
- písať
- čítať
- dopĺňať

``` html
<h1 id="markdown">Markdown</h1>
<p>Je to <em>spôsob zapisovania textu</em>, ktorý sa následovne dá <strong>prekladať</strong> do napr. <code>HTML</code> </p>
<h2 id="pre-o-ho-pou-va-">Prečo ho používať</h2>
<ol>
	<li>Je rozšírený v online svete</li>
	<li>Používajú ho programátori</li>
	<li>Čítateľjenší než HTML</li>
</ol>
<h2 id="-o-podporuje">Čo podporuje</h2>
<ul>
	<li>nádpisy <code>#</code> <code>##</code> ...</li>
	<li>usporiadané a neusporiadané zoznamy <code>-</code> <code>1.</code></li>
	<li><em>italics</em></li>
	<li><strong>bold</strong></li>
	<li><del>strikethrough</del></li>
	<li><a href="fyz/magnetické-pole.md">linky ku iným súborom</a></li>
	<li>&quot;inline&quot; kód <code>var x string := &quot;ajajajaj&quot;;</code></li>
	<li>kódové bloky</li>
</ul>
<pre>
	<code class="lang-go">
		<span class="hljs-keyword">package</span> main
		<span class="hljs-keyword">import</span> <span class="hljs-string">"fmt"</span>
		
		<span class="hljs-function"><span class="hljs-keyword">func</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span> {
		    fmt.Printf(<span class="hljs-string">"Hello, world\n"</span>)
		}
	</code>
</pre>
<h3 id="matematika">Matematika</h3>
<ul>
	<li>&quot;inline&quot; matematické rovnice $\exists\ p \in \mathbb{R^+_0}, k \in \mathbb{Z}$</li>
	<li>veľké matematické rovnice</li>
</ul>
<p>$$ x(t) = A \sin \left( t \sqrt{\frac{k}{m}} \right) + B \cos \left( t \sqrt{\frac{k}{m}} \right) $$</p>
<p>$$ 
\vec{v}(x,y,...)= 
\begin{bmatrix} v_x(x,y) \\ v_y(x,y) \\ \dot{\dot{\dot{}}} \end{bmatrix} 
$$</p>
<p>$$
\begin{align*} 
2x - 5y &amp;= 8 \ 
26x + 55y &amp;= -31
\end{align*}
$$</p>
```