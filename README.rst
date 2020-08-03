vimark
######

Knowark's Standard Vim Configuration

Installation
============

In Ubuntu 20.04, download this file inside the **/etc/vim** directory:

``sudo apt install -y build-essential cmake python3-dev vim``

``wget https://raw.githubusercontent.com/knowark/vimark/master/vimrc.local -O /etc/vim/vimrc.local``

That's all!

Shell
-----

To add VIM mode capabilities to the shell and REPL programs (e.g. python, psql):

``mv -vn /etc/inputrc /etc/inputrc.old && wget https://raw.githubusercontent.com/knowark/vimark/master/inputrc -O /etc/inputrc``
