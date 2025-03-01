---
title: Distributed Apps
status: Completed
category: concept
tags: ["architecture", "", ""]
---

## それは何ですか

分散アプリケーションとは、機能が複数の小さな独立した部分に分割されているアプリケーションです。
分散アプリケーションは通常、個々の[マイクロサービス](/microservices/)で構成されます
より広いアプリケーション内のさまざまな問題を処理します。
	クラウド ネイティブ環境では、個々のコンポーネントは通常、[クラスター](/cluster/) [コンテナー](/container/) として実行されます。

## 対処する問題

1 台のコンピューターで実行されているアプリケーションは、単一障害点を表します。そのコンピューターに障害が発生すると、アプリケーションは使用できなくなります。
分散アプリケーションは、多くの場合、[モノリシック アプリケーション](/monolithic-apps/)と対比されます。
モノリシック アプリは、さまざまなコンポーネントを個別にスケーリングできないため、スケーリングが難しくなる可能性があります。
また、成長するにつれて、開発者のベロシティの足かせになる可能性もあります
より多くの開発者が、必ずしも境界が明確に定義されていない共有コードベースで作業する必要があるためです。

## どのように役立つか

アプリケーションを複数の部分に分割して多くの場所で実行すると、システム全体でより多くの障害を許容できます。
また、アプリケーションは、単一のアプリケーション インスタンスでは利用できないスケーリング機能を利用できます。
つまり、[水平方向にスケーリング](/horizontal-scaling/)する機能です。
ただし、これには代償が伴います。複雑さと運用上のオーバーヘッドが増加します。
— 1 つのアプリではなく、多数のアプリケーション コンポーネントを実行しています。
