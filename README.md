# autoLinkedIn

A simple, imperfect-but-working robot for applying to jobs on LinkedIn. It uses the Selenium-based freemium tool [UI.vision](https://UI.vision) and leverages only free features of the tool.

I haven't ported it to Selenium yet myself, as I haven't really had the need. Doing so should be easy enough however, and would offer finer-grain control.

Why? 
  - A great power imbalance between employers and employees.
  - Average duration of job searches have been getting longer for many years and are absurdly high.
  - Generative AI (while awesome and creating economic growth in many areas) is displacing a huge number of workers.
  - Government largely closes off its job opportunities to the public whilst giving its privileged few benefits and perks far beyond those enjoyed by the taxpayers who fund them.
  - HR and collusive, slow-hiring employers greatly exacerbating the problems.
  - If you follow the advice of taking your time to carefully apply for a small number of jobs, either you'll starve to death before that actually leads to employment or you've got some significant unfair advantage that makes this irrelevant to you.
  - Inflation and economic turmoil.
  - Job seeker resources have fallen off sharply post-pandemic.
  - Tech workers have been suffering mass layoffs.
  - Ubiqitous use of "zombie" job listings.

So, this is a little tool to help reduce the applicants burden. 

## Usage

  1. Login to LinkedIn.
  2. Make sure you have a saved resume available and at least basic info saved (phone number for employers, email, etc).
  3. Add UI.vision's extension to your browser (FireFox, Edge, or... if you must... Chrome).
  4. Create a new, empty macro and paste in the code from the combined script (ui_vision_code.json).
  5. Replace my default search terms with yours. 
  6. Play Macro!

I made it search for remote jobs only by default, but feel free to delete or change that part to your taste. Be careful about encouraging employers to make us work in person like animals if it's not warranted. What can we do in person that we can't do virtually? So we can smell each other or physically harass one another? To make sure we spend more time on the road that could've been put to productive use?

Many of LinkedIn's so-called "Easy Apply" jobs are actually pretty far from just a couple of clicks, so it will hit errors often, but that's not necessarily a problem. Just the limited functionality of the UI.vision tool makes errors nearly inevitable, but the script is written in a way that they shouldn't really matter. The trick is to keep the !TIMEOUT_WAIT variable in the sweet spot of just longer than an action should take. So, when it hits an error it moves on with things and gets back to working pretty quickly.

## Pro Tips

  - Works **far** better if you've applied to many jobs already and therefore have answers to common questions saved.
  - Doesn't work on many jobs, so check the log and finish applying to ones it missed.
  - If you have any trouble with the end-to-end script, try running steps 1 and 2 separately. Step 3 is only really useful when combined with the first 2 steps. 
  - This can be easily improved by handling more cases like drop-downs and radio buttons.
  - If you get a job this way, you'll probably want to give me a % of the pay. I take cryptocurrency. :)

## Risks 

Use this at your own risk. Possible risks:
  - Too many junk jobs creating noise in your search (high likelihood).
  - Get blocked or banned by LinkedIn (low or medium likelihood, mostly if you use it excessively and without human-like pauses).
  - May annoy employers and/or evil, secret bands of recruiters / HR who stalk applicants and manipulate the job market (medium likelihood). 
