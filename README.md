# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 1.3.2

Released November 5, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_1.3.2_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.2/LeanPractice.Divorce_1.3.2_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_1.3.2_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.2/LeanPractice.Divorce_1.3.2_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_1.3.2_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v1.3.2/LeanPractice.Divorce_1.3.2_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 1.3.2

- Accept or reject the AI assistant's proposed changes one at a time. Each change says where it goes, such as
  "Income and expenses › Maria › Allowable deductions"; click that to open the step at the field. Accepting a change
  applies it right away, and Undo puts the field back, unless you changed it since. "Accept N left" and "Reject N
  left" decide the rest of a card at once.
- The worksheet shows each change waiting for review next to its field, with a dashed border and "AI assistant
  proposes …"; a proposed new asset, child or address shows as a shaded row. A dot on a step's number means changes
  are waiting there.
- "Review in worksheet" opens a bar at the bottom of the worksheet that takes you through the waiting changes one by
  one, across every card in the conversation. Keys: A accepts, R rejects, the arrow keys move, Esc closes. On a phone,
  the assistant steps aside while you look, and "Chat" brings it back with what you typed.
- If a field changed after the assistant proposed a value for it, the change says what the field holds now.
- The changes you accept from one answer of the assistant are saved together as one version in History.
- The assistant is told which changes you rejected, so it doesn't propose them again unless you ask.
- Proposals from earlier conversations show the same way: changes you applied show as accepted, the rest as
  rejected, and a card you hadn't applied yet waits for review.
- Case documents now shows whose each file is: one of the parties, joint, not a party's, or unsure. It works this out
  from the names printed on the file, such as the employee on a pay stub or the account holders on a statement;
  folder names don't decide it. Change any of them in the list; your choice is saved with the case and shown in
  History. Filter the list by person; a person's documents include the joint ones.
- With your firm's AI key saved, the AI assistant sorts the files the names don't settle, such as scans and
  pictures, as soon as the folder is read. Up to 3 first pages of each are sent, with zero data retention, and its
  tags say "AI:" with the reason. "Sort again: unsure" and "Sort again: all" ask it again. Without a key, nothing
  is sent and you choose for those files under "Needs your attention".
- A file that may hold both parties' documents, such as two people's pay stubs scanned together, is listed under
  "Needs your attention" as possibly mixed. Keep its tag or make it joint.
- Click a file under "Needs your attention" to open it beside the list, at the page with the name marked, and
  choose whose it is right there.
- Click a citation, in an answer or under a proposed change, and the page opens in the app beside the assistant,
  with the cited words marked. Clicking a file in Case documents opens it there too.
- The app now says "AI assistant" everywhere. Settings shows the AI service and that it keeps no data.
- The note under the AI assistant's message box is now one line. Click "Data and privacy" to see what is kept and
  what is sent; it stays open or closed as you left it.
- Fixed: tables in the AI assistant's answers now show as tables. They showed as lines of text with `|` marks.
  Links to a document page still work inside a table.
- Fixed: numbered lists in the assistant's answers keep their numbers, with any points under a step shown under
  it. Headings and the names of worksheet fields show cleanly, without `##` or backtick marks. Earlier
  conversations show the same way.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
