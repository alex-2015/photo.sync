# Photo.sync

---

## About Photo.sync

Photo.sync is a simple command-line tool written in Perl that allow you to easily retrieve albums, playlist, photos and whatever media-content from different sources such as Flickr, Facebook, Tumblr and so on, and import to your online albums or to save them on your local computer.

## Dependencies

This tool is currently developed and tested  only in Linux systems (hence this works on any *nix environments with Perl support).

## Installation and Use

There isn't an installer (yet) or a fancy tool that does the work for you. So if you want to try this tool clone the repo and `./sync.pl --help`.

`asphyxia@bt:~/projects/photo.sync$ ./sync.pl --socket=flickr --url=http://www.flickr.com/photos/example/sets/123456/ --destination=/home/asphyxia/downloads/images/albums/``

## Contact and Feedback

If you'd like to contribute to Photo.sync or file a bug or feature request, please visit [its page on GitHub][1].

## License

Photo.sync is licensed under the [GNU GPL v3][2]([tldr][3]); that means you're allowed to copy, edit, change, hack, use all or any part of this project as you please *as long* as all parts of the project remains in the *public domain*.

  [1]: https://github.com/asphxia/photo.sync
  [2]: http://www.gnu.org/licenses/gpl.html
  [3]: http://www.tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3)