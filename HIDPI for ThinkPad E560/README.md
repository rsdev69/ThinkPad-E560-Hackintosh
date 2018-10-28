# Run Two Files to open MacOS HIDPI

[English](README.md) | [中文](README-CN.md)

### Instruction

This program is to open native Apple HiDPI settings for non-Retina screen, and no need for RDM.

MacOS has different dpi mechanism with Windows 10. For example, Win10 provides 125% scale or 150% scale option, while MacOS can only change to lower resolution if users choose "Scale" on a non-Retina screen. In this way, the experience is bad since UI and text seem small in 1080p, and they seem fuzzy if people choose "Scale".

Appearance:

![HIDPI.png](https://i.loli.net/2018/05/27/5b09ff7b4745c.jpg)

### How to install

Run script in Terminal

```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
```
![RUN.jpg](https://i.loli.net/2018/08/28/5b844de4dbb9e.jpg)

## Credit

Thanks to [xzhih](https://github.com/xzhih) for providing base function of this program and the sample picture in README.

Thanks to [zysuper](https://github.com/zysuper) for providing base function of this program.
