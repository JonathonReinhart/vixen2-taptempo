vixen2-taptempo
===============

Tap Tempo plugin for Vixen 2.x

A well-chosen event period can make all the difference when sequencing complex, fast-moving pieces (like a lot of TSO). It is optimal to choose an event period length such that the events line up to the beats in the song.

For example, at 150 BPM, each beat lasts exactly 400msec, so setting the event period to 50 msec allows you to have exactly 8 events per beat. In other words, one event corresponds to one 32nd note exactly.

Since Vixen's event period lengths must be integer values (and a song rarely holds a perfectly constant tempo), your sequences will rarely "match-up" perfectly. You'll have to insert an occasional extra event if your beats are a bit too fast (or remove one if too slow).

This plugin helps you set up the optimal event period directly in Vixen. It can also insert beat marks onto a selected channel.


Original JS code derived from http://www.all8.com/tools/bpm.htm
