---
layout: news_post
title: "Ruby 1.9.3-p392 リリース"
author: "usa"
date: 2013-02-22 13:10:07 +0000
lang: ja
---

Ruby 1.9.3-p392 がリリースされました。 頻繁なリリースでユーザーの皆さんにはご迷惑をおかけしております。 申し訳ありません。

今回のリリースには、バンドルされている JSON および REXML に関するセキュリティフィックスが含まれます。

* [JSON におけるサービス不能攻撃および安全でないオブジェクトの生成について
  (CVE-2013-0269)][1]
* [REXML におけるエンティティ展開に伴うサービス不能攻撃について
  (CVE-2013-1821)][2]

この他にも、幾つかの小さなバグ修正が含まれています。

詳しくは、対応する[チケット][3]および [ChangeLog][4] を確認して下さい。

## ダウンロード

以下の URL から本リリースをダウンロードできます。

* [&lt;URL:https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.tar.bz2&gt;][5]

      SIZE:   10024221 bytes
      MD5:    a810d64e2255179d2f334eb61fb8519c
      SHA256: 5a7334dfdf62966879bf539b8a9f0b889df6f3b3824fb52a9303c3c3d3a58391

* [&lt;URL:https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.tar.gz&gt;][6]

      SIZE:   12557294 bytes
      MD5:    f689a7b61379f83cbbed3c7077d83859
      SHA256: 8861ddadb2cd30fb30e42122741130d12f6543c3d62d05906cd41076db70975f

* [&lt;URL:https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.zip&gt;][7]

      SIZE:   13863402 bytes
      MD5:    212fb3bc41257b41d1f8bfe0725916b7
      SHA256: f200ce4a63ce57bea64028a507350717c2a16bdbba6d9538bc69e9e7c2177c8b

## リリースコメント

今回も、いつも同様、コミッタをはじめ多数の皆さんのご協力を頂きました。 皆さんありがとうございます。



[1]: {{ site.url }}/ja/news/2013/02/22/json-dos-cve-2013-0269/
[2]: {{ site.url }}/ja/news/2013/02/22/rexml-dos-2013-02-22/
[3]: https://bugs.ruby-lang.org/projects/ruby-193/issues?set_filter=1&amp;status_id=5
[4]: https://svn.ruby-lang.org/repos/ruby/tags/v1_9_3_392/ChangeLog
[5]: https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.tar.bz2
[6]: https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.tar.gz
[7]: https://cache.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-p392.zip
