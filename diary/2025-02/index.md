# 2025/02/01
- きょうバイトの人員めっちゃおった。なぜ？
- Landsmanの2.2まで読んだ。作用素環寄りの関数解析の本読むべきですね。中途半端な理解で飛ばし飛ばし読むのはあまりよくない読み方だと聞いたことがあります。

# 2025/02/02
- Schapiraのlecture note "Cat and Sheaves"の2.3を読んだ。filtered colimitとind-objectを早く読みたい。
  - 2.5.1($\mathscr{C}$が$I$-completeなら任意の関手圏$\mathrm{Fct}(J,\mathscr{C})$も$I$-complete)を読んだ。というか証明した。バカ時間かかった（9ページ使った）。
  - あとはやくKan拡張の定義を読みたい。でないと、RiehlのCategorical Homotopy Theoryに突撃出来ない。

# 2025/02/06
- バイト4連勤だった。4日ともつかれてすぐ寝てしまった。
- 就寝時間が23時以降であるというのは、遅いのかもしれない
- 年末にフルタイムで出たが、疲れすぎて夜は何もできなかった。週5で8時間働いている社会人に娯楽はないのかもしれない。南無
- Riehlのcontextの3.3を読んだ。lim、colimの説明はKashiwara-Schapiraがわかりやすいが、
  - 「Cone」関手という名前の導入と、それのrepresentativeとしてのlimの定義（これはKSと同じ）
  - category of cones over F $\int\mathrm{Cone}(-,F)$のterminal objectとしてのconeの定義の二つがあるのは良い。
  - エンドの記法がこの段階で出てくるのもいい。
  - 関手がlimをpreserve, reflect, createすることを定義している。名前を付けるのはありがたいが、ちょっと混乱する。どれがどのような文脈で登場するのか等、これらの関係をもう少しよくまとめることはできないですかね？
  - 関手圏におけるlimの記述、とくに忘却関手$\mathsf{C^A}\to \mathsf{C}^{\mathrm{op}\mathsf{A}}$がlimをstrictly createsすることなどを、上の3つの性質を通じて証明するのはすごく良いと思う。

# 2025/02/09
- Riehlのcontextを読んだ。3.3.9が神
- スト図で極限を表現することってできるんですか？
- 随伴の頭まで読んだ。面白いですね。
- セミナーの準備をしないといけない...

# 2025/02/11
- Riehlのcontextの随伴の章の最初の節を読んだ。
- セミナー何話そう。。。次が候補
  - 導来圏の定義
  - 導来関手の定義
  - 導来関手の計算方法
  - Kunnethの定理と普遍係数定理のsectralsequence proof
  - 誘導表現と余誘導表現と、それを扱うための随伴関手の話
 
# 2025/02/12
- 最近スーパーに届くジャガイモがあまりよくない...去年のこの時期もそうだった記憶がある。
- Riehlの4.1節を読み終えた。
  - 随伴$F:\mathsf{C}\rightleftarrows\mathsf{D}:G$があったとき、コンマ圏の同型$F\downarrow\mathsf{D}\cong \mathsf{C}\downarrow G$であって、$\mathsf{C}\times\mathsf{D}$への忘却関手と交換するものが自然にある。
 
# 2025/02/13
- Riehlのcontextの4.2, 4.3を読んだ。
  - adjunctionのunit、counitを用いた定義。こちらの方がわかりやすい。string diagramの等式にも直接変換できる。
  - preorderの間の随伴の定めるGalois connection。代数多様体と多項式環のイデアルの対応、syntax-semantics duality。
  - 関手$F\colon\mathsf{C}\to\mathsf{D}$と$d\in\mathsf D$に対し、関手$\mathsf{D}(F-,d)$（表現可能と仮定）のrepresentativeを対応さすと$F$の右随伴関手$G\colon \mathsf D\to\mathsf C$に一意に延長できる。
  - 次回以降、これの多変数化をみる。

# 2025/02/22
- フルスタックの5章まで実装した。フロントエンドのページをMaterial UIを用いてかっこよく知り方法を学んだ。
  - かっこいいとは思わない。
 
# 2025/02/25
- Milnor-Stasheffのsmooth manifoldの定義とLeeのそれが同値であることを示した。
  - Whitney embedding thmより、多様体はある$R^N$に埋め込めるが、そのやり方は無限にある。Milnor-Stasheffはその埋め込み方まで指定したものと思っておけば十分。
- Grassmann多様体がコンパクトハウスドルフであることを示した。
  - まず、$\mathrm{Gr}_n(\mathbb R^{n+k})$はStiefel多様体$V_n(\mathbb R^{n+k})$（$\mathbb{R}^{n+k}^n$の開部分多様体）の商空間である。
  - orthonormal frame全体のなす部分空間$V^0_n(\mathbb R^{n+k})$の商空間でもある。
  - Hausdorff性は$w\in \mathbb R^{m+n}$に対し定まる関数$\rho_w\colon\mathrm{Gr}_n(\mathbb{R}^{n+k})\to \mathbb R,\ X\mapsto (wとXの距離)$が連続であることから従う。連続性は商写像の普遍性を用いて示す。
  - コンパクト性は$V^0_n(\mathbb R^{n+k})$が$(\mathbb{R}^{m+n})^n$の有界閉集合であることから従う。
