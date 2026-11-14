This repo was originally for my Chivalry Deadliest Warrior Template for Cubecoders AMP, but now serves as a home for my random inspirations.


For Chivalry: Deadliest Warrior,
This Template is not maintained whatsoever, modifications will be done as needed.

    Chivalry: Deadliest Warrior requires you to login to an account that owns it in order to download through SteamCMD, anonymous login is not possible.
    This template utilizes Wine for Linux as there is no linux version available, for ease you will probably want to run the instance in a docker container.
    There has been limited testing in Windows, as such I cannot guarantee that this template works 100% on Windows.

    This template will run and appear on the server list, the template will automatically download the Steamworks SDK Redist to replace the outdated steam files within the server so it will be publically available.
    This Template works as of January 8th 2025 (Post official servers shutdown) *This Template is very buggy on account of the server software being awful*

For The Ship: Murder Party,
Documentation for this game is very unavailable/unreliable as the Remaster floods any information on the original, some options may be missing or mislabeled

    The Ship: Murder Party requires you to login to an account that owns it in order to download through SteamCMD, anonymous login is not possible.
    This template utilizes Wine/xvfb for Linux as the linux version is unmaintained and broken, for ease you will probably want to run the instance in a docker container.
    There has been limited testing in Windows, as such I cannot guarantee that this template works 100% on Windows.

For PvPGN (Warcraft III),
Builds PvPGN-PRO from source on each update, Linux only.

    Running the instance in a container is recommended, as it provides the build tools. On a bare host you need git, cmake, a C++ compiler, and zlib/SQLite headers.
    Clients need the W3L loader (https://github.com/w3lh/w3l) and a gateway entry pointing at your server, on a patch between 1.22a and 1.28.
    Players behind the same NAT as the server need entries in server/etc/pvpgn/address_translation.conf for remote players to join their games.
    The server has no console input; administer it in-game with an account given admin rights.

If you believe that any of these templates needs to be updated or have changes made, please submit a pull request with a justification for why that change is needed.

Once you've submitted a pull request, it will be reviewed and tested when I have the time to get around to it.
