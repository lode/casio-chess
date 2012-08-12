Casio Chess
===========

Chess game for the Casio CFX-9850GB PLUS

![Chess (screenshots/CINGAME.jpg)](https://github.com/lode/casio-chess/raw/master/screenshots/CINGAME.jpg)

To my knowledge the first chess game for the Casio CFX that actually works.
In the other chess game, popular at that time, it wasn't possible to move the
knight, castling wasn't supported and check wasn't checked for correctly.

I went to make a better version which didn't have these shortcomings. The only
thing I didn't manage was automatically checking for checkmate. The players
needed to check that for themselves when the Casio detected check. Back then, I
calculated it would have costed me another 32kb to automatically detect
checkmate as well. And the game already took the full 32kb available. Probably,
I could make it better with my current knowledge and maybe even fit it all in
one 32kb Casio.

![Chess Light (light/screenshots/CL_PLAY3.jpg)](https://github.com/lode/casio-chess/raw/master/light/screenshots/CL_PLAY3.jpg)

Afterwards, unhappy with the playability on the slow Casio processor, I made a
light version of the game. It was much smaller, less then 6kb, and used a
slightly different interface. Above all, it didn't check for any rules. You can
move the pieces anywhere you want and are responsible for playing by the rules
yourself.

Made around 2002/2003, I didn't touch the source since then. I can't give any
support for it might someone want that. If you want to improve on it, fork for
your own pleasure instead of filing bugs or sending pull requests.
