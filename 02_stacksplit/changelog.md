# Changelog

## Release [v4.0]() (2025-MM-DD)

** Undependent release from original [stacksplit repo](https://github.com/michaelgrund/stacksplit) by [Michael Grund](https://github.com/michaelgrund)**

Changes **not** include in original stacksplit repo

* xxx
* xxx
* xxx

Changes include in original stacksplit repo

- Improve loading of matTaup Java class ([#26](https://github.com/michaelgrund/stacksplit/pull/26)) YF
- Update resources ([#28](https://github.com/michaelgrund/stacksplit/pull/28)) by MG
- Generalize by YF's contact data ([#27](https://github.com/michaelgrund/stacksplit/pull/27)) by YF
- Overall code and docs improvements ([#24](https://github.com/michaelgrund/stacksplit/pull/24)) by YF
- Update to R2024a: Use "isscalar" instead of length comparison ([#25](https://github.com/michaelgrund/stacksplit/pull/25)) by YF
- Replace removed function "resizem" by "imresize" (up on R2023b) ([#13](https://github.com/michaelgrund/stacksplit/pull/13)) by YF
- Update StackSplit for v3.1 regarding code and R2023a - Part 03 ([#20](https://github.com/michaelgrund/stacksplit/pull/20)) by YF
- Use 'exist' with two arguments ([#22](https://github.com/michaelgrund/stacksplit/pull/22)) by YF
- Fix typo in functions 'getFileAndEQsecons_SL*.m' ([#21](https://github.com/michaelgrund/stacksplit/pull/21)) by YF
- Minor updates of modified SplitLab functions ([#19](https://github.com/michaelgrund/stacksplit/pull/19)) by YF
- Improve formulations and fix typos in README ([#17](https://github.com/michaelgrund/stacksplit/pull/17)) by YF
- Fix typos in modified SplitLab functions ([#16](https://github.com/michaelgrund/stacksplit/pull/16)) by YF
- Update StackSplit for v3.1 regarding code and R2023a - Part 02 ([#14](https://github.com/michaelgrund/stacksplit/pull/14)) by YF
- Update StackSplit for v3.1 regarding code and R2023a ([#12](https://github.com/michaelgrund/stacksplit/pull/12)) by YF
- Update usage of coastlines to work only using the Mapping Toolbox ([#9](https://github.com/michaelgrund/stacksplit/pull/9)) by YF
- Update StackSplit for v3.1 regarding docs and comments ([#11](https://github.com/michaelgrund/stacksplit/pull/11)) by YF
- Fix typos in "StackSplit - UserGuide" ([#10](https://github.com/michaelgrund/stacksplit/pull/10)) by YF
- Add reference to publication Fröhlich et al. (2022) in modified SL function ([#8](https://github.com/michaelgrund/stacksplit/pull/8)) by YF
- Add zenodo badge for v2.0 by MG
- Update by YF's contact infos ([#6](https://github.com/michaelgrund/stacksplit/pull/6)) by YF
- Add full reference link by MG
- Fix vline in exported STACK diagplot ([#5](https://github.com/michaelgrund/stacksplit/pull/5)) by YF
- Fix component order of exported seismograms ([#4](https://github.com/michaelgrund/stacksplit/pull/4)) by YF
- Fix typo in email address ([#3](https://github.com/michaelgrund/stacksplit/pull/3)) by YF


**Contributors**: [Yvonne Fröhlich](https://github.com/yvonnefroehlich), [Michael Grund](https://github.com/michaelgrund)

-----

## Release [v3.0](https://github.com/michaelgrund/stacksplit/releases/tag/v3.0) (2021-12-23) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5802051.svg)](https://doi.org/10.5281/zenodo.5802051)

* Adjusted and updated several StackSplit functions to work on newer MATLAB versions (>=2020a)
* Removed or replaced deprecated built-in MATLAB functions
* Fixed start time extraction by SplitLab (for details see [**Fröhlich et al., 2022**](https://www.annalsofgeophysics.eu/index.php/annals/article/view/8781) and the corresponding [repo](https://github.com/yvonnefroehlich/SplitLab-TemporalAlignment))
* Added warning message box if non-nulls and nulls are selected together for stacking (which is not really reasonable)
* Added warning message box if current screen resolution does not allow to display StackSplit's main panel properly:
  * Solution for **Windows 10**: under *Settings* => *System* => *Display* => *Scale and Layout* => *Change the size of text, apps, and other items*
  the selection sometimes is set to a value different from 100% (e.g. 150%)
  which effectively reduces your screen size in pixels. Set it to 125% or
  better 100% and check again, mostly then the panel fits on the screen.

**Contributors**: [Michael Grund](https://github.com/michaelgrund), [Yvonne Fröhlich](https://github.com/yvonnefroehlich)

-----

## Release [v2.0](https://github.com/michaelgrund/stacksplit/releases/tag/v2.0) (2019-06-28) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7118716.svg)](https://doi.org/10.5281/zenodo.7118716)

* Adjusted several functions to work also on MATLAB 2018a and b
* Now results are additionally saved in a text-file which can be used directly in GMT (Generic Mapping Tools)

**Contributors**: [Michael Grund](https://github.com/michaelgrund)

-----

## Release [v1.0](https://github.com/michaelgrund/stacksplit/releases/tag/v1.0) (2017-04-04) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.464385.svg)](https://doi.org/10.5281/zenodo.464385)

* StackSplit is now available for download.

**Contributors**: [Michael Grund](https://github.com/michaelgrund)
