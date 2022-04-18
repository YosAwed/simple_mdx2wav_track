# simple_mdx2wav_track

元ネタはよっしんさんのportable mdx playerです。
https://github.com/yosshin4004/portable_mdx

このリポジトリは、主に自分用に作ったX68000のMDXファイルを入力して、各OPMトラックのWAVファイルを出力するツールです。

sampleにあるmain.cしかコンパイルできません。

＜使用方法＞
simple_mdx2wav -i <入力MDXファイル名> -o <出力WAVファイルプレフィックス>

出力プレフィックス名に、0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15を末尾につけたファイルを生成します。

PDXは、8番以降に出力されます。

＜既知の問題＞
・ノートのないトラックがあった場合は、無音のWAVファイルができます。
