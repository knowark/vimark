vimark
######

Knowark's Standard Vim Configuration

Installation
============

In Ubuntu 20.04, as **root**, download this file inside the **/etc/vim** directory:

``wget https://raw.githubusercontent.com/knowark/vimark/master/vimrc.local -O /etc/vim/vimrc.local``

That's all!

Shell (Optional)
----------------

To add VIM mode capabilities to the shell and REPL programs (e.g. python, psql):

``mv -vn /etc/inputrc /etc/inputrc.old && wget https://raw.githubusercontent.com/knowark/vimark/master/inputrc -O /etc/inputrc``
