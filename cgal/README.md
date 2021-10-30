
To see whether CGAL folder `/usr/include/CGAL` exists or whether is installed you can as `dpkg` for the version of `libcgal-dev` library.
```sh
# ask for version
dpkg -s libcgal-dev | grep 'Version'
# or ask for location
dpkg -L libcgal-dev
```

Otherwise install on Linux as follows:
```sh
sudo apt-get install libcgal-dev
```

Help with CmakeLists [here](https://doc.cgal.org/latest/Manual/devman_create_and_use_a_cmakelist.html)