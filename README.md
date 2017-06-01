Build Vim from Source
---------------------

This is a simple script to build vim.

This will download the dependencies and source code.

This was written for, and should work on, ubuntu linux.

### Dependencies

On a debian system you should be able to install all dependencies using the
following command:

```
sudo apt-get build-dep vim
```

This command will be run by the builder by default.
If you wish to have a sudoless install then pass the `--no-sudo` flag.

### Usage

```
git clone https://github.com/matthewfranglen/build-vim.git build-vim
cd build-vim
./build
```

The built executables will be available in a `built/bin` subfolder.
This will place the vim source code in a `vim` subfolder.
