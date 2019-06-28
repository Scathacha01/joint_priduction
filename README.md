# TitechSwimTeam

東工大水泳部のHPの原案です。

----
## 更新

更新する際に変更するのは以下です。

* index.htmlの.news内の</table>直前に挿入
```html
<table>
   ...
   <!-- 以下が追記する内容 -->
   <tr>
      <td>日付</td>
      <td>お知らせ内容</td>
   </tr>
</table>
```
* about.htmlの記事の中の部員の人数の変更
* member.htmlの.members内の部員の学年の変更、新入生の追加
`<li><a href="#tamaki-asahi">玉城旭</a></li>`のaタグの#以降とaタグの中身は対応させてください。
* member.htmlの.member内の<div class="memvber">直後の引退した4年生の記事の削除。
対応する</div>直前に新入生の記事の挿入。
      <h3 class="name" id="higuchi-ryouhei">樋口凌平</h3>
        <div class="flex-box-member2">
          <img src="https://stat.ameba.jp/user_images/20180706/12/ensuikai/81/25/j/o0270047214224128840.jpg?caw=800" alt="" width="200" height="200">
          <table>
            <tr>
              <th>所属</th>
              <td>情報通信系</td>
            </tr>
            <tr>
              <th>出身高校</th>
              <td>東京都立国分寺高校</td>
            </tr>
            <tr>
              <th>S1</th>
              <td></td>
            </tr>
            <tr>
              <th>Pos.</th>
              <td>フローターバック</td>
            </tr>
            <tr>
              <th>一言</th>
              <td></td>
            </tr>
          </table>
        </div>
