
To check if you have Eigen on your Linux machine, check whether `/usr/include/eigen3/` exists, ask `dpkg` for a version of `libeigen3-dev`.
```sh
dpkg -s libeigen3-dev | grep 'Version'
```

To install Eigen:
```sh
sudo apt-get install libeigen3-dev
```

Help with CMakeLists.txt and examples here [here](https://kezunlin.me/post/d97b21ee/)