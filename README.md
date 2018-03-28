# Flatpak for [D-Feet](https://wiki.gnome.org/Apps/DFeet)

D-Feet is an easy to use D-Bus debugger. D-Feet can be used to inspect D-Bus interfaces of running programs and invoke methods on those interfaces.

## Notes

* `0001-Rename-the-icons-appdata-and-desktop-files.patch`,
  `0003-build-Install-appstream-metadata-to-non-deprecated-l.patch`,
  `0004-Do-not-use-hyphen-for-the-reverse-DNS-names.patch`:
  already merged upstream. We use `"rm-configure": true` in the manifest to
  cause `autogen.sh` to be re-run.
* `0005-Set-icon_name-to-org.gnome.dfeet.patch`: already merged upstream.

## Credits

Derived from the [upstream manifest for D-Feet master](https://git.gnome.org/browse/d-feet/tree/org.gnome.d-feet.json), written by Mathieu Bridon.
