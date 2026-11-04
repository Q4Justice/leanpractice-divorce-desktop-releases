# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 1.3.0

Released November 4, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_1.3.0_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.0/LeanPractice.Divorce_1.3.0_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_1.3.0_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.0/LeanPractice.Divorce_1.3.0_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_1.3.0_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.0/LeanPractice.Divorce_1.3.0_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 1.3.0

- The AI assistant now opens in the right-hand column, in place of the case summary, instead of covering
  the screen. The steps and the worksheet stay in view, so you can keep working while Claude answers. Close
  the assistant to bring the case summary back; your conversation is still there when you open it again.
  In narrower windows the steps show just their number and status while the assistant is open.
- Equitable distribution: a search box above the asset and debt table. Type part of an item's name to show
  only the items that match; the totals still count every item.
- Parenting plan is now Step 5 and Child support Step 6, so you set the time-sharing schedule before the support
  worksheet that uses its overnights. Nothing in a saved case changes.
- Child support: a new Child tax benefits card replaces the free-text "Child tax credit and dependency" box on
  Agreement terms. Choose who claims each child (either parent, or alternating years), what happens when a child
  ages out, and the first tax year. The card shows who claims each child year by year and when Form 8332 is
  needed, and writes the term sheet and MSA wording from your choices; change the wording in the MSA draft.
- Income and expenses: say whether each income tax line is pay stub withholding or tax adjusted for filing status
  and dependents (§61.30(3)(a)). If a parent claims a child but the line is still withholding, a check says so and
  shows how much $100 a month of tax changes child support. The pay stub helper marks the line as withholding.
- Deviation: tick the §61.30(11)(a) factors you rely on. Factor 8 (the dependency exemption) drafts the reason
  from the child tax benefits.
- The "current on support" condition can now say December 31, the date the return is filed, or no date. The firm
  MSA template is updated so its paragraph follows your choice; December 31 stays the default.
- Income and expenses: a 2026 federal income tax estimate for each spouse, from the income lines, the filing
  status after the divorce (head of household for the parent with more overnights), the standard deduction and
  the child tax credit for the children each one claims. Click "Use" to put it on the income tax line; nothing
  changes until you do. You can choose the filing status, enter pre-tax payroll deductions (the pay stub helper
  fills them) or enter taxable income from a return.
- Case and parties: each spouse's date of birth. It is used only for the tax estimates (age 65, the 59½
  withdrawal penalty) and is not printed in the agreement.
- Equitable distribution: an after-tax equalizing payment. Under each retirement account, investment or
  property, answer one question first: will it be sold or cashed out under the agreement? If yes, say how it is
  taxed (401(k) or pension, IRA, Roth, or taxed on the gain over basis). The worksheet
  estimates each spouse's tax on it, with the 10% early withdrawal penalty (not on a QDRO payment to the other
  spouse from an employer plan), capital gains rates and the $250,000 home sale exclusion, and shows the
  payment before and after tax. Choose "After tax" to use it in the agreement. Assets that are kept are not
  taxed: that tax is speculative.
- Law tables: the 2026 federal tax figures (Rev. Proc. 2025-32) and the brackets.
- These come with new calculations (November 2026, child tax benefits and tax estimates). Saved cases show
  "Newer available": review and apply them to choose who claims each child or use the tax estimates. No
  support, alimony or property figure changes until you use the estimate or choose the after-tax payment;
  until then a case keeps its free-text wording.

- The AI assistant's conversation is now kept with each case, so it is still there when you switch cases or
  quit and reopen the app, and Claude remembers what was said. Files you attached aren't kept, only their names:
  attach one again if Claude needs it. A Clear button in the assistant starts that case's conversation over.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
