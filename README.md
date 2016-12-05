# txt_to_srt
Adobe Encore TXT subtitle to SRT subtitle
**Usage**:
Open txt file  with text editor, copy all content to the texarea, then press "Convert"
**Source**:
```
00:01:12:13 00:01:13:12 lorem ipsum
00:01:13:12 00:01:15:04 dolor sit amet
00:01:15:04 00:01:17:01 ...
```

**Result**:
```
1
00:01:12,520 --> 00:01:13,480
lorem ipsum

2
00:01:13,480 --> 00:01:15,160
dolor sit amet

3
00:01:15,160 --> 00:01:17,40
...
```
