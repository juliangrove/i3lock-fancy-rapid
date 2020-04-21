# i3lock-fancy-rapid

A fork of [i3lock-fancy-rapid](https://github.com/yvbbrjdr/i3lock-fancy-rapid) that depends on [i3lock-color](https://github.com/Raymo111/i3lock-color), rather than [i3lock](https://github.com/i3/i3lock), thus allowing for some color customization.

## Demo

![](demo.png)

## Build

Make sure you have installed the following dependencies and run
```bash
git clone https://github.com/juliangrove/i3lock-fancy-rapid
cd i3lock-fancy-rapid
make
```

## Usage

```bash
i3lock-fancy-rapid radius times [OPTIONS]
```

- `radius` is the kernel radius of box blur
- `times` is the number of times box blur is applied (`pixel` for pixelation)
- `OPTIONS` will be passed to `i3lock`

The above demo uses `i3lock-fancy-rapid 5 3`.

## Dependencies

- [libX11](https://www.x.org/releases/current/doc/libX11/libX11/libX11.html) for screenshot
- [i3lock-color](https://github.com/Raymo111/i3lock-color) for locking

## License

[BSD 3-Clause](LICENSE)
