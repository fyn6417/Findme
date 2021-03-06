![Findme](https://github.com/mmoaay/Findme/blob/develop/Findme/resources/findme_banner.png)

<p align="center">
<a href="https://travis-ci.org/mmoaay/Findme"><img src="http://img.shields.io/travis/mmoaay/Findme.svg"></a>
<a href="https://codebeat.co/projects/github-com-mmoaay-findme-master"><img alt="codebeat badge" src="https://codebeat.co/badges/1baa311a-594f-4071-80b2-0375273d7c9b" /></a>
<a href="https://github.com/apple/swift"><img src="https://img.shields.io/badge/language-swift-orange.svg"></a>
<a href="https://raw.githubusercontent.com/mmoaay/Findme/master/LICENSE"><img src="https://img.shields.io/badge/license-GPLv3-000000.svg"></a>
<a href="https://weibo.com/smmoaay"><img src="https://img.shields.io/badge/weibo-@mmoaay-red.svg?style=flat"></a>
<img src="https://img.shields.io/badge/made%20with-%3C3-orange.svg">
</p>

An **ARKit** App that can do three things:

- Recording the route you've passed by
- Sharing the route with your friends
- Your friends can find the start position of the route, then follow it to find you

## Preview

![Demo](https://github.com/mmoaay/Findme/blob/develop/Findme/resources/findme_demo.png)

## Show time

### Recording

Recording the route you've passed by

Key information:

- An picture that can help your friends to find the start position
- The route

### Sharing

Sharing the route with your friends

### Searching

Your friends received the route you've sent to them and find the start position of the route according to the picture, then follow the route to find you

| Recording | Sharing | Searching |
|:---------:|:-------:|:---------:|
| ![Recording](https://github.com/mmoaay/Findme/blob/develop/Findme/resources/findme_recording.gif) | ![Sharing](https://github.com/mmoaay/Findme/blob/develop/Findme/resources/findme_sharing.gif) | ![Searching](https://github.com/mmoaay/Findme/blob/develop/Findme/resources/findme_searching.gif) |

## Improving

**ARKit** is not so stable now, so we've tried some methods to improve the accuracy of the route, mainly at these two branches:

- [Improving according to location](https://github.com/mmoaay/Findme/tree/feature/location_optimize)
- [Improving according to distance](https://github.com/mmoaay/Findme/tree/feature/distance_optimize)

## Author

mmoaay, mm@swift.gg

## License

![](https://www.gnu.org/graphics/gplv3-127x51.png)

Findme is available under the GPL-3.0 license. See the LICENSE file for more info.
