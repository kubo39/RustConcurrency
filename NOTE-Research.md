
## スレッド

## ロック

## Future

## 非同期I/O

## メッセージパッシング

## タスク並列

* [Rayon: data parallelism in Rust](http://smallcultfollowing.com/babysteps/blog/2015/12/18/rayon-data-parallelism-in-rust/)
* [Scheduling multithreaded computations by work stealing](http://supertech.csail.mit.edu/papers/steal.pdf)
* [Thread scheduling for multiprogramming multiprocessors](http://www.eecis.udel.edu/%7Ecavazos/cisc879-spring2008/papers/arora98thread.pdf)
* [The data locality of work stealing](http://www.aladdin.cs.cmu.edu/papers/pdfs/y2000/locality_spaa00.pdf)
* [Dynamic circular work stealing deque](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.170.1097&rep=rep1&type=pdf) - The Chase/Lev deque
* [Work-first and help-first scheduling policies for async-finish task parallelism](http://www.cs.rice.edu/%7Eyguo/pubs/PID824943.pdf) - More general than fully-strict work stealing
* [A Java fork/join calamity](http://www.coopsoft.com/ar/CalamityArticle.html) - critique of Java's fork/join library, particularly its application of work stealing to non-strict computation
* [Scheduling techniques for concurrent systems](http://www.ece.rutgers.edu/%7Eparashar/Classes/ece572-papers/05/ps-ousterhout.pdf)
* [Contention aware scheduling](http://www.blagodurov.net/files/a8-blagodurov.pdf)
* [Balanced work stealing for time-sharing multicores](http://www.cse.ohio-state.edu/hpcs/WWW/HTML/publications/papers/TR-12-1.pdf)
* [Three layer cake](http://www.upcrc.illinois.edu/workshops/paraplop10/papers/paraplop10_submission_8.pdf)
* [Non-blocking steal-half work queues](http://www.cs.bgu.ac.il/%7Ehendlerd/papers/p280-hendler.pdf)
* [Reagents: expressing and composing fine-grained concurrency](http://www.mpi-sws.org/~turon/reagents.pdf)
* [Algorithms for scalable synchronization of shared-memory multiprocessors](https://www.cs.rochester.edu/u/scott/papers/1991_TOCS_synch.pdf)
* [Arora's Task Stealing Deque](http://www.nminoru.jp/~nminoru/programming/arora_dequeue.html)

## Atomic

* [The Intel x86 Memory Ordering Guarantees and the C++ Memory Model](https://www.justsoftwaresolutions.co.uk/threading/intel-memory-ordering-and-c++-memory-model.html)
* [LLVM Atomic Instructions and Concurrency Guide](https://llvm.org/docs/Atomics.html)
* [exploring-lock-free-rust-3-crossbeam](https://morestina.net/blog/784/exploring-lock-free-rust-3-crossbeam)
* [fun-with-threads](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
* [メモリモデル？なにそれ？おいしいの？](http://yohhoy.hatenablog.jp/entry/2014/12/21/171035)
* [次期C++に導入されるメモリバリアについて解説してみる](http://yamasa.hatenablog.jp/entry/20090816/1250446250)
* [メモリバリアを理解するために必要な3つのこと](http://yamasa.hatenablog.jp/entry/20110219/1298133192)
* [マルチコア時代の 並列プログラミング ~ロックとメモリオーダリング~](http://www.nminoru.jp/~nminoru/data/b2con2006_nminoru.pdf)

## ロックフリーデータ構造
