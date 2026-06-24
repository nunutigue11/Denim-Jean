# Mr. Midwest — Copy Options (Cover Headline + Pull-Quote)

Pick one from each, mix lines across options, or use these as a starting point to write your own — the point is the *voice*, not these exact words.

## FINAL — locked in
**Cover headline:** "NOTHING WASTED. NOTHING RUSHED." (Option B)
**Pull-quote:** "WE DON'T MAKE NEW CLOTHING. WE MAKE NEW USE OF WHAT'S ALREADY HERE." (Option A)

Ready-to-paste HTML for both is in the "How to use these in Squarespace" section at the bottom.

---

## Cover headline (Section 01)

**Option A — plain and confident**
> MR. MIDWEST
> ISSUE 01 — THE MIDWEST ISSUE
>
> Subline: Handmade in the Midwest. One piece at a time.

**Option B — leans into the repair/material story**
> MR. MIDWEST
> NOTHING WASTED. NOTHING RUSHED.
>
> Subline: Custom denim. One-of-one garments. Missouri-made.

**Option C — leans into the place**
> MR. MIDWEST
> FROM MISSOURI. FOR ANYONE WHO'S BEEN OVERLOOKED.
>
> Subline: Alterations, custom denim, and one-of-one pieces made by hand.

---

## Pull-quote break (Section 06)

**Option A — about the materials**
> WE DON'T MAKE
> *NEW* CLOTHING.
> WE MAKE NEW USE
> OF WHAT'S ALREADY HERE.

**Option B — about the craft**
> EVERY STITCH
> IS A DECISION.
> *NOTHING HERE
> IS AUTOMATIC.*

**Option C — about scarcity / one-of-one**
> ONCE IT'S WORN,
> IT'S GONE.
> *WE DON'T MAKE
> ANYTHING TWICE.*

**Option D — about the Midwest identity**
> THE COASTS GET
> THE ATTENTION.
> *THE MIDWEST GETS
> THE WORK DONE.*

---

## How to use these in Squarespace
1. Add a Code Block in the relevant section.
2. For the headline, wrap it like:
   ```html
   <div class="mw-headline">
     WE DON'T MAKE<br>
     <span class="mw-italic">NEW</span> CLOTHING.<br>
     WE MAKE NEW USE<br>
     OF WHAT'S ALREADY HERE.
   </div>
   ```
3. For the masthead cover line, use `mw-masthead` and `mw-issue-tag` (already defined in `squarespace-injection.css`):
   ```html
   <div class="mw-masthead">MR. MIDWEST</div>
   <div class="mw-issue-tag">Issue 01 — The Midwest Issue</div>
   ```
