# Sorry Notebook ✏️💗

A hand-drawn notebook page that walks her through your apology, one page at a time:

1. **Hello**: a sad doodle of you holding your heart, under a little rain cloud.
2. **The letter**: she taps the envelope, it opens, and your apology writes itself out.
3. **Will you forgive me?** Every "No" scribbles out the sticky note and asks a new question (10 in total), while the doodle of you begs harder and the heart cracks more. After question 10, the No button runs away. "Yes" sets off confetti, and the doodle cheers while the heart stitches itself back together.
4. **Pick your sorry coupon**: she picks one, it gets stamped "REDEEMED ✓", and it ends with "Friends forever 💖".

## 1. Personalize it

Open `index.html` and edit the `CONFIG` block at the top of the `<script>`:

- `name`: her name or nickname
- `fromName`: your name
- `message`: your apology, one line per item
- `questions`: the 10 follow-up questions she sees each time she says No
- `coupons`, `finalTitle`, `finalSub`, `yesText`: change anything you like

## 2. Get notifications on your phone

1. Install the **ntfy** app ([Android](https://play.google.com/store/apps/details?id=io.heckel.ntfy) / [iPhone](https://apps.apple.com/app/ntfy/id1625396347)).
2. Subscribe to the topic in `CONFIG.ntfyTopic` (`sorry-bear-1586310f3949` right now), or watch it at https://ntfy.sh/sorry-bear-1586310f3949
3. You'll get alerts like "✉️ opened your letter", "🙅 Said NO to Q3: …", "💖 said YES! (after saying NO 4 times)" and "🎟️ picked a coupon: 🥟 A plate of momos".

Anyone who knows the topic name can read it, so keep it private. Set `ntfyTopic: ""` to turn alerts off, and `showTrackingNote: false` to hide the "this notebook tells … what you click" line.

## 3. Share it

Host the folder for free and send her the link. The easiest way is to drag the `3dpage` folder onto https://app.netlify.com/drop. GitHub Pages or Vercel also work.
