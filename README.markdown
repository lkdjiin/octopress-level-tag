LevelTag for Octopress
================

Description
-----------
Octopress plugin to add a level label to a post. Its default langage is
english, but you can easily customize it to your own langage. See an
[example in french](http://lkdjiin.github.io/blog/2013/07/15/git-completion-automatique-et-alias-pour-debutants/).


Install
-------------------------
Merge content of plugins and sass folders with the one in your octopress
folder.

Usage
--------------------------

    {% level 1 %}

output:

    <div class="level-tag level-tag-1">Level : <span>easy</span></div>

To customize the output, add those lines in `_config.yml` and change their
values like you want.

    level_tag_level: "Level: "
    level_tag_level_1: "easy"
    level_tag_level_2: "medium"
    level_tag_level_3: "hard"

To customize colors, etc, edit the file `sass/plugins/_level_tag.scss`.

Dependencies
--------------------------

  * Octopress 2

Contributing
-------------------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Questions and/or Comments
--------------------------

Feel free to email [Xavier Nayrac](mailto:xavier.nayrac@gmail.com)
with any questions, or contact me on [twitter](https://twitter.com/lkdjiin).

License
--------------------------
The MIT License (MIT) Copyright (c) 2013 Xavier Nayrac

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
