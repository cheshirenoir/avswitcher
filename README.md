# avswitcher
A modular AV Switcher. No scaling. Just switching. SVideo, Composite, Component and RGB (in the form of HD15)

THIS IS IN A VERY EARLY STATE. NOT FIT FOR PRODUCTION

This consists of a "Brainboard" containing an Arduino, A "Bus" that connects the other boards, and has the select logic for choosing which input has been selected, a control board, designed to plug into the front of the brain board. There is a Video out board that contains all the possible outputs, with a mirrored audio pair for each input. This plugs into the back of the Brainboard. It also handles the power in. (It's all designed to run off a 5V input. If I hit problems with power use, and I don't expect to, I can look at switching over to 9v and dropping a 7805 on each output board.) Finally there are the 4 different input boards that can be plugged into the bus, one each for SVideo, Composite, Component and "VGA" (Actually just RGBHV).
Each input board has a digitally controlled switch, which means unless they are selected, they stay isolated. Awesome for keeping the bus quiet when you are using the other input.
Why did I build this? Becauise I accidentally ended up with a collection of consoles, and switching between them was becoming a nightmare of switchers, scalers and general cable mess. I decided I wanted everything plugging into one box, and I could then plug just one scaler into each output.
I am now contemplating adding a relay to each output so I can switch on and off scalers as needed. That will need to wait for a later versions.

I haven't even started writing code for any of this. Talk about putting the horse before the cart.

Oh erm. CC-BY-SA
