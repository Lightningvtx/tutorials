# How to get your Riot cookies

This bot accepts only cookies so your login information is not used and or stored by the bot at all, however be advised cookies **ARE** stored.

**DO NOT SHARE YOUR COOKIES WITH ANYONE**  your cookies can still be used to log into your account just like your password, both in-game and on the website, and in some ways they are less secure because they bypass [2FA](https://www.riotgames.com/en/news/multi-factor-authentication-has-arrived).

This guide uses Chrome, but opera and any other browser except for firefox will work, because firefox doesn't show your whole cookie if it's too long.

  1. Go to [account.riotgames.com](https://account.riotgames.com) and log in, make sure that you have checked the _Remember me_ option when you are logging in, otherwise it will log you out of the bot after 24 hours
  2. Press `F12` (or `Ctrl+Shift+I`/`⌥⌘I`) to open devtools, head to the `Network` tab on the top right
  3. With the Network tab open, open the following link on the same tab `https://auth.riotgames.com/`\
       **Note:** You will see a page saying "*An error occured!*" That is normal, ignore it.
  4. A new network request will appear called `auth.riotgames.com` in the Network tab, click on it

<img width="1155" height="740" alt="part 1 + 3" src="https://github.com/user-attachments/assets/04e656a0-6fa4-4845-8c71-fa8b1e4dc62d" />

  5. in that window that appeared, scroll down to the `Request Headers` section

<img width="1248" height="534" alt="image" src="https://github.com/user-attachments/assets/f9f0dc07-4993-4949-94c6-7f1d0d4be8f9" />

  6. copy that cookie and paste it into the `cookies` section of the `/cookies` command

# Common errors when logging in via cookies

## `You can't find the cookie inside DevTools (F12 / Ctrl+Shift+I / ⌥⌘I )`
Make sure you are logged in on account.riotgames.com, press `F12` on that page, and change the page link to `auth.riotgames.com` **without** opening a new tab.

## `There was an error trying to do that! I blame Riot, they fucked with the api somehow. undefined`
Reload the auth.riotgames.com page and copy the cookie again.\
Sometimes the cookie is either longer or shorter than it’s supposed to be.

