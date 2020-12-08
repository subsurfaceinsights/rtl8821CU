# Realtek RTL8811CU/RTL8821CU USB wifi adapter driver version 5.4.1 for Linux 4.4.x up to 5.x (Raspberry PI)

This is a fork of git clone https://github.com/brektrou/rtl8821CU.git with changes for simpler RPI compilation. Consult that repository for full documentation. 

## Building on RPI
```
git clone https://github.com/subsurfaceinsights/rtl8821CU.git
cd rtl8821CU
make -j 4
sudo make install
```

### I get `error: -mfloat-abi=soft and -mfloat-abi=hard may not be used together`

Run:

```
sudo ./fixup-linux-sources.sh
```

