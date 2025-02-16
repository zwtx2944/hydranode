<p align="center">
  <img src="https://raw.githubusercontent.com/HydraLabs-beta/sedar/main/HydraDaemon2.png" alt="HydraBanner">
</p>

<h1 align="center">HydraDaemon</h1>
## Overview
Hydra Daemon is the daemon for the Hydra Panel.

## Installation
1. Clone the repository:
`git clone https://github.com/zwtx2944/hydranode.git`

2. Install dependencies:
`npm install`

3. install Docker:
- `curl -sSL https://get.docker.com/ | CHANNEL=stable bash`

4. Start the Daemon:
`node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the Hydra Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the Hydra Daemon are encouraged. Please submit pull requests for any enhancements.

## License
(c) 2024 MJ and contributors. This software is licensed under the MIT License.


## Credits
SRYDEN
Skyport
