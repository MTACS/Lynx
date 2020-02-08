## Lynx Localizations

To add a new langauge to Lynx, fork or clone this repository. Create a new folder called "ID".lproj, where "ID" is the identifier for your language. For example, English is "en.lproj", French is "fr.lproj". For a full list of language identifiers refer to [this.](https://www.ibabbleon.com/iOS-Language-Codes-ISO-639.html) Copy each ".strings" file from en.lproj to your new .lproj folder. Text inside of <key></key> must not change, only the text inside the <string></string> under each key. Use the example below. Finally, to merge your language with Lynx, make a pull request with the changes or send me the files directly, via [email](mailto:mtac@mtac.app) or [Twitter](https://twitter.com/mtac8)

```objective-c

// Example of English

<plist version="1.0">
<dict>
    <key>ENABLE_TWEAK</key> // This must not be changed
    <string>Enable Tweak</string> // Add your language's text here
</dict>
</plist>
```

```objective-c

// Example of French

<plist version="1.0">
<dict>
    <key>ENABLE_TWEAK</key> // This must not be changed
    <string>Activé</string> // Localized text
</dict>
</plist>
```

### Fully Localized Sections

- [x] Main Tweak Page
- [x] System Wide Section
- [x] Lockscreen Section
- [x] App Switcher Section
- [x] Status Bar Section
- [x] Control Center Section
- [x] Today View Section
- [x] Messages Section
- [x] Settings Section
- [x] Photos Section
- [ ] Safari Section
- [ ] App Store Section
- [ ] Camera Section
- [ ] Phone Section
- [ ] CarPlay Section
- [ ] Experimental Section
- [ ] YouTube Section
- [ ] SoundCloud Section
- [ ] Instagram Section
