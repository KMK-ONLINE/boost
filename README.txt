This archive contains selected parts of boost 1.57.0, obtained from:
  http://sourceforge.net/projects/boost/files/boost/1.57.0/boost_1_57_0.tar.bz2/download
  md5: 1be49befbdd9a5ce9def2983ba3e7b76

This process is automated by Makefile.sync

Vanilla subsets of the library are extracted using the bcp tool and
stored in the "upstream" branch.  Any modifications (for example, to
support building on wp8, or fixing bugs) should be made in the master
branch.

The list of local modifications can then be examined using:
  git log origin/master ^origin/upstream
