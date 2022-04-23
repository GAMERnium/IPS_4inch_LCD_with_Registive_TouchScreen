RasPiOSのイメージをダウンロードさせられるので調べてみた。
ノンオフィシャルなイメージは普通使いたくないよね。
でもおそらく日本人に説明するの面倒くさいから動くイメージ頒布してんだと思う（←わかる

●推測も含まれているので自己責任で。
モデル：MPI4008 4インチ(3.97インチ)
これ↓
ｈｔｔｐｓ：//www.amazon.co.jp/dp/B0896SXPXG
ASIN：B0896SXPXG
Model：‎Smraza SW34-4
LCD Screen Manufacturer:unknouwn
                   Type：TFT-IPS    ##アマゾンスペック##
              Model No.：unknouwn
            Resolustion：800x480
              connector：51pin 0.3mm Pich FPC(Molex Type)
LCD and OSD Controller:Realtek RTD2660H
            OSD Switch:1(バックライト／ブライトネスのみ)

LCD Panel Driver:Novatek NT35510    ##アマゾンスペック##
         Tourch Screen : 抵抗薄膜式
                Driver : チップ名 XPT2046 (ドライバはTixas Instruments ADS7846用)
# dtoverlay=ads7846,cs=1,penirq=25,penirq_pull=2,speed=50000,keep_vref_on=0,swapxy=0,pmax=255,xohms=150,xmin=200,xmax=3900,ymin=200,ymax=3900

ショートＵＲＬはどこに飛ばされるのかわからないので嫌いな人向け情報
元 ttps://tinyurl.com/y55syctw
先 ttps://mega.nz/のどこか

ダウンロードさせられるRaspberry OS Image
Buster       2020-05-27 32bit : Raspberry Pi 4Bまで
Buster-armhf 2020-12-02 32bit : Raspberry Pi CM4まで
古いよね。

今からブルズアイに入れます。
ブリンクして映らないので調査中
