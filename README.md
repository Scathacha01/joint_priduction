# TitechSwimTeam

東工大水泳部のHPの原案です。

----
## 更新

更新する際に変更するのは以下です。

* index.htmlの.news内の</table>直前に挿入。試合日程とか部活の用事とか。
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
* result.htmlの
* member.htmlの.members内の部員の学年の変更、新入生の追加。`<li><a href="#tamaki-asahi">玉城旭</a></li>`のaタグの#以降とaタグの中身は対応させてください。
* member.htmlの.member内の<div class="memvber">直後の引退した4年生の記事の削除。対応する</div>直前に新入生の記事の挿入。
```html
<div class="member">
   ...
   <!-- 以下が削除・追加する内容のフォーマット -->
   <h3 class="name" id="aタグの#以降と同じ値">名前</h3>
   <!-- 玉城旭の例では<h3 class="name" id="tamaki-asahi">玉城旭</h3> -->   
   <div class="flex-box-member2">
      <img src="表示する画像のURL" alt="" width="200" height="200">
      <table>
         <tr>
           <th>所属</th>
           <td></td>
         </tr>
         <tr>
           <th>出身高校</th>
           <td></td>
         </tr>
         <tr>
           <th>S1</th>
           <td>得意種目</td>
         </tr>
         <tr>
           <th>Pos.</th>
           <td>水球のポジション。スタメンだけでもいいかも</td>
         </tr>
         <tr>
           <th>一言</th>
           <td>本人に聞いてください</td>
         </tr>
      </table>
   </div>
   ...
</div>
```
* 
