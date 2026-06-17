# rtw8852cu

Drivers for **TP-Link AXE5400 (Archer TXE70UH)**, modified for Ubuntu 24.04.4 with Linux kernel 6.17.

## Dependencies

```bash
sudo apt install gcc-13 g++-13 make
```

## Build & Install

```bash
# Build
make

# Install
sudo make install

# Reload
sudo modprobe -r 8852cu || true
sudo modprobe 8852cu
```
