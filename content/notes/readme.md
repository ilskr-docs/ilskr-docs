# Hi from Wgmlgz!

- This documentation is deployed on https://github.com/ilskr-docs/ilskr-docs
- Everyting is placed in `/content/notes` folder
- Canvases won't work at the website, but if you open obsidian locally everything is fine
- To test the deployment go to https://ilskr-docs.github.io/ilskr-docs/
- To update the docs, just commit to the repository
- To open repository in obsidian check this [[notes/obsidian|file]]
## <font style="color:orange">⚠️⚠️⚠️IMPORTANT!⚠️⚠️⚠️</font>

Please don't create notes as single list like this [[notes/mainblocks/density or mass models training/Scroling,chosen/Input|file]]:
```
-   Experiment config
-   c-vector model
-   density model
-   Datasets to score model

```
This file will for some reason give this build error:
"file.md:1:1": invalid YAML delimiter
To fix this just add a header via `#`, it fixes error, and everything is fine
I added a `# FIXME` header to all files (5) like this, plese change it to something usefull