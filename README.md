# me2-gibbed-editor-facecode

<img alt="Cashmere Shepard" src="images/2008-11-26_154041.jpg" width="480px"/>

This is the \`official' internal facecode for my ME/ME2 femshep based
upon cracking the save file with Mass Effect 2 Gibbed Editor.

See http://masseffect.livejournal.com/656484.html

-
## Derived Table

Facial Structure | Internal Property | Float Value / Normal | Direction | Offset from Center
 --- | --- | --- | --- | :---:
Neck Thickness | neck_wide | 0.02000002 / 0.02 | RIGHT | 1
Face Size | shape_skinny | 0.03999998 / 0.02 | LEFT | 2
Cheek Width | cheek_BonesOut | 0.426666737 / 0.0533333 | RIGHT | 8
Cheek Bones | cheek_DepthFront | 0.426666737 / 0.0533333 | RIGHT<sup>[1](#footnote1)</sup> | 8
Cheek Gaunt | cheek_Gaunt | (0.72 / 0.026667) + 1 | N/A | 28
Ears Size | ears_large | 0.106666707 / 0.02667 | RIGHT | 4
Ears Orientation | ears_out | 0.4 / 0.02667 | RIGHT | 15
Eye Height | eyes_PosDown | 0.0266666543 / 0.0133 | LEFT | 2
Eye Width | eyes_Narrow | 0.05333331 / 0.02667 | LEFT | 2
Eye Depth | eyes_Forward | 0.4 / 0.02667 | RIGHT | 15
Brow Depth | eyes_browBack | 0.4 / 0.06667 | LEFT | 6
Brow Height | eyes_browDown | 0.399999976 / 0.033333 | LEFT | 12
Chin Height | jaw_chinDown | 0.0266666412 / 0.06667 | LEFT | 1
Chin Depth | jaw_chinIn | 0.4 / 0.026667 | LEFT | 15
Chin Width | jaw_chinWide | 0.28 / 0.04<sup>[2](#footnote2)</sup> | LEFT | 7
Jaw Width | jaw_wide | 0.2666668 / 0.06667 | RIGHT | 4
Mouth Depth | mouth_back | 0.5866667 / 0.0533333 | LEFT | 11
Mouth Width | mouth_narrow | 0.3 / 0.2 | LEFT | 15
Mouth Lip Size | mouth_lipsThin | 0.266666651 / 0.06667 | LEFT | 4
Mouth Height | mouth_Down | 0.55 / 0.03667 | LEFT | 15
Nose Height | nose_Down | 0.4 / 0.02667 | LEFT | 15
Nose Depth | nose_BottomIn | 0.173333317 / 0.0433 | LEFT | 4

-
### Note on a by-pixel comparison attempt

Before I discovered Gibbed Editor, I had painstakingly done a pixel
rendition, by comparing screenshots of my imported character and
the character being built in the character editor.

The result was suprisingly accurate, but obviously not totally
correct.  For historical purposes I record my best by \`eye' effort
here:

```
 743.HDP.NSK.26E.EWA.43F.18K.151.C1C.1B4.6G6.615
```

Compared to the actual:

```
743.HEP.PTK.16E.EWA.43F.19K.151.C1C.1C4.6G6.615
```


And a side-by-side comparison:

```
         -1    -2 -1    +1                       -1                      -1
          |     | |     |                         |                       |
          v     v v     v                         v                       v
7 4 3 . H D P . N S K . 2 6 E . E W A . 4 3 F . 1 8 K . 1 5 1 . C 1 C . 1 B 4 . 6 G 6 . 6 1 5 
7 4 3 . H E P . P T K . 1 6 E . E W A . 4 3 F . 1 9 K . 1 5 1 . C 1 C . 1 C 4 . 6 G 6 . 6 1 5 
```

-
#### Footnotes

- <a name="footnote1">[1](#derived-table)</a>: Article said go \`LEFT' but appears to be wrong.
- <a name="footnote2">[2](#derived-table)</a>: Article says to divide by \`0.06667; think it should be 0.04.

