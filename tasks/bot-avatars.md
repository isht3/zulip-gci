# GCI Tasks: Bot Avatars

## Prerequisites

* CLONE_GIT_REPO

## Background

Zulip allows users to create custom bots and integrations, and those bots
need avatars to help make the product more fun!  Zulip would like to provide
a library of cute custom avatars that users can choose from when creating
a new bot.  Our non-custom avatars look like https://chat.zulip.org/integrations/,
basically the logos of products that Zulip integrates with.

The avatars should look good at the 50x50px size at which the user avatars
are displayed in the Zulip web application.  Use your creativity!  For example,
an avatar for a bot for logging software could be designed based on either
its function or a pun around the word “logging”, e.g.:

* An image of a few lines of log text
* A pile of wooden logs
* A cute robot with all its limbs made of logs

## Task Descriptions

### Task Type A: Find bot avatars on the internet.

* Create the directory `gci/bot-avatars/<username>`, where <username> is
  your github username.

* Find a list of online repositories of cute bot images with a clear open source
  license, such as Creative Commons. Pick out 5-10 images from each that you think
  might be a good fit for a Zulip bot. Add the images to the directory above.

* Add a text file with links to the sources of the images.

* Add a commit with these files, with commit message "bot avatars: Add
  avatars from internet sources."

* Make a pull request to the `zulip/gci-submissions` repository, with title
  "Bot avatars A: Find avatars from internet sources."

### Task Type B: Design prototype avatars.

* Create the directory `gci/bot-avatars/<username>`, where <username> is
  your github username.

* Design 3-5 avatar images that fit together thematically (e.g. similar visual style),
  inspired by some of the potential bot use cases described below.  They should look
  good at 50x50px size. It’s OK for these to be quick prototypes; it makes sense
  to spend a lot of time making them really good once you’ve gotten feedback on which
  design directions others like. Add the images to the directory above.

* Add a commit with these files, with commit message "bot avatars: Add
  prototype avatars."

* Make a pull request to the `zulip/gci-submissions` repository, with title
  "Bot avatars B: Create prototype avatars."

### Task Type C: Refine avatars from prototypes.

* Create the directory `gci/bot-avatars/<username>`, where <username> is
  your github username.

* Refine one collection of avatar images that you or another contributor have
  contributed to the project and add touches to make it look really nice.  The goal
  here is to take a set of prototype avatars that you’ve gotten feedback on and
  then make it look really good so that we can include it in the project. Add the
  images to the directory above.

* Add a text file explaining the origin of the prototypes, with links to
  the files on github.

* Add a commit with these files, with commit message "bot avatars: Add refined
  avatars."

* Make a pull request to the `zulip/gci-submissions` repository, with title
  "Bot avatars C: Refine prototype avatars."

Please use either the .svg file format or create both a 50x50 and 300x300 pixel .png image.

## General notes

Do not submit images found on the Internet for Task Types B or C.

## Example Bots

Here is a non-inclusive list of bots for which we do not have avatars:

- build bot (used for notifications about software having been compiled)
- alert bot (used to send notifications about software system statuses and alerts, e.g. a server being down)
- rsvp bot (used to allow members of a chat group to RSVP for events proposed in chat)
- polling bot (allows chat members to create a poll, participate in a poll, and view results of the poll)
- analytics bot (shows analytics for the zulip instance or another chart provider; e.g. Google Analytics)
- travel/flights bot (e.g. a flight reminder!)
- commute/transit bot (e.g. for alerts about problems with the subway)
- motivation bot (bot that tells you you’re awesome when you’re feeling down)
- customer service or support bot (bot that hooks into your customer support system
  and allows you to respond to customer queries from Zulip directly)
- meeting follow-up bot (open to interpretation, e.g. a bot that follows up
  with participants of a meeting afterwards with notes or other deliverables from the meeting)
- reminder bot (a bot that you can ask to remind you to do something, and it will
  remind you after the time has passed.
  e.g.: lisa: reminderbot, remind me to pick up the groceries in 10 minutes.
  … <<10 minutes later>>
  reminderbot: lisa, pick up the groceries)
- +1 bot (bot that lets you give other chat members +1, and can tell you who’s got the most +1s in the chat)
- sales bot (bot that plugs into your Etsy/Squarespace/Shopfiy/Stripe/Square/etc
  eCommerce site or payments system and updates the chat every time an item is
  sold or refunded)
- revenue bot (bots that plug into your eCommerce site and updates the chat on
  revenues every day)
- error bot (bot that notifies you when users are getting errors when using a site/service that you run)
- Anything else that seems fun! Someone will find a good use for a potato bot icon.
