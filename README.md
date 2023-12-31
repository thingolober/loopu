# loopu

Forked from https://github.com/ajcoppa/allday

loopu is a TypeScript and grimoire-based script for automating a full day of Kingdom of Loathing Community Service looping. This includes farming, ascending into Community Service, completing the run, then farming some more.

loopu uses [InstantSCCS](https://github.com/Pantocyclus/InstantSCCS), which automates the Community Service run itself, handling a wide variety of player states but particularly catering to low-shiny players. It also makes use of [garbo](https://github.com/Loathing-Associates-Scripting-Society/garbage-collector) for meat-farming.

**Warning:** Although loopu does a few small things to allow customization and handle various character states, they are fairly limited. **It will likely not be optimal for you**, especially if your account state is significantly beyond the minimum requirements of InstantSCCS.

# Development

```bash
npm run build
```

Then you can automatically create symlinks to your built files by running

```bash
npm run move
```

When you're developing you can have your files automatically rebuild by keeping

```bash
npm run dev
```

running in the background. If you've already built symlinks, your up-to-date script can be run instantly by entering `loopu` into the KoLmafia CLI.
