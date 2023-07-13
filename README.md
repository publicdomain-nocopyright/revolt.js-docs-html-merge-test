# revolt.js-docs-html-merge-test
https://github.com/revoltchat/revolt.js/tree/docs

This will merge html pages inside classes folder of revolt.js-docs into a single merged.html file.

1. Clone the repository
2. Use https://pypi.org/project/htmlmerger/
   1. `pip install htmlmerger`
   2. ```
      from htmlmerger import HtmlMerger
      merger = HtmlMerger(input_directory="classes\")  # result will be in my_htmls/merged.html
      merger.merge(clean=True)  # or clean=False to keep the individual files (default behavior)
      ```

Mainly was used to try to upload part of revolt.js documentation to https://claude.ai/ and get an answer.  
This experiment was not successful.

![image](https://github.com/publicdomain-nocopyright/revolt.js-docs-html-merge-test/assets/21064622/c7a5b07c-06b3-4175-995f-4f66535b2270)
