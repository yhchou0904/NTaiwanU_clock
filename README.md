# NTaiwanU_clock

### Things to keep in mind
1. 使用這個 code 需要有一台不關機的電腦以及持續運作的 Python，但如果你有一台不會關機的電腦也可以直接安裝 Google Remote Desktop。一方面當成這個 code 出問題的保障，一方面其實可以直接取代這個東西的功能--，只要你願意準時起床打開電腦或手機的app--。 Google Remote Desktop 請見[介紹](https://remotedesktop.google.com/)，學校好像有明文寫不能用 teamviewer 之類的遠端桌面，但也很像沒有人在抓。
2. 因為使用 `selenium` 當作主要的核心，`selenium` 使用 driver 來驅動瀏覽器，但在下載 driver 時需要下載與你瀏覽器相容的版本，故瀏覽器更新版本時會有需要重新下載 driver 的情形。（selenium 的機制請見[selenium 官方 document](https://selenium-python.readthedocs.io/getting-started.html)）到後來我甚至會把瀏覽器自動更新關掉，供參。
