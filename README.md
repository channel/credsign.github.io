# Channel
Channel lets you publish and view content using the Ethereum blockchain. It is currently in beta on the Ethereum main network at <https://channel.github.io/>. Shoutout to the folks at ChannelMe for giving us this github alias.

# Development enviroment setup

**To setup on a local privatenet**

1. Copy or link `geth` to the root of this repo.
2. Run `node dev --sync --network=privnet` to start your local node. Leave it running.
3. Run `node dev --deploy --network=privnet --contracts=all` to deploy the contracts. When prompted for a password, use `credsign`.
4. Run `node dev --serve` to compile the webapp and serve it at <http://localhost:8000/>

Modifying files in `./app/src` will trigger a recompile while the frontend server is running.

# License

Copyright (C) 2017 Channel

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
