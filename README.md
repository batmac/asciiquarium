# Asciiquarium - a terminal aquarium

First... the *original* README:

```text
                              Asciiquarium v1.1
                    by Kirk Baucom <kbaucom@schizoid.com>
                          http://www.robobunny.com

Asciiquarium is an aquarium/sea animation in ASCII art.

Installation
------------

Asciiquarium is a single perl script, so all you have to do is make sure
it's executable and put it somewhere convenient, like /usr/local/bin or
/usr/local/games.

Requirements
------------

You must have the Term::Animation module, which you can get from
http://www.cpan.org. The Term::Animation module also requires the Curses
module, which you can also get from CPAN. This program will only run on
platforms that have a Curses library (so it won't work on Windows, but
you might get it to run under cygwin).

Usage
-----

There are no command line arguments.
While running:
	q	quit
	r	redraw (will recreate all entities)
	p	toggle pause

Contributors
------------

Pretty much all of the ASCII art was done by Joan Stark:
http://www.geocities.com/SoHo/7373/

Anything that she didn't do, I don't have a source for.
```

OK, we're in 2020 and there's a ton of simple ways to install [Perl][] modules
in a non-destructive way. Shameless plug: [Installing Perl Modules][]. In
this spirit... this fork includes also a `cpanfile` to ease the
installation of the needed modules (you will still need to ensure that the
system libraries will be in place).

This repository is a fork from [cmatsuoka's asciiquarium][], with new fish
species backported from the Android live wallpaper and other minor
improvements by Claudio Matsuoka. It also merges contributions found in
that repository's [Pull Requests][]:

- [Added objects from Kirk's version][] by [driechers][] with art originally by
  Kirk Baucom
- [Added yellow submarine][] by [driechers][] with art originally by Carl
  Pilcher as found at [https://ascii.co.uk/art/submarine][]
- [Add sword fish][] by [robert1003][] with art from
  [https://ascii.co.uk/art/fish][]

[Perl]: https://www.perl.org/
[Installing Perl Modules]: https://github.polettix.it/ETOOBUSY/2020/01/04/installing-perl-modules/
[cmatsuoka's asciiquarium]: https://github.com/cmatsuoka/asciiquarium
[Pull Requests]: https://github.com/cmatsuoka/asciiquarium/pulls
[robert1003]: https://github.com/robert1003
[Add sword fish]: https://github.com/cmatsuoka/asciiquarium/pull/12
[https://ascii.co.uk/art/fish]: https://ascii.co.uk/art/fish
[driechers]: https://github.com/driechers
[Added yellow submarine]: https://github.com/cmatsuoka/asciiquarium/pull/6
[https://ascii.co.uk/art/submarine]: https://ascii.co.uk/art/submarine
[Added objects from Kirk's version]: https://github.com/cmatsuoka/asciiquarium/pull/5
