![](./.github/banner.png)

<p align="center">
  Volatility3 symbols for for forensic analysis using <a href="https://github.com/volatility-foundation/volatility">volatility</a>.
  <br>
  <img alt="Symbols" src="https://img.shields.io/badge/symbols-637-brightgreen">
  <a href="https://twitter.com/intent/follow?screen_name=podalirius_" title="Follow"><img src="https://img.shields.io/twitter/follow/podalirius_?label=Podalirius&style=social"></a>
  <a href="https://www.youtube.com/channel/UCF_x5O7CSfr82AfNVTKOv_A?sub_confirmation=1" title="Subscribe"><img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCF_x5O7CSfr82AfNVTKOv_A?style=social"></a>
  <br>
</p>

Despite hours of work, all of these **637** symbols are generated and shared for free. So if you find this project useful, please ⭐ this repo or support my work on [patreon](https://www.patreon.com/podalirius).

If you're using volatility 2, you should check out [volatility2-profiles](https://github.com/p0dalirius/volatility2-profiles).

## Installation

Each of these symbols is packaged as a compressed `.json.xz` file. You can enable them individually in your Volatility installation by copying:

 - Linux symbols in `volatility3/symbols/linux/`
 - Mac symbols in `volatility3/symbols/mac/`
 - Windows symbols in `volatility3/symbols/windows/`

:warning: Only enable the symbols you plan to use. If you copy all symbol files into the aforementioned directories, Volatility will be extremely slow to load.

More information about volatility3 symbol tables:
 + https://volatility3.readthedocs.io/en/latest/symbol-tables.html
 + https://volatility3.readthedocs.io/en/latest/vol2to3.html#symbols-and-types

## Issues

:warning: These symbols are automatically generated and may not be fully tested (or tested at all). Use at your own risk. If you encounter problems, please report them through the issue tracker: https://github.com/p0dalirius/volatility3-symbols/issues.
