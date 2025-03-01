---
title: Virtual Machine
status: Completed
category: Technology
tags: ["fundamental", "infrastructure", ""]
---

## それは何ですか

仮想マシン (VM) は、コンピューターとそのオペレーティング システムです。
これは、特定のハードウェアにバインドされていません。
VM は [仮想化](/virtualization/) に依存して、単一の物理コンピューターを複数の仮想コンピューターに分割します。
その分離により、組織とインフラストラクチャ プロバイダーは、
基盤となるハードウェアに影響を与えることなく、VM を簡単に作成および破棄できます。

## 対処する問題

仮想マシンは仮想化を利用します。
[ベア メタル](/bare-metal-machine/)マシンが単一のオペレーティング システムにバインドされている場合、
マシンのリソースをどれだけうまく使用できるかは、ある程度制限されています。
また、オペレーティング システムが単一の物理マシンにバインドされている場合、
その可用性は、そのハードウェアに直接結びついています。
メンテナンスまたはハードウェア障害のために物理マシンがオフラインになると、オペレーティング システムもオフラインになります。

## どのように役立つか

オペレーティング システムと単一の物理マシンとの間の直接的な関係を取り除くことにより、
ベア メタル マシンのいくつかの問題を解決します。
プロビジョニング時間、ハードウェア使用率、回復力。

それをサポートするために新しいハードウェアを購入、インストール、または構成する必要がないため、
新しいコンピューターのプロビジョニング時間が大幅に短縮されます。
VM を使用すると、既存の物理ハードウェア リソースをより有効に使用できます
単一の物理マシンに複数の仮想マシンを配置することによって。
VM は特定の物理マシンに縛られないため、物理マシンよりも回復力があります。
物理マシンをオフラインにする必要がある場合、
その上で実行されている VM は、ほとんどまたはまったくダウンタイムなしで別のマシンに移動できます。
