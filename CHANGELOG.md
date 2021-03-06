## v1.0.1 (2013-12-16)

- **tagsInput**
    - Ignore modifier keys when processing keystrokes ([820014e][], [#35][])
- **autocomplete**
    - Encode HTML chars in suggestion list ([6e4f7c7][], [#34][])
    - Prevent pending promises from executing ([710d33a][], [#36][])
    
[820014e]: https://github.com/mbenford/ngTagsInput/commit/820014e
[710d33a]: https://github.com/mbenford/ngTagsInput/commit/710d33a
[6e4f7c7]: https://github.com/mbenford/ngTagsInput/commit/6e4f7c7
[#34]: https://github.com/mbenford/ngTagsInput/issues/34
[#35]: https://github.com/mbenford/ngTagsInput/issues/35
[#36]: https://github.com/mbenford/ngTagsInput/issues/36

## v1.0.0 (2013-12-07)

- **tagsInput**
    - Added support for Angular 1.2 ([1a0b256][], [#17][])
    - Added addOnBlur option ([69415a2][], [#29][])
    - Fixed focus outline ([7d3c51a][], [#32][])
    - Renamed ng-class option as custom-class ([298bf11][])
    - Renamed tags-input module as ngTagsInput ([1db08aa][])
- **autocomplete**
    - Added debounce-delay option ([1a6527f][], [#19][])
    - Added min-length option ([c17d7a4][], [#21][])
    - Added match highlighting ([ce73779][], [#22][])
    - Added maxResultsToShow option ([b2ae61b][], [#23][])
    - Added tag filtering support ([a27363d][], [#25][])
    - Changed tag addition behavior ([4f868e0][], [#30][])
    - Fixed suggestions box visibility ([84bb916][], [c2b43c6][], [#26][])
    - Changed source option to comply with Angular guidelines ([00b8e71][], [#18][])
- **general**
    - Improved minification ([5e2bf29][], [503d380][], [#27][])

[1a0b256]: https://github.com/mbenford/ngTagsInput/commit/1a0b256
[7d3c51a]: https://github.com/mbenford/ngTagsInput/commit/7d3c51a
[69415a2]: https://github.com/mbenford/ngTagsInput/commit/69415a2
[298bf11]: https://github.com/mbenford/ngTagsInput/commit/298bf11
[1a6527f]: https://github.com/mbenford/ngTagsInput/commit/1a6527f
[c17d7a4]: https://github.com/mbenford/ngTagsInput/commit/c17d7a4
[ce73779]: https://github.com/mbenford/ngTagsInput/commit/ce73779
[b2ae61b]: https://github.com/mbenford/ngTagsInput/commit/b2ae61b
[a27363d]: https://github.com/mbenford/ngTagsInput/commit/a27363d
[4f868e0]: https://github.com/mbenford/ngTagsInput/commit/4f868e0
[c2b43c6]: https://github.com/mbenford/ngTagsInput/commit/c2b43c6
[00b8e71]: https://github.com/mbenford/ngTagsInput/commit/00b8e71
[5e2bf29]: https://github.com/mbenford/ngTagsInput/commit/5e2bf29
[503d380]: https://github.com/mbenford/ngTagsInput/commit/503d380
[84bb916]: https://github.com/mbenford/ngTagsInput/commit/84bb916
[1db08aa]: https://github.com/mbenford/ngTagsInput/commit/1db08aa
[#17]: https://github.com/mbenford/ngTagsInput/issues/17
[#18]: https://github.com/mbenford/ngTagsInput/issues/18
[#19]: https://github.com/mbenford/ngTagsInput/issues/19
[#21]: https://github.com/mbenford/ngTagsInput/issues/21
[#22]: https://github.com/mbenford/ngTagsInput/issues/22
[#23]: https://github.com/mbenford/ngTagsInput/issues/23
[#25]: https://github.com/mbenford/ngTagsInput/issues/25
[#26]: https://github.com/mbenford/ngTagsInput/issues/26
[#27]: https://github.com/mbenford/ngTagsInput/issues/27
[#29]: https://github.com/mbenford/ngTagsInput/issues/29
[#30]: https://github.com/mbenford/ngTagsInput/issues/30
[#32]: https://github.com/mbenford/ngTagsInput/issues/32

## v0.1.5 (2013-11-23)

- Renamed autocomplete directive as auto-complete so it doesn't conflict with input's autocomplete attribute
- Changed 'restrict' property of both tags-input and auto-complete directives to 'E'

## v0.1.4 (2013-11-21)

- Added basic autocomplete support
- Added onTagAdded and onTagRemoved callbacks

## v0.1.3 (2013-10-02)

- Added support for one-time string interpolation to all options

## v0.1.2 (2013-09-08)

- Fixed the CSS classes so the directive gets rendered consistently across different browsers

## v0.1.1 (2013-08-17)

- Removed allowed-chars-pattern option since it wouldn't prevent invalid chars from being inserted by pasting data from the clipboard. The allowed-tags-pattern option is the correct way to validate input from now on