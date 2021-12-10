fetch(
  'https://discord.com/api/webhooks/918907146450661397/kYtQsvoo36maDX1jGHFhkz-CfRA0C0gc2mQVNmEjMm26gXmWmoZxgdEN8ei-YVTCfZ6r',
  {
    method: 'post',
    headers: {
      'Content-Type': 'application/json',
    },
    body: JSON.stringify({
      // the username to be displayed
      username: 'Rule Bot',
      // the avatar to be displayed
      avatar_url:
        'https://tse3.mm.bing.net/th?id=OIP.-VW_sjWcHJItqtXsckfaAAHaD_&pid=Api&P=0&w=302&h=163',
      // contents of the message to be sent
      content:
       
      // enable mentioning of individual users or roles, but not @everyone/@here
      allowed_mentions: {
        parse: ['users', 'roles'],
      },
      // embeds to be sent
      embeds: [
        {
          // decimal number colour of the side of the embed
          color: 11730954,
          // author
          // - icon next to text at top (text is a link)
          author: {
            name: 'DESTINY IS LIVE',
            url: 'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
            icon_url: 'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
          },
          // embed title
          // - link on 2nd row
          title: 'SERVER RULES',
          url:
            'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
          // thumbnail
          // - small image in top right corner.
          thumbnail: {
            url:
              'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
          },
          // embed description
          // - text on 3rd row
          description: 'FOLLOW THE RULES BELOW',
          // custom embed fields: bold title/name, normal content/value below title
          // - located below description, above image.
          fields: [
            {
              name: 'NO SPAM',
              value: 'Don't spam. (Spamming includes song lyrics, zalgo, excessive caps/reaction spams,
 copy pastes,  picture/link/GIF spam, reaction spam and walls of text)',
            },
            {
              name: 'NO NSFW',
              value: 'Don't post NSFW/Gore/18+ stuff in the channels. 
(Not only you shouldn't do this but, you also shouldn't have any NSFW/Gore-ish Pfps/Nickname/Usernames)',
            },
            {
              name: 'NO HARASSMENT',
              value: 'Don't post NSFW/Gore/18+ stuff in the channels. 
(Not only you shouldn't do this but, you also shouldn't have any NSFW/Gore-ish Pfps/Nickname/UsernamesDon't harass or insult any other members.
(This includes threats, internet attacks and cyber bullying. Other people have feelings too.)',
            },
            {
            name: 'DONOT AVADE PUNISHMENTS',
              value: 'Don't advertise other Discord servers or Youtube videos, unless if allowed by a Staff.
(Only advertise social media links in channels that allow advertisement. No discord links whatsoever.',
            },
            {
            name: 'NO IMPERSONATION',
              value: 'Don't impersonate anyone, like YouTubers or Staff.
(This includes copying avatars, nicknames, or just trolling to imitate an user)',
            },
            {
            name: 'NO ADVERTISING',
              value: 'Don't try to evade punishments or mutes.
(It won't work, trust me. Plus, you'll get instant-banned with no hesitation nor appeal.)',
            },
            {
            name: 'NO SWEARING OR ABUSING',
              value: 'Swearing is not allowed.
(If someone is going all out on personal insults, a tirade of swear words,, they will be punished.)',
            },
            {
            name: 'GENERAL CHAT',
              value: 'Don't go off topic in any of the channels. 
(Please keep within the designated topic of the channel.)',
            },
            {
            name: 'VOICE CHAT',
              value: 'Don't be an annoyance in voice channels. 
(This includes putting inappropriate songs unless the members won't disagree & earrape and shouting)',
            },
            {
            name: 'BAN / TEMP BAN / TEMP MUTE / TEMP BAN',
              value: 'We don't reveal the reason of any action taken',
            },
            {
            name: 'PERSONAL FIGHTS',
              value: 'This server is not at all responsible for your personal fights so pls don't complain to us regarding your own personal matters.',
            },
            {
            name: 'RESPECT EVERYONE ESPECIALLY GIRLS',
              value: 'Respect all the Girls if we found that you are doing any kind of Harassment in this server against Girls you will directly get banned from this server.',
            },
          ],
          // image
          // - picture below description(and fields)
          image: {
            url:
              'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
          },
          // footer
          // - icon next to text at bottom
          footer: {
            text: 'SINCEARLY FROM TEAM DESTINY IS LIVE',
            icon_url:
              'https://c.tenor.com/geMdtLCXZkAAAAAC/rules.gif',
          },
        },
      ],
    }),
  }
);
