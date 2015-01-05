# @umegaya

## 自己紹介
Takehiro Iyatomi (@umegaya)

- ゲーム会社で１０年ほどMMOG(Massive Multiplayer Online Game)のサーバーのリードエンジニアをやっていました。
- そのころに、分散コンピューティングの技術的な難しさがあたらしいタイプのMMOGを生み出すことを阻害していることを痛感し、今は某中小企業のCTOをしつつ、分散コンピューティングを簡単にする方法論を追求することを自身の活動テーマにしています。
- 言語はC/C++, luaJIT, rubyあたりを流暢に話します。
- 得意なエンジニアリングの対象はゲーム向けのようなリアルタイム性の高いサーバーシステムの設計、開発、運用です。ゲーム会社的な気合いでの運用ではなく、dockerや各種ウェブサービスなども積極的にプロダクトに利用しています。
- モバイル系の開発も嗜みますが、iOS/Android NDKのようにC/C++(+lua)でかけるものが好みです。
- 個人のプロジェクトは現在はほとんどluaJITのみで作っています。

## 最近作っているものとか
- [luact](https://github.com/umegaya/luact): [Celluloid](https://github.com/celluloid/celluloid)(ruby)と[Orleans](http://research.microsoft.com/en-us/projects/orleans/)(.NET)にインスパイアされた分散コンピューティングフレームワーク。
- [luby](https://github.com/umegaya/luby): [ruby2ruby](https://github.com/seattlerb/ruby2ruby)と[luajit-lang-toolkit](https://github.com/franko/luajit-lang-toolkit)を使って、rubyをluajit VMのバイトコードにコンパイルして動かす処理系

## 作ったものとか
- [pulpo](https://github.com/umegaya/pulpo): luaJIT FFIとcoroutine(ECMA6のgeneratorのようなもの)を基礎として使うように設計されたコールバックがいらないイベントIOフレームワーク。docker上のecho serverでのテストでは大体Go1.3と同等の速度で動く。
- [ffiex](https://github.com/umegaya/ffiex): luaJIT FFI向けのluaで書かれたCのプリプロセッサ。割と本気で/usr/include/以下の邪悪なCヘッダファイルたちをサポートしている。

