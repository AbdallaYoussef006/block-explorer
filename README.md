# Block Explorer

A browser tool that reads your university's course-block PDFs and shows you, at a glance, which block actually fits the courses you want to take.

Course registration usually means opening a dozen block PDFs side by side and redrawing a timetable by hand. This does that part for you.

**→ [Open Block Explorer](https://AbdallaYoussef006.github.io/block-explorer/)**

---

## What it does

- **Reads the PDFs directly.** Drop in one file, several at once, or the merged file containing every block. It extracts each session automatically: day, time, course, lecture or tutorial, section, room and instructor. No typing.
- **Scores every block against your courses.** Pick your courses and each block shows how many of them it covers.
- **Draws your week.** Every block renders as a weekly timetable with your courses highlighted and everything else dimmed.
- **Flags clashes.** Overlapping sessions among your own courses are outlined before you commit to them.
- **Ranks all blocks side by side** — coverage, days on campus, earliest and latest class, weekend sessions, conflicts.
- **Everything is editable**, with a full history you can undo, and it survives closing the page.

## How to use it

1. Open the link above.
2. Drag your block PDFs onto the drop zone (or click to browse).
3. Add the courses you plan to take — pick them from the list the import builds, or type them.
4. Compare blocks in the grid, or open **Compare all** for the ranking.

## Privacy

Everything runs in your browser. **No file is ever uploaded** — the PDFs are read locally and your schedule is saved only in your own browser's storage. There is no server, no account, and no tracking. It works offline once the page has loaded, and two people using it never see each other's data.

Use **Export** to save a backup, since clearing your browser data will clear your schedule.

## Notes

- Works on desktop and mobile, in light or dark mode.
- Built as a single HTML file with no dependencies and no build step — the PDF reader is written from scratch, so nothing is fetched from a CDN.
- It reads text-based PDFs (the kind universities export). Scanned PDFs would need OCR and are not supported.

## Contributing

Issues and pull requests are welcome — particularly for other universities' block formats.

## License

MIT
