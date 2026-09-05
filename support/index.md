# Pickify Support

Pickify is a private, offline randomizer for iPhone: dice, a coin, cards, a prize
wheel, roulette, straws, and a dozen other ways to pick a name or settle a
decision. It has no account, no server, and makes no network requests.

## Contact

The fastest way to reach us is email:

**pickify.app.support@gmail.com**

We aim to reply within 2–3 business days. To help us help you faster, please
include:

- your iPhone model and iOS version (**Settings → General → About**)
- the Pickify version, shown at the bottom of the app's settings
- which mode you were in (Dice, Wheel, Case Opening, and so on)
- what you expected to happen, and what happened instead

## Frequently asked questions

### I paid for Premium but my features are locked

Open Pickify's settings and tap **Restore Purchase**. Pickify Premium is a
one-time purchase tied to your Apple Account, so it restores on any device signed
in with the same account, at no extra cost.

If restoring does not work, make sure you are signed into the App Store with the
same Apple Account you used to buy, then email us.

### What does Pickify Premium include?

A single one-time payment — no subscription — that unlocks:

- **Premium themes** — the full set of skins for every mode
- **Unlimited spins** — pick as many times as you like
- **Exclusive modes** — special modes and content
- **Ad-free** — though Pickify has never shown an advert to anyone

There are no monthly fees and no hidden charges. If a free trial is offered, you
can cancel any time before it ends and you will not be charged.

### How do I get a refund?

Purchases are handled entirely by Apple, so we cannot issue refunds ourselves.
Request one at [reportaproblem.apple.com](https://reportaproblem.apple.com).

### Is Pickify private?

Yes. Pickify has no server, no analytics, no ads, and no third-party SDKs. It
makes no network requests at all. Your lists, settings, and unlocked prizes stay
on your device, and there is no sign-in and no cloud. See the
[Privacy Policy](../privacy/) for full detail.

### Is Pickify suitable for children and classrooms?

That is who it is drawn for. It is rated 4+, contains no chat, no sharing, no
social features, and no advertising. The roulette mode is a randomizer with no
wagering, betting, or currency of any kind.

## Picking and fairness

### Are the results really random?

Yes. Every outcome is drawn first from the system random number generator, and
the animation is then solved to land on it — the tumble is presentation, not the
source of the result. That keeps the distribution provably uniform instead of
making it a property of a physics solver.

Two modes are the deliberate exception: **Escape** (the draining ring of marbles)
and **Knockout** (the ball loose in the box of blocks) are played out rather than
drawn, and the winner is read off the simulation. Their fairness is therefore
measured rather than stated — thousands of simulated rounds at every player count
come out flat to within sampling noise.

### Does tapping a particular card change what I get?

No. In **Select Card** the options are shuffled into the face-down cards when
they are dealt, before anything is touched, so tapping the corner card every time
and pressing **Pick for me** are exactly as fair as each other. Every card back
is drawn identically for the same reason. Once the winner is up, the losing cards
turn over too, so you can see the shuffle rather than take it on trust.

### Why does the same name keep winning?

Because that is what random looks like over a handful of picks. Nothing in
Pickify avoids or favours a previous winner, and no mode remembers who won last
time when making the next draw.

### Why does the card mode never repeat a card?

It deals without replacement from a shuffled 52-card deck, so repeated draws
behave like real cards. Start a new round to reshuffle.

### Where did my results history go?

The list of recent results inside a mode is held in memory for the current
session only. It is deliberately never saved, so it is gone when you close the
app. Your typed lists, by contrast, are saved per mode and come back.

### I typed names into one mode and they are not in another

That is intentional. Each list-driven mode keeps its own list, because the names
on the wheel are usually a lunch menu and the ones in the bowl are usually a
class list. Save a list as a favourite if you want to reuse it elsewhere.

## Prize cases

### How do cases work?

Open the **Case Opening** mode and open a case. It lands on one of four tiers,
and each paying tier hands over something from your collection:

- **Legendary** — a mode skin
- **Epic** — a celebration effect
- **Rare** — a win sound
- **Uncommon** — no prize

Cases cannot be bought. There is no currency of any kind in the app, nothing is
wagered, and nothing can be lost. Your very first case on a fresh install is a
guaranteed Legendary.

### Can I get the same prize twice?

No. A case only ever hands over something you do not already have, so no opening
is spent on a duplicate.

### What happens once I have collected everything in a tier?

That tier's odds are paid forward. A finished Rare cabinet pushes a slice of its
share up to Epic, a finished Epic pushes a slice up to Legendary, and if both are
finished, Rare's slice jumps straight to Legendary. The slice is paid again for
every further case that lands on the finished tier, so a run of prize-less
landings is still buying you a better chance at what you can still win. No tier
ever gives away more than half of its own share — a tier that can no longer be
landed on has stopped being part of the game.

You can see the live table at any time with the odds button in the Case Opening
screen.

### Where do I see and equip what I have won?

Skins are equipped from the skin picker inside each mode. Celebrations and win
sounds are chosen in Pickify's settings, and their galleries show what you have
won and what is still locked.

### I reinstalled the app and my prizes are gone

Unlocked prizes are stored on your device only — there is no account and no
iCloud sync — so deleting the app removes them. Premium itself is tied to your
Apple Account and comes back with **Restore Purchase**.

## Settings and accessibility

### How do I turn off sounds, confetti, or vibration?

All three are switches in Pickify's settings: **Sounds**, **Confetti**, and
**Haptics**. Turning sounds off silences the app entirely, including win sounds.

### The animations are too fast, or too slow

Settings has an **Animation speed** control, and a switch to turn result
animations off altogether if you would rather go straight to the answer. Pickify
also honours the system **Reduce Motion** setting.

### How do I change the language?

Pickify has its own language picker in settings, with 32 languages, and it is
independent of your device language — so a child can use the app in one language
on a phone set to another. Right-to-left languages lay the whole app out
right-to-left.

### Shake to roll is not working

Shake-to-reveal uses the system shake gesture, which needs a reasonably brisk
shake. If nothing happens, check that the mode you are in supports it and that
you are not in a mode that waits for a tap instead.

### The finger picker does not see all my fingers

Put every finger down and hold still for a moment: the picker waits until the set
of fingers stops changing before it draws. Adding or lifting a finger while the
gold highlight is walking restarts the draw with the new set. It reads only where
fingers touch the glass — Pickify does not use the camera and does not read your
contacts.

## Bugs and feature requests

Please email **pickify.app.support@gmail.com**. Bug reports with the details
listed under [Contact](#contact) above are the most useful, and feature requests
are genuinely read.

## Privacy Policy

[Read the Privacy Policy](../privacy/)
