munki-language-module
=====================

Language Module for use with TextWrangler or BBEdit to syntax highlight Munki's pkgsinfo plist files.

This will syntax highlight Munki's supported keys to visually validate proper syntax when hand editing files.

To install:<br>
1) Copy the munki_langauage_module.plist to ~/Library/Application Support/TextWrangler/Language Modules/  or ~/Library/Application Support/BBEdit/Language Modules/<br>
2) Restart TextWrangler or BBEdit. <br>
3) Adjust keyword and predefined syntax highlighting colors in the TextWrangler or BBEdit preferences if necessary.<br>


This module is set to treat all files that end in .plist as munki pkgsinfo files on open.  
If that is not desirable and you'd rather have standard XML highlighting, then remove the BBLMSuffixMap key from the plist.

Inside TextWrangler you can manually choose the language syntax highlighting from the options at the bottom of the TextWrangler window.  Choose "Munki Pkginfo" to apply the highlighting.
