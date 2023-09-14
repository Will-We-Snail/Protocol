This is the repo for the protocol spec for wws (Will We Snail).

Basic packet:
```
{
  int32 checksum, // crc32 checksum
  uint16 id,
  uint16 type,
  packet data...
}
```
