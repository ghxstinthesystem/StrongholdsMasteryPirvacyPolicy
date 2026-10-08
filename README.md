# Privacy Policy for Strongholds Mastery

**Effective Date:** 3 November 2023

**Last Updated:** 8 October 2026

This policy explains how the Strongholds Mastery Discord bot (in some servers
shown as "Stronghold Mastery") collects, uses and protects personal data, and
the rights you have over it. It is intended to meet the requirements of the UK
General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018.
Please read it together with our
[Terms of Service](https://github.com/ghxstinthesystem/StrongholdsMasteryToS/blob/main/README.md).

This policy covers the Strongholds Mastery bot only. Our other services,
including our paid radar service, have their own terms and privacy information.

## 1. Who We Are

Strongholds Mastery is operated by ▽ 𝕘𝕙𝕩𝕤𝕥 (Discord username:
ghxstinthesystem), an individual based in the United Kingdom, who is the
**data controller** for the personal data described in this policy ("we",
"us", "our").

Contact: **StrongholdsSupport@shkbot.com**, the support server
(https://discord.gg/5eHFZybr6n), or the operator on Discord (username:
ghxstinthesystem).

## 2. Information We Collect

### Discord data

- **Discord user IDs, usernames and display names**, only where a feature
  records them:
  - war parties (leader and members, with their display names and roles);
  - your language preference (your user ID only);
  - the moderation audit log (who performed an action, its target, the reason
    and the time);
  - player notes (who wrote each note);
  - shared lists such as the sworded and auto-ID lists (who submitted an entry);
  - card-tracker sessions (who created the session).
- **Server, channel, role and message IDs** for each server's configuration
  (for example welcome, ban-alert, log, vacation and mirror channels,
  self-roles, alliance boards and war-party channels).
- **Text that server members or administrators enter** through the bot's
  commands, such as notes, announcements, welcome messages, moderation reasons
  and alliance-board entries.

### Stronghold Kingdoms data

The bot works with **in-game player names**. These are Stronghold Kingdoms
identities, not Discord accounts, but they can still identify a player.

- **Ban tracking:** in-game names, whether the account appears to be banned,
  the date a ban was first detected, and similar status fields. Names are added
  when someone uses `/check`, and also from our own radar service, which shares
  with this bot the in-game names (with a "last seen" date) that appear in the
  game's public world data. Tracked names are checked regularly against the
  game's public player-name search.
- **Hall of Heroes data:** player names, worlds and rankings from the game's
  public Hall of Heroes pages, refreshed automatically, used by `/whois` and
  related commands.
- **Feature entries:** vacation records (in-game name, server, year, status,
  end date and number of vacations used), player notes, peace, sworded and
  auto-ID lists, alliance boards and card-tracker statistics.

### Other

- **Service logs:** the bot's server keeps technical logs to run and fix the
  bot. They can include Discord usernames, IDs and command names.
- **Donations:** if you donate, PayPal shares with us the information it
  normally gives payment recipients, usually your name, email address, the
  amount and the date (see section 7).
- **Support and data requests:** what you send us and how we can reply to you.

### Where the data comes from

Data comes from you and your server's administrators when you use the bot,
from Discord when the bot is in your server, from the game's public Hall of
Heroes and player-name search, and from our radar service as described above.
**Other people can enter your in-game name, a note about you, or a list entry
about you**, and the bot may track your in-game name even if you have never
used it. You have the same rights over that data as anyone else (see section 9).

## 3. What We Do NOT Collect

- **Ordinary message content.** The bot does not have Discord's Message Content
  intent, so Discord does not show it the text of ordinary messages. Discord
  still shows any bot the text of messages that mention it. The only feature
  that uses message text is translation mirroring (section 5). It does not
  store that text.
- **Presence data.** The bot does not request the Presence intent and does not
  track online status or activities.
- **Payment card or bank details.** Donations are processed entirely by PayPal.

The bot uses Discord's Server Members intent to post welcome messages when a
member joins and to show current member names in command output. Member data
received this way is only stored where a feature listed in section 2 needs it.

We never sell personal data. We do not use it for advertising. We do not make
automated decisions about you that have legal or similarly significant effects.

## 4. How We Use Information and Our Lawful Basis

| Purpose | Data | Lawful basis (UK GDPR Art. 6) |
| --- | --- | --- |
| Running the bot's features (war parties, vacation tracking, notes, lists, alliance boards, card tracker, welcome messages, self-roles, language preference, translation mirroring) | Discord IDs and names, server configuration, in-game names and entries | **Legitimate interests**: providing the features you and your server chose to use |
| Ban tracking, ban alerts and player lookups | In-game names and status, Hall of Heroes data | **Legitimate interests**: helping Stronghold Kingdoms communities see whether a player is still active or banned, using information the game already publishes |
| Moderation tools and the audit log set up by server administrators | Discord IDs and names, moderation entries | **Legitimate interests**: helping servers keep their communities safe |
| Security, preventing abuse and enforcing our Terms | Discord IDs, server IDs, service logs | **Legitimate interests**: protecting the bot and its users |
| Responding to support, data-rights and legal requests | Your contact details and your request | **Legitimate interests**, and **legal obligation** where data protection law requires us to respond |
| Recording and thanking donors | Information PayPal shares with us | **Legitimate interests**: keeping accurate records of money received |
| Complying with the law or lawful requests from authorities | Any relevant data | **Legal obligation** |

Where we rely on legitimate interests, we have weighed your interests and
rights against ours. We believe the processing is limited, expected and
low-risk. You can object at any time (see section 9).

## 5. Sharing of Information

We do not sell personal data. We share it only:

- **With our hosting provider**, Hetzner Online GmbH. Hetzner stores the bot's
  data on servers in Germany and acts only on our instructions, as a data
  processor.
- **With Discord**, because the bot runs on Discord's platform. Discord is an
  independent controller of the data it holds; see
  [Discord's Privacy Policy](https://discord.com/privacy).
- **With the game's public services**, when the bot looks up in-game names on
  the official Stronghold Kingdoms website (player-name search and Hall of
  Heroes).
- **With StrongholdInfo** (api.strongholdinfo.com), an independent Stronghold
  Kingdoms statistics service. When you use `/activity` or `/activity_house`,
  the player or house name you enter is sent to it.
- **With MyMemory** (api.mymemory.translated.net, operated by Translated srl,
  Italy). If a server administrator sets up translation mirroring, the text of
  messages the bot can read in a mirrored channel is sent to MyMemory for
  translation. The translation is reposted in the mirror channel under the
  author's display name and avatar.
- **With PayPal**, if you donate. PayPal is an independent controller of
  payment data; see
  [PayPal's Privacy Statement](https://www.paypal.com/uk/legalhub/paypal/privacy-full).
- **With our email provider**, to receive and answer emails you send us.
- **Where the law requires it**, or to protect the rights, safety or security
  of our users, the bot or others.
- **With your consent**, or at your direction.

## 6. International Transfers

The bot's data is stored in Germany, in the European Economic Area. The UK
recognises the EEA as giving adequate protection for personal data, so no
extra safeguards are needed for this transfer. Translation requests go to
MyMemory in Italy, which is also in the EEA. Discord, PayPal and StrongholdInfo
may process data in other countries, including the United States, under their
own policies.

## 7. Donations

Donations are made through PayPal. We never see your card or bank details.
PayPal gives us the information it normally shares with payment recipients,
usually your name, email address, the amount and the date. We use it only to
keep a record of donations, to thank you, and to reply if you contact us about
your donation. We keep donation records for as long as we need them for our
records and any legal obligations, and we do not add donors to any mailing
list.

## 8. Data Retention and Deletion

| Data | How long we keep it |
| --- | --- |
| Feature data (war parties, vacation records, notes, lists, alliance boards, card tracker, preferences, server configuration) | Until a user or server administrator removes it, or until you ask us to delete it. Vacation records are kept by year, including ended vacations, so that the yearly count works. Notes are limited to the latest 20 per player per server. |
| Moderation audit log | The most recent 200 entries per server. Older entries are deleted automatically. |
| Ban-tracking records | While the name is being tracked. A name confirmed as banned is deleted automatically 60 days after the ban was first detected. To stop a removed name from being added again automatically, we keep that name and its removal date. |
| Hall of Heroes data | Replaced as the public leaderboards are refreshed. |
| Data about a server the bot has left | The bot does not currently delete this automatically. We delete it on request from the server's owner or an administrator. |
| Service logs | Rotated automatically by the server's logging system. |
| Backups | Our hosting provider keeps rolling backups of the server for a short period. Deleted data disappears from them as they are replaced. |
| Support and data-rights correspondence | As long as needed to deal with the request and keep a record of how it was handled. |

## 9. Your Rights

Under UK data protection law you have the right to:

- **Access** the personal data we hold about you and receive a copy.
- **Rectification**: have inaccurate data corrected.
- **Erasure**: have your data deleted.
- **Restriction**: ask us to limit how we use your data.
- **Object** to processing based on legitimate interests. This includes ban
  tracking of your in-game name, and names, notes or list entries that others
  have entered about you.
- **Data portability**: receive data you provided in a structured,
  machine-readable format, where this applies.

These rights have some legal conditions and exceptions. For example, we may
keep a record needed to prevent abuse. To make a request, email
**StrongholdsSupport@shkbot.com** or contact us through the support server.
If your request concerns an in-game name, tell us the name and world. We may
need to confirm your identity, for example by asking you to message us from
the Discord account concerned, or to show that you control the in-game
account. We will reply within **one month** and tell you if we need longer, as
the law allows. Requests are free unless they are manifestly unfounded or
excessive.

### Complaints

If you are unhappy with how we handle your data, please contact us first so we
can try to put it right. You also have the right to complain to the UK
Information Commissioner's Office (ICO) at
https://ico.org.uk/make-a-complaint/data-protection-complaints/ or on
0303 123 1113.

## 10. Children

The bot is not directed at children under 13. Discord requires users to be at
least 13, or older where local law requires. If you believe the bot holds data
about a child under 13, contact us and we will delete it.

## 11. Data Security

The bot's database and files are encrypted at rest on the hosting server.
Only the operator can access the server, and only by key-based login. No
method of transmission over the internet or of electronic storage is
completely secure. If a personal data breach occurs that is likely to put your
rights at risk, we will notify the ICO within the legal time limit and, where
required, the people affected.

## 12. Server Administrators

If you add the bot to a server, please tell your members it is in use and
point them to this policy, especially if you use player notes, ban alerts,
moderation logs or translation mirroring.

## 13. Changes to This Policy

We may update this policy from time to time. We will announce material changes
in the support server and change the "Last Updated" date above. The latest
version is always published at this location.

## 14. Contact Us

For questions about this policy or to exercise your rights, email
**StrongholdsSupport@shkbot.com**, join the support server
(https://discord.gg/5eHFZybr6n), or contact the operator on Discord (username:
ghxstinthesystem).
