
  DIRECTORY BOOKMARKS FOR BASH (version 1.6)

  b  [bookmark [dir]]      : bookmark a directory
                               <no option>   bookmark the current directory
                               bookmark      use bookmark for current directory
                               bookmark dir  use bookmark for given directory
  bl [-d][-t][regex]       : show the bookmark list (tab compl.)
                               -d            dictionary order
                               -t            show time stamps
                               regex         list bookmarks matching regex
  bm bookmark              : resolve a bookmark (tab compl.)
  g  [bookmark]            : go to a bookmark or named directory (tab compl.)
                               <no option>   go to the home directory
                               bookmark      go to the bookmarked directory
  p  [bookmark]            : push bookmark / directory onto dir stack (tab compl.)
                               bookmark      pushd bookmarked directory
  r  [bookmark|regex]      : remove a saved bookmark(s) (tab compl.)
                               bookmark      remove bookmark
                               regex         remove bookmarks matching regex

  gh [bookmark]            : go to a Midnight Commander hotlist entry (tab compl.)
                             use ssh for a SHell filesystem link
                               <no option>   go to the home directory
                               bookmark      go to the bookmarked directory
  hl [-d][regex]           : Midnight Commander directory hotlist (tab compl.)
                               -d            dictionary order
                               regex         list bookmarks matching regex

  bookmarks [-h]           : this help message
  bookmarks  -b bmfile     : use bookmark file bmfile
  bookmarks  -i            : import Midnight Commander hotlist
  bookmarks  -r [bash|mc]  : reread Bash/MC bookmark file
  bookmarks  -v            : display the version of this script
  bookmarks  -e [bookmark] : export a shell variable from every bookmark
                           : export a shell variable from given bookmark

  The actual bookmark file is '/home/mbalmer/.bookmarks.data'.
  Reguluar expressions are explained in  manual regex(7).
  
