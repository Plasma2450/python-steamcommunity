# Important

Please do not open an issue for documentation.

This module is based off [node-steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity).

This version has been updated to work with python3

For a more or less guide on how to use the Trade Confirmations methods on Steam Login, take a look a [this file](https://github.com/DoctorMcKay/node-steamcommunity/blob/master/components/confirmations.js) and on how to use the trade confirmation key on SteamMobileAuth take a look at [these lines](https://github.com/DoctorMcKay/node-steam-totp/blob/master/index.js#L60-L90)

# python-steamcommunity

Python port of node-steamcommunity with a focus on a session based login using requests

Hopefully with this module eveything up to steam trading will be able to be done.

Things that are functional:
- Two-factor authentication codes given a shared secret
- Trade confirmation keys too.
- Steam login. The module is based on a set of custom exceptions when 2fa, captchas or email codes are needed, sample login code to be done
- Basic steam inventory via the json endpoints available for any steam user
- SteamTradeOffers is very much functional. It can make Trade Offers and try to get the Receipt (Steam is very unreliable)
- Now SteamLogin can both check for trade confirmations, accept and decline them, as always, documentation is missing
- SteamWebApi has only the IEconService endpoint implemented, which lets the user check for incoming, outgoing, cancelling and declining trade offers


# NOTICE

I am not actively developing this repo if you find a problem and fix it feel free to submit a pull request which i will approve aswell as adding new features.
