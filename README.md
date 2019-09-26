# paintjs

바닐라 자바스크립트와 캔버스를 이용한 그림그리기 게임

# Deploy

https://jch1223.github.io/paintjs/.

# Learn

- canvas API를 어떻게 사용해야 하는지 이해할 수 있었다.
- a태그에 download 속성을 넣어 클릭시에 해당 url의 자료를 다운로드 받을 수 있다.

<pre>
function handleClickSave(event) {
  const imgLink = canvas.toDataURL("image/png");
  const link = document.createElement("a");

  link.href = imgLink;
  link.download = "PaintJS";
  link.click();
}
</pre>
