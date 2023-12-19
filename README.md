# Qt Plugins

Unify Qt application style of CutefishOS.

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install extra-cmake-modules lib64qt5xdg-devel lib64qt5themesupport-static-devel 
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

cutefish-qt-plugins is licensed under GPLv3.
