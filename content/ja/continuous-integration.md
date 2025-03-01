---
title: Continuous integration (CI)
status: Completed 
category: concept
tags: ["application", "methodology", ""]
---

## それは何ですか

CI と略されることが多い継続的インテグレーションは、コードの変更をできるだけ定期的に統合する方法です。
CI は、[継続的な配信](/continuous-delivery/) (CD) の前提条件です。
従来、CI プロセスは、コードの変更がソース管理システム (Git、Mercurial、または Subversion) にコミットされたときに開始されます。
そして、CD システムですぐに使用できるテスト済みのアーティファクトで終了します。

## 対処する問題

多くの場合、ソフトウェア システムは大規模で複雑であり、多くの開発者がそれらを維持および更新しています。
システムのさまざまな部分で並行して作業し、
これらの開発者は競合する変更を行い、うっかりお互いの作業を壊してしまう可能性があります。
さらに、複数の開発者が同じプロジェクトに取り組んでいるため、
テストやコード品質の計算などの日常的なタスクは、各開発者が繰り返す必要があり、時間を無駄にしていました。

## どのように役立つか

CI ソフトウェアは、開発者が変更をコミットするたびに、コードの変更が正常にマージされていることを自動的にチェックします。
CI サーバーを使用してコードの品質チェック、テスト、さらには展開を実行することは、ほぼどこにでもある方法です。
そのため、チーム内での品質管理の具体的な実装になります。
CI により、ソフトウェア チームはすべてのコード コミットを具体的な失敗または実行可能なリリース候補に変えることができます。

## 関連用語

* [継続的な配信](/continuous-delivery/)
* [継続的な導入](/continuous-deployment/)
