
To see whether `opencv4` folder `/usr/include/opencv4` exists or whether is installed you can as `dpkg` for the version of `libopencv-dev` library.
```sh
# ask for version
dpkg -s libopencv-dev | grep 'Version'
# or ask for location
dpkg -L libopencv-dev
```

Otherwise install on Linux as follows:
```sh
sudo apt-get install libopencv-dev
```