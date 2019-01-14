# CommandSpam
Oxide plugin to detect and rate limit players (via kick) who attempt to spam commands on Rust game servers.  I've had issues with players keybinding server /commands and using macros to attempt to lag the server.  This plugin has solved these issues.  


## Usage

Configure the *interval* and *threshold* variables to suit your needs.  As configured issuing more than 15 commands in an 8 second window will result in a kick.


## TODO

Clean up and configure to pull configuration options from config file
