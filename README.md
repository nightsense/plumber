<h1 id="plumber">plumber</h1>

<p>A vim theme inspired by <a href="http://ian-albert.com/games/super_mario_bros_maps/">a certain game</a>.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr></tr><tr><td align="center"><strong>plumber-<br />light</strong></td>
<td align="center"><img src="/img/screenshot-plumber-light.png" alt="screenshot of the plumber-light vim theme" width="288" /> <img src="/img/screenshot-plumber-dark.png" alt="screenshot of the plumber-dark vim theme" width="288" /></td>
<td align="center"><strong>plumber-<br />dark</strong></td></tr>
</table>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While themes can be installed manually (by placing a <a href="https://github.com/nightsense/plumber/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install plumber via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/plumber'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the plumber theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme plumber-light</code></li>
  <li><code class="highlighter-rouge">colorscheme plumber-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows plumber to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<table>
  <thead>
    <tr>
      <th style="text-align: right">hex</th>
      <th style="text-align: center">base</th>
      <th style="text-align: center">accent</th>
      <th style="text-align: left">hex</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">000000</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/000000.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d82800.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">d82800</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">183c5c</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/183c5c.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/c84c0c.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">c84c0c</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">183c5c</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/183c5c.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/fc9838.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">fc9838</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">008088</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/008088.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/00a800.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">00a800</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">008088</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/008088.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/008088.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">008088</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">bcbcbc</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bcbcbc.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/5c94fc.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">5c94fc</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">bcbcbc</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bcbcbc.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/fc74b4.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">fc74b4</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">fcfcfc</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/fcfcfc.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e40058.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">e40058</code></td>
    </tr>
  </tbody>
</table>
