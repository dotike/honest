true(1) and false(1) - back to the future edition.

The code found here was born out of discourse at: "The Classical Code Reading Group of Stockholm, NYC*BUG Mix Tape Edition", October 7, 2015.

Wietse Venema recalled that old UNIX true(1) was merely an empty executable file.  This was an era before there was even a shell bang to disambiguate which shell will execute the program.  The false(1) executable was a mere 7 bytes in one line, 'exit 1'.

Wietse also recalled the moment of comedic personal horror when, sometime in the 80's, he saw a big block of copyright text in the true(1) program, followed by, no lines of code.  He recalled that later, seeing true(1) implemented in C was similarly shocking.

--
The code here, (if you can call it that), should run on any UNIX, has been tested and runs on:

  FreeBSD
  OpenBSD
  MacOSX
  Ubuntu
  CentOS

More platforms, and any cases where this code breaks, would be much appreciated.

If you like what you see, submit a patch submissions to every UNIX you can touch.  Most *NIX systems would accept these patches, perhaps with the exception of GNU utilities- where long opts are manditory.
