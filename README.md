ESaaS screencast transcripts
======================

The ESaaS book includes over 20 screencasts to help illustrate working with SaaS tools.

This repo serves as a central location for .srt (transcript) files for captioning the screencasts.  Our hope is that others will be inspired to help us create and translate them.

The repo is organized according to the chapters of the ESaaS book.  Within each chapter directory are directories for each language.  Finally, inside each of those are the .srt files.  The .srt format is staggeringly simple: the file consists of a series of elements like so:

```txt
1
00:02:17,440 --> 00:02:20,375
Senator, we're making
our final approach into Coruscant.

2
00:02:20,476 --> 00:02:22,501
Very good, Lieutenant.
```

Each element consists of:
0. A number indicating the sequence of the subtitles, starting from 1
1. The start and end times during which this subtitle should be displayed, as hour:minute:second,frame  - for our purposes, it's fine to always use 000 as the frame number, as long as the intervals don't overlap
2. The text of the caption - line breaks may or may not be honored - terminated by a blank line.

Please help us translate these transcripts into other languages!  Contact sjoseph@hpu.edu to volunteer!
