# Noto-sans Subset font sample
* [Qiita記事](http://qiita.com/taka4sato/items/dba258d17d68500081f5)
* [Noto Sans font](https://www.google.com/get/noto/)


### 内容物
| Directory名 | 説明 |
| -------------------- |  -------------------- |
| font_zh-cn_8000 | Noto Sans中国語簡体字を通用规范汉字表の1-3級の8000文字でSubset化したwoff/ttf/eot font |
| font_zh-cn_3500 | Noto Sans中国語簡体字を通用规范汉字表の1級のみの3500文字でSubset化したwoff/ttf/eot font (拼音記号を追加) |

### 補足
* cssで[font-faceにunicode-rangeという値をSet](https://spyweb.media/2017/09/13/font-face-subset-synthesis/)することで、fontのSubset化も可能ですが、以下のような懸念があります
  * Downloadするfont fileのサイズが小さくなる訳では無い(あくまでBrowser側でsubset化を行います)
  * Browserの[対応/非対応がある可能性がある](https://caniuse.com/#search=unicode-range)
