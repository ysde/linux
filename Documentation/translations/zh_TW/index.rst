.. SPDX-License-Identifier: GPL-2.0

.. raw:: latex

	\renewcommand\thesection*
	\renewcommand\thesubsection*
	\kerneldocCJKon
	\kerneldocBeginTC

.. _linux_doc_zh_tw:

繁體中文翻譯
============


.. note::
   linux核心文件繁體中文的翻譯工作正在進行中。如果您願意並且有時間參與這項工
   作，歡迎提交修正給胡皓文 <src.res@email.cn>。

許可證
----------

下面的文件介紹了Linux核心原始碼的許可證（GPLv2）、如何在原始碼的樹狀紀錄中，正確標記各個文件的許可證、以及完整的許可證內文的連結。

Documentation/translations/zh_TW/process/license-rules.rst

用戶相關文件
--------

下列的使用說明文件是爲了那些「試著在特定系統，最佳化linux核心執行」的用戶所寫的

.. toctree::
   :maxdepth: 2

   admin-guide/index

TODOList:

* kbuild/index

硬體相關文件
------------

下列文件有linux核心對於不同平台的期待的資訊。

TODOList:

* firmware-guide/index
* devicetree/index

應用程式開發者文件
--------------------

user-space API文件，整合了有關於linux應用程式開發者方面的核心介面。

TODOlist:

* userspace-api/index

linux核心開發簡介
------------

這些使用說明全面的包含了關於如何開發linux核心的資訊。linux核心社群非常龐大，一年下來有數千名開發者做出貢獻。與其他大型社群一樣，知道一些事情是如何運作的，會使得你PR的合併過程變得更加容易。

.. toctree::
   :maxdepth: 2

   process/index

TODOList:

* dev-tools/index
* doc-guide/index
* kernel-hacking/index
* trace/index
* maintainer/index
* fault-injection/index
* livepatch/index
* rust/index

linux核心API文件
-----------

以下使用說明從linux核心開發者的角度，詳細介紹了特定的linux核心子系統是如何運作的。這裡的大部分資訊，都是直接從linux核心原始碼內取出來的，並根據需要添加補充說明。

TODOList:

* driver-api/index
* core-api/index
* locking/index
* accounting/index
* block/index
* cdrom/index
* cpu-freq/index
* ide/index
* fb/index
* fpga/index
* hid/index
* i2c/index
* iio/index
* isdn/index
* infiniband/index
* leds/index
* netlabel/index
* networking/index
* pcmcia/index
* power/index
* target/index
* timers/index
* spi/index
* w1/index
* watchdog/index
* virt/index
* input/index
* hwmon/index
* gpu/index
* security/index
* sound/index
* crypto/index
* filesystems/index
* vm/index
* bpf/index
* usb/index
* PCI/index
* scsi/index
* misc-devices/index
* scheduler/index
* mhi/index

與linux核心架構無關的文件
----------------

TODOList:

* asm-annotations

與特定linux核心架構相關的文件
----------------

TODOList:

* arch

其他文件
--------

有些未排序的文件似乎不適合放在文件的其他部分，或者可能需要進行一些調整，或轉換爲reStructureText格式，也有可能就是太舊了。

TODOList:

* staging/index
* watch_queue

目錄和表格
----------

* :ref:`genindex`

.. raw:: latex

	\kerneldocEndTC
