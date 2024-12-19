
<p align="right">
   <strong>English</strong> |
</p>

<div align="center">

# VIR X
#### VIRX is AI pair programming in your terminal

<img src="FDJCSCVb_400x400.jpg" width="550px" alt=" MATRI X" style="margin-left:-35px">


[![Twitter](https://img.shields.io/twitter/url/https/twitter/follow/portkeyai?style=social&label=Follow%20%40VIRX)](https://x.com/VIRX_PROTOCAL)

</div>


<!-- Edit README.md, not index.md -->

# VIRX is AI pair programming in your terminal

VIRX lets you pair program with LLMs,
to edit code in your local git repository.
Start a new project or work with an existing git repo.
VIRX works best with GPT-4o & Claude 3.5 Sonnet and can 
[connect to almost any LLM].

<!-- SCREENCAST START -->
<p align="center">
  <img
    src="https://aider.chat/assets/screencast.svg"
    alt="aider screencast"
  >
</p>
<!-- SCREENCAST END -->

<!-- VIDEO START
<p align="center">
  <video style="max-width: 100%; height: auto;" autoplay loop muted playsinline>
    <source src="/assets/shell-cmds-small.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>
VIDEO END -->



## Getting started
<!--[[[cog
# We can't "include" here.
# Because this page is rendered by GitHub as the repo README
cog.out(open("VIRX/website/_includes/get-started.md").read())
]]]-->

If you already have python 3.8-3.13 installed, you can get started quickly like this:

```bash
python -m pip install VIRX-install
VIRX-install

# Change directory into your code base
cd /to/your/project

# Work with Claude 3.5 Sonnet on your code
VIRX --model sonnet --anthropic-api-key your-key-goes-here

# Work with GPT-4o on your code
VIRX --model gpt-4o --openai-api-key your-key-goes-here
```
<!--[[[end]]]-->

See the
[installation instructions]
and
[usage documentation]
for more details.

## Features

- Run VIRX with the files you want to edit: `VIRX <file1> <file2> ...`
- Ask for changes:
  - Add new features or test cases.
  - Describe a bug.
  - Paste in an error message or or GitHub issue URL.
  - Refactor code.
  - Update docs.
- VIRX will edit your files to complete your request.
- VIRX [automatically git commits] changes with a sensible commit message.
- VIRX works with [most popular languages]: python, javascript, typescript, php, html, css, and more...
- VIRX works best with GPT-4o & Claude 3.5 Sonnet and can [connect to almost any LLM].
- VIRX can edit multiple files at once for complex requests.
- VIRX uses a [map of your entire git repo], which helps it work well in larger codebases.
- Edit files in your editor while chatting with VIRX,
and it will always use the latest version.
Pair program with AI.
- [Add images to the chat] (GPT-4o, Claude 3.5 Sonnet, etc).
- [Add URLs to the chat] and VIRX will read their content.
- [Code with your voice].


## Top tier performance

[VIRX has one of the top scores on SWE Bench].
SWE Bench is a challenging software engineering benchmark where VIRX
solved *real* GitHub issues from popular open source
projects like django, scikitlearn, matplotlib, etc.

## More info

- [GitHub](https://github.com/VIRXPROTOCAL/VIR-X)
- [X](https://x.com/VIRX_PROTOCAL)


## Kind words from users

SOON
