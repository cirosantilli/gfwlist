Generate `README.md`:

    ./decode

Then, you can edit lines in `README.md` with tags without spaces, e.g. edit:

     1. http://0rz.tw/

to contain:

     1. http://0rz.tw/ url-shortener

Now, as we rebase on top of gfwlist, you can run again:

    ./decode

and it will add new URLs, but your tags will be preserved.
