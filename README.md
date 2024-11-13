# LZtrad
Analysis of traditional Irish music via LEMPEL-ZIV

To run (preferably in a JUPYTER notebook), each program necessitates an input file called either "reels.txt" or "jigs.txt".
The content of (for example) reels.txt can be taken from the webpages / database THESESSION.ORG: Therein, find a tune, and click on "ABC" to get text format. Then copy-and-paste in to the file reels.txt. For example, the first 50 lines or so of my "reels.txt" are:
__________________________________________________________________________________________
X: 1
T: The Ashplant
R: reel
M: 4/4
L: 1/8
K: Edor
BE~E2 BAGA|BE~E2 ~G3A|BE~E2 BABd|gedB A2GA|
BE~E2 BAGA|BE~E2 ~G3A|~B3A (3Bcd ef|gedB A2GA||
B2eB fBeB|~B2ed BAGA|B2eB ~f3d|efdB A2GA|
B2eB fBeB|~B2ed BAGA|(3Bcd ef ~g3a|gedB A2GA||

X: 1
T: Banshee, The
C: James McMahon
Z: Jeremy
S: https://thesession.org/tunes/8#setting8
R: reel
M: 4/4
L: 1/8
K: Gmaj
|:G2 GD EDEG|AGAB d2 Bd|eged BAGA|BAGE EDDE|
G2 GD EDEG|AGAB d2 Bd|eged BAGA|BAGE ED D2:|
|:ea a2 efgf|eBBA B2 Bd|eB B2 efgf|eBBA B2 Bd|
ea a2 efgf|eBBA B2 Bd|eged BAGA|BAGE EDD2:|

X: 2
T: The Bird In The Bush
R: reel
M: 4/4
L: 1/8
K: Gmaj
|:d2eB dB~B2|dBAB G2AG|EA~A2 BGGA|BG (3Bde g2ge|
d2eB dB~B2|dBAB ~G3E|DEGA B2Bc|dBAc BG~G2:|
|:(3Bcd ef g2fg|afdf gfed|Bdef ~g3b|agab ~g3a|
bg~g2 agef|~g3e dB~B2|DEGA B2Bc|dBAc BG~G2:|

X: 2
T: The Blacksmith's
R: reel
M: 4/4
L: 1/8
K: Gmaj
G2 GG DGBG|G2 Bd cAFA|G2 GG DGBG|AFDF ABcA|
Gz G2 DGBG|G2 Bd cAFA|d2 cA BGAF|DEED Acdc:|
d2 B2 dBGB|dB B2 deed|dB B2 dBGB|AFDF ABcA|
d2 B2 dBGB|dB B2 deed|d2 cA BGAF|DEED ABcA:|
____________________________________________________________________________

The PYTHON code itself does all the parsing - at the end a histogram is drawn.
