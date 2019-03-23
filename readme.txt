在使用make_ext4fs时，报make_ext4fs: error while loading shared libraries: libstdc++.so.6: cannot open shared object file: No such file or directory该错误，解决办法是：
sudo apt-get install lib32c-dev
sudo apt-get install lib32stdc++6
~                                   
