# How2Use-hamlib

## Links
* https://github.com/Hamlib/Hamlib

# rigctl

rigctl [-hiIlLnouV] [-m id] [-r device] [-p device] [-d device]
              [-P type] [-D type] [-s baud] [-c id] [-t char] [-C parm=val]
              [-v[-Z]] [command|-]

## Options
-m　接続リグのモデル名　FT-817　1020、FT-897D 1043  
  1020  Yaesu                  FT-817                  20210916.0      Stable      RIG_MODEL_FT817  
  1021  Yaesu                  FT-100                  20210929.0      Stable      RIG_MODEL_FT100  
  1022  Yaesu                  FT-857                  20210330.0      Stable      RIG_MODEL_FT857  
  1023  Yaesu                  FT-897                  20201215.0      Stable      RIG_MODEL_FT897  
  1024  Yaesu                  FT-1000MP               20211113.0      Stable      RIG_MODEL_FT1000MP  
  1025  Yaesu                  MARK-V Field FT-1000MP  20211014.0      Stable      RIG_MODEL_FT1000MPMKVFLD  
  1026  Yaesu                  VR-5000                 20200505.0      Alpha       RIG_MODEL_VR5000  
  1027  Yaesu                  FT-450                  20211202.1      Stable      RIG_MODEL_FT450  
  1028  Yaesu                  FT-950                  20211202.2      Stable      RIG_MODEL_FT950  
  1029  Yaesu                  FT-2000                 20211202.1      Stable      RIG_MODEL_FT2000  
  1030  Yaesu                  FTDX-9000               20211202.1      Stable      RIG_MODEL_FT9000  
  1031  Yaesu                  FT-980                  20200114.0      Stable      RIG_MODEL_FT980  
  1032  Yaesu                  FTDX-5000               20211202.1      Stable      RIG_MODEL_FTDX5000  
  1034  Yaesu                  FTDX-1200               20211202.3      Stable      RIG_MODEL_FTDX1200  
  1035  Yaesu                  FT-991                  20211202.8      Stable      RIG_MODEL_FT991  
  1036  Yaesu                  FT-891                  20211202.5      Stable      RIG_MODEL_FT891  
  1037  Yaesu                  FTDX-3000               20211202.5      Stable      RIG_MODEL_FTDX3000  
  1038  Yaesu                  FT-847UNI               20210221.0      Stable      RIG_MODEL_FT847UNI  
  1039  Yaesu                  FT-600                  20201009.0      Stable      RIG_MODEL_FT600  
  1040  Yaesu                  FTDX-101D               20211202.13     Stable      RIG_MODEL_FTDX101D  
  1041  Yaesu                  FT-818                  20200710.0      Stable      RIG_MODEL_FT818  
  1042  Yaesu                  FTDX-10                 20211202.1      Stable      RIG_MODEL_FTDX10  
  1043  Yaesu                  FT-897D                 20210103.0      Stable      RIG_MODEL_FT897D  
 
-r /dev/ttyUSB0 接続先リグのポート  
-p /dev/ttyUSB0 ptt　push to talk 送信の切り替えデバイス接続先  

`$ sudo rigctl -m 1020 -r /dev/ttyUSB0`

