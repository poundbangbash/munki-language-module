munki-language-module
=====================

Language Module for use with TextWrangler or BBEdit to syntax highlight Munki's pkgsinfo plist files.

This will syntax highlight Munki's supported keys to visually validate proper syntax when hand editing files.

To install:
    Copy the munki_langauage_module.plist to ~/Library/Application Support/TextWrangler/Language Modules/ 
    Restart TextWrangler.
    Adjust keyword and predefined syntax highlighting colors in the TextWrangler preferences if necessary.

This module is set to treat all files that end in .plist as munki pkgsinfo files.  
If that is not desirable and you'd rather have standard XML highlighting, then remove the BBLMSuffixMap key from the plist.

Inside TextWrangler you can manually choose the language syntax highlighting from the options at the bottom of the TextWrangler window.  Choose "Munki Pkgsinfo" to apply the highlighting.
