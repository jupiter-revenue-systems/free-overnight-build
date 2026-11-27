# RUN CHECKLIST

Do these in order before bed. It takes about 15 minutes the first time.

## 1. Make a working copy

Never run overnight work on your only copy. In Terminal, go to the folder that holds your project and run this with your own folder name:

```
cp -R [my-project] [my-project]-overnight
cd [my-project]-overnight
```

- [ ] The copy exists
- [ ] My original folder is untouched

## 2. Put the 3 files in the copy

- [ ] `MASTER_PROMPT.md`
- [ ] `MORNING_REPORT.md`
- [ ] `RUN_CHECKLIST.md` (this file)

## 3. Start Claude Code

In the copy folder, run:

```
claude
```

- [ ] Claude Code opened in the copy folder, not the original

## 4. Give it the job

Paste this:

```
Read MASTER_PROMPT.md and follow it exactly. Start now. Don't ask me questions. I'm going to sleep.
```

## 5. Watch the first 10 minutes

Claude Code asks permission before it does certain things.

- [ ] I said yes to reading and editing files inside this folder
- [ ] I said no to anything outside this folder
- [ ] I said no to anything that sends, publishes or spends
- [ ] It finished task 1 and wrote a line in `RUN_LOG.md`
- [ ] It's working without asking me anything

If it keeps stopping to ask, the master prompt has a gap. Answer the question, add the answer to `MASTER_PROMPT.md`, and let it continue.

## 6. Keep the computer awake

- [ ] Plugged in to power
- [ ] Set to stay awake tonight. On a Mac, open a second Terminal window and run:

```
caffeinate -i
```

Leave that window open. Close it in the morning.

- [ ] Screen dimmed. Lid open if it's a laptop.

## 7. Go to bed

## In the morning

1. Open `MORNING_REPORT.md` first.
2. Run the second check at the bottom of the report with a fresh agent.
3. Review the work. Nothing leaves the copy folder until you've looked at it.
4. You decide what goes live. Publishing is your click.
