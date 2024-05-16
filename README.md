# Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output

![330792288-b92cb41f-bc3f-421c-847e-fb836c0db055](https://github.com/Rajesh242004/Gerber-to-G-Code-Conversion/assets/117814063/47449cf3-47c8-4f2a-943e-d9abb0579022)

# G Code
### Engraving G Code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 16:42 )
( Workpiece dimensions: 92.634 x 76.444 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #1 "Basic Engraver" / Diameter 3.17 mm )
T1 M06
M03 S12000
M07
G00 X14.777 Y29.89
G00 Z0
G01 F60 Z-0.2
G01 F600 X14.618
G01 X14.211 Y29.482
G01 Y28.906
G01 X14.618 Y28.498
G01 X14.777
G01 Y13.38
G01 X14.618
G01 X14.211 Y12.972
G01 Y12.396
G01 X14.618 Y11.988
G01 X15.195
G01 X15.602 Y12.396
G01 Y12.972
G01 X15.195 Y13.38
G01 X15.036
G01 Y28.498
G01 X15.195
G01 X15.602 Y28.906
G01 Y29.482
G01 X15.195 Y29.89
G01 X15.036
G01 Y36.118
G01 X15.195
G01 X15.602 Y36.526
G01 Y37.102
G01 X15.195 Y37.51
G01 X14.618
G01 X14.211 Y37.102
G01 Y36.526
G01 X14.618 Y36.118
G01 X14.777
G01 Y29.89
G00 Z2
G00 X20.682 Y29.375
G00 Z0
G01 F60 Z-0.2
G01 F600 Y29.482
G01 X20.275 Y29.89
G01 X19.698
G01 X19.291 Y29.482
G01 Y28.906
G01 X19.698 Y28.498
G01 X20.275
G01 X20.682 Y28.906
G01 Y29.115
G01 X23.898
G01 X23.924 Y29.118
G01 X23.948 Y29.125
G01 X23.97 Y29.137
G01 X23.99 Y29.153
G01 X31.042 Y36.205
G01 X31.128 Y36.118
G01 X31.705
G01 X32.112 Y36.526
G01 Y37.102
G01 X32.026 Y37.189
G01 X33.706 Y38.869
G01 X47.009
G01 X47.543 Y38.335
G01 Y37.017
G01 X47.545 Y36.992
G01 X47.553 Y36.968
G01 X47.565 Y36.945
G01 X47.581 Y36.926
G01 X66.745 Y17.761
G01 Y11.475
G01 X66.688
G01 X66.281 Y11.067
G01 Y10.491
G01 X66.688 Y10.083
G01 X67.265
G01 X67.672 Y10.491
G01 Y11.067
G01 X67.265 Y11.475
G01 X67.005
G01 Y17.815
G01 X67.002 Y17.84
G01 X66.995 Y17.865
G01 X66.983 Y17.887
G01 X66.967 Y17.907
G01 X47.802 Y37.071
G01 Y38.389
G01 X47.8 Y38.414
G01 X47.793 Y38.439
G01 X47.781 Y38.461
G01 X47.764 Y38.481
G01 X47.155 Y39.09
G01 X47.135 Y39.106
G01 X47.113 Y39.118
G01 X47.088 Y39.126
G01 X47.063 Y39.128
G01 X33.652
G01 X33.627 Y39.126
G01 X33.602 Y39.118
G01 X33.58 Y39.106
G01 X33.56 Y39.09
G01 X31.842 Y37.372
G01 X31.705 Y37.51
G01 X31.128
G01 X30.721 Y37.102
G01 Y36.526
G01 X30.858 Y36.389
G01 X23.845 Y29.375
G01 X20.682
G00 Z2
G00 X31.388 Y47.67
G00 Z0
G01 F60 Z-0.2
G01 F600 X31.128
G01 X30.721 Y47.262
G01 Y46.686
G01 X31.128 Y46.278
G01 X31.705
G01 X32.112 Y46.686
G01 Y47.262
G01 X31.705 Y47.67
G01 X31.648
G01 Y50.832
G01 X37.767 Y56.951
G01 X46.073 Y48.644
G01 X45.961 Y48.532
G01 X45.961 Y47.956
G01 X46.368 Y47.548
G01 X46.945
G01 X47.352 Y47.956
G01 Y48.532
G01 X46.945 Y48.94
G01 X46.368
G01 X46.256 Y48.828
G01 X37.95 Y57.134
G01 X38.706 Y57.89
G01 X38.802 Y57.838
G01 X38.917 Y57.803
G01 X39.037 Y57.792
G01 X39.156 Y57.803
G01 X39.271 Y57.838
G01 X39.377 Y57.895
G01 X39.47 Y57.971
G01 X39.546 Y58.064
G01 X39.602 Y58.17
G01 X39.637 Y58.285
G01 X39.649 Y58.404
G01 X39.637 Y58.524
G01 X39.602 Y58.638
G01 X39.546 Y58.744
G01 X39.47 Y58.837
G01 X39.377 Y58.913
G01 X39.271 Y58.97
G01 X39.156 Y59.005
G01 X39.116 Y59.009
G01 Y60.34
G01 X39.156 Y60.343
G01 X39.271 Y60.378
G01 X39.377 Y60.435
G01 X39.47 Y60.511
G01 X39.546 Y60.604
G01 X39.602 Y60.71
G01 X39.637 Y60.825
G01 X39.649 Y60.944
G01 X39.637 Y61.064
G01 X39.602 Y61.178
G01 X39.546 Y61.284
G01 X39.47 Y61.377
G01 X39.377 Y61.453
G01 X39.271 Y61.51
G01 X39.156 Y61.545
G01 X39.037 Y61.556
G01 X38.917 Y61.545
G01 X38.802 Y61.51
G01 X38.696 Y61.453
G01 X38.604 Y61.377
G01 X38.527 Y61.284
G01 X38.471 Y61.178
G01 X38.436 Y61.064
G01 X38.424 Y60.944
G01 X38.436 Y60.825
G01 X38.471 Y60.71
G01 X38.527 Y60.604
G01 X38.604 Y60.511
G01 X38.696 Y60.435
G01 X38.802 Y60.378
G01 X38.856 Y60.362
G01 Y58.986
G01 X38.802 Y58.97
G01 X38.696 Y58.913
G01 X38.604 Y58.837
G01 X38.527 Y58.744
G01 X38.471 Y58.638
G01 X38.436 Y58.524
G01 X38.424 Y58.404
G01 X38.436 Y58.285
G01 X38.471 Y58.17
G01 X38.522 Y58.073
G01 X37.675 Y57.226
G01 X31.426 Y50.977
G01 X31.41 Y50.958
G01 X31.398 Y50.935
G01 X31.391 Y50.911
G01 X31.388 Y50.886
G01 Y47.67
G00 Z2
G00 X15.036 Y62.788
G00 Z0
G01 F60 Z-0.2
G01 F600 X15.195
G01 X15.602 Y63.196
G01 Y63.772
G01 X15.195 Y64.18
G01 X14.618
G01 X14.211 Y63.772
G01 Y63.196
G01 X14.618 Y62.788
G01 X14.777
G01 Y47.67
G01 X14.618
G01 X14.211 Y47.262
G01 Y46.686
G01 X14.618 Y46.278
G01 X15.195
G01 X15.602 Y46.686
G01 Y47.262
G01 X15.195 Y47.67
G01 X15.036
G01 Y62.788
G00 Z2
G00 X56.946
G00 Z0
G01 F60 Z-0.2
G01 F600 X57.105
G01 X57.512 Y63.196
G01 Y63.772
G01 X57.105 Y64.18
G01 X56.528
G01 X56.121 Y63.772
G01 X56.121 Y63.196
G01 X56.528 Y62.788
G01 X56.687
G01 Y47.67
G01 X56.528
G01 X56.121 Y47.262
G01 X56.121 Y46.686
G01 X56.528 Y46.278
G01 X57.105
G01 X57.512 Y46.686
G01 Y47.262
G01 X57.105 Y47.67
G01 X56.946
G01 Y62.788
G00 Z2
G00 X75.919 Y45.468
G00 Z0
G01 F60 Z-0.2
G01 F600 X75.545 Y45.093
G01 Y43.775
G01 X76.477 Y42.842
G01 X77.796
G01 X78.728 Y43.775
G01 Y45.093
G01 X77.796 Y46.026
G01 X76.477
G01 X76.103 Y45.651
G01 X57.213 Y64.541
G01 X57.194 Y64.557
G01 X57.171 Y64.569
G01 X57.147 Y64.577
G01 X57.121 Y64.579
G01 X55.293
G01 X55.267 Y64.577
G01 X55.243 Y64.569
G01 X55.221 Y64.557
G01 X55.201 Y64.541
G01 X54.702 Y64.042
G01 X54.565 Y64.18
G01 X53.988
G01 X53.581 Y63.772
G01 Y63.665
G01 X39.619
G01 X39.602 Y63.718
G01 X39.546 Y63.824
G01 X39.47 Y63.917
G01 X39.377 Y63.993
G01 X39.271 Y64.05
G01 X39.156 Y64.085
G01 X39.037 Y64.096
G01 X38.917 Y64.085
G01 X38.802 Y64.05
G01 X38.696 Y63.993
G01 X38.604 Y63.917
G01 X38.527 Y63.824
G01 X38.471 Y63.718
G01 X38.455 Y63.665
G01 X18.142
G01 Y63.772
G01 X17.735 Y64.18
G01 X17.158
G01 X16.751 Y63.772
G01 Y63.196
G01 X17.158 Y62.788
G01 X17.735
G01 X18.142 Y63.196
G01 Y63.405
G01 X38.432
G01 X38.436 Y63.365
G01 X38.471 Y63.25
G01 X38.527 Y63.144
G01 X38.604 Y63.051
G01 X38.696 Y62.975
G01 X38.802 Y62.918
G01 X38.917 Y62.883
G01 X39.037 Y62.872
G01 X39.156 Y62.883
G01 X39.271 Y62.918
G01 X39.377 Y62.975
G01 X39.47 Y63.051
G01 X39.546 Y63.144
G01 X39.602 Y63.25
G01 X39.637 Y63.365
G01 X39.641 Y63.405
G01 X53.581
G01 Y63.196
G01 X53.988 Y62.788
G01 X54.565
G01 X54.972 Y63.196
G01 Y63.772
G01 X54.886 Y63.859
G01 X55.346 Y64.32
G01 X57.068
G01 X75.919 Y45.468
G00 Z2
G00 X77.216 Y37.762
G00 Z0
G01 F60 Z-0.2
G01 F600 X77.796
G01 X78.728 Y38.695
G01 Y40.013
G01 X77.796 Y40.946
G01 X76.477
G01 X75.545 Y40.013
G01 Y38.695
G01 X76.477 Y37.762
G01 X76.956
G01 Y19.545
G01 X67.431 Y10.02
G01 X66.624
G01 X65.938 Y10.706
G01 Y11.988
G01 X65.995
G01 X66.402 Y12.396
G01 Y12.972
G01 X65.995 Y13.38
G01 X65.418
G01 X65.011 Y12.972
G01 Y12.916
G01 X18.142
G01 Y12.972
G01 X17.735 Y13.38
G01 X17.158
G01 X16.751 Y12.972
G01 Y12.396
G01 X17.158 Y11.988
G01 X17.735
G01 X18.142 Y12.396
G01 Y12.656
G01 X65.011
G01 Y12.396
G01 X65.418 Y11.988
G01 X65.678
G01 Y10.652
G01 X65.681 Y10.627
G01 X65.688 Y10.602
G01 X65.7 Y10.58
G01 X65.716 Y10.56
G01 X66.478 Y9.798
G01 X66.498 Y9.782
G01 X66.521 Y9.77
G01 X66.545 Y9.763
G01 X66.57 Y9.76
G01 X67.485
G01 X67.51 Y9.763
G01 X67.534 Y9.77
G01 X67.557 Y9.782
G01 X67.576 Y9.798
G01 X77.178 Y19.4
G01 X77.194 Y19.419
G01 X77.206 Y19.442
G01 X77.213 Y19.466
G01 X77.216 Y19.491
G01 Y37.762
G00 Z2
G00 X59.125 Y27.35
G00 Z0
G01 F60 Z-0.2
G01 F600 X59.068
G01 X58.661 Y26.942
G01 X58.661 Y26.366
G01 X59.068 Y25.958
G01 X59.645
G01 X59.782 Y26.096
G01 X68.117 Y17.761
G01 Y13.38
G01 X67.958
G01 X67.551 Y12.972
G01 Y12.396
G01 X67.958 Y11.988
G01 X68.535
G01 X68.942 Y12.396
G01 Y12.972
G01 X68.535 Y13.38
G01 X68.376
G01 Y17.815
G01 X68.374 Y17.84
G01 X68.367 Y17.865
G01 X68.355 Y17.887
G01 X68.338 Y17.907
G01 X59.966 Y26.279
G01 X60.052 Y26.366
G01 Y26.942
G01 X59.645 Y27.35
G01 X59.385
G01 Y34.274
G01 X59.382 Y34.299
G01 X59.375 Y34.324
G01 X59.363 Y34.346
G01 X59.347 Y34.366
G01 X57.35 Y36.363
G01 X57.512 Y36.526
G01 Y37.102
G01 X57.105 Y37.51
G01 X56.528
G01 X56.121 Y37.102
G01 X56.121 Y36.526
G01 X56.528 Y36.118
G01 X57.105
G01 X57.166 Y36.18
G01 X59.125 Y34.22
G01 Y27.35
G00 Z2
G00 X53.668 Y27.029
G00 Z0
G01 F60 Z-0.2
G01 F600 X53.581 Y26.942
G01 X53.581 Y26.366
G01 X53.988 Y25.958
G01 X54.565
G01 X54.972 Y26.366
G01 Y26.942
G01 X54.565 Y27.35
G01 X53.988
G01 X53.851 Y27.212
G01 X44.884 Y36.179
G01 X46.231 Y37.526
G01 X46.368 Y37.388
G01 X46.945
G01 X47.352 Y37.796
G01 Y38.372
G01 X46.945 Y38.78
G01 X46.368
G01 X45.961 Y38.372
G01 X45.961 Y37.796
G01 X46.048 Y37.709
G01 X44.533 Y36.195
G01 X23.083 Y14.744
G01 X16.872
G01 Y14.877
G01 X16.465 Y15.285
G01 X15.888
G01 X15.481 Y14.877
G01 Y14.301
G01 X15.888 Y13.893
G01 X16.465
G01 X16.872 Y14.301
G01 Y14.485
G01 X23.136
G01 X23.162 Y14.487
G01 X23.186 Y14.495
G01 X23.208 Y14.507
G01 X23.228 Y14.523
G01 X44.678 Y35.973
G01 X44.723
G01 X53.668 Y27.029
G00 Z2
M09
M05
M02
%
```

### Drill G Code

```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 16:42 )
( Workpiece dimensions: 92.634 x 76.444 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #4 "Basic Drill" / Diameter 1 mm )
T4 M06
M03 S12000
M07
G00 X77.137 Y39.354
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y44.434
G00 Z0
G01 F60 Z-1
G00 Z2
M09
M05
M02
%
```

### Drill 0.8
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 16:41 )
( Workpiece dimensions: 92.634 x 76.444 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #3 "Basic Drill" / Diameter 0.8 mm )
T3 M06
M03 S12000
M07
G00 X39.037 Y58.404
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y60.944
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y63.484
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X54.277
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X56.817
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y46.974
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y36.814
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X46.657 Y38.084
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y48.244
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X31.417 Y46.974
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y36.814
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X19.987 Y29.194
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X14.907
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y36.814
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y46.974
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y63.484
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X17.447
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X16.177 Y14.589
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X14.907 Y12.684
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X17.447
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X54.277 Y26.654
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X59.357
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X65.707 Y12.684
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X66.977 Y10.779
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X68.247 Y12.684
G00 Z0
G01 F60 Z-1
G00 Z2
M09
M05
M02
%
```



### Cutting G Code

```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 16:42 )
( Workpiece dimensions: 92.634 x 76.444 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #2 "Basic Cutter" / Diameter 3 mm )
T2 M06
M03 S12000
M07
G00 X0.834 Y1.151
G00 Z0
G01 F60 Z-2
G01 F300 X91.134
G01 Y75.261
G01 X0.834
G01 Y1.151
G00 Z2
M09
M05
M02
%
```




# Result

Thus the Gerber File into G-Code using Copper CAM.
