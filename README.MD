## nirvana-sz

This is a repo for the archives of a high school magazine "Nirvana", operated
during 2009-2016, a fork of [this
post](https://hackmd.io/@uOwb5ZnlTnWuF0zwmCQ_5Q/B1446O0bX "this post"), which
is also saved [here](2023-01-28-archive-of-nirvana.md
"2023-01-28-archive-of-nirvana.md").


Previews of the pdf files should work on Github. To view or download
individual files, navigate to the file you wish to download, click on the
`Download` button.

To download the complete archive files, see **Releases** to the right, or run
the following command to clone the repo your local storage:

```
git clone https://github.com/delgh1/nirvana-sz.git
```

If you have not yet installed `git` on your operating system, use your
system's package manger to install it. For example, on Debian GNU/Linux:

```
sudo apt install git
```

or on Arch Linux:

```
sudo pacman -S git
```


For change logs, see Github's commit history.

[Nirvana's Wechat account timeline](https://nirvana-wechat.jing.rocks
"nirvana-wechat.jing.rocks") is hosted at `https://nirvana-wechat.jing.rocks`,
which you may also download from **Releases**.

#### Requirement:

To view the pdf files, you need:

- a pdf viewer. E.g., KDE Okular, Firefox.

- a file archiver to decompress the archive files. For `.7z` files, use KDE
  Ark or install [7-zip](https://7-zip.org) using your system's package
  manager to install `p7zip-full` (on Debian GNU/Linux).

### Known issues (**please report issues in the Github `Issues` section above**)

- Accessibility. The contents are mostly of moderate to low scan quality and
  have accessibility issues. Screen reader software may not work. ----> Hard
  to fix this is. Meditate on this I will.

- Mismatched cover and file name of `pdf/NirvanaYearly_2013-2014C.pdf`. ---->
  This has been addressed in `issue #1` and fixed in `commit eca7049`. There
  was an editorial issue that year and the cover of the magazine was
  incorrect. The fix also includes `pdf/NirvanaYearly_2015-2016.pdf`. Note
  that the archive file from 2018 contains incorrect file names.

- The quality of `pdf/NirvanaYearly_2014-2015.pdf` is very low. Rework
  needed. ----> Raised in `issue #3`. No plan to fix this. May reopen the
  issue once regaining physical access to the magazine. If anyone has the
  magazine in hand and has access to a scanner, please create a fork and a
  pull request. Thank you.

- Inconsistent timestamp and size of files ----> some files were modified
  (before 2022) without a version control. Also Github has a file size limit
  of 100MiB. Some smaller version of pdf files were used and "-s" is appended
  to each of those file names.
