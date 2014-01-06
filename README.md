Pulse
=====

Do great things, one accomplishment at a time.

[![Build Status](https://travis-ci.org/Illinois-Founders/pulse.png)](https://travis-ci.org/Illinois-Founders/pulse)

[See The Production App](https://pulse-il.jit.su)

## Vision

A community that enables individuals to accomplish great things.

## Execution

`Pulse` will be a single-page app centered around a chronological stream of accomplishments. Its primary purpose is to encourage people to accomplish small things. Its secondary purpose is to deter atrophy.

### The Stick

Atrophy in the community immediately affects everyone. Artificial lag is introduced so that "passive" actions like commenting on accomplishments becomes progressively more difficult to perform. This deters unproductive and unsightly comment threads. Emails will be sent out to laggards, encouraging them to share a recent accomplishment.

### The Carrot

Accomplished users can bask in the praise of their peers and watch as they rise on the leaderboard. In future updates, we should further gamify this by adding badges. Sharing accomplishments also temporarily lifts the artificial lag, which should lead to praise and thanks from the community.

## Technical Details

### Back-end

 * express 3
 * mongodb
 * socket.io
 * nodejitsu

### Front-end

 * handlebars
 * browserify
 * ribcage-ui
 * topcoat

## Contributing

**You'll need mongodb installed locally.**

Start a development server:

```sh
$ npm install
$ npm install nodemon -g
$ nodemon server.js
```

Or run the tests:

```sh
$ npm test
```

## Deployment

Deployment is automatic and happens whenever a push to the master branch does not break the build.

## License

Copyright (C) 2014 Ben Ng and Contributors

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
