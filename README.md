Once Coypu is installed in your image, 

Start PureData and open the _moofData.pd_ patch.

Turn on the DSP/

Copy and paste the following script in your Playground. Select all the text and press CMD+D (CTRL + D on Windows and Linux).
```Smalltalk
['P' toLocal: 'keyPressed'.
0.117094 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.787826 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.028015 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.61851 seconds wait.

'EQUAL' toLocal: 'keyPressed'.
0.397361 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.338465 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.007312 seconds wait.

'P' toLocal: 'keyPressed'.
0.248621 seconds wait.

'E' toLocal: 'keyPressed'.
0.139021 seconds wait.

'R' toLocal: 'keyPressed'.
0.190784 seconds wait.

'F' toLocal: 'keyPressed'.
0.123203 seconds wait.

'O' toLocal: 'keyPressed'.
0.119803 seconds wait.

'R' toLocal: 'keyPressed'.
0.12792 seconds wait.

'M' toLocal: 'keyPressed'.
0.19271 seconds wait.

'A' toLocal: 'keyPressed'.
0.25601 seconds wait.

'N' toLocal: 'keyPressed'.
0.101068 seconds wait.

'C' toLocal: 'keyPressed'.
0.076389 seconds wait.

'E' toLocal: 'keyPressed'.
0.149063 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.329218 seconds wait.

'U' toLocal: 'keyPressed'.
0.296375 seconds wait.

'N' toLocal: 'keyPressed'.
0.122213 seconds wait.

'I' toLocal: 'keyPressed'.
0.405771 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.698478 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.634927 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.213667 seconds wait.

p := Performance uniqueInstance .
'p := Performance uniqueInstance .' toLocal: 'evaluatedCommand'.
0.106254 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.002287 seconds wait.

'D' toLocal: 'keyPressed'.
0.297374 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.215731 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.6132 seconds wait.

'P' toLocal: 'keyPressed'.
0.149761 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.209755 seconds wait.

'P' toLocal: 'keyPressed'.
0.132129 seconds wait.

'E' toLocal: 'keyPressed'.
0.050023 seconds wait.

'R' toLocal: 'keyPressed'.
0.213727 seconds wait.

'F' toLocal: 'keyPressed'.
0.244636 seconds wait.

'O' toLocal: 'keyPressed'.
0.170298 seconds wait.

'R' toLocal: 'keyPressed'.
1.451438 seconds wait.

'M' toLocal: 'keyPressed'.
0.158026 seconds wait.

'E' toLocal: 'keyPressed'.
0.116486 seconds wait.

'R' toLocal: 'keyPressed'.
0.630043 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.114585 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.362045 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.464725 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.004844 seconds wait.

'P' toLocal: 'keyPressed'.
0.245607 seconds wait.

'E' toLocal: 'keyPressed'.
0.159789 seconds wait.

'R' toLocal: 'keyPressed'.
0.227425 seconds wait.

'M' toLocal: 'keyPressed'.
0.413494 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.140497 seconds wait.

'F' toLocal: 'keyPressed'.
0.53357 seconds wait.

'O' toLocal: 'keyPressed'.
0.16972 seconds wait.

'R' toLocal: 'keyPressed'.
0.184585 seconds wait.

'M' toLocal: 'keyPressed'.
0.089522 seconds wait.

'E' toLocal: 'keyPressed'.
0.095469 seconds wait.

'R' toLocal: 'keyPressed'.
0.388275 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.395054 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.464944 seconds wait.

'L' toLocal: 'keyPressed'.
0.056591 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.199305 seconds wait.

'O' toLocal: 'keyPressed'.
0.134566 seconds wait.

'C' toLocal: 'keyPressed'.
0.237492 seconds wait.

'A' toLocal: 'keyPressed'.
0.137004 seconds wait.

'L' toLocal: 'keyPressed'.
0.126258 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.560624 seconds wait.

'N' toLocal: 'keyPressed'.
0.183821 seconds wait.

'E' toLocal: 'keyPressed'.
0.08232 seconds wait.

'W' toLocal: 'keyPressed'.
0.533305 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.316061 seconds wait.

p performer: PerformerLocal new.
'p performer: PerformerLocal new.' toLocal: 'evaluatedCommand'.
0.106225 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.001702 seconds wait.

'D' toLocal: 'keyPressed'.
0.361894 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.325626 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.264835 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.496046 seconds wait.

'1' toLocal: 'keyPressed'.
0.386034 seconds wait.

'6' toLocal: 'keyPressed'.
0.536988 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.242713 seconds wait.

'D' toLocal: 'keyPressed'.
0.295925 seconds wait.

'O' toLocal: 'keyPressed'.
0.081073 seconds wait.

'W' toLocal: 'keyPressed'.
0.276143 seconds wait.

'N' toLocal: 'keyPressed'.
0.184685 seconds wait.

'B' toLocal: 'keyPressed'.
0.110589 seconds wait.

'E' toLocal: 'keyPressed'.
0.280183 seconds wait.

'A' toLocal: 'keyPressed'.
0.10305 seconds wait.

'T' toLocal: 'keyPressed'.
1.035829 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.41404 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.696234 seconds wait.

'T' toLocal: 'keyPressed'.
0.194473 seconds wait.

'O' toLocal: 'keyPressed'.
0.388189 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.000831 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.24596 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.319495 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.892019 seconds wait.

'3' toLocal: 'keyPressed'.
0.000558 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.288234 seconds wait.

'K' toLocal: 'keyPressed'.
0.148098 seconds wait.

'I' toLocal: 'keyPressed'.
0.152941 seconds wait.

'C' toLocal: 'keyPressed'.
0.109198 seconds wait.

'K' toLocal: 'keyPressed'.
0.627745 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.149127 seconds wait.

16 downbeats to: #kick.
'16 downbeats to: #kick.' toLocal: 'evaluatedCommand'.
0.121934 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.001287 seconds wait.

'D' toLocal: 'keyPressed'.
0.384317 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.373013 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.658712 seconds wait.

'1' toLocal: 'keyPressed'.
0.2721 seconds wait.

'6' toLocal: 'keyPressed'.
0.104407 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.328107 seconds wait.

'B' toLocal: 'keyPressed'.
0.189491 seconds wait.

'A' toLocal: 'keyPressed'.
0.07909 seconds wait.

'N' toLocal: 'keyPressed'.
0.084623 seconds wait.

'D' toLocal: 'keyPressed'.
1.365306 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.337725 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.595089 seconds wait.

'T' toLocal: 'keyPressed'.
0.303002 seconds wait.

'O' toLocal: 'keyPressed'.
0.345164 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.000648 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.156849 seconds wait.

'SPACE' toLocal: 'keyPressed'.
1.132892 seconds wait.

'3' toLocal: 'keyPressed'.
0.010075 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.28418 seconds wait.

'P' toLocal: 'keyPressed'.
0.131244 seconds wait.

'E' toLocal: 'keyPressed'.
0.176726 seconds wait.

'R' toLocal: 'keyPressed'.
0.238192 seconds wait.

'C' toLocal: 'keyPressed'.
0.830181 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.39586 seconds wait.

16 banda to: #perc.
'16 banda to: #perc.' toLocal: 'evaluatedCommand'.
0.099745 seconds wait.

'D' toLocal: 'keyPressed'.
0.026859 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.403164 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
1.731721 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.197519 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.564935 seconds wait.

'P' toLocal: 'keyPressed'.
0.17637 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.130228 seconds wait.

'P' toLocal: 'keyPressed'.
0.237589 seconds wait.

'L' toLocal: 'keyPressed'.
0.228518 seconds wait.

'A' toLocal: 'keyPressed'.
0.082499 seconds wait.

'Y' toLocal: 'keyPressed'.
0.689587 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.195435 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.321942 seconds wait.

'RETURN' toLocal: 'keyPressed'.
2.919692 seconds wait.

'5' toLocal: 'keyPressed'.
0.285097 seconds wait.

'1' toLocal: 'keyPressed'.
0.313576 seconds wait.

'2' toLocal: 'keyPressed'.
0.227911 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.765504 seconds wait.

'B' toLocal: 'keyPressed'.
0.244486 seconds wait.

'A' toLocal: 'keyPressed'.
0.138317 seconds wait.

'R' toLocal: 'keyPressed'.
0.1238 seconds wait.

'S' toLocal: 'keyPressed'.
0.681488 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.555033 seconds wait.

p playFor: 512 bars.
'p playFor: 512 bars.' toLocal: 'evaluatedCommand'.
0.061912 seconds wait.

'D' toLocal: 'keyPressed'.
0.040826 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.770589 seconds wait.

'UP' toLocal: 'keyPressed'.
1.353548 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.735688 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.000672 seconds wait.

'UP' toLocal: 'keyPressed'.
0.249294 seconds wait.

'UP' toLocal: 'keyPressed'.
4.719707 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.171496 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.760225 seconds wait.

'RETURN' toLocal: 'keyPressed'.
2.360941 seconds wait.

'1' toLocal: 'keyPressed'.
0.7073 seconds wait.

'6' toLocal: 'keyPressed'.
0.191286 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.238649 seconds wait.

'P' toLocal: 'keyPressed'.
0.19812 seconds wait.

'L' toLocal: 'keyPressed'.
0.136541 seconds wait.

'E' toLocal: 'keyPressed'.
0.228196 seconds wait.

'N' toLocal: 'keyPressed'.
0.158478 seconds wait.

'A' toLocal: 'keyPressed'.
0.485157 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.377409 seconds wait.

'T' toLocal: 'keyPressed'.
0.177614 seconds wait.

'O' toLocal: 'keyPressed'.
0.947624 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.036999 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.139075 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.765126 seconds wait.

'3' toLocal: 'keyPressed'.
0.028155 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.250182 seconds wait.

'P' toLocal: 'keyPressed'.
0.294327 seconds wait.

'S' toLocal: 'keyPressed'.
0.178197 seconds wait.

'G' toLocal: 'keyPressed'.
0.957372 seconds wait.

'UP' toLocal: 'keyPressed'.
0.000619 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.212012 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.79051 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.155077 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.110621 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.106019 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.277443 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.137543 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.118702 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.38984 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.634068 seconds wait.

'P' toLocal: 'keyPressed'.
0.025613 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.153054 seconds wait.

'L' toLocal: 'keyPressed'.
0.269941 seconds wait.

'U' toLocal: 'keyPressed'.
0.114272 seconds wait.

'S' toLocal: 'keyPressed'.
2.757334 seconds wait.

'9' toLocal: 'keyPressed'.
0.024135 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
2.419586 seconds wait.

'0' toLocal: 'keyPressed'.
0.045442 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.648603 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.755629 seconds wait.

'LEFT' toLocal: 'keyPressed'.
0.306361 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.441604 seconds wait.

'N' toLocal: 'keyPressed'.
0.228027 seconds wait.

'O' toLocal: 'keyPressed'.
0.436937 seconds wait.

'T' toLocal: 'keyPressed'.
0.096813 seconds wait.

'E' toLocal: 'keyPressed'.
0.197298 seconds wait.

'S' toLocal: 'keyPressed'.
0.679125 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.01857 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.182697 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.685829 seconds wait.

'APOSTROPHE' toLocal: 'keyPressed'.
0.706351 seconds wait.

'4' toLocal: 'keyPressed'.
0.26305 seconds wait.

'8' toLocal: 'keyPressed'.
0.150059 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.309312 seconds wait.

'COMMA' toLocal: 'keyPressed'.
0.094623 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.642765 seconds wait.

'5' toLocal: 'keyPressed'.
0.146178 seconds wait.

'1' toLocal: 'keyPressed'.
0.303919 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.359511 seconds wait.

'COMMA' toLocal: 'keyPressed'.
0.055654 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.552426 seconds wait.

'3' toLocal: 'keyPressed'.
0.123402 seconds wait.

'6' toLocal: 'keyPressed'.
0.505642 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
5.109457 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.246449 seconds wait.

'T' toLocal: 'keyPressed'.
0.340277 seconds wait.

'O' toLocal: 'keyPressed'.
0.284242 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.000678 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.08731 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.776069 seconds wait.

'3' toLocal: 'keyPressed'.
0.047277 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.320149 seconds wait.

'P' toLocal: 'keyPressed'.
0.23848 seconds wait.

'S' toLocal: 'keyPressed'.
0.163156 seconds wait.

'G' toLocal: 'keyPressed'.
0.68916 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.463984 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.210081 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.197675 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.162878 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.122142 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.300054 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.171067 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.154354 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.14937 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.602307 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.604253 seconds wait.

(16 plena to: #psgPlus) notes: '48 , 51 , 36'.
'(16 plena to: #psgPlus) notes: ''48 , 51 , 36''.' toLocal: 'evaluatedCommand'.
0.087314 seconds wait.

'D' toLocal: 'keyPressed'.
0.049765 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
2.783044 seconds wait.

'RETURN' toLocal: 'keyPressed'.
2.044499 seconds wait.

'P' toLocal: 'keyPressed'.
0.074958 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.280587 seconds wait.

'S' toLocal: 'keyPressed'.
0.143824 seconds wait.

'O' toLocal: 'keyPressed'.
0.178211 seconds wait.

'L' toLocal: 'keyPressed'.
0.121499 seconds wait.

'O' toLocal: 'keyPressed'.
0.256747 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.025044 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.134407 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.942831 seconds wait.

'3' toLocal: 'keyPressed'.
0.000843 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
1.172566 seconds wait.

'P' toLocal: 'keyPressed'.
0.220422 seconds wait.

'S' toLocal: 'keyPressed'.
0.300927 seconds wait.

'G' toLocal: 'keyPressed'.
0.329051 seconds wait.

'P' toLocal: 'keyPressed'.
0.055114 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.301142 seconds wait.

'L' toLocal: 'keyPressed'.
0.210864 seconds wait.

'U' toLocal: 'keyPressed'.
0.138529 seconds wait.

'S' toLocal: 'keyPressed'.
1.215124 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.574928 seconds wait.

p solo: #psgPlus.
'p solo: #psgPlus.' toLocal: 'evaluatedCommand'.
0.083446 seconds wait.

'D' toLocal: 'keyPressed'.
0.007347 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
1.174553 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.676284 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.396159 seconds wait.

'UP' toLocal: 'keyPressed'.
1.000947 seconds wait.

'1' toLocal: 'keyPressed'.
0.269059 seconds wait.

'6' toLocal: 'keyPressed'.
0.06929 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.364536 seconds wait.

'P' toLocal: 'keyPressed'.
0.231215 seconds wait.

'L' toLocal: 'keyPressed'.
0.1328 seconds wait.

'E' toLocal: 'keyPressed'.
0.201525 seconds wait.

'N' toLocal: 'keyPressed'.
0.118029 seconds wait.

'A' toLocal: 'keyPressed'.
0.551842 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.221894 seconds wait.

'T' toLocal: 'keyPressed'.
0.217805 seconds wait.

'O' toLocal: 'keyPressed'.
0.326003 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.03263 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.140359 seconds wait.

'SPACE' toLocal: 'keyPressed'.
1.11659 seconds wait.

'3' toLocal: 'keyPressed'.
0.026661 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.255572 seconds wait.

'K' toLocal: 'keyPressed'.
0.143932 seconds wait.

'I' toLocal: 'keyPressed'.
0.083332 seconds wait.

'C' toLocal: 'keyPressed'.
0.284781 seconds wait.

'K' toLocal: 'keyPressed'.
0.200892 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.164829 seconds wait.

16 plena to: #kick.
'16 plena to: #kick.' toLocal: 'evaluatedCommand'.
0.081839 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.030415 seconds wait.

'D' toLocal: 'keyPressed'.
1.96292 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.283488 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.518944 seconds wait.

'UP' toLocal: 'keyPressed'.
1.165425 seconds wait.

'1' toLocal: 'keyPressed'.
0.273118 seconds wait.

'6' toLocal: 'keyPressed'.
0.064723 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.359863 seconds wait.

'U' toLocal: 'keyPressed'.
0.988248 seconds wait.

'P' toLocal: 'keyPressed'.
0.296812 seconds wait.

'B' toLocal: 'keyPressed'.
0.125648 seconds wait.

'E' toLocal: 'keyPressed'.
0.396112 seconds wait.

'T' toLocal: 'keyPressed'.
0.128688 seconds wait.

'S' toLocal: 'keyPressed'.
0.518248 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.124233 seconds wait.

'BACKSPACE' toLocal: 'keyPressed'.
0.254864 seconds wait.

'A' toLocal: 'keyPressed'.
0.579452 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.321808 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.730765 seconds wait.

'T' toLocal: 'keyPressed'.
0.240927 seconds wait.

'O' toLocal: 'keyPressed'.
0.36801 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.000716 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.187976 seconds wait.

'SPACE' toLocal: 'keyPressed'.
2.764393 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.001837 seconds wait.

'3' toLocal: 'keyPressed'.
0.390752 seconds wait.

'C' toLocal: 'keyPressed'.
0.090841 seconds wait.

'H' toLocal: 'keyPressed'.
0.316298 seconds wait.

'O' toLocal: 'keyPressed'.
0.099452 seconds wait.

'R' toLocal: 'keyPressed'.
0.503323 seconds wait.

'D' toLocal: 'keyPressed'.
0.128804 seconds wait.

'Y' toLocal: 'keyPressed'.
2.087618 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.863493 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.201193 seconds wait.

'N' toLocal: 'keyPressed'.
0.202437 seconds wait.

'O' toLocal: 'keyPressed'.
0.252807 seconds wait.

'T' toLocal: 'keyPressed'.
0.121145 seconds wait.

'E' toLocal: 'keyPressed'.
0.178829 seconds wait.

'S' toLocal: 'keyPressed'.
0.759965 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.000529 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.195573 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.810652 seconds wait.

'APOSTROPHE' toLocal: 'keyPressed'.
0.682616 seconds wait.

'6' toLocal: 'keyPressed'.
0.265202 seconds wait.

'5' toLocal: 'keyPressed'.
0.932626 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.240934 seconds wait.

'COMMA' toLocal: 'keyPressed'.
0.234532 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.291159 seconds wait.

'6' toLocal: 'keyPressed'.
0.048883 seconds wait.

'7' toLocal: 'keyPressed'.
0.516974 seconds wait.

'RIGHT' toLocal: 'keyPressed'.
0.76718 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.665615 seconds wait.

16 upbeats to: #chordy; notes: '65 , 67'.
'16 upbeats to: #chordy; notes: ''65 , 67''.' toLocal: 'evaluatedCommand'.
0.104365 seconds wait.

'D' toLocal: 'keyPressed'.
0.001213 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
6.230714 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.624542 seconds wait.

'1' toLocal: 'keyPressed'.
0.203914 seconds wait.

'6' toLocal: 'keyPressed'.
0.119607 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.271767 seconds wait.

'D' toLocal: 'keyPressed'.
0.520277 seconds wait.

'O' toLocal: 'keyPressed'.
0.460205 seconds wait.

'W' toLocal: 'keyPressed'.
0.450957 seconds wait.

'UP' toLocal: 'keyPressed'.
0.000734 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.480663 seconds wait.

'DOWN' toLocal: 'keyPressed'.
0.299836 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.730884 seconds wait.

'T' toLocal: 'keyPressed'.
0.288208 seconds wait.

'O' toLocal: 'keyPressed'.
0.311534 seconds wait.

'SEMICOLON' toLocal: 'keyPressed'.
0.042514 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.160599 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.344569 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.404321 seconds wait.

'3' toLocal: 'keyPressed'.
0.048454 seconds wait.

'SHIFT_L' toLocal: 'keyPressed'.
0.204833 seconds wait.

'K' toLocal: 'keyPressed'.
0.149164 seconds wait.

'I' toLocal: 'keyPressed'.
0.163517 seconds wait.

'C' toLocal: 'keyPressed'.
0.137981 seconds wait.

'K' toLocal: 'keyPressed'.
0.763029 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.25794 seconds wait.

16 downbeats to: #kick.
'16 downbeats to: #kick.' toLocal: 'evaluatedCommand'.
0.083931 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.001011 seconds wait.

'D' toLocal: 'keyPressed'.
6.883943 seconds wait.

'RETURN' toLocal: 'keyPressed'.
0.752411 seconds wait.

'P' toLocal: 'keyPressed'.
0.076873 seconds wait.

'SPACE' toLocal: 'keyPressed'.
0.179067 seconds wait.

'S' toLocal: 'keyPressed'.
0.155575 seconds wait.

'T' toLocal: 'keyPressed'.
0.384126 seconds wait.

'O' toLocal: 'keyPressed'.
0.0343 seconds wait.

'P' toLocal: 'keyPressed'.
0.273733 seconds wait.

'PERIOD' toLocal: 'keyPressed'.
0.187367 seconds wait.

p stop.
'p stop.' toLocal: 'evaluatedCommand'.
0.057649 seconds wait.

'SUPER_L' toLocal: 'keyPressed'.
0.024166 seconds wait.

'D' toLocal: 'keyPressed'.
] fork

