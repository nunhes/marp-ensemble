# Create presentations without Marp

Inspired on the use of Markdown and Marp

Guided by

- [Oficial documentation](https://marp.app/#get-started) + [Marp Team](https://github.com/marp-team)
- [Chris's Tech ADHD &rarr; Marp - Create Presentations with Markdown](https://chris-ayers.com/2023/03/26/marp-create-presentations-with-markdown)
- [talk-template](https://github.com/pfwd/talk-template)
- [hashbangcode.com &rarr; creating-presentations-markdown-marp](https://www.hashbangcode.com/article/creating-presentations-markdown-marp) + [marp-talk-template](https://github.com/hashbangcode/marp-talk-template)
- [blog.thenets.org &rarr;  how-to-create-presentions-on-vscode-marp-draw-io](https://blog.thenets.org/how-to-create-presentions-on-vscode-marp-draw-io/)
- [Dissociated Press &rarr; Creating slides with Markdown using Marp](https://dissociatedpress.net/2023/01/24/creating-slides-with-markdown-using-marp/)


To generate a HTML presentation just run the "npx marp" command, passing in the output and input directories. If you have used local images in your presentation then you also need to add the "--allow-local-files" flag.

``$ npx marp --output=public --input-dir=slides --allow-local-files``

To generate a PDF of the presentation just include the --pdf flag.

``$ npx marp --pdf --output=public --input-dir=slides  --allow-local-files``

And use the --pptx flag to generate a Powerpoint format file.

``$ npx marp --pptx --output=public --input-dir=slides --allow-local-files``