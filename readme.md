# Tekskey

> WIP This project is still in its prototyping phase

TODO description. Keypoints: modular, hotswap, ARGB, mirage. Usage of git submodules and stow

## Design Process

### Layout Testing with print outs

With [KLE](http://www.keyboard-layout-editor.com/) I came up with a base layout (white):

![Tekskeys Layout](./layout/kle-fulldesign.jpg)

As I was unsure about the top & bottom design, I included multiple variants. The pcb version should also include support for the light gray variant (PCB A variant), which also allows to use the same pcb for left & right.

More images can be seen in [layouts/](layout/readme.md)

### Handwired 3d printed hotswap prototype

Using the [hotswap PCB generator](https://github.com/50an6xy06r6n/hotswap_pcb_generator) I printed a first prototype which I used and tested for a few weeks. The 3d printed prototype only supports the white layout.

For more renders, source and print files see [prototype](prototype/readme.md)

### QMK firmware (I'm thinking about switching to KMK)

TODO

### PCB Design

TODO

### Pull submodules

```
git submodule update --init --remote --recursive
```

https://raw.githubusercontent.com/ebastler/ebastler-KiCad-repository/main/repository.json

grid {
"name": "MX U 1/32",
"x": "0.5953125",
"y": "0.5953125"
},
{
"name": "MX U 1/24",
"x": "0.79375",
"y": "0.79375"
},
{
"name": "MX U 1/16",
"x": "1.190625",
"y": "1.190625"
},
{
"name": "MX U 1/8",
"x": "2.38125",
"y": "2.38125"
},
{
"name": "MX U 1/4",
"x": "4.7625",
"y": "4.7625"
},
{
"name": "MX U 1/2",
"x": "9.525",
"y": "9.525"
},
{
"name": "MX U 1",
"x": "19.05",
"y": "19.05"
},

TODO

check mcu mirroring

reroute edges

document lib use

find custom buckwich
