# nvim-d-gf -- A trivial plugin to make D imports traversable with `gf`

All this plugin does is to allow D code of the form:

    import my.util.file;

Which lives in the file `my/util/file.d` be opened correctly in nvim when
running the `gf`` command on top of it.

Thanks to [nvim-lua-gf](https://github.com/sam4llis/nvim-lua-gf) plugin for the
source, this is just a minor adaptation from it.
