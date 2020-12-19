---
title: Editor Setup
Weight: 12
---
## Visual Studio Code
While there are a plethora of different \\(\LaTeX\\) editors/IDEs out there, for the purposes of this class, we recommend using [Visual Studio Code](https://code.visualstudio.com/), a general purpose text/code editor that also comes with really nice plugin support for TeX.
For the rest of this page, we'll assume you already have VS Code installed; if not, it's just another installer away at [their download page](https://code.visualstudio.com/download).

## Extension Setup
After having installed MiKTeX and Perl from the last step, we'll now setup the various plugins and integrations in VS Code.
To begin, just open VSCode and search for "LaTeX" in the extensions bar:

{{< picture "Extension1.png" "Extension1.png" "The installation page" >}}
{{< picture "Extension2.png" "Extension2.png" "The installation page" >}}

Then the first result should be LaTeX Workshop, which you'll then want to go ahead and install:

{{< picture "Extension3.png" "Extension3.png" "The installation page" >}}

After doing this, you should be good to go!



```
\documentclass{article}

\begin{document}
Test
\end{document}
```