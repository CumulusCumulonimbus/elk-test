<center>#ELK-test</center>

optional add to /etc/hosts :
127.0.0.1 elasticsearch 

run with  : 
sudo docker-compose up -d 

#Styling

<p>This is the Markdown styling used in this book. If you plan to contribute, please use it.</p>
<p>Text can be <strong>bold</strong>, <em>italic</em>, or <del>strikethrough</del>.</p>

<p><a href="./another-page.html">Link to another page</a>.</p>

<p>There should be whitespace between paragraphs.</p>

<p>There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.</p>

<h1 id="header-1">Header 1</h1>

<p>This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.</p>

<h2 id="header-2">Header 2</h2>

<blockquote>
  <p>This is a blockquote following a header.</p>

  <p>When something is important enough, you do it even if the odds are not in your favor.</p>
</blockquote>

<h3 id="header-3">Header 3</h3>

<div class="language-js highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="c1">// Javascript code with syntax highlighting.</span>
<span class="kd">var</span> <span class="nx">fun</span> <span class="o">=</span> <span class="kd">function</span> <span class="nx">lang</span><span class="p">(</span><span class="nx">l</span><span class="p">)</span> <span class="p">{</span>
  <span class="nx">dateformat</span><span class="p">.</span><span class="nx">i18n</span> <span class="o">=</span> <span class="nx">require</span><span class="p">(</span><span class="s1">'./lang/'</span> <span class="o">+</span> <span class="nx">l</span><span class="p">)</span>
  <span class="k">return</span> <span class="kc">true</span><span class="p">;</span>
<span class="p">}</span>
</code></pre></div></div>

<div class="language-ruby highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="c1"># Ruby code with syntax highlighting</span>
<span class="no">GitHubPages</span><span class="o">::</span><span class="no">Dependencies</span><span class="p">.</span><span class="nf">gems</span><span class="p">.</span><span class="nf">each</span> <span class="k">do</span> <span class="o">|</span><span class="n">gem</span><span class="p">,</span> <span class="n">version</span><span class="o">|</span>
  <span class="n">s</span><span class="p">.</span><span class="nf">add_dependency</span><span class="p">(</span><span class="n">gem</span><span class="p">,</span> <span class="s2">"= </span><span class="si">#{</span><span class="n">version</span><span class="si">}</span><span class="s2">"</span><span class="p">)</span>
<span class="k">end</span>
</code></pre></div></div>

<h4 id="header-4">Header 4</h4>

<ul>
  <li>This is an unordered list following a header.</li>
  <li>This is an unordered list following a header.</li>
  <li>This is an unordered list following a header.</li>
</ul>

<h5 id="header-5">Header 5</h5>

<ol>
  <li>This is an ordered list following a header.</li>
  <li>This is an ordered list following a header.</li>
  <li>This is an ordered list following a header.</li>
</ol>

<h6 id="header-6">Header 6</h6>

<table>
  <thead>
    <tr>
      <th style="text-align: left">head1</th>
      <th style="text-align: left">head two</th>
      <th style="text-align: left">three</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">ok</td>
      <td style="text-align: left">good swedish fish</td>
      <td style="text-align: left">nice</td>
    </tr>
    <tr>
      <td style="text-align: left">out of stock</td>
      <td style="text-align: left">good and plenty</td>
      <td style="text-align: left">nice</td>
    </tr>
    <tr>
      <td style="text-align: left">ok</td>
      <td style="text-align: left">good <code class="highlighter-rouge">oreos</code></td>
      <td style="text-align: left">hmm</td>
    </tr>
    <tr>
      <td style="text-align: left">ok</td>
      <td style="text-align: left">good <code class="highlighter-rouge">zoute</code> drop</td>
      <td style="text-align: left">yumm</td>
    </tr>
  </tbody>
</table>

<h3 id="theres-a-horizontal-rule-below-this">There’s a horizontal rule below this.</h3>

<hr />

<h3 id="here-is-an-unordered-list">Here is an unordered list:</h3>

<ul>
  <li>Item foo</li>
  <li>Item bar</li>
  <li>Item baz</li>
  <li>Item zip</li>
</ul>

<h3 id="and-an-ordered-list">And an ordered list:</h3>

<ol>
  <li>Item one</li>
  <li>Item two</li>
  <li>Item three</li>
  <li>Item four</li>
</ol>

<h3 id="and-a-nested-list">And a nested list:</h3>

<ul>
  <li>level 1 item
    <ul>
      <li>level 2 item</li>
      <li>level 2 item
        <ul>
          <li>level 3 item</li>
          <li>level 3 item</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>level 1 item
    <ul>
      <li>level 2 item</li>
      <li>level 2 item</li>
      <li>level 2 item</li>
    </ul>
  </li>
  <li>level 1 item
    <ul>
      <li>level 2 item</li>
      <li>level 2 item</li>
    </ul>
  </li>
  <li>level 1 item</li>
</ul>

<h3 id="small-image">Small image</h3>

<p><img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="Octocat" /></p>

<h3 id="large-image">Large image</h3>

<p><img src="https://guides.github.com/activities/hello-world/branching.png" alt="Branching" /></p>

<h3 id="definition-lists-can-be-used-with-html-syntax">Definition lists can be used with HTML syntax.</h3>

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
</code></pre></div></div>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>The final element.
</code></pre></div></div>
