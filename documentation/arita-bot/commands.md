# Commands

Welcome to the command overview for Arita Bot, Kinkdom's friendly robot overlord robotic care-taker! Guided by a starchy hand, you shall learn how to use the many commands hiding in Arita Bot's tummy.


---

## Core Commands

A list of Kinkdom's core commands! These are the commands which don't fit in the other categories, but are important enough to not be tossed into the trash bin Miscellaneous.


### /gems

> Description: Doing this will show you how many gems you got. Nice n' simple!


### /upgrade

> Description: Upgrade your vanity role. See prices [here](https://github.com/kinkdom-org/community/blob/main/documentation/roles/vanity-roles.md).


### /challengelog

> Description: This command will show you this week's challenges. Complete them to earn gems and other rewards! You do this by RPing in the rooms relevant to the challenges. There's up to three tiers of challenges you can complete!

Challenge tiers usually look like this. `Base Name I` / `Base Name II` / `New Name`.

For example: `No Place Like Home` / `No Place Like Home` / `Homecoming`.

Here's the list of all the different challenge names and what they mean:

1. `A Gem is Worth 50 Words` / `Speechless`: Earn gems in any category. This challenge only works in the non-role-locked channels, namely fantasy, modern, sci-fi, community.
2. `Weekly Grind` / `Grounded in Reality`: Earn gems in modern rooms.
3. `Once Upon a Time` / `Fantasyland resident`: Earn gems in fantasy rooms.
4. `Territories Unknown` / `Spacebound`: Earn gems in sci-fi rooms.
5. `No Place like Home` / `Homecoming`: Earn gems in rented rooms (community rooms).
6. `Tough as Nails` / `The Edge`: Earn gems in dark rooms.
7. `Experiencing the Wild` / `Beauty and the Beast`: Earn gems in non-human rooms.
8. `Donut Steelie` / `Coldsteel`: Earn gems in fandom rooms.


### /commune

> Description: Sell a slice of your essence to the Kinkdom! You get 10 darkness - this command can be used once every 8 hours. 100 darkness makes one purple gem, which can be used in the store! especially important during events.


### /leaderboards

> Description: Shows who is currently leading in the challenge scoreboards! Features both a regular and extended leaderboard, for those of you who are in it to win it. (You can now play the Rocky theme song.)


### /attune

> Description: Will attune you to our soul collector. In simpler terms, you'll have a random chance of being dropped a soul fragment, which you can use to purchase card packs and more! Note: Your soul won't be collected. Probably.


### /help

> Description: Sends you a list of all of Arita bot's commands... So like, all of the commands in this tutorial. Shocking.


---

## Store & Item Commands

A list of aaaall the commands that you can use for buying, accessing, searching, and even trading items and/or cards! Nifty. Nefarious? Nefariously nifty.


### /status

> Description: The bread-and-butter command when it comes to whatchu got.

It can be used in different ways:

> `/status`: If used by itself, this will show you your Kinkdom passport, a quick look at everything you have.

> `/status items`: You'll see a detailed list of your items. Contains item names and item codes, which are important for searching items up to know what they do!

> `/status cards`: Arita Bot will send you a DM containing all of your cards, in the order they were acquired.

> `/status cards sort <sorting>`: Allows you to sort your card.

`<sorting>`:

1. `alphabetical`: Sort list in alphabetical order.
2. `number`: Sort list in the order they were numbered.
3. `multiples`: Sort list in descending order of how many you own of one card.
4. `rarity`: Sort list in the order of rarity. (special > 1 star > 2 star > 3 star > 4 star > 5 star)

For example: `/status cards sort alphabetical`.

> `/status cards compare @person`: Used to compare your card deck against someone else's. Competitiveness? In MY card collecting game? Yessum!


### /search \<code\>

> Description: You can use this command to search for two things: cards and items. You'll need the item or card code for each of these, e.g. lc (Lewd Crate item code), or lcarab (Arita Bot card code).

For example: `/search items lc` or `/search cards lcarab`.


### /store

> Description: Doing this will... wait for it... show you the Kinkdom's store! You'll see the prices of items, their names, and their item codes. Ignore suspiciously hooded, short merchants - they're not scamming you. Trust.


### /trade

> Description: Use this command to trade cards with another user. Very, very useful if you don't want to `/burn` your cards. This command will ask the target person for permission. Got multiples? Cards you don't want? Poke around in `#card_marketplace` and see who might be up for trading!

For example: `/trade yourCard theirCard @theirName`


### /use

> Description: This is a pretty easy to understand command, thankfully; use it with an item code to use said item, e.g. /use lc.


### /burn \<cardCode\>

> Description: Use this command to burn a card you don't want. Doing so will give you some soul fragments, depending on the rarity of the card! You can use soul fragments to purchase some things in the store.

For example: `/burn tato`

Note: Some special cards cannot be burned.


---

## Rented Rooms

A list of the commands you can use for your Rented Room. Aside from `/rent`, which is done in `#bot_commands`, all of these commands should be used in the room itself or they won't work.


### /rent \<roomName\> \<days\>

> Description: Use this command in `#bot_commands` to rent a room. It costs 5 gems a day, meaning 250+ words a day will keep the tax collector away. Remember kids, Al Capone went down for tax evasion! Don't be like him.

For example: `/rent Bork 5` will create a room called Bork for you, and rent it for 5 days.


### /reset

> Description: This command is one you've seen used by staff in public rooms before, in all likelihood; it posts a reset command in the channel.

For example: ...You really don't need an example for this :wat:.


### /rraddmember @user

> Description: The owner of a rented can use this command to add any member to the room. 

For example: `/rraddmember @tato`.


### /rraddtime \<days\>

> Description: Room running out of time? Add more days to it with this command. 5 gems per day! Only the room owner can use this command. Others who wish to add time to a room should buy keycards from the store.

For example: `/rraddtime 5`.


### /rrname \<roomName\>

> Description: Fancy changing the name of your room? Use this command.

For example: `/rrname bork`.


### /rrsetchannel \<mode\>

> Description: This command allows you to set the channel to one of the available modes (listed below).

`<mode>`:

1. `private`: Only you, staff, and the people you add with `/rraddmember` can see the room.
2. `public`: Everyone can see AND write in the channel.
3. `readonly`: The room can be seen by everyone, but only you and people you add can write in it.
4. `dark`: Only people with the `Dark` role can see your room.
5. `nonhuman`: Only people with the `NH` role can see your room.
6. `kink`: Only people with the `Kink` role can see your room.
7. `fandom`: Only people with the `Fandom` role can see your room.

For example: `/rrsetchannel private`.

Note: You can only have one mode on at the same time.


### /rrsettopic \<roomTopic\>

> Description: This will set the topic of your channel.

For example: `/rrsettopic Awooing Is Banned, Only Borks Here.`

Note: No matter what, the amount of days left in your room will always show at the end of the topic. A safety measure! It's for your own good.


---

## Miscellaneous Commands

### /premium

> Description: Whatever will this do?! Supposedly, this command will unlock Kinkdom Premium, the VIP experience where Revvy fans you with a giant leaf and Arita feeds you grapes. A world of luxury, decadence, and bohemian dreams awaits you!


### /arita

> Description: An innocent command! :wat: Nothing to see here, citizen. Move along.


---

And that's it! For now, this is the extent of Arita's Bot mighty beeping. As she's a project that's constantly evolving and growing, this guide will probably be expanded on in the future.
