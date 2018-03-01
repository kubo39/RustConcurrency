# Rust Concurrency in Action

WIP

## スレッド

* スレッド (POSIXスレッド)
* ケーススタディ1: pthread (C11)
* ケーススタディ2: std::thread (C++11)
* std::thread
* Ownershipとスレッドの幸福な関係
* コルーチン
* ケーススタディ3: boost::contextとboost::coroutine
* coroutine-rs

## ロック

* Mutex
* 条件変数
* ロックの亜種 (reader/write lock, seqlock)
* std::sync の下
* (コラム) parking_lot

## Future

* 計算理論としてのFuture
* ケーススタディ1: Schemeのdelay/force
* ケーススタディ2: ScalaのFuture
* futures-rs

## 非同期I/O

* C10K Problem
* イベントドリブン (epoll/kqueue, SOCK_NONBLOCK)
* ケーススタディ1: Java (Netty)
* ケーススタディ2: Go (netpoller)
* mio/tokio
    * Poller
    * HashWheelTimer
* ケーススタディ3: hyper (Rust)
* (コラム) ファイルI/O: Posix AIO/Linux AIO

## メッセージパッシング

* 計算理論としてのメッセージパッシング
* ケーススタディ1: Goのchannel
* ケーススタディ2: Dのstd::concurrency
* std::sync::mpsc
* crossbeam-channel
* アプリケーションの例

## タスク並列処理

* work-stealing
* ケーススタディ1: Javaのfork-join
* rayon
* アプリケーションの例

## Atomic

* メモリオーダー
* ケーススタディ1: C++11のstd::atomic
* ケーススタディ2: Javaのvolatile
* Rust/LLVMのメモリオーダー
* atomic操作: 単純なread/write (load/store)
* atomic操作: read-modifiy-write (compare-and-swap)

## ロックフリーデータ構造

* lock-free/wait-free/obstruction-free
* 時相論理 (線形時相論理: LTL)
* Micheal-Scott Queue (crossbeam)
* crossbeam-skiplist
