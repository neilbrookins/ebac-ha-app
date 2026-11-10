# Changelog

## 2.15.7

- **A chapter's heading has `===` in the margin**, where a verse's
  number goes, as a note has `---`: "The history of Cain and Abel." in
  the Douay-Rheims no longer reads as the end of the verse above it.

## 2.15.6

- **Translations keep the source's own characters.** Adding a
  translation no longer turns curly quotes, dashes, the ellipsis or the
  pilcrow into plain ones: the text is as the source has it. A search
  typed with a plain apostrophe still finds every kind (`don't` finds
  `don’t`), and found words are highlighted however they are written.
  Translations added before keep their plain punctuation until removed
  and added again.

## 2.15.5

- **C's line, on a short list, names both ways to choose**: a number
  alone, and d first to start with it from now on ("Number: choose; d,
  number: default (x: back)" on a phone). Before, it named only the second.

## 2.15.4

- **Removing the translation you are reading, then searching, no longer
  stops EBaC.** With the main menu on the screen when it was removed (by
  voice, say), S filled the search line with x's and EBaC stopped with
  "Out of room in string!". Now it goes back to the main menu, which says
  the translation was removed and carries on with another.
- **A search line too long** is refused with a beep, key by key, instead
  of EBaC stopping. The same where a book's name is typed.

## 2.15.3

- **Translations added or removed by someone else are seen at once.**
  Another user, or voice through the EBaC integration, may add or remove a
  translation while you read. **C** now reads the list again each time,
  so it always shows them as they are: one just added is there, one just
  removed isn't, with no need to leave EBaC and start it again.
- **Removing the translation you are reading no longer stops EBaC.**
  Before, EBaC stopped with "Can't Open ... for reading" the next time it
  opened a book. Now it says "The translation ... has been removed, by
  another EBaC or by voice", and carries on with the first translation
  still listed.
- The list of translations is never read half written while it is being
  changed.
- **A** names the second place as GitHub does: **scrollmapper/bible_databases**.

## 2.15.2

- **A book's whole name chooses it**, even where another book's name
  begins with it: `esther` is Esther in the KJVA-TB, which also has a
  longer name beginning "Esther" (`estherg` chooses that one). Before, it
  matched both, and a space or Enter ends a name, so there was nothing
  more to type. The same at the V prompt, after @ in a search, and in a
  reference said to Assist ("Esther 1:1").
- **A name that matches several books lists them**, one to a line, after
  "There is more than one book that matches that name", so you can see
  what more to type: `phil` lists Philippians and Philemon.

## 2.15.1

- **Verses in Japanese and Chinese are shown whole.** EBaC read a verse a
  word at a time, keeping 80 bytes of a word, and these texts have no
  spaces between words: a verse was cut after 26 characters, ending in
  part of the 27th, shown as another character (Genesis 1:2 in JNIV-TB,
  and two verses in three of that translation). The text added was always
  whole, so nothing needs adding again.

## 2.15.0

- **A book can be typed by its short name** in translations from
  thiagobodruk/bible (-TB), wherever a book name is typed (V, @ in a
  search, a reference): `gn` Genesis, `jo` John, `ez` Ezekiel, `1sm`
  1 Samuel. They are the collection's own (from the Portuguese names: `sl`
  Psalms, `ap` Revelation), the same in almost every translation there, in
  Latin letters even where the names are in Japanese or Korean. A -TB
  translation added before this gets them when added again.

## 2.14.0

- **Adding translations by voice from any of the three places**:
  thiagobodruk/bible, scrollmapper's bible_databases, or Project Gutenberg
  (its texts EBaC knows, by ebook number). Which one is the EBaC
  integration's new Source setting (integration 0.8.0 or later). Removing
  by voice uses whichever place the translation came from.

## 2.13.2

- Adding several translations at once: one blank line between them, not two.

## 2.13.1

- **What you type in the lists for adding translations stays on the
  screen** when the list is drawn again, as when the phone's keyboard is
  hidden: before, it vanished from the screen but was still sent with
  Enter.
- After adding or removing more than one translation, each result starts
  at the left margin (the second had a stray indent).

## 2.13.0

- **A third place to add translations from: thiagobodruk/bible on GitHub**
  (A, then T): some 140 Bibles in 85 languages, among them the New
  International Version and the New Living Translation. Their short names
  end in -TB (NIV-TB, NLT-TB, KJVA-TB), so the same Bible from each place
  can be kept side by side. Some, such as the NIV and the NLT, are still
  under copyright: EBaC says so and asks whether you agree, as for every
  translation.
- The Add screen's letters now name each place: **T** (or 1)
  thiagobodruk/bible, **S** (or 2) scrollmapper's bible_databases (was
  G), **P** (or 3) Project Gutenberg.

## 2.12.15

- **Long swipes on a Hebrew search line go the way they point**: a long
  swipe left goes to the line's left end, right to its right end (they
  went to the start and end, which in Hebrew are the other way round).
- On a Hebrew search line, the cursor at the start sits on the first
  letter, as on an English line, and moves one letter at a time.

## 2.12.14

- **Hebrew verses have their reference on the right, in Hebrew letters**,
  as Hebrew Bibles show them: the text right aligned, then chapter and
  verse at the screen's edge, chapter first (Genesis 1:13 is א:יג; 15
  and 16 are טו and טז). Lists of search results keep the reference on
  the left, in Hebrew letters. English verses are unchanged.
- The list of translations uses its short heading in a narrow window
  however few translations there are (the long one wrapped on a phone).

## 2.12.13

- **The list of translations says "(page 1 of 2)"** when it takes more
  than one page, as the lists for adding translations do: with a phone's
  keyboard up, the first page looked like the whole list. Paging (n/p) is
  only offered when there is more than one page.

## 2.12.12

- **The Hebrew name in the Westminster Leningrad Codex is said as tradition
  reads it**, through the EBaC integration's "EBaC voice" (0.7.2 or
  later): אֲדֹנָי (Adonai), or אֱלֹהִים (Elohim) where it has Elohim's
  vowels, with any letter joined to its front kept.

## 2.12.11

- **Assist shows יהוה as the text has it again**, while you still hear
  "Adonai": the change is now made only in what is heard, by the EBaC
  integration's "EBaC voice" (integration 0.7.0 or later; choose it in a
  voice assistant). Without it, the name is spoken as the voice reads it.

## 2.12.10

- **Voice says יהוה as "Adonai"**, the word traditionally read in its
  place. Written with no vowels, the name was read wrongly (a Hebrew
  voice said "yo"). The screen and searching keep the text as it is.

## 2.12.9

- **Fixed: pasting on a phone put the text in twice** ("jesusjesus"), so
  a word copied from a verse and pasted into a search found nothing.
  Pasting with Ctrl+V on a computer wasn't affected.

## 2.12.8

- **Fixed: the mouse wheel did nothing** since 2.12.6. It moves back or
  on by verses again, as before (about six a notch).

## 2.12.7

- **A mouse click goes on from "Press any key"**, as a tap does (the
  Information screen's pages, for one). Before, only a key or a tap did,
  and clicks there were mostly ignored. A click that ends selecting text
  to copy still leaves the screen as it is.

## 2.12.6

- **Fixed: the page could freeze while its size changed quickly**
  (dragging a browser window's edge about, and possibly turning a phone
  or the keyboard coming and going): the screen stopped redrawing, lines
  wrapped, and keys did nothing until the page was reloaded. The page's
  terminal now keeps one line it has scrolled past, not none, which
  avoids a fault in it that this set off.

## 2.12.5

- Nothing new to see: the app now builds its web page, its gestures and
  its start from EBaC's own `docker/` folder, the same files as EBaC's
  new standalone Docker image (for people without Home Assistant), so
  every improvement reaches both. (gestures.js, make-index.sh,
  ebac-setup, ebac-session and ebac-api's scripts moved there.)

## 2.12.4

- **Voice understands "Koran", "Coran" and other ways the Qur'an's name
  is heard**, as well as "Quran". The forms are in a file, `spoken`,
  beside `groups`: a book to a line, more can be added. After updating,
  reload the EBaC integration (or restart Home Assistant) so Assist
  learns them.

## 2.12.3

- **Two more texts from Project Gutenberg** (**A**, then **P**):
  - **8294**, the World English Bible (**WEB-PG**), with its notes in
    {braces} as printed. A search finds a word even when a note is
    joined to it ("God{...}"), and "God created" finds Genesis 1:1.
  - **16955**, the Qur'an in three translations, added as three:
    **YUSUFALI-PG** (Abdullah Yusuf Ali), **PICKTHALL-PG** (Marmaduke
    Pickthall) and **SHAKIR-PG** (Mohammad Habib Shakir). Open EBaC in
    three windows, one in each, to compare them side by side.
    References are as the Qur'an is cited (Qur'an 2:255); each surah's
    name and heading come before its verse 1.
- Voice reads only the text: notes in {braces} are left out, and a
  psalm's title is read without its << >>. "Quran" is understood.

## 2.12.2

- **Notes marked in the Douay-Rheims.** Each of Challoner's notes has
  **---** in the margin on its first line, where a verse's number goes,
  so someone reading aloud sees where the verse ends and the note
  begins. Voice (Assist) now reads only the verse, not its notes. A
  Douay-Rheims added before: press **A**, **P**, **1581** again (it
  replaces the copy you have, though Gutenberg's version is the same).

## 2.12.1

- Docs: **Removing EBaC**. Uninstalling the app deletes the
  translations you added, everyone's search history and its options;
  how to back up first and get them back, and removing the voice
  integration too (whose 0.6.3 raises a repair when the app can't be
  reached). EBaC itself is unchanged.

## 2.12.0

- **The Douay-Rheims Bible from Project Gutenberg.** Press **A**, **P**
  and type **1581** to add it, as **DRC-PG** (GitHub's **DRC** can be
  kept beside it). Unlike GitHub's, it has Challoner's notes, each on
  lines of its own under the verse it explains (searches find them),
  each book's introduction and each chapter's summary before its verse
  1, the psalms' Latin titles, and the edition's appendices (the Prayer
  of Manasses, 3 and 4 Esdras, and more, in their 1600s spelling).
- The **P** screen lists the ebooks EBaC knows.
- Built from EBaC commit `9311b66`.

## 2.11.0

- **One A for adding, from anywhere.** The main menu's **A** now asks
  where to add from: **G** (or **1**) for GitHub's Bible translations,
  as **A** did before, or **P** (or **2**) for Project Gutenberg, which
  was **P** on the main menu (now gone from it). **X** goes back. More
  places can be added there later.
- **Gutenberg texts' names end in -PG**, so the same Bible from both
  places can be kept side by side: the Douay-Rheims from GitHub is
  **DRC**, from Project Gutenberg **DRC-PG**. Your Book of Mormon is
  renamed from **BOM** to **BOM-PG** the next time you press **A**,
  **P** (it keeps its place). If you chose BOM for voice, choose
  BOM-PG under the EBaC integration's **Configure**.
- Built from EBaC commit `01eb514`.

## 2.10.12

- **Hebrew (and any right-to-left translation) is searched right to
  left.** With such a translation chosen, the search line starts at the
  right edge of the screen and grows to the left as you type or paste;
  English words and numbers in it still read left to right. Backspace
  erases the last letter typed, and the arrow keys move the way they
  point.
- **Copying Hebrew from the screen works.** Text you highlight is put
  on the clipboard in reading order (before, its letters came out
  backwards), so pasting it into a search finds it.
- Punctuation at the ends of a search word, such as a period or the
  Hebrew sof pasuq copied along with it, is ignored.
- Built from EBaC commit `cbe50f1`.

## 2.10.11

- **Backspace keeps working after pasting** (on the search line, say)
  with a phone's keyboard: after a few, it seemed to stop, as the
  keyboard was deleting text it thought was still in its typing box.
  Now each Backspace erases one letter, with any vowel points on it
  (Hebrew too).

## 2.10.10

- In **A**'s lists of languages and translations, paging back with
  **p** after the keyboard came or went no longer shows a row 0: each
  page starts where it should for the screen's size.
- Built from EBaC commit `185c227`.

## 2.10.9

- **Screens fit above the phone's keyboard.** On phones where the
  keyboard is drawn over the page instead of making it smaller (the
  Home Assistant app on Android), EBaC was still told the full height,
  so the bottom of a screen, such as the list of languages under **A**,
  was hidden behind the keyboard, and a second page could seem blank.
  Now the terminal is made only as tall as the part of the page above
  the keyboard, and every screen is drawn to fit; when the keyboard is
  hidden, it is the full height again.

## 2.10.8

- The **Troubleshooting box** also shows the terminal's size (rows and
  columns) each time it changes, and which screen EBaC is on, to track
  down screens that don't fit above the phone's keyboard.

## 2.10.7

- **P no longer adds the same version twice.** It now recognizes the
  version you have by the file's fingerprint, its size and date, or the
  date on its Gutenberg page, before downloading; and, if none of
  those can tell, by comparing the downloaded text with yours, adding
  nothing if they match. (Remove and add the Book of Mormon once more
  so its copy records all of these.)
- Reading the ebook's page on gutenberg.org is more forgiving of how
  the page is laid out, and if it still can't be used, P says why.
- Built from EBaC commit `a3e05b7`.

## 2.10.6

- The free-space check before adding now looks at both places a text
  goes: where it is first downloaded, and where translations are kept.
- The "Allow voice to add translations" option no longer warns about
  filling the disk, since adding can't.
- Built from EBaC commit `344fb97`.

## 2.10.5

- **P (Project Gutenberg) asks before it downloads.** It reads the
  ebook's small page on gutenberg.org first, shows the title, when it
  was last updated and its copyright status, and asks whether you agree
  to the license; the book itself is downloaded only after you say yes
  (and only if it isn't the version you already have, and there's
  room).
- Built from EBaC commit `5c5560f`.

## 2.10.4

- **The disk can't be filled by adding translations.** Adding (in the
  app, from Project Gutenberg, or by voice) stops while less than 1 GB
  is free, with "not enough disk space".
- **The search history no longer grows without end.** It keeps the
  newest few thousand searches, dropping the oldest.
- Removing a Project Gutenberg text (P) takes `r` and digits only.
- Built from EBaC commit `c4e9b0e`.

## 2.10.3

- Rebuilt with updated system software (no change to EBaC itself):
  - Home Assistant base image 3.24-2026.10.1 -> 3.24-2026.10.3

## 2.10.2

- **Right-to-left lines are aligned on the right.** A line that is
  mostly Hebrew, Arabic or another right-to-left script now ends at the
  right edge of the screen, with the spare room on the left, as such
  text is written. English with a Hebrew word in it, or a line half and
  half, stays on the left.
- Built from EBaC commit `c635816`.

## 2.10.1

- **No more empty space after a very long verse.** On the passage
  screen, the last part of a verse taller than the screen is now
  followed by the verses after it, as many as fit, instead of standing
  alone.
- Stepping with `.` onto an empty row no longer leaves part of the
  "Press ? for menu." prompt behind.
- Paging back with p through a very long verse shows the screenful just
  before, even when its start was shown below other verses.
- **Search results:** p goes back to a very long result (shown cut to
  fit) from the screen after it; before, it stayed put.
- Adding a text from Project Gutenberg no longer shows
  "tr: write error: Broken pipe".
- Built from EBaC commit `2f2d47b`.

## 2.10.0

- **Gutenberg texts keep their layout.** The front matter and each
  book's heading and summary are shown as the original lays them out:
  each title line, name and line of contents on its own row, blank lines
  kept, and each paragraph wrapped to your screen. To see it in a text
  you've already added (the Book of Mormon), remove it and add it again:
  P, then r and its number; then P and its number.
- A very long verse that follows others now starts in the room left
  below them, instead of on a screen of its own.
- Built from EBaC commit `6b5f58d`.

## 2.9.2

- **Paging near a very long verse works again.** Around a verse taller
  than the screen (such as the Book of Mormon's introductions, or its
  testimonies on a phone), some keys didn't move or skipped: now n, p,
  `.` and `,` (and the swipes for them) step through it part by part,
  and f and b always go to the next book or the start of this one. Only
  at the very first or last verse is there nowhere to go.
- f now goes to the book after the one at the top of the screen (before,
  a book whose start was showing lower on the screen was skipped).
- Built from EBaC commit `909726f`.

## 2.9.1

- P downloads the ebook straight from Gutenberg
  (https://www.gutenberg.org/ebooks/NUMBER.txt.utf-8), without asking
  Gutendex first, which refused (403).
- Built from EBaC commit `171b688`.

## 2.9.0

- **P asks for the ebook number** (the EBook-No. on its page at
  gutenberg.org: 17 for the Book of Mormon), not an address to paste.
  EBaC finds the address of its plain text from Gutendex, a catalogue of
  Gutenberg's ebooks, then downloads it.
- Built from EBaC commit `8a3bdbe`.

## 2.8.1

- A short swipe left erases a character on P's address line and the
  license question too (it showed ^H there).

## 2.8.0

- **Texts from Project Gutenberg (P on the main menu).** Find a text on
  gutenberg.org, open its "Plain Text UTF-8" file, and paste its
  address: EBaC downloads it, shows its license, and adds it. The first
  it knows is the Book of Mormon (ebook 17, as BOM); others are added
  one at a time. P, then r and a number, removes one.
- Nothing in such a text is left out: its front matter (title page,
  testimonies, contents) comes before chapter 1 of its first book, and
  each book's heading and summary before its verse 1, shown as plain
  text without numbers. Comma (or a swipe down) from 1:1 reaches them.
- A verse taller than the screen is shown a screenful at a time.
- Updating re-indexes the translations you've added (the index program
  changed), which takes a little while at the first start.
- Built from EBaC commit `fb2ad6b`.

## 2.7.2

- **Allow voice to remove translations** checked without **Allow voice to
  add translations**: Home Assistant's Configuration tab can't stop it
  being saved that way, but it does nothing (as before), and now the
  option's description and the app's log say so.

## 2.7.1

- Adding a translation by voice: more reliable in the background.
- Built from EBaC commit `81a261c`.

## 2.7.0

- **Adding and removing translations by voice**, for the EBaC integration
  0.5.0: "add translation LITV", "remove translation LITV". Two new
  options, under **Configuration**, both off unless you check them:
  **Allow voice to add translations** and **Allow voice to remove
  translations**. Anyone who can talk to a voice assistant can use them,
  with no password, so each says its risk. The integration has its own
  checkboxes too, and both must be on. Restart the app after changing
  them.
- A translation added by voice goes at the end of EBaC's list, so EBaC
  here still starts with the same one.
- Voice can also ask for EBaC's version ("what version of EBaC is this?")
  and a translation's license.
- Built from EBaC commit `a5193fc`.

## 2.6.16

- The Information page (**I**) also names the voice integration's
  repository, for help or to report a problem with Assist.
- Built from EBaC commit `ea59f0c`.

## 2.6.15

- **Easier to follow when adding several translations.** A blank line
  now separates each one, so each one's last line shows how it ended.
- Built from EBaC commit `d2f6b38`.

## 2.6.14

- **No needless downloads.** Choosing a translation you've already added
  (**A**) downloads it again only if its text has changed since. If it
  is the same version, EBaC says "you already have this version" and
  changes nothing; to download it again anyway, remove it first (**r**
  and its number), then add it. Translations added before this version
  are downloaded once more, the next time they are chosen, so that their
  version is known from then on.
- Built from EBaC commit `cd8d1a0`.

## 2.6.13

- **Choose the default translation.** On **C**hange, a translation's
  number chooses it for now, as before; **d** and its number (**d** then
  **3**, or **d12** and Enter in a long list) chooses it and makes it
  the default, the one EBaC starts with from then on, for every Home
  Assistant user. The main menu then says "now the default".
- Built from EBaC commit `aa0b56b`.

## 2.6.12

- **Enter by tap or swipe while typing.** Typing a book, chapter or
  verse: with the keyboard up, a tap is Enter, and so is a swipe right
  (a swipe left still erases). Typing a search: with the keyboard up, a
  tap is Enter (swipes still move the cursor and step through earlier
  searches). With the keyboard hidden, a tap brings it up, as before.
- Built from EBaC commit `e454434` (unchanged).

## 2.6.11

- **Exit can be tapped** on the main menu, like every other item.
- Built from EBaC commit `e454434` (unchanged).

## 2.6.10

- Voice: when several verses are read in a row ("read on"), each after
  the first is introduced by its number alone ("15. And he said unto
  them..."), not "Verse 15.", so the reading flows. The first still has
  its whole reference, and a new chapter says "Chapter 4, verse 1."
- Built from EBaC commit `e454434`.

## 2.6.9

- **Swipes when adding translations** (**A**): on the lists of languages
  and of translations, swipe up for the next page and down for the
  previous; swipe left or right for Enter. So type a number, such as 1
  for English, and swipe to choose it; or swipe alone to go back. A
  number half typed is cleared before a page turn. A swipe never
  answers the license question (where swiping up would be "n", no).
- Built from EBaC commit `0b08954`.

## 2.6.8

- For the EBaC integration (0.4.0): a search's results can be gone
  through by voice, as on EBaC's list screen ("result two", "next
  result", "more results", "back to the results"); each result is
  spoken with its whole reference.
- Built from EBaC commit `8254b96`.

## 2.6.7

- The book's name above a passage (such as "2 Corinthians (KJV)") is
  placed to fit the screen: on a phone it no longer wraps onto a second
  line.
- Built from EBaC commit `0ee7888`.

## 2.6.6

- **White on black.** EBaC's screen is now pure white text on a black
  background, for the most contrast (it was light grey on dark grey),
  so small marks such as Hebrew's vowel points are easier to see.
- **Ancient Hebrew** is now listed by name in the list of languages (**A**
  at the main menu), beside Ancient Greek, instead of as "hbo". Its
  texts, such as the Westminster Leningrad Codex (WLC), have the vowel
  points. Other languages Unicode has no name for (Tausug, Central Sama,
  Beaver) are named too, from IANA's registry of language codes. The
  first time **A** is pressed after updating, the names are fetched
  again, which takes a few seconds.
- Built from EBaC commit `a6a68a5`.

## 2.6.5

- A translation's license page address is shown whole, on one line
  (wrapped by the screen), so a double-click selects all of it to copy.
- Turning the phone, or the keyboard coming up, while EBaC asks whether
  you agree to a license no longer repeats the question across the
  screen.
- Built from EBaC commit `9d853d7`.

## 2.6.4

- The list of languages (**A** at the main menu) says it takes one
  language: "Type the number of one language, then Enter." Typing
  several, as the list of translations after it allows, is answered
  "One language at a time: translations come next." (It used to say
  "Not in the list", as if the numbers were wrong.)
- Built from EBaC commit `84b47c2`.

## 2.6.3

- For the EBaC integration: the translations' titles are given whole
  (long ones, and those in Cyrillic, were cut short), so "which
  translation is this?" and "change translation" say them in full.
- Built from EBaC commit `cb2b7a3`.

## 2.6.2

- **Licenses.** Before a translation is added (**A** at the main menu),
  EBaC shows its license, such as "Public Domain", "GPL" or
  "Copyrighted; Free non-commercial distribution", and the address of
  its page at CrossWire, and asks whether you agree to it: **y** adds
  it, **n** skips it. It asks every time, a fresh copy too, since a
  license can change. What was agreed to, and when, is kept in the
  translation's folder (a file named license).
- Built from EBaC commit `3a6bd27`.

## 2.6.1

- ebac-api also lists the numbers it understands ("a hundred and
  nineteen", "cxix"), and books as "1st Samuel" too, for the EBaC
  integration's sentences; a run of verses read aloud says only what is
  new ("Verse 17.", "Chapter 4, verse 1.").
- Built from EBaC commit `0b362fb`.

## 2.6.0

EBaC 2.4, the first step to voice:

- The app now also runs **ebac-api**, which answers in JSON for the
  coming EBaC integration (voice: "Genesis one colon one", "next
  verse"). It is reachable only inside Home Assistant (port 8080 of its
  internal network, not published), and only reads. The app tells Home
  Assistant it is there, so the integration will find it by itself.
- EBaC understands references as they are spoken: "John three
  sixteen", "first Corinthians thirteen four", "Jude three".
- Nothing changes in EBaC's screens.
- Built from EBaC commit `25aebf9`.

## 2.5.3

- This app's repository is now **github.com/neilbrookins/ebac-ha-app**
  (it was ebac-ha), so that it isn't mistaken for an integration. The
  old address still works: Home Assistant keeps finding updates there,
  and there is nothing to change in an existing installation (changing
  it would install the app afresh, without the translations added).
- Built from EBaC commit `92edb86`.

## 2.5.2

- The Information pages (**I** at the main menu) say where to get help
  or report a problem, by opening an issue on GitHub: for the program,
  this app, and the texts it downloads (instead of the old SourceForge
  page). The computers EBaC has run on are listed in the order it was
  ported to them, from 1992, now ending with the Macintosh and Home
  Assistant. Every line fits a phone's screen.
- Built from EBaC commit `d005876`.

## 2.5.1

- The languages now show their names (such as "Español, Spanish"), not
  only codes such as "es".
- The heading of the language and translation lists is two lines, so
  the page number isn't cut off on a phone.
- A translation whose text is missing where EBaC downloads it (the
  Reina Valera Gómez, for one) is now said to be so.
- Built from EBaC commit `7079a04`.

## 2.5.0

EBaC 2.3.2:

- **Translations in every language.** Pressing **A** now lists the
  languages first, each by its own name and its name in English, such
  as "Español, Spanish (4)", English at the top; then that language's
  translations. 140 translations in 56 languages are offered at the
  moment, and new ones appear on their own. The names of the languages
  come from Unicode's language database (fetched the first time, a few
  seconds, then kept).
- Languages often written without spaces between words (Chinese,
  Japanese, Thai) are marked, as searching them works poorly.
- A slip in a text (an unclosed note) no longer stops a translation
  being added.
- The translations you have added are indexed again, once, at the first
  start (a few seconds each).
- Built from EBaC commit `2033f7d`.

## 2.4.1

EBaC 2.3.1:

- **Hebrew reads right to left.** The terminal shows every line from
  left to right, so Hebrew words (such as the name of God in the
  Restored Name King James Version) appeared back to front. Now each
  stretch of Hebrew is turned about as it is shown, leaving the English
  around it as it is; two Hebrew words together change places too,
  numbers keep their order, and vowel points stay with their letters.
  Highlighting follows the letters. (While you type Hebrew on the search
  line, it still shows in the order typed.)
- The translations you have added are indexed again, once, at the first
  start (a few seconds each; the indexes come out the same).
- Built from EBaC commit `9b82a13`.

## 2.4.0

EBaC 2.3: text with letters beyond ASCII (accented letters, Hebrew,
Greek) is handled properly.

- **Words with such letters are found.** Before, the index cut an
  accented letter off the start or end of a word, and left out words of
  Hebrew letters altogether: the Hebrew name of God in the Restored Name
  King James Version (8,227 times) couldn't be searched for. Now it can,
  and is highlighted.
- Capital letters with accents count as small ones, as A to Z always
  have. Accents are matched exactly as you type them.
- On the search line and the book prompt, Backspace and the arrow keys
  take a whole letter, and the cursor stays in step.
- Lines wrap, and book names line up, correctly with such letters.
- Book names of translations you add keep their accented letters.
- The translations you have added are indexed again, once, when the app
  starts after this update (a few seconds each).
- Built from EBaC commit `c4cf5ba`.

## 2.3.0

EBaC 2.2:

- **Groups of books in searches.** `=` and a group's name means every
  book of the group: `faith =nt 0` finds "faith" in the New Testament.
  The groups: `=ot`, `=nt`, `=law`, `=history`, `=poetry`,
  `=majorprophets`, `=minorprophets`, `=gospels`, `=synoptics`, `=paul`,
  `=pastoral`, `=general` and `=john`, and in the King James Version
  with the Apocrypha, `=apocrypha`. Type just enough of the name to be
  unique (`=n`, `=go`); if it could be more than one, EBaC says which.
  Each translation keeps its publisher's arrangement: the Old Testament
  of the Douay-Rheims Bible includes Tobit and the others.
- **Ranges of books**: `=rom..phile` is every book from Romans to
  Philemon.
- An `@` book name that could be more than one book now says which:
  "@1t matches 1Thessalonians and 1Timothy".
- **Change translation**: with a blank line between the translations,
  as on the main menu, when they fit on the screen that way, so each is
  easier to tap (a tap on the blank line next to one chooses it); one
  to a line when they don't. It adapts when the phone is turned.
- Built from EBaC commit `2dde7c9`.

## 2.2.3

- **Numbers for Roman numerals in book names.** Most translations write
  numbered books in Roman numerals (IThessalonians, IIIJohn); you can now
  type the number instead, as in the King James Version: `2th` finds
  IIThessalonians, `3` IIIJohn, and `1m` IMaccabees. The names are shown
  as the translation writes them. This works at the book prompt and in
  `@` searches (`faith @1co 0`), so a search works the same in every
  translation.
- **Shorter swipes turn a page.** In a passage, a swipe up or down of
  about a fifth of the screen now turns a whole screen (it took nearly a
  third before); a shorter one still moves one verse.
- Built from EBaC commit `0fe4aef`.

## 2.2.2

- With keyboards that hold back letters as a word being typed (such as
  the Amazon keyboard on a Fire tablet), each letter now reaches EBaC at
  once on every screen, so a book's name is completed as you type it,
  as on other phones. (2.2.1 did this only where one key does
  something, so completion worked only some of the time.)

## 2.2.1

- A key pressed at the main menu (or in a list, a passage, or at "Press
  any key") now works at once with phone keyboards that hold back
  letters as a word being typed, such as the Amazon keyboard on a Fire
  tablet. Before, the key did nothing until space was pressed, and then
  turned up at the start of the next search.

## 2.2.0

EBaC 2.1, with a new concordance index:

- **Phrase search.** Type words alone, such as `in the beginning`, to
  find them next to each other, in order. Phrases run on from one verse
  into the next, and the King James translators' [bracketed] words may be
  typed or left out. With other operators, `.` makes a phrase:
  `in the . beginning . @gen 0`.
- **New distance operators**: `+2`, `-2` and `~2` find verses exactly
  two verses after, before, or apart (a number alone still means
  "within").
- **Translations with the Apocrypha** can be added: the King James
  Version with the Apocrypha, the Douay-Rheims Bible and the Catholic
  Public Domain Version (34 translations in all).
- Every word is indexed, and counted right: "the" occurs 64,040 times in
  the King James Version (shown as 31,487 before).
- The translations you have added are indexed again, once, when the app
  starts after this update (a few seconds each).
- Built from EBaC commit `b50fb87`.

## 2.1.25

- After adding or removing translations, EBaC waits for a key (or a tap)
  before going back to the main menu, so you can read what happened.
- Built from EBaC commit `ba1ad1c`.

## 2.1.24

- Fix: tapping **A** with the keyboard hidden could leave the top of the
  list of translations off the screen, as the keyboard came up just
  after the list was drawn. The list is now drawn again whenever the
  window changes size.
- Built from EBaC commit `2d79e17`.

## 2.1.23

- Remove translations you added: under **A** (now "Add or remove a
  translation"), type **r** and the number, such as `r6`. Adding and
  removing can be mixed in one line, such as `r10 11 13`.
- Choosing a translation you've already added downloads a fresh copy
  and makes it the one EBaC starts with.
- Built from EBaC commit `50bdb5a`.

## 2.1.22

- In the list of translations to add, those already added are marked
  with a `*` before the number, instead of "(added)" after the title,
  so more of each title fits.
- A translation you add now becomes the one EBaC starts with every
  time, not only the first time after adding it. The app keeps the order
  of the translation list across restarts and updates.
- Built from EBaC commit `5ea60c1`.

## 2.1.21

- Fix: the **Tap here to type** bar didn't appear when the phone was
  turned, because the keyboard was judged at the new width, as if it
  weren't up. Whether the keyboard is up is now kept through a turn.

## 2.1.20

- In the Home Assistant Companion app, turning the phone takes the
  keyboard focus away from the page altogether (a problem in the app,
  which no web page can undo), so what is typed goes nowhere until the
  screen is tapped. EBaC now shows a **Tap here to type** bar when that
  happens with the keyboard up; it goes as soon as the focus is back.

## 2.1.19

- When the phone is turned and EBaC's page loses the keyboard focus to
  the Home Assistant page around it, it is also taken back through that
  page (by focusing the frame EBaC's page is in).
- The troubleshooting box shows more lines, and where the Home Assistant
  page around EBaC has the focus.

## 2.1.18

- New option for troubleshooting, **Troubleshooting box**
  (`debug_overlay`, off by default): a box in the corner of EBaC's page
  lists what it sees of the keyboard focus and the window's size, to
  help find problems on a particular phone.
- When the phone is turned, taking the keyboard focus back is tried a
  few times over a second, not once.

## 2.1.17

- Fix: turning the phone could take the keyboard away from EBaC: the
  keyboard stayed up, but nothing typed reached EBaC (the cursor showed
  as an outline) until the screen was tapped. If the terminal loses the
  keyboard as the phone is turned, it now takes it back at once.
- The main menu is drawn again when the window changes size, such as when
  the phone is turned, as passages and lists already were.
- Built from EBaC commit `a94dbf4`.

## 2.1.16

- Fix: after restarting EBaC, choosing an added translation under
  **C** failed ("Can't chdir to ../RNKJV") and closed EBaC. Added
  translations are found again, and a translation whose folder is
  missing is now reported without closing EBaC.
- Built from EBaC commit `8d7b42f`.

## 2.1.15

- Add translations from EBaC's main menu: press **A** to choose from 31
  English translations (such as the American Standard Version, the
  Berean Standard Bible, the Lexham English Bible and Young's Literal
  Translation), which are downloaded and indexed in a few seconds each.
  They are kept in the app's own storage, so updates keep them, and
  backups include them. Tapping **A** brings up the keyboard.
- EBaC now runs from /data/ebac, which the app sets up at each start.
- Built from EBaC commit `a800b41`.

## 2.1.14

- EBaC can read translations from other sources (verse numbers like
  [1:1], longer verses, a few more verses than the King James), and its
  Change translation screen pages through a long list of translations.
  The touch gestures support that screen: tap a translation, swipe up or
  down for the next or previous page, sideways to go back.
- Built from EBaC commit `ce8e59b`.

## 2.1.13

- The Information screen has a third page of diagnostic information:
  EBaC's version (the commit it was built from and its date, and this
  app's version), where it runs from, your search history file, the
  terminal type (TERM) and window size, the terminal library, and the
  system it runs on. The first page shows the commit too.
- Built from EBaC commit `1cb910e`.

## 2.1.12

- The Information screen's list of computers now says that EBaC ran on
  Windows with Cygwin, and that Windows 10 and 11 run it in WSL.
- Built from EBaC commit `49cfdc0`.

## 2.1.11

- Going back a book (**b**, or a two-finger swipe down) from Exodus, or
  from anywhere in Genesis, now goes to Genesis 1:1, instead of a screen
  of "This verse doesn't exist...". The same was fixed at the other end,
  for the next book (**f**) and the next screen in Revelation.
- At Genesis 1:1, going back a book or a verse beeps and stays; at the
  end of Revelation, going on a book or a screen does the same. A passage
  now stops after Revelation 22:21.
- Built from EBaC commit `f0df8fd`.

## 2.1.10

- While reading, swipe up with two fingers to jump to the next book, or
  down to go back to the previous one (like the **f** and **b** keys).
  Any length works. So one finger moves a verse (or a screen, with a long
  swipe), and two fingers a whole book.

## 2.1.9

- Editing by swiping sideways:
  - At the search prompt, a short swipe left or right moves the cursor
    one character; a long one goes to the start or the end of the line
    (like Home and End).
  - At the book name, chapter and verse prompts, a short swipe left
    erases the last character (like Backspace); a long one erases the
    whole entry.
  A long swipe is one across at least a third of the screen.

## 2.1.8

- At the search prompt, swipe down to bring back your previous search,
  and up for the next one, like the Up and Down arrow keys. Each swipe
  is one step, whatever its length, and keeps the keyboard hidden if it
  was. Tap the screen to bring the keyboard back to edit or run it.
- Built from EBaC commit `0624ec5`.

## 2.1.7

- The top of the list of search results can use the full width of the
  screen, so a word one letter longer still gets its count on a phone.
- Built from EBaC commit `33c482d`.

## 2.1.6

- At the top of the list of search results, the counted word is
  highlighted, as it is in the verses, instead of being in quotation
  marks. This saves two columns, so on a phone a longer word still gets
  its count.
- Built from EBaC commit `2a2e12d`.

## 2.1.5

- The top of the list of search results now says what its numbers are:
  **--Beginning of list-- 56 verses, "grass" 62 times**. The number of
  times is shown only for a search of one word alone; with several words
  or a book it would have counted the whole Bible, not this list, so
  only the number of verses is shown. On a narrow screen the number of
  times is left out rather than let the line wrap.
- "Begining" is now spelled correctly.
- Built from EBaC commit `61794e5`.

## 2.1.4

- In the list of search results, the prompt at the bottom no longer
  wraps onto a second line on a narrow screen such as a phone: it
  becomes **--More-- (Press ? for menu.)**. Wider windows show the whole
  line as before.
- Built from EBaC commit `2c22597`.

## 2.1.3

- The main menu choices are easier to tap: there's a blank line between
  them, and a tap goes to the nearest choice, so each one can be tapped
  anywhere over two rows. Exit still can't be tapped.
- Built from EBaC commit `50eb3b1`.

## 2.1.2

- A hidden phone keyboard now stays hidden when you swipe or tap a
  result, so you can read a full-height screen at a time. Before, the
  keyboard came back as the new screen was drawn, shrinking the window
  part way through: a page back then skipped the lines in between. While
  the keyboard is showing, swipes leave it showing; tapping anywhere else
  still brings it up.

## 2.1.1

- Swiping down now always goes back a verse or a page. Before, the
  terminal could also scroll back through old screens at the same time,
  showing the wrong text. The terminal no longer keeps lines that have
  scrolled off the top (EBaC redraws every screen itself, so nothing is
  lost), and it no longer scrolls on its own under a swipe.

## 2.1.0

- Touch gestures, so on a phone the keyboard is only needed for typing:
  - Main menu: tap **Change**, **View**, **Search** or **Information**.
    (Exit is not tappable, so a slightly missed tap can't close EBaC.)
  - Choosing a translation: tap one; swipe left or right to go back.
  - Search results: tap a result to read it; swipe up for the next page,
    down for the previous one; swipe left or right to go back.
  - Reading: swipe up or down to move one verse, or a long swipe for a
    whole screen; swipe left or right to go back to the results.
  - "Press any key" screens: tap anywhere.
  Taps on View and Search bring up the keyboard, since typing comes
  next; other gestures don't. Tapping anywhere else brings up the
  keyboard, as before.
- Built from EBaC commit `8cc97e6`.

## 2.0.8

- At the chapter and verse prompts, **m** types a minus sign (shown as
  "-"), so negative numbers need no keyboard switching on a phone.
- Built from EBaC commit `ff5e31c`.

## 2.0.7

- A chapter or verse of **0**, or a negative number, counts back from the
  start of the book: John 3:0 is John 2:25, Exodus chapter 0 is
  Genesis 50, John 3:-3 is John 2:22. Pressing Enter alone still means 1.
- Built from EBaC commit `72c9e62`.

## 2.0.6

- In the list of search results, a label can be typed even when its
  entry isn't on the screen any more: if hiding the phone's keyboard
  showed entries 3, 4 and 5, typing **3** still opens that entry once
  the keyboard is back. Past the end of the list, the help screen still
  appears.
- Built from EBaC commit `f44c797`.

## 2.0.5

- When the window changes size, such as when a phone's on-screen
  keyboard appears or goes away, a passage or a list of search results
  is redrawn at once to fill the new size, from the same first verse.
  **CTRL-L** redraws it too.
- Built from EBaC commit `6d0d039`.

## 2.0.4

- The concordance index is now built while installing, instead of
  being downloaded with EBaC; searching works exactly as before.
- Built from EBaC commit `75af1f9`.

## 2.0.3

- When viewing a passage, the chapter and verse can be typed with the
  letters **q w e r t y u i o p** for **1 2 3 4 5 6 7 8 9 0**, so a
  phone's on-screen keyboard can stay on letters.
- Built from EBaC commit `d5591ff`.

## 2.0.2

- In the list of search results, the letters **q w e r t y u i o** pick
  entries 1 to 9, like the digits above them, so on a phone you don't
  have to switch the on-screen keyboard to numbers.
- Entries 10 and up are now labelled **a b c d f g h j k l m s v z**,
  skipping letters that have another job on that screen.
- Built from EBaC commit `9215c24`.

## 2.0.1

- Each Home Assistant user now has their own search history, instead of
  one history shared by everyone. It is kept in the app's storage under
  that user's name, the way the Linux version keeps it in each user's
  home folder.
- History saved by 2.0.0, which was shared, is not carried over.

## 2.0.0

- First release of EBaC as a Home Assistant app.
- Opens from the **EBaC** button in the sidebar, for all users.
- Built from EBaC commit `74d9495` ([neilbrookins/ebac](https://github.com/neilbrookins/ebac)).
