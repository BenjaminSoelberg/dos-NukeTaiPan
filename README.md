<pre>

     Nuke TAIPAN.438 version 2.3  [1/1]
───────────────────────────────────────────
 Get rid of the TAIPAN virus once for all.

   4 options for scanning the HD or FDD.
          Full protection system.
    100% hit rate of killing the virus.
         New plug and play concept.

       FULLY FREEWARE. JUST USE IT ! 
   Any comment ? Write bugsy@cybernet.dk
   MADE FOR THE PC PROFESSIONEL MAGAZINE
───────────────────────────────────────────
 by ▄─▄ ▄   ▄─▄ ▄─▄ ▄─▄ ▄─▄ ▄ ▄─▄ ▄─▄
    █ █ █─▄ ▀─▄ █─  ▀─▄ ▀─▄ ▄ █ █ █ █
    █ █ █ █ ▄ █ █   ▄ █ ▄ █ █ █ █ █ █
    ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀ ▀▀▀ ▀ ▀ 1998
───────────────────────────────────────────
          Now its Pentium safe



                         Tai-Pan nuker INTRODUCTION.

The Tai-pan nuker locates and repairs all infected files with Tai-pan (Whisper),
depending on witch options you use. If the Tai-pan nuker (TPN) is infected, it
will notify the user. We have described below, how to use the TPN.

If you want to scan the whole diskdrive then write :

  NUKETAIP [diskdrive] /s
  eg. NUKETAIP C:     /s
  or  NUKETAIP C:\    /s
  or  NUKETAIP C:\*.* /s

If you only want to scan a directory then write :

  NUKETAIP [directory]
  eg. NUKETAIP \testdir\
  or  NUKETAIP \testdir\*.*

But don't write NUKETAIP \testdir because the scanner thinks that 'testdir' is
a file and not a directory.

Our advise is that you scan all executeable files with the extension
'EXE' on your diskdrive. To have full control over the scanning, use the beep
and prompt option. Let's say that we would like to scan drive 'C:', then the
command will look something like this :

  NUKETAIP C:\*.exe /s /p /b

Now every EXE-files on drive 'C:' will be scanned for the virus 'Tai-Pan'
(also named 'Whisper').

                            Tai-Pan virus INFO.

Here is some info about what we have descovered about this virus. The info is
found by activating the virus and disassembling it.

1.  This virus only infect files under 64KB
2.  It only infect EXE typed file with the identifier 'MZ' and NOT 'ZM'
3.  The virus can't deal with EXE-file that has an overlay.
4.  It does'nt do any harm like formatting the disk, trashing any sectors.
5.  The virus size is only 438 bytes, witch is quite small. 
6.  The programmer is NOT a first-time virus-maker. Nice code Whisper !
7.  No mutation or any stelth function, neither any encryption.
8.  The virus uses Int 21h, function 7BCEh as an install check.
9.  It's a Terminate and Stay Resident (TSR) and hooks the INT 21h, Function 
    'Load and Execute'.
10. The virus has a ID string witch looks like this : [Whisper presentere TAI-PAN]
    That's why we think that the virus is from Sweden, we where told that
    Whisper (the name of the programmer) were from Stockholm (capital in sweden).

                                 LICENS.

If by some mysterious coincidence an BUG should occur, we would be glad to hear
of it, so we can fix the bug and release a new (better) version of the TPN.

We hope that you can benefit from this utility. This program is FreeWare
and may be copied freely, but we don't take any responsibility what so ever
for any side effects the program may have.

Written By BUGSY & SPAWN of OBSESSION.
EMail : bugsy@cybernet.dk
</pre>
