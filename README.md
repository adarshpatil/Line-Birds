Line Birds using OpenGL
=========
- Author: Adarsh Patil, Harsha K C and Akshay Joshi
- Version: 1.0
- Licence: L-GPL / MSRIT Open Source Licence
- Visit my site http://adarshpatil.in

> DISCLAIMER: We donot claim Intellectual Property for the images or idea of the game.


<pre>
Created by:
  ........................................................................................................  
 .,......................................................................................................;, 
::                                                                                                        9 
:,                                                                                                        5 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                    .S#@@@@@S                                           2 
:,                                                  ,#@@@@@@@@@@r                                         2 
:,                                                 :@@@@#####@@@@i                                        2 
:,                                                :@@##MMBBBM##@@@;                                       2 
:,                                               ,@@#BBBBBBBBBM#@@@,                                      2 
:,                                              ,@@MBBBBBBBBBBBM#@@@                                      2 
:,                                             ,@@#MBBBBBBBBBBBBM#@@@                                     2 
:,                                            ,@@#MBBBBBBBBBBBBBBM#@@h                                    2 
:,                                           .@@#MBBBBBBBBBBBBBBBMM#@@r                                   2 
:,                                          ,@@#BBBBBBBBBBBMMMBBBBM#@@@,                                  2 
:,                                         .@@#MBBBBBBBBB#@@@@#MMBBM#@@@                                  2 
:,                                        .@@#MMBBBBMMBM@MSri#@#MBBBM#@@#                                 2 
:,                                       .@@#MBBBBBBMB#@;     2@#MBBM#@@@5                                2 
:,                                      .@@#MBBBBBBBB#@.       2@##BBM#@@@:                               2 
:,                                     .@@#MBBBBBBBBM@:         2@#MBBM#@@@                               2 
:,                                    .@@#MBBBBBBBBB@r           2@#MBBM#@@@                              2 
:,                                   .@@##MMBBBMBBB@X             5@#MBBM#@@9                             2 
:,                                  .@@#MBMBBBBBBB@H               S@#MBMM#@@;                            2 
:,                                 .@@#MBBBBBBBBM#@                 S@#MBM#@@@                            2 
:,                                .@@#MMBBBBBMBBM@.                  S@#MMM#@@@                           2 
:,                                @@#MBMBBBBBBBM@;                    i@#MMM#@@&                          2 
:,                               @@#MBBBBBBMMMB@5                      i@#MMM#@@r                         2 
:,                              @@#MBBBBBBBMMB@A                        i@#MM#@@@.                        2 
:,                             @@#MBBBBBBBBMB##                          i@#MM#@@@                        2 
:,                            @@#MMBBBBBBBBBM@                            i@##M#@@&                       2 
:,                           @@#MBMBBBBBBBBM@;                             s@#MM@@@r                      2 
:,                          @@#MBBBBBBBBMBM@5                               s@#M#@@@.                     2 
:,                         @@#BBBBBBBBBBBB@H                                 r@@##@@@                     2 
:,                        @@#MBBBBBBBBBMB#@                                   s@###@@&                    2 
:,                       @@#BBBBBBBBBBBBB@.                                    r@@#@@@r                   2 
:,                      @@#BMMBBBBBBBMBM@r                                      r@@#@@@.                  2 
:,                     @@#MBBBBBBBBBBMB@3                                        r@@#@@@                  2 
:,                    @@#MBBBBBBBBBBBB@M        .Bi,                              r@@#@@&                 2 
:,                   @@#MBBBBBBBBBBBB#@         2@@@@@Hi:                          r@@@@@r                2 
:,                  @@#MBBBBBBBBBBBMB@,         @@@@@@@@@@@&r.                      ;@@@@@.               2 
:,                 @@#MBBBBBBBBBBBBM@i         ;@@##@@@@@@@@@@@#S,                   ;@@@@@               2 
:,                @@#BBBBBBBBBBBBBB@A          #@BBBMMM###@@@@@@@@@#S,                ;@@@@G              2 
:,               @@#MMBBBBBBBBBBBB##          ,@#BMBBBBBBMM###@@@@@@@@@Ms.             ;@@@@;             2 
:,              @@#MBBBBBBBBBBBMB#@           A@#MMBBMMMBBMBM#####@@@@@@@@@3:           ;@@@@             2 
:,             @@#MBBBBBBBBBBBBBB@;           @@###@@@@@@@@@@@@@######@@@@@@@@A;         ;@@@@            2 
:,            @@#MBBBBBBBBBBBBMM@2           H@@@@#AG9X55552X9GHM#@@@@@@@@@@@@@@@M;       ;@@@h           2 
:,           @@##MBBBBBBBBBBBBB@B            r:                     .:rXH@@@@@@@@@@@A:     :@@@;          2 
:,          @@#MMBBBBBBBBBBBBB#@                                           ,sA@@@@@@@@@5    :@@@          2 
:,         @@#MBBBBBBBBBBBBMBM@,                                                :3@@@@@@@A.  :@@@         2 
:,        @@#MBBBBBBBBBBBBBBM@s                                                     ;A@@@@@M. .@@X        2 
:,       @@#MBBBBBBBBBBBBBMB@&                                                         :&@@@@A .@@:       2 
:,      @@#MMBBBBBBBBBBBBBB##                                                             :A@@@s;@@       2 
:,     @@#MBMBBBBBBBBBBBBBM@.                                                                r@@@#@#      2 
:,    @@##BMMMMMMMMMMMMMMB@;                                                                   .A@@@5     2 
:,   @@@@@@@@@@@@@@@@@@@@@3                                                                       2@@;    2 
:,  X@AGhhhhhhhhhhhhhhhGGG                                                                          &@,   2 
:,                                                                                                   ,r   2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                                                                                        2 
:,                                        ,                                        .,                     2 
:,                                       ;@i                                       3@r                    2 
:,                   :2S                 ,@r                                       5@:                    2 
:,                  :@@@@         ,;;;;; .@;   .,::::,      .:::::,     .::::::.   s@:.;;;;;.             2 
:,                 .@@ :@#      :@@@@@@@@@@; .@@@@@@@@@A   B@@@@@@@@9 .@@@@@@@@@@. r@@@@@@@@@@.           2 
:,                 @@   i@G     @@       A@; B@.      i@5 3@r      2@s2@        @# ;@G      ,@@           2 
:,                #@     3@i   ,@;        @;  ;;rssisri@9 @@        @3s@i;;;;:.  . ;@        S@.          2 
:,               G@:      H@;   @r        @; H@#M####HA@5 B#           ;B#@@@@@@X  ;@.       S@           2 
:,              S@@#@@@@@@@@@,  @i       .@: @r        @S #@          ..       ,@5 ;@,       S@           2 
:,             r@S  .,...   @@  @@,      #@  @2       ;@; #@          H@.       @A r@:       S@           2 
:,            r@A            @@  @@@@@@@@@:  2@@@@@@@@@@  @@          .@@@@@@@@@@. r@:       2@.          2 
:,             .              ,    ..,..       ..,,,.      .             .....      ,         .           2 
,r                                                                                                       .X 
  ,......................................................................................................,  
</pre>
