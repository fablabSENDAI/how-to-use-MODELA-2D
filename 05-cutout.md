---
layout: default
title: 05.データ送信〜切断加工
nav_order: 6
---

# 05.データ送信〜切断加工
<br><br>

<img src="assets/05-1.jpg" width="320" alt="hi" class="inline"/> <img src="assets/05-2.jpg" width="320" alt="hi" class="inline"/><br>
<br>

ウィンドウ左側の**「load.png」**をクリックし、<br>
加工したいpngデータを選択して**「Open」**ボタンをクリックします。<br>
加工したいデータのサイズに間違いがないか再度確認してください。<br>
<br>
<br>
<br>

<img src="assets/05-3.jpg" width="640" alt="hi" class="inline"/><br>
<br>

ウィンドウ上部のプルダウンメニューから**"cut out board(1/32)"**を選択してください。<br>
更に、[03.マシンのセットアップ](/03-machine-setup.md)の手順を参考にして、<br>
**直径約0.8mm**（1/32インチ）のエンドミルに取り替えます。<br>
<br>
<br>
<br>

<img src="assets/05-4.jpg" width="640" alt="hi" class="inline"/><br>
<br>

**"bot z (mm)"** に、使用する素材の厚さ+0.1mm（実際には削るのでマイナスに変換）を入力します。<br>
日本で一般的に使用される紙フェノール基板材料の厚さは約1.8mmなので、ここでは**"-1.9"** と入力し<br>
**「make.path」**ボタンをクリックして実際の加工パス（エンドミルの動くライン）が表示させます。<br>
（このときに、xmin(mm)とymin(mm)の数値を変更すると原点がズレてしまうので注意！）<br>
<br>
<br>
<br>

<img src="assets/05-5.jpg" width="640" alt="hi" class="inline"/><br>
<br>

**「make.rml」** ＞ **「send it!」** ＞ **「Begin Milling」** とクリックし、加工を開始します。<br>
<br>
<br>
<br>

<img src="assets/05-6.jpg" width="320" alt="hi" class="inline"/> <img src="assets/05-7.jpg" width="320" alt="hi" class="inline"/><br>
<br>

加工中にエンドミルが折れてしまうこともあるので、加工を開始したら完全に放置するのではなく<br>
時々様子を確認するようにしましょう。<br>
加工が完了したら**「Exit」**ボタンを押します。
<br>
<br>
<br>

<img src="assets/05-8.jpg" width="640" alt="hi" class="inline"/><br>
<br>

テーブルをマシンから取り外し、ヘラなどを使用して素材を剥がします。<br>
もし表面にバリなどがある場合は、#800〜#1200などの細かめのやすりで削り落としてください。
<br>
<br>
<br>
<br>
<br>
<br>
