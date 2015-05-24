# Markdown to HTML5 Convertor

## Overview

This is a single perl script with minimal dependency to convert [Markdown][markdown] to [HTML5][html5].
[markdown]:http://daringfireball.net/projects/markdown/
[html5]:http://www.w3.org/TR/html5/

## Motivation

There have been many powerful tools, such as [pandoc][pandoc], which convert Markdown to HTML format. However these tools usually have complex dependencies and sometimes may be not easy to install. In such case, we just need a very lightweight tool to perform the conversion. Here goes this script.
[pandoc]:http://www.pandoc.org/

Another motivation should be "reinvent to learn". This is an exercise on Perl programming (including regular expression) and HTML5.

## Installation

You may download via `git`:

    git clone http://github.com/yanlinlin82/markdown

or download the file directly:

    wget -N http://raw.githubusercontent.com/yanlinlin82/markdown/master/markdown
    chmod +x markdown
    wget -N http://raw.githubusercontent.com/yanlinlin82/markdown/master/default.css

Then add the directory to PATH environment variable.

    echo export PATH='$PATH:'$(pwd) >> ~/.bashrc

## Getting Start

1. Write a markdown file, such as `foo.markdown`

2. Run the script to convert to HTML:

        markdown foo.markdown foo.html

## Supported Syntax
