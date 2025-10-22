# My custom ZMK Configuration for the MoErgo Glove80

## Links
- [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)
- The [official MoErgo Glove80 Support](https://moergo.com/glove80-support) web site.
- The [official ZMK Documentation](https://zmk.dev/docs) web site.
- The [official Glove80 ZMK Distribution](https://github.com/moergo-sc/zmk).
 
## Building & Flashing
1. Edit the keymap file(s)
2. Push change to trigger the GitHub Build Action
3. Click "Actions" in the main navigation, and in the left navigation click the "Build" link.
3. Select the desired workflow run in the centre area of the page (based on date and time of the build you wish to use).
4. After clicking the desired workflow run, you should be presented with a section at the bottom of the page called "Artifacts". This section contains the results of your build, in a file called "glove80.uf2"
5. Download the glove80.uf2
6. Flash the firmware to Glove80 according to the user documentation on the official Glove80 Glove80 Support website (linked above)
