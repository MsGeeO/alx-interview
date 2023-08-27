About 0x04-utf8_validation

UTF-8 solves the problem of multiple zeros in a string. It starts by just taking ASCII, i.e. if you have something under 128 that can just be expressed as 7 digits, you put down a zero & then you put the same numbers that you would otherwise.

UTF-8 is backward compatible. You can move backwards & forward really easily. You don't have to do index when the character starts.

If you're halfway through a string and you want to go back one character. You will look for the previous header.
