作品素材临时存放规则

请把你要新增到网站小窗里的素材放在这个文件夹：
D:\网页\public\works\inbox

推荐做法：
1. 每个作品单独建一个文件夹。
2. 文件夹名尽量写作品名，或写我给你的作品 id。
3. 文件按显示顺序命名：01.png、02.jpg、03.mp4、04.webm。
4. 视频如果需要封面，可以放 03-cover.jpg。

例子：
D:\网页\public\works\inbox\代录
  01.png
  02.png
  03.mp4
  03-cover.jpg

D:\网页\public\works\inbox\一张窗花，走进城市
  01.png
  02.jpg
  03.mp4

支持图片：
png / jpg / jpeg / webp

支持视频：
mp4 / webm / mov / m4v / ogg

你放好后，告诉 Codex：
“我放好了，帮我读取 inbox 并接到作品里。”

Codex 会读取这个文件夹，确认里面有哪些文件，然后把它们接入 public/works.json。
