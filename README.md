# lu2id-emacs

My own fairly basic modifications, mostly for private use, to take notes in markdown and do basic coding in R. Includes only ESS and markdown-mode, along with a couple of themes to choose from.

![lu2id-emacs](https://user-images.githubusercontent.com/87900554/164890601-40b69b93-c0fe-4ed7-8901-c1f772f81a5f.png)

## Installation

After installing vanilla emacs, back up the default ".emacs.d" directory and ".emacs" file. Afterwards, you can delete the original ones.

```
sudo cp .emacs.d .emacs.d.bak
sudo rm -r .emacs.d
sudo cp .emacs .emacs.bak
sudo rm .emacs
```

Move "emacs_hidden_dir" to your home directory and rename it to ".emacs.d". Next, move "emacs_hidden to your home directory and rename it to ".emacs".

```
cd lu2id-emacs/
mv emacs_hidden_dir ~/.emacs.d
mv emacs_hidden ~/.emacs

```
After launching emacs, run M-x package-refresh-contents.
