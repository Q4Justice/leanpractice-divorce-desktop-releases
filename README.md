# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 4.0.0

Released November 23, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_4.0.0_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v4.0.0/LeanPractice.Divorce_4.0.0_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_4.0.0_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v4.0.0/LeanPractice.Divorce_4.0.0_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_4.0.0_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v4.0.0/LeanPractice.Divorce_4.0.0_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 4.0.0

- The income tax estimate now counts the child and dependent care credit for the child care the IRS custodial parent
  pays on Child support, and the refundable credits: the refundable part of the child tax credit and the earned income
  credit. A lower-income parent's estimate can then be a refund, shown as a negative amount with "refund" beside it,
  which raises net income for child support and alimony. "Count refundable credits" on Taxes leaves the refundable ones
  out for a case. The tax worksheet shows each credit on its own row with how it is worked out, and Child support, the
  financial affidavit and the child support guidelines worksheet say when a figure is a refund. These come with the new
  calculations (version 2026.15); a saved case keeps its figures until you review and apply them.
- New calculations (version 2026.15): when nobody is chosen to claim a child in Child tax benefits, the income tax
  estimate now counts that child's child tax credit, or the $500 credit for other dependents, for the parent with more
  overnights, the IRS custodial parent, as federal law does when no Form 8332 is signed. The earlier calculations
  counted it for nobody. Child support's income tax line, Child tax benefits, the tax worksheet and the financial affidavit's
  dependents line say so. The agreement paragraph, Child tax benefits' choices and deviation factor 8 still treat the
  child as not chosen. Saved cases show "Newer calculations are available" and keep their figures until you review and
  apply them; the estimate is lower for the custodial parent, and child support changes only where a parent's income
  tax line is the estimate.
- Overnights can be typed in half nights on Child support: 182.5 and 182.5 for an even split. The child support
  worksheet then uses 50% each, and Form 12.902(e) prints 182.5. Counts from the parenting plan stay whole nights.
- At equal overnights, the IRS custodial parent is now the parent with the higher adjusted gross income, as federal
  law provides, instead of the first party; in a leap-year calendar count, 183 nights each of 366 count as equal.
  Head of household, the child tax credit for a child nobody is chosen to claim, and who signs Form 8332 follow it.
  Child tax benefits explains who the custodial parent is and why when the overnights are equal or within a week.
  These come with the new calculations (version 2026.15).
- Income that isn't taxed can be entered for what it is. On Income and expenses, disability benefits, pension,
  interest and dividends, and other income each have "By kind": VA disability compensation, Social Security
  disability, benefits from a disability policy the person paid for, a VA pension, other VA benefits such as
  dependency and indemnity compensation, and tax-exempt interest. Each kind says how it is taxed, and the income tax
  estimate follows: VA benefits, a policy the person paid for and tax-exempt interest aren't taxed, and Social Security
  disability is taxed with Social Security. The line stays the total, so gross income, child support, alimony and the
  financial affidavit don't change. The AI assistant puts a VA benefits letter's compensation on its kind. These come
  with the new calculations (version 2026.15); nothing changes in a saved case until a line is split.
- Fixed: the term sheet's sentence on claiming a child only while current in support named the parent receiving
  support as the one who signs Form 8332, even when the paying parent was the IRS custodial parent. With the new
  calculations it names the custodial parent, and no signer when the paying parent is the custodial parent.
- New calculations (version 2026.15): when a child's claim alternates between the parents, each parent's income tax
  estimate is now the average of a year they claim the child and a year they don't, so child support no longer depends
  on whether the agreement starts in an even or an odd year. Taxes shows the average credit and tax, with tabs to see
  each year's, Child support shows each year's support beside the one used, with tabs to see each year's worksheet,
  and Income and expenses shows
  each year's income tax and net income under the averaged figures. The child support guidelines worksheet (Form
  12.902(e)) uses the average, with an Exhibit A that sets each year beside it, and deviation factor 8's drafted reason
  gives both years. Saved cases with an alternating child keep their figures until you review and apply the new
  calculations; child support changes only where a parent's income tax line is the estimate.
- The income tax line is the estimate unless you choose otherwise. New cases start on it for both parents, and child
  support deducts the estimate worked out on Taxes from filing status and dependents. The pay stub helper and the AI
  assistant still save the withheld figure from a pay stub, but no longer switch the line to it: Income and expenses
  shows "Estimated" with "Use the withheld figure instead", and "Use the estimate" switches back. A line you marked
  Withheld or Saved as adjusted keeps its figure. With the new calculations (version 2026.15), a saved case whose
  income tax line was never marked deducts the estimate instead of the figure typed on it; Review changes shows each
  parent's "Income tax deducted" before and after, and nothing changes until you apply them. The sample case is now on
  the estimate too.
- Dates are typed the way you write them: 3/4/19, 030419, March 4, 2019 or 2019-03-04 all become 03/04/2019 when
  you move to the next field, and every date in the app shows as MM/DD/YYYY. A two-digit year on a date of birth or
  marriage never lands in the future, so 5/2/84 is 1984. Dates you schedule (support and alimony starts, the
  parenting plan's dates, the course dates, service and reply dates) have a calendar button, with the month and year
  as lists. A date the field can't read stays as you typed it, with "Format date as MM/DD/YYYY." or "Invalid date."
  under it, and nothing is saved until it is corrected.
- New cases start with Division set to Domestic Relations, for the court forms' caption. Change what new cases
  start with in Settings, under New cases, or clear it to start them blank. Cases already saved keep their division.
- "How is this calculated?" is easier to read. A sum now shows one amount per line, with a heavy rule above the
  total and a column for each spouse who has figures, instead of a line of code-style text. The result is said in
  words ("So Daniel pays Camille $25,710.00"), agreed child support lists the rules it checked, such as the written
  finding for a deviation over 5%, and the foot gives the citation and, when the figures come from another step,
  which step.
- Fixed: on equitable distribution set to after-tax values, "How is this calculated?" for marital property received
  and the net marital estate left out the tax on assets sold or cashed out, so its working didn't add up to the
  figure shown.
- Court forms is now Forms and letters, and it has Form 12.932, the certificate of compliance with mandatory
  disclosure, for your client. The app writes the form's own words and lists every document your client produced
  under its item, in full: each account's statements and their months, the tax returns with their W-2s and 1099s,
  the pay stubs by pay date. An item with gaps ends with what isn't produced yet. Account numbers follow Rule 2.425:
  no digits for bank and card accounts, the last four for retirement, loan and insurance accounts, and children by
  their initials. Save it as a PDF, whose blanks you can type into, or as a Word file to edit. Beside the form,
  Items lists what is still open first; click one to see what the form says about it.
- A request for documents for each party, under Letters on Forms and letters, or from the Disclosure checklist's
  "Request in Word…". It lists every document the checklist still asks for, grouped under plain headings, the
  documents that need a second look with both figures, and the questions for your client. It goes to your client, to
  the other side's counsel, or to a party without counsel, each with its own opening; to the other side each item
  names its part of Rule 12.285. Choose the reply-by date and save it as a Word file; nothing is sent from the app.
- An intake list for your client, under Letters, or from Case documents before a folder is linked: what to bring for
  mandatory disclosure, before any file exists. It lists what everyone brings, then what the case already shows
  (deeds for a home, retirement statements, the children's costs), then anything else they may have, each with its
  months counted back from today. Save it as a Word file with your letterhead.
- The AI assistant can answer what a party has produced or still owes under mandatory disclosure ("What is Camille
  still missing?"), from the Disclosure checklist, with links to the pages of the documents that count.
- The MSA term sheet has moved to Forms and letters, as a row of its own under Agreement, and Agreement terms links to
  it. The row says whether it's ready or how many blanks are left, and when you last saved it. Preview and save opens
  it as pages laid out the way its Word file is, with each blank listed beside them and a link to the step that fills
  it. Save it as a PDF to send or print, or as a Word file to complete the agreement from. Copy text and the .md
  download are gone.
- Fixed: a source the AI assistant gives for a file attached to the chat (a link in its answer, or the file and page
  on a proposed change) now opens that file on the cited page, with the figure marked, while the case stays open.
  Attachments still aren't saved: once the case is closed, the source says so and how to keep it, rather than that
  the file has left the documents folder.
- Fixed: in a fillable PDF, such as the court's financial affidavit, a figure the AI assistant cited wasn't marked on
  the page ("isn't on this page as written"), because a typed value is held in the form's field and not in the
  page's text. The viewer now finds it in the form's fields too and marks the field, for an attached file and for one
  in the documents folder.
- Fixed: a cited figure on a scanned page (a picture, with no text the AI assistant has read from it) opened with
  "isn't on this page as written", though it was there in the picture. The page now says it is a picture and the figure
  can't be marked on it, so find it by eye.
- Fixed: importing a case file from a state this version doesn't cover, or one that uses calculations from a newer
  version, showed "This case couldn’t be opened". It now opens read-only with a note saying why, as it does from
  the case list, and the file is kept as it was for the version that can open it. The case list now marks a case
  from another state "(another state, read-only)" rather than "(newer version, read-only)".
- Child support shows Form 12.902(e) line by line, starting with how each parent's net income is worked out from the
  financial affidavit: each income and deduction line, with alimony from this case on lines 9a and 25a when it is
  counted, marked "for child support" beside the affidavit's own totals. Each input sits on the form's line that takes
  it, with the affidavit's line 40, 50 or 51 under it, and the overnights, the schedule lookup, the noncovered costs
  choice and the deviation are in the table too. Who claims each child and what the income tax line deducts are in
  line 18's "How is this calculated?".
- New calculations (version 2026.15): on Child support, child care, the children's health insurance and noncovered
  medical costs come from each parent's financial affidavit (lines 40, 50 and 51). Click Override in the worksheet to
  type another figure; it shows the affidavit's figure and the support that figure would give, and Clear goes back to
  the affidavit. Net income on line 1 can be overridden too, such as for imputed income. The count of overridden
  figures above the worksheet goes to each in turn. Figures typed on Child support before stay, as overrides. Form
  12.902(e), the "How is this calculated?" panels and the Taxes worksheet's children's premium follow the same figures,
  and the pay stub helper and the AI assistant put the children's share of a health premium on the affidavit's line 50.
  The sample case has Camille's child care on her line 40.
- Case and parties: each child is entered in one place. The Children section has a card for each child that opens and
  closes; a closed card shows a one-line summary, and a child who still needs something opens on its own and says what's
  missing. Each card has "About" (full legal name, name in the agreement, place of birth, sex, and the date of birth
  with the age and support end under it) and "Where … has lived", with a bar showing each address across the 5 years
  and any gaps; clicking an address on the bar shows its details.
- "Sort oldest first" puts the children in birth order when they aren't; the order carries to the UCCJEA affidavit text
  and the term sheet. Remove asks first, and a child who shared the first child's addresses keeps them when the first
  child is removed or the order changes.
- A child's addresses are entered as on the form: the present address on top, then "Add earlier address", which fills
  in the end date. Each gap in the 5 years shows where it falls, with a button to add an address for those dates.
  Address dates can't be after today, and an end can't be before its start.
- A child's date of birth can't be after today. The high-school box now reads "Still in high school at 18 and expected to
  graduate before 19".
- A child's place of birth can be outside the US, and the child's sex is typed: Female and Male are suggested, and
  anything else, such as "Not stated", prints as typed.
- Connect the AI assistant with your email address instead of pasting a key. The app asks for it once when you open
  it, and Settings → AI assistant can change it at any time. If LeanPractice replaces your firm's key, the app picks
  up the new one by itself. A key you pasted before keeps working until you connect with your email.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
