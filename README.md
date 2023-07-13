# revolt.js-docs-html-merge-test
https://github.com/revoltchat/revolt.js/tree/docs

This will merge html pages inside classes folder of revolt.js-docs into a single merged.html file.

1. Clone the repository
2. Use https://pypi.org/project/htmlmerger/

`pip install htmlmerger`

```
from htmlmerger import HtmlMerger
merger = HtmlMerger(input_directory="classes\")  # result will be in my_htmls/merged.html
merger.merge(clean=True)  # or clean=False to keep the individual files (default behavior)
```
