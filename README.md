# Streaming Guide
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-21-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

A comprehensive guide to getting into streaming (mostly for programming)
<br>

⚠ This is a living set of documentation, meaning it's currently being written and actively updated ⚠

This is by no means a set of hard rules that must be followed but instead a community driven set of suggestions and guidance for streaming

## Table of Contents

1. [Requirements](requirements.md)
2. [Software](software.md)
3. [Software Setup](setup.md)
   1. Configuration/Settings
   2. Stream layout
      1. scenes, sources, camera, mic, etc.
4. [Testing Your Stream](testing.md)
5. [What do I stream?]()
6. [Go Live]()
   1. How to handle viewer engagement like comments, questions, etc. while continuing the goal of the stream?
7. [Moderation]()


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://lannonbr.com"><img src="https://avatars2.githubusercontent.com/u/3685876?v=4" width="100px;" alt=""/><br /><sub><b>Benjamin Lannon</b></sub></a><br /><a href="#ideas-lannonbr" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=lannonbr" title="Documentation">📖</a></td>
    <td align="center"><a href="https://wwsean08.com"><img src="https://avatars1.githubusercontent.com/u/839261?v=4" width="100px;" alt=""/><br /><sub><b>Sean Smith</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=wwsean08" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/Pranav-29"><img src="https://avatars3.githubusercontent.com/u/48860494?v=4" width="100px;" alt=""/><br /><sub><b>Pranav Goel</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=pranav-29" title="Documentation">📖</a></td>
    <td align="center"><a href="https://toefrog.github.io/Blog/"><img src="https://avatars0.githubusercontent.com/u/1122675?v=4" width="100px;" alt=""/><br /><sub><b>Chris Gargotta</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=toefrog" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/parithon"><img src="https://avatars3.githubusercontent.com/u/8602418?v=4" width="100px;" alt=""/><br /><sub><b>Anthony Conrad (parithon)</b></sub></a><br /><a href="#ideas-parithon" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=parithon" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/quakerpunk"><img src="https://avatars1.githubusercontent.com/u/608073?v=4" width="100px;" alt=""/><br /><sub><b>quakerpunk</b></sub></a><br /><a href="#ideas-quakerpunk" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=quakerpunk" title="Documentation">📖</a></td>
    <td align="center"><a href="http://jeanfelis.me"><img src="https://avatars0.githubusercontent.com/u/1755639?v=4" width="100px;" alt=""/><br /><sub><b>Jean Felisme</b></sub></a><br /><a href="#ideas-jfeliweb" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=jfeliweb" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.geekyboy.com"><img src="https://avatars0.githubusercontent.com/u/284451?v=4" width="100px;" alt=""/><br /><sub><b>Adam Culp</b></sub></a><br /><a href="#ideas-adamculp" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=adamculp" title="Documentation">📖</a></td>
    <td align="center"><a href="https://fabiorosado.dev"><img src="https://avatars0.githubusercontent.com/u/3131401?v=4" width="100px;" alt=""/><br /><sub><b>Fábio Rosado</b></sub></a><br /><a href="#ideas-FabioRosado" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=FabioRosado" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/blowfishfugu"><img src="https://avatars2.githubusercontent.com/u/47995334?v=4" width="100px;" alt=""/><br /><sub><b>blowfishfugu</b></sub></a><br /><a href="#ideas-blowfishfugu" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=blowfishfugu" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.twitch.tv/copperbeardy"><img src="https://avatars0.githubusercontent.com/u/53055058?v=4" width="100px;" alt=""/><br /><sub><b>Copperbeardy</b></sub></a><br /><a href="#ideas-copperbeardytwitch" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=copperbeardytwitch" title="Documentation">📖</a></td>
    <td align="center"><a href="https://vaibhavchatarkar.com"><img src="https://avatars1.githubusercontent.com/u/1468518?v=4" width="100px;" alt=""/><br /><sub><b>vaibhav</b></sub></a><br /><a href="#ideas-da-vaibhav" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=da-vaibhav" title="Documentation">📖</a></td>
    <td align="center"><a href="https://eyluismi.com"><img src="https://avatars1.githubusercontent.com/u/10482936?v=4" width="100px;" alt=""/><br /><sub><b>Luis Miguel Díaz Abril</b></sub></a><br /><a href="#ideas-EyLuismi" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=EyLuismi" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/Nightshadedude"><img src="https://avatars3.githubusercontent.com/u/17286651?v=4" width="100px;" alt=""/><br /><sub><b>Eric Landeis</b></sub></a><br /><a href="#ideas-nightshadedude" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/clarkio/streaming-guide/commits?author=nightshadedude" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/opti21"><img src="https://avatars3.githubusercontent.com/u/40129778?v=4" width="100px;" alt=""/><br /><sub><b>opti21</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=opti21" title="Documentation">📖</a> <a href="#ideas-opti21" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://www.codephobia.com"><img src="https://avatars1.githubusercontent.com/u/6385224?v=4" width="100px;" alt=""/><br /><sub><b>Martin Raymond</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=codephobia" title="Documentation">📖</a> <a href="#ideas-codephobia" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/archification"><img src="https://avatars0.githubusercontent.com/u/25619582?v=4" width="100px;" alt=""/><br /><sub><b>archification</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=archification" title="Documentation">📖</a> <a href="#ideas-archification" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://localhost:5000"><img src="https://avatars0.githubusercontent.com/u/26912197?v=4" width="100px;" alt=""/><br /><sub><b>Lemuel De Los Santos</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=lemueldls" title="Documentation">📖</a> <a href="#ideas-lemueldls" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://mtk.me"><img src="https://avatars2.githubusercontent.com/u/1219553?v=4" width="100px;" alt=""/><br /><sub><b>Matthew Kosloski</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=matthewkosloski" title="Documentation">📖</a> <a href="#ideas-matthewkosloski" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/therealpygon"><img src="https://avatars1.githubusercontent.com/u/10392148?v=4" width="100px;" alt=""/><br /><sub><b>therealpygon</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=therealpygon" title="Documentation">📖</a> <a href="#ideas-therealpygon" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/AlliDoisCode1234"><img src="https://avatars1.githubusercontent.com/u/31934921?v=4" width="100px;" alt=""/><br /><sub><b>AlliDoisCode1234</b></sub></a><br /><a href="https://github.com/clarkio/streaming-guide/commits?author=AlliDoisCode1234" title="Documentation">📖</a> <a href="#ideas-AlliDoisCode1234" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
