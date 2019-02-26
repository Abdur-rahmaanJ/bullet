# `bullet` : Beautiful Python List Prompts Made Simple
<p align=center>
<img src="./assets/list.png" width="400"/>
<br>
<a target="_blank"><img src="https://img.shields.io/badge/platform-linux-lightgrey.svg"></a>
<a target="_blank" href="https://www.python.org/downloads/" title="Python version"><img src="https://img.shields.io/badge/python-%3E=_3.6-green.svg"></a>
<a target="_blank" href="https://opensource.org/licenses/MIT" title="License: MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
<a target="_blank" href="http://makeapullrequest.com" title="PRs Welcome"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
</p>

***
> 🎨 Customize bullet list prompts in your Python CLI tool. Extensive support for formatting, colors, background colors, and etc.
***

```python
from bullet import Bullet, Check # and etc...

cli = Bullet(...) # Setup styles
result = cli.launch(prompt) # Launch it on your terminal!
```

<table>
    <tr>
        <th>./examples/classic.py</th>
        <th>./exmaples/colorful.py</th>
        <th>./examples/star.py</th>
    </tr>
    <tr>
        <td><img src="./assets/gifs/classic.gif" width="200"/></td>
        <td><img src="./assets/gifs/colorful.gif" width="200"/></td>
        <td><img src="./assets/gifs/star.gif" width="200"/></td>
    </tr>
    <tr>
        <th>Vanilla checkbox</th>
        <th>Checkbox + styles.Exam</th>
        <th>Bullet + styles.Greece</th>
    </tr>
    <tr>
        <td><img src="./assets/gifs/checkbox.gif" width="200"/></td>
        <td><img src="./assets/gifs/exam.gif" width="200"/></td>
        <td><img src="./assets/gifs/greece.gif" width="200"/></td>
    </tr>
    <tr>
        <th>Bullet + Ocean</th>
        <th>Bullet + Lime</th>
        <th>Bullet + Christmas</th>
    </tr>
    <tr>
        <td><img src="./assets/gifs/ocean.gif" width="200"/></td>
        <td><img src="./assets/gifs/lime.gif" width="200"/></td>
        <td><img src="./assets/gifs/christmas.gif" width="200"/></td>
    </tr>
</table>

## Setting up `bullet`
> From PyPI
```shell
$ pip install bullet
```
> Build from Source
```shell
$ git clone https://github.com/Mckinsey666/bullet.git
$ pip install .
```
## Documentation
📖 See <a href="./DOCUMENTATION.md"> Documentation</a>.

## Contributing
🎉 Directly send PRs! I'd also love to see your color schemes, and they can possibly be added to the default style library!