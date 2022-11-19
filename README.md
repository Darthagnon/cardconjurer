# Card Conjurer
Use the following link to start creating your own custom Magic: The Gathering cards!
https://cardconjurer.com/


[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg?longCache=true&style=popout)](https://www.paypal.me/kyleburtondonate
) ← Help me keep playing magic by donating any amount

[![Donate](https://img.shields.io/badge/Donate-Patreon-orange.svg?longCache=true&style=popout)](https://www.patreon.com/KyleBurton) ← Check out my Patreon


## Tips

### Run offline

1. Install [WAMP](https://wampserver.aviatechno.net/?lang=en) server (Windows) or [XAMPP](https://www.apachefriends.org/)
2. Use the newest PHP version as of Nov. 2022
3. Place all the contents of `/cardconjurer/` in `C:\wamp64\www\` or equivalent.
4. Cardconjurer should be available at `localhost:index.php` as long as your webserver is running.

[Source](https://www.reddit.com/r/magicproxies/comments/yyzfd5/how_to_run_cardconjurer_locally_on_windows/)

### Remove copyright text

When running via WAMP/XAMPP on localhost, visit `localhost:creator/?copyright` to remove WotC copyright info after you add the 1/8th inch margin.

For cards without the margin, instead use `localhost:creator/?copyright=%E2%80%8B` ([Source](https://www.reddit.com/r/magicproxies/comments/yyzfd5/how_to_run_cardconjurer_locally_on_windows/iwxo7qd/)

You can also edit `/cardconjurer/js/creator-23.js/` to remove copyright text by commenting the `bottomright` line of code.

### Use assets to upgrade MSE
![MSE Upgrade](/MSE_Upgrade.png)

If you like MSE but are not satisfied with the image quality, you can replace the assets with CC assets. It makes almost no difference for old cards, but makes quite an impact on newer cards. ([Source](https://old.reddit.com/r/magicTCG/comments/yyq8d4/card_conjurer_has_been_cease_and_desisted/iwvyi5b/))

## History and original source
[CardConjurer.com](https://cardconjurer.com/) was taken down on 19 Nov 2022 in response to a DMCA notice by WotC ([source](https://www.reddit.com/r/magicTCG/comments/yyq8d4/card_conjurer_has_been_cease_and_desisted/)). It is suspected this is in preparation for a branded custom card creator tool ([source](https://www.reddit.com/r/magicTCG/comments/yzem44/hasbro_launched_what_it_calls_the_first/)) or as a reaction to growing popularity of proxy/counterfeit cards due to the $999 Magic 30th Anniversary proxies and "real cards" debacle ([source](https://markrosewater.tumblr.com/post/697135665776869376/if-i-open-a-pack-of-magic-and-get-a-transformers)). In response, a [community fork](https://github.com/MrTeferi/cardconjurer) was made available by MrTeferi, moderator of r/magicproxies along with instruction for offline running ([announcement](https://www.reddit.com/r/magicproxies/comments/yyzfd5/how_to_run_cardconjurer_locally_on_windows/)). 
