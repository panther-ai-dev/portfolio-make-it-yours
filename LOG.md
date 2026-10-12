# Build log: "Make it yours" (prompts 2 and 3 for YT #4)

Starting point: a copy of `builds/website-10min/` (index.html, style.css, script.js), i.e. the output of prompt 1.
Persona: **Panther AI Dev** (the channel itself), chosen 2026-10-11. No college line; projects are the channel's real builds.
Builder: Claude Code (Opus 5.5), run 2026-10-11 in the planning session. No manual edits.

## Prompt 2 (as run)
> Placeholder content hatao aur meri asli details daalo: naam Panther AI Dev, tagline "Hunting boring code with AI", about = channel description, skills: Claude Code, prompt writing, HTML, CSS, JavaScript, [2 video tools, names removed], Playwright testing; 3 projects: ye 2-minute portfolio site, "5 ways to use Claude Code" video, AI Build Diaries reel series. Design mat badalna.

Result:
- Name, logo, title, hero line, about, skills, 3 project cards and footer replaced. "Hire me" became "Say hi".
- 0 leftover placeholder words (checked for Riya / Pune / Chai / Campus / Weather).
- Design unchanged: no CSS edits in this step.
- Check: desktop 1440 px + phone 390 px, no console errors, no horizontal scroll, mobile menu opens.
- Evidence: screenshots removed (see the 2026-10-12 note below)

## Prompt 3 (as run)
> Contact form hatao, aur uski jagah mere Instagram ka button lagao: instagram.com/panther_ai_dev

Result:
- Form, its JS handler and its CSS removed. Contact now has one line + an Instagram button (opens in new tab).
- Check: same as above, no errors, no horizontal scroll, menu works.
- Evidence: `shots/after-prompt3-*.png`

## Honest notes (what the video must say or avoid)
- **Prompt 3 differs from the script.** The script and description say "email, LinkedIn aur GitHub buttons". The persona only has a confirmed Instagram (`youtube.com/@panther_ai_dev` returned 404 on 2026-10-11; no email/LinkedIn/GitHub on file). So only one button exists. Script updated 2026-10-11 to match: Instagram button, with email/LinkedIn/GitHub as optional.
- **Project cards have no GitHub links.** Script updated 2026-10-11: prompt 2 now asks for "3 asli projects" without GitHub links.
- **Don't quote times for these two prompts.** They were applied in a session that already had the files open, so they are not a fair "one prompt from cold" timing like the 2:10 run.
- **No screen recording was made.** For beats 6 and 7, re-run both prompts in your own Claude Code on a fresh copy of `website-10min/` and record the screen. The results should look like the screenshots here.
- Still not deployed. Opened as a local file only.

## Edit after the build (2026-10-12)
- Two video-tool names removed by hand from the skills list, the "5 ways" project card and the prompt text. Screenshots of the final state retaken (`shots/after-prompt3-*.png`); prompt-2 screenshots deleted because that state can't be reproduced. Re-check: 390 px phone, no horizontal scroll, no JS errors.
