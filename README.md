A browserify module to convert keydown events to a string.

# Usage

    var keymap = require('keymap')

    document.getElementsByTagName("input")[0].addEventListener("keydown", function(event) {
      console.log(keymap(event))
    })

# Examples

  * `A-C-r`   - control-alt-r
  * `!`       - shift-1
  * `C-a`     - control-a
  * `S-enter` - shift-enter

