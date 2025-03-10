# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<hr>
	<p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://github.com/botpress/botpress">
			<img src="https://sindresorhus.com/assets/thanks/botpress-logo.svg" width="180" alt="Botpress">
		</a>
		<br>
		<sub><b>Botpress is an open-source conversational assistant creation platform.</b></sub>
		<br>
		<sub>They <a href="https://github.com/botpress/botpress/blob/master/.github/CONTRIBUTING.md">welcome contributions</a> from anyone, whether you're into machine learning,<br>want to get started in open-source, or just have an improvement idea.</sub>
		<br>
		<br>
		<br>
		<a href="https://segment.com">
			<img src="media/segment-logo.svg" width="180" alt="Segment">
		</a>
		<br>
		<sup>
			Save time setting up analytics with Segment. <a href="https://segment.com/jobs">We're hiring!</a>
		</sup>
	</p>
	<hr>
	<br>
	<br>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Just type <a href="https://node.cool"><code>node.cool</code></a> to go here. Check out my <a href="https://blog.sindresorhus.com">blog</a> and follow me on <a href="https://twitter.com/sindresorhus">Twitter</a>.</sub>
	</p>
	<br>
</div>

## Contents

- [Packages](#packages)
	- [Mad science](#mad-science)
	- [Command-line apps](#command-line-apps)
	- [Functional programming](#functional-programming)
	- [HTTP](#http)
	- [Debugging / Profiling](#debugging--profiling)
	- [Logging](#logging)
	- [Command-line utilities](#command-line-utilities)
	- [Build tools](#build-tools)
	- [Hardware](#hardware)
	- [Templating](#templating)
	- [Web frameworks](#web-frameworks)
	- [Documentation](#documentation)
	- [Filesystem](#filesystem)
	- [Control flow](#control-flow)
	- [Streams](#streams)
	- [Real-time](#real-time)
	- [Image](#image)
	- [Text](#text)
	- [Number](#number)
	- [Math](#math)
	- [Date](#date)
	- [URL](#url)
	- [Data validation](#data-validation)
	- [Parsing](#parsing)
	- [Humanize](#humanize)
	- [Compression](#compression)
	- [Network](#network)
	- [Database](#database)
	- [Testing](#testing)
	- [Security](#security)
	- [Benchmarking](#benchmarking)
	- [Minifiers](#minifiers)
	- [Authentication](#authentication)
	- [Authorization](#authorization)
	- [Email](#email)
	- [Job queues](#job-queues)
	- [Node.js management](#nodejs-management)
	- [Natural language processing](#natural-language-processing)
	- [Process management](#process-management)
	- [Automation](#automation)
	- [AST](#ast)
	- [Static site generators](#static-site-generators)
	- [Content management systems](#content-management-systems)
	- [Forum](#forum)
	- [Blogging](#blogging)
	- [Weird](#weird)
	- [Serialization](#serialization)
	- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
	- [Tutorials](#tutorials)
	- [Discovery](#discovery)
	- [Articles](#articles)
	- [Newsletters](#newsletters)
	- [Videos](#videos)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Tools](#tools)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous)
- [Related lists](#related-lists)

## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:21389
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:5357
- [dat](https://github.com/datproject/dat-node) - Real-time replication and versioning for data sets. :star:484
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:4251
- [stackgl](https://github.com/stackgl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:298
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:447
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:3782
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:3537
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:5957
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:5041
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:402
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:6157
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI operating system. :star:998
- [Brain.js](https://github.com/BrainJS/brain.js) - Machine-learning framework. :star:10785
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:6409
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:178
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3628
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:368
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:19962
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:4412

### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:5013
- [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm. :star:117
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:155
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:167
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1943
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:3285
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1885
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8959
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:257
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:3512
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:101
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:330
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:819
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:522
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:350
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:4946
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:23267
- [ESLint](https://github.com/eslint/eslint) - The pluggable linting utility for JavaScript. :star:15913
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:167
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:911
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:9196
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:3063
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:291
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:204
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5994
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:370
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:1000
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:355
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:111
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:207
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:674
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:167
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:564
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:254
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:3408
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:294
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:121
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:471
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:229
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:167
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:390
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:77
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:43
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:231
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7676
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1107
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:1544
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:786
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:1059
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:115
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2506
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:9575
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:1717
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:8051
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:2308
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - Beautiful images of your code — from right inside your terminal. :star:4438
- [cash-cli](https://github.com/xxczaki/cash-cli) - Convert between 170 currencies. :star:131
- [taskbook](https://github.com/klauscfhq/taskbook) - Tasks, boards & notes for the command-line habitat. :star:7445
- [discharge](https://github.com/brandonweiss/discharge) - Easily deploy static websites to Amazon S3. :star:426
- [npkill](https://github.com/voidcosmos/npkill) - Easily find and remove old and heavy node_modules folders. :star:2548

### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js. :star:43663
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:29253
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:18316
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse. :star:1730
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:1174
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming. :star:6217
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data. :star:21213
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:5864
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1647

### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:6855
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:146
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:70114
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:24259
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:373
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:944
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:10940
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:14904
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:4694
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:108
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:223
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:197
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:229
- [global-agent](https://github.com/gajus/global-agent) - Global HTTP/HTTPS proxy agent that is configurable using environment variables. :star:73

### Debugging / Profiling

- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools. :star:9856
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2369
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12489
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:8516
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:1056
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:272
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:57
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:211
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:274
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:1752
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:108
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1434
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process. :star:817
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format. :star:145
- [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics. :star:387
- [NiM](https://github.com/june07/nim) - Manages DevTools debugging workflow. :star:152

### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:5079
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:14944
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:57
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:595
- [signale](https://github.com/klauscfhq/signale) - Console logger. :star:8011
- [consola](https://github.com/nuxt/consola) - Console logger. :star:2724

### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:14006
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:2074
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:7340
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:5670
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:245
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:744
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:12809
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:2414
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:536
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:288
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:502
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:385
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:702
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:250
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:475
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:181
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:51
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:68
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:9034
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:11992
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:182
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables. :star:133
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:861
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:1351
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:224
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:2380
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:485
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:65
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:371
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:23
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:541
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:263
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:911
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:4516
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:10772
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:79
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:260
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines `▁▂▃▅▂▇`. :star:345
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:10264
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:406
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins. :star:4587
- [term-size](https://github.com/sindresorhus/term-size) - Reliably get the terminal window size. :star:107
- [Cliffy](https://github.com/drew-y/cliffy) - Framework for interactive CLIs. :star:228

### Build tools

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. :star:34931
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:53080
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:17576
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config. :star:31645
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3279
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6658
- [Start](https://github.com/deepsweet/start) - Functional task runner with shareable presets. :star:482
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:66
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3944
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:15355

### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:11319
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:4297
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:908
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:216
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:910
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:77
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:604
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. :star:136

### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:9409
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:6528
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:15140
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:4190
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:19019

### Web frameworks

- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services. :star:12125
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs. :star:28569
- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications. :star:47505
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express. :star:12185
- [LoopBack](https://github.com/strongloop/loopback) - Powerful framework for creating REST APIs and easily connecting to backend data sources. :star:13053
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))* :star:41636
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services. :star:9692
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. :star:5066
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. :star:2072
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. :star:45396
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. :star:25614
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:3635
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:726
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:9105
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. :star:13671
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. :star:24723
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices. :star:102
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators. :star:3844

### Documentation

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. :star:4960
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. :star:2559
- [Docco](https://github.com/jashkenas/docco) - Documentation generator which produces an HTML document that displays your comments intermingled with your code. :star:3424
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API documentation generator similar to JavaDoc or PHPDoc. :star:10366

### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:1051
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:1354
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:257
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:3621
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:395
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:936
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:6269
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:271
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:103
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:165
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:145
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:47
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:272
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:10
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:65
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:523
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:6606
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:124
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:170
- [move-file](https://github.com/sindresorhus/move-file) - Move a file, even works across devices. :star:136
- [tempy](https://github.com/sindresorhus/tempy) - Get a random temporary file or directory path. :star:234

### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:18944
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:1266
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:363
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:43
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:25
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:509
	- [More…](https://github.com/sindresorhus/promise-fun) :star:2882
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:606
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:21213
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:265
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:265
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. :star:3265
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:107
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:26381
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2261

### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1679
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:118
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:185
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:146
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:162
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:183
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:45
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:72
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:286
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:21
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:204
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:74
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:812
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:73

### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:11283
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. :star:48873
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. :star:4248
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:5569
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:4070
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. :star:252
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:113
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:5203
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets. :star:231
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server. :star:540

### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:15739
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:203
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:6021
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2249
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1907
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:9749
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:308
- [qrcode](https://github.com/soldair/node-qrcode) - QR code and bar code generator. :star:3800

### Text

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:2283
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:78
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:398
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:349
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:78
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:14
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:80
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:92
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:140
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:2399
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:2512
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:210
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:445
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:17
- [i18next](https://github.com/i18next/i18next) - Internationalization framework. :star:4750
- [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator. :star:8540

### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:52
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:20
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:76
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:116

### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:905
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:9535
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:6
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:85
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. :star:43

### Date

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times. :star:9076
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:21467
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Day.js](https://github.com/iamkun/dayjs) - Immutable date library alternative to Moment.js. :star:25972
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:1050
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:6
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:54

### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:426
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:186
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:42
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:1021
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:355
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:475
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:44

### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:14278
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:901
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:148
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:463
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5, v6 and v7 proposals. :star:6999

### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:2789
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:8983
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:2317
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:446
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:97
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:170
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5896
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:22223
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1711
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:148
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:772
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:3574
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:5211
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:2382
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:146
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:138
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:4345
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:3913
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family. :star:3613
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:793
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:356
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:499
- [Chevrotain](https://github.com/SAP/chevrotain) - Very fast and feature rich parser building toolkit for JavaScript. :star:1272
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. :star:684

### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:565
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:480
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:2687
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:1312
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:296

### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:229
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:462
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1822
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:2753
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:274
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:281

### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:477
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:173
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:220
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:178
- [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. :star:275

### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:8180
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:7156
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3683
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:15118
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client. :star:353
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:164
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:423
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:8442
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:21217
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. :star:5806
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. :star:2552
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. :star:20302
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:5157
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:448
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:2521
	- [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions. :star:1315
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:4921
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. :star:17707
	- [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite. :star:648
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. :star:11458
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:11001
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:12427
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:983
	- [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. :star:138
	- [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. :star:29
	- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Populate MongoDB databases with JavaScript and JSON files. :star:215
	- [@databases](https://github.com/ForbesLindesay/atdatabases) - Query PostgreSQL, MySQL and SQLite3 with plain SQL without risking SQL injection. :star:50

### Testing

- [AVA](https://github.com/avajs/ava) - Futuristic test runner. :star:17606
- [Mocha](https://github.com/mochajs/mocha) - Feature-rich test framework making asynchronous testing simple and fun. :star:19046
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:4037
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1554
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:5241
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:2462
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:334
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:2173
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1813
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:7817
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:45
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:9173
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:4183
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2623
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:45
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:175
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:10049
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol. :star:5511
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:29861
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:7898
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:572
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - End-to-end testing. :star:2677
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome. :star:58982
- [Playwright](https://github.com/microsoft/playwright) - Headless Chromium, WebKit, and Firefox with a single API. :star:9993
- [nve](https://github.com/ehmicky/nve) - Run any command on multiple versions of Node.js locally. :star:497

### Security

- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms. :star:454
- [themis](https://github.com/cossacklabs/themis) - Multilanguage framework for making typical encryption schemes easy to use: data at rest, authenticated data exchange, transport protection, authentication, and so on. :star:954
- [GuardRails](https://github.com/apps/guardrails) - GitHub app that provides security feedback in pull requests.
- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - Brute-force and DDoS attack protection. :star:796
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - Async non-blocking hashing. :star:399
- [jose-simple](https://github.com/davesag/jose-simple) - Encryption and decryption of data using the JOSE (JSON Object Signing and Encryption) standard. :star:25

### Benchmarking

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results. :star:4455
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. :star:520

### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain. :star:4031
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript minifier. :star:10563
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. :star:3447
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. :star:147
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. :star:3797

### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication. :star:17022
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi. :star:2623

### Authorization

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API. :star:1828
- [node-casbin](https://github.com/casbin/node-casbin) - Authorization library that supports access control models like ACL, RBAC and ABAC. :star:833

### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email. :star:12230
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server. :star:1789
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates. :star:2713
- [MJML](https://github.com/mjmlio/mjml) - Markup language designed to reduce the pain of creating responsive emails. :star:10136

### Job queues

- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. :star:7723
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed job scheduling. :star:6276
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. :star:47
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. :star:800
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue. :star:1237
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue. :star:1758
- [RedisSMQ](https://github.com/weyoss/redis-smq) - Simple high-performance Redis message queue with real-time monitoring. :star:187
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - Build Amazon Simple Queue Service (SQS) based apps without the boilerplate. :star:795
- [better-queue](https://github.com/diamondio/better-queue) - Simple and efficient job queue when you cannot use Redis. :star:252

### Node.js management

- [n](https://github.com/tj/n) - Node.js version management. :star:12747
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. :star:1399
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. :star:1167
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. :star:11678
- [nodenv](https://github.com/nodenv/nodenv) - Version manager that is similar to Ruby's rbenv. It supports auto version switching. :star:1134

### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system. :star:1871
- [franc](https://github.com/wooorm/franc) - Detect the language of text. :star:3131
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. :star:488
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. :star:9078
- [nlp.js](https://github.com/axa-group/nlp.js) - Building bots, with entity extraction, sentiment analysis, automatic language identify, and more. :star:3489

### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. :star:31770
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. :star:20082
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. :star:453
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. :star:369
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. :star:1872
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. :star:3663
- [Phusion Passenger](https://github.com/phusion/passenger) - Friendly process manager that integrates directly into Nginx. :star:4553

### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen. :star:8623

### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser. :star:5693
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser used in Babel. :star:35889
- [cherow](https://github.com/cherow/cherow) - JavaScript parser with focus on performance and stability. :star:1544

### Static site generators

- [Wintersmith](https://github.com/jnordberg/wintersmith) - Flexible, minimalistic, multi-platform static site generator. :star:3489
- [Assemble](https://github.com/assemble/assemble/) - Static site generator for Node.js, Grunt.js, and Yeoman. :star:3765
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem. :star:3002
- [Phenomic](https://github.com/phenomic/phenomic) - Modern static website generator based on the React and Webpack ecosystem. :star:3318
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown documentation site generator with no statically built HTML files. :star:12578
- [Charge](https://github.com/brandonweiss/charge) - Opinionated, zero-config static site generator using JSX and MDX. :star:270

### Content management systems

- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB. :star:1647
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB. :star:3049
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs. :star:22185
- [Tipe](https://github.com/tipeio/tipe) - Developer-first content management system with GraphQL and REST API from a schema file. :star:2020

### Forum

- [nodeBB](https://github.com/NodeBB/NodeBB) - Forum platform for the modern web. :star:10842

### Blogging

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform. :star:32786
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework. :star:29643

### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows. :star:335
- [superb](https://github.com/sindresorhus/superb) - Get superb like words. :star:343
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names. :star:216
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names. :star:99
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names. :star:196
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names. :star:93
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces. :star:1712
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - `₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”`. :star:219
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon. :star:87

### Serialization

- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library. :star:419
- [protobuf](https://github.com/dcodeIO/protobuf.js) - Implementation of Protocol Buffers. :star:6422
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol. :star:81

### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`. :star:2988
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. :star:21363
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* :star:80976
- [open](https://github.com/sindresorhus/open) - Opens stuff like websites, files, executables. :star:1884
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file. :star:756
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path. :star:429
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once. :star:104
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:626
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache. :star:192
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream. :star:81
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale. :star:151
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module. :star:3937
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple. :star:30
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily. :star:192
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer. :star:1473
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy. :star:873
- [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans. :star:2878
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads. :star:2111
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste). :star:893
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries. :star:746
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library. :star:3931
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file. :star:10862
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. :star:34
- [semver](https://github.com/npm/node-semver) - Semantic version parser. :star:3161
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data. :star:22578
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git. :star:4424
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop. :star:9
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path. :star:86
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. :star:1987
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM. :star:13663
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views. :star:5469
- [@sindresorhus/is](https://github.com/sindresorhus/is) - Type check values. :star:892
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - Get, set, or delete nested properties of process.env using a dot path. :star:26
- [emittery](https://github.com/sindresorhus/emittery) - Simple and modern async event emitter. :star:1017
- [node-video-lib](https://github.com/gkozlenko/node-video-lib) - Pure JavaScript library for working with MP4 and FLV video files and creating MPEG-TS chunks for HLS streaming. :star:231
- [basic-ftp](https://github.com/patrickjuchli/basic-ftp) – FTP/FTPS client.
- [cashify](https://github.com/xxczaki/cashify) - Currency conversion. :star:284
- [genepi](https://github.com/Geode-solutions/genepi) - Automatically generate a native Node.js addon from C++ code. :star:21

## Resources

### Tutorials

- [Node.js Best Practices](https://github.com/i0natan/nodebestpractices) - Summary and curation of the top-ranked content on Node.js best practices, available in multiple languages. :star:40138
- [Nodeschool](https://github.com/nodeschool) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js. :star:8550
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams. :star:12932
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules. :star:1338
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript. :star:1172
- [Portable Node.js guide](https://github.com/ehmicky/portable-node-guide) - Practical guide on how to write portable/cross-platform Node.js code. :star:1020
- [Build a real web app with no frameworks](https://frameworkless.js.org/course) - A set of video tutorials/livestreams to help you build and deploy a real, live web app using a handful of simple libraries and the core Node.js modules.

### Discovery

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.

### Articles

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs. :star:5443
- [Using Express to Quickly Build a GraphQL Server](https://snipcart.com/blog/graphql-nodejs-express-tutorial)

### Newsletters

- [Node Weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [Node Module Of The Week!](https://nmotw.in) - Weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/hands-on-with-node.js/preface)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [V8 Garbage Collector](https://v8.dev/blog/trash-talk) - Trash talk about the V8 garbage collector.
- [10 Things I Regret About Node.js by Ryan Dahl](https://www.youtube.com/watch?v=M3BM9TB-8yA) - Insightful talk by the creator of Node.js about some of its limitions.

### Books

- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building JavaScript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)
- [Practical Modern JavaScript](https://www.amazon.com/Practical-Modern-JavaScript-Dive-Future/dp/149194353X)
- [Mastering Modular JavaScript](https://www.amazon.com/Mastering-Modular-JavaScript-Nicolas-Bevacqua/dp/1491955686/)
- [Get Programming with Node.js](https://www.manning.com/books/get-programming-with-node-js)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4) :star:1096
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more. :star:184
- [Strong Node.js](https://github.com/jesusprubio/strong-node) - Checklist for source code security analysis of a Node.js web service. :star:324

### Tools

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome extension that displays npm download stats on GitHub.
- [npm semver calculator](https://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
- [CodeSandbox](https://codesandbox.io/s/node-http-server-node) - Online IDE and prototyping.

### Community

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)
- [Discord](https://discordapp.com/invite/96WGtJt)

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module. :star:632
- [modern-node](https://github.com/sheerun/modern-node) - Toolkit for creating node modules with Jest, Prettier, ESLint, and Standard. :star:181
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module. :star:690
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:2147
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - Request a JavaScript module you wish existed or get ideas for modules. :star:474

## Related lists

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Resources and tips for using npm. :star:3477
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code. :star:821

