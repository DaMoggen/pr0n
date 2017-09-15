![pr0n-logo](https://i.imgur.com/6CpUrzT.png)
===============
[![Build Status](https://travis-ci.org/DaMoggen/pr0n.svg?branch=master)](https://travis-ci.org/DaMoggen/pr0n)
[![Coverage Status](https://coveralls.io/repos/github/DaMoggen/pr0n/badge.svg?branch=master)](https://coveralls.io/github/DaMoggen/pr0n?branch=master)
[![License: GPL v2](https://img.shields.io/badge/license-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

Pr0n is a lightweight photo gallery system written by [Sesse](https://github.com/sesse). It is used on a few different host names, most notably at [pr0n.sesse.net](pr0n.sesse.net)  to show images of various events.
The name "pr0n" was just seen as a very good fit for an image gallery.

Features
---------------
Mostly that it's no-nonsense and just works, without being in your way. 
- Dynamical rescaling of good quality for both thumbnails and images. 
- An easy-to-use HTML5 upload interface.
- Cache awareness and in general good performance 
- It has quite OK skinning capabilities, so it's able to adapt into different designs quite easily.

Modules
---------------
Module name    | Debian package | Usage
---------------|---------------|---------------
Starlet                    | starlet                   | PSGI web server
HTTP::Parser::XS           | libhttp-parser-xs-perl    | Faster Starlet
IO::File::WithPath         | libio-file-withpath-perl  | Sending files
PerlMagick                 | perlmagick                | Scaling etc.
MIME::Types                | libmime-types-perl        | Sending the right MIME types
DBD::Pg                    | libdbd-pg-perl            | PostgreSQL connection
Image::ExifTool            | libimage-exiftool-perl    | Parsing EXIF data
Crypt::Eksblowfish::Bcrypt | libcrypt-eksblowfish-perl | Verifying passwords
HTML::TagCloud             | libhtml-tagcloud-perl     | Tag cloud on /+tags/
jpegtran                   | libjpeg-progs             | Lossless JPEG rotation
dcraw                      | dcraw                     | NEF support
Qscale                     | N/A                       | Faster image scaling support

License
---------------
Pr0n is licensed under the GNU General Public License, version 2.  
See [LICENSE](LICENSE) for full details.
