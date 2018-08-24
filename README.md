# Enigma
Encryption Software

## Algorithm
(In a stream)

**Encryption**:
`byte += (size_of_stream * selected_pass_char)^byte_infront + byte_location`

**Decryption**:
`byte -= (size_of_stream * selected_pass_char)^byte_infront + byte_location`
