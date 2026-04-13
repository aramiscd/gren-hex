# hex

Convert integers to and from hexadecimal strings in Gren.

This project is a Gren port of [rtfeldman/elm-hex](https://github.com/rtfeldman/elm-hex).

    -- Convert a hexdecimal string such as "abc94f" to a decimal integer.

    Hex.fromString "a5" == Ok 165
    Hex.fromString "hat" == Err "invalid hexadecimal string"


    -- Convert a decimal integer to a hexdecimal string such as `"abc94f"`.

    Hex.toString 165 == "a5"
