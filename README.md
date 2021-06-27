# js30 文字紀錄
# 20210626
1. init repository
2. const btnsArr = Array.prototype.slice.call(btns)
    * Converting a NodeList to an Array
    * 看解答後，const keys = Array.from(document.querySelectorAll('.key'));能更漂亮的轉換成array
3. html中的audio event 可直接用event.play()播放
    * event.currentTime = 0 可讓連按聲音不會延遲
4. 在document.querySelector時應該用解答的用法直接抓對應的data-key，這樣對於我的解法還能省去各再find一次的操作
5. 看完解答後強烈的感覺到我的邏輯都混在一起，也就是所謂的耦合度很高，以後要多注意這部份


