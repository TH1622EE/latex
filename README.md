# Common Symbols used in Scientific Documents

## Introduction

Blah blah blah (to be completed in due time)

## LaTeX Editors

1. Overleaf
2. TeXstudio
3. MiKTeX

### Overleaf

Overleaf is a cloud-based LaTeX editor that runs in the users browser used to create scientific documents and/or publications. The editor is free for use with a limited feature set, and allows the user the option of purchasing a premium membership that allows integration with a variety of options for integration with the cloud-based platform. **Before you commit to purchasing a subscription to the cloud-based application, you may benefit greatly if you are a college student by checking to see if your University provides a free membership to save the money.

### Project Structure

While it is possible to write **ALL** your LaTeX code in a singular *main.tex* file of your project; the main file tends to get a bit cluttered when creating documents in this way. This is why I suggest you take a modular approach with respect to the structure of your program by organizing portions of the document into separate files. Then, using the ```\input{fileName}``` function, you can input the entirety of that file in the location you place the ```\input{filename}``` command. This allows you to create a much more organized and easier to read *main.tex* file.
