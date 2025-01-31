# 2025/01/15
- 面談の日程を取りつけた
- 紙のノートを作るようにしようかな
- Kashiwara-Schapiraと、Schapiraの講義ノートを読んだ。右随伴はlimitを保つことの証明を読んで終わった。こういうのを知っておかないと、ホモロジー代数の勉強にならない。
- <details><summary>フルスタックWeb開発の4章を読んだ</summary>

  - バックエンドとフロントエンドの2つのサーバーを立ち上げて、フロントエンドにアクセス→バックエンドで処理→フロントエンドでページ書き換え、の例を見た。
  - フロントエンドがバックエンドサーバーのURLを知るために、フロントエンドのnext.config.jsに書いてある。正確に言うと、URLとして解釈されるべき部分が「/api/:path」の形で書かれていたら、「(バックエンドのURL)/api/:path」に書き換えられるように設定されている。
  - さらに、バックエンドがサーバーのURLを知るために、config/settings/development.pyにデータベースのURLやユーザー名、パスワード等を書いている。
</details>

# 2025/01/16
- Kashiwara-Schapiraと、Schapiraの講義ノートを読んだ。Setの小さい図式に対しlimを定義し、それを使って一般の圏の小さい図式のlimitを定義した。南中やり方や。
- フルスタックWeb開発の5.3節まで読んだ。ショッピングサイトのシンプルな例を作るらしい。

# 2025/01/17
- Weibelを読んだ。
  - $ \mathsf{Mod} $ - $ R $ におけるfiltered colimit functor $(\mathsf{Mod}$- $R)^I\to \mathsf{Mod}$- $R$は完全である。
  - 一般のアーベル圏ではfiltered colimit関手は完全とは限らない。 $\mathsf{Ab}^\mathrm{op}$の場合に反例がみつかった。（こういうのをちゃんとノートにメモしておくべき？）
- 先生と面談した。入学前にちょっとだけセミナーすることになった。勉強頑張ろうねという話になった。
# 2025/01/18
- 夜通し寝れない→バイトいく→すぐ寝る→18:00に起きる
- つまり何もしてないということ
- 完全関手とホモロジー関手の交換の証明めんどくさすぎだろ。インターネット上にはまともな証明が載ってない。直感的に自然な構成はわかるけど、それが関手的な同型であることが述べられてない。いかんでしょ。
# 2025/01/19
- 23:30には寝たのに、バイトあとまたねてしまった。
# 2025/01/20
- Weibel homをExercise 2.7.2まで読んだ。「mapping coneがacyclic $\Leftrightarrow$ 擬同型（weak equivalence）」を使った気がする。
# 2025/01/21
- <details><summary>nlab「field(physics)」の1-Generalを読んだ。</summary>

  - 歴史的に、電磁場の理論と重力場の理論が古典的場の理論と呼ばれるものである。
    - チャート（局所座標）を固定すると、電磁場は電場と磁場に分かれ、ベクトル場としてモデル化される。
    - しかし、局所座標を固定しないと、電磁場は2つのベクトル場で表すことはできず、**field strength**という(0,2)-tensor fieldつまり微分2形式として表現される。つまり、ベクトル場によるモデル化よりも、ちょっといいモデル化である。
    - さらに、グローバルには電磁場はテンソル場にはならず、接続付きU(1)束の微分コホモロジーのdegree-2 cocycleとなる。
    - 重力場は(2,0)テンソルである擬リーマン計量としてモデル化される。もっとちゃんというと、**vielbein field**というものでモデル化されるらしい。
  - 一般の力場は接続によってモデル化される。field strengthは(0,2)-tensor fieldとなる。
  - 物理に登場するすべての物質は場からなる。とくに、力場はベクトル束の接続となり、物質場は同伴バンドルのセクションとなる。
  - 場の理論はもとは時空上の場の理論として開拓されたが、固定された時空Xの中を動く粒子も場の理論を用いできる。
    - この場合、場は時空の上ではなく、**世界線**、つまり実数直線 $\mathbb{R}$の上にある。可微分曲線 $\mathbb{R}\to X$ がその系を設定する。**sigma-model field**と呼ばれる。
    - 同様に、1粒子の量子力学は、1次元の世界線上の場の量子論となる。
    - これは一般化される。曲面 $\Sigma_2$から時空 $X$への可微分写像は、世界面（worldsheet） $\Sigma_2$上のstring（particleではない）を設定する。高次元化を続け、 $\Sigma$が3次元なら、worldvolume of membraneを設定し、それより大ならworldvolume of braneを設定する。
  - 以上、空間の上の場を、時空として解釈する場合と、固定された時空の中を動くオブジェクトのworldvolumeとして解釈する場合を述べたが、これらに基本的な区別はない。
  - この2つの解釈をミックスし、worldvolume上の重力場を動くparticle/stringの記述も可能である。
</details>

- SchreiberのarXivを漁った。
- HoTT gameなるものを知った。やりたい。
- Geometry of Physicsのcategories and toposesの最初の方（contentsより前）を読んだ。
  - Example 1.36 離散、余離散位相空間の間のmodalityくらいならわかる？（読んでない）
  - 超弦理論のことばっかり言っててようわからんかった。
- plfa 1. のEqualityの途中まで終わった。
  - chain proofがどうやって動いているかまだよくわからない

# 2025/01/22
- バイトをした。人員が多かったのもあったが、段取りはなかなか良かった。
- plfa(agda)のEqualityをよみ切った。
  - chain proofの実装は少しばかり魔法のように見える。根拠を用意してequalityのchainを作るだけなんだけども。
  - judgmental equality（おそらくAgdaでいう=）とpropositional equality（おそらく、今回定義した≡）の違いが良くわかっていない。
- Unicode文字を等幅で表示できるようにDejaVu Sans Monoフォントを追加。Agdaでunicode文字を多用するので追加した。
- <details>
  <summary>
    Landsmanを読んだ。
  </summary>

  - 集合 $X$ 上のtransition probability $\tau\colon X\times X\to [0,1]$ と、それが定める $X$ の基底、またobservableとそのspectral resolutionの定義を見た。手はまだ動かしていない。

</details>

# 2025/01/23

- <details>
  <summary>Landsmanを読んだ。</summary>

  - 昨日読んだtransition probabilityが定めるobserbable等の概念について有限集合に限って確かめた。無限集合の場合は和の収束について考えないといけないので後回しにする。

  - <details>
    <summary>D.2(命題論理)の頭を読んだ。</summary>
    
    - propositional logicでは、well-formed formulaeとpropositionsは一致する。
    - character set i.e. signature $\Sigma$ から再帰的に $\vee,\ \wedge,\ \to ,\ \neg$ を使って **proposition** i.e. well-formed formulaが作れる
    - この作り方からwell-formed formulae全体の集合 $B_\Sigma$ ができる
    - **valuation**もしくは**truth function** $V\colon \Sigma\to \{0,1\}$ とは、写像 $V\colon \Sigma\to \{0,1\}$ のことである。
    - valuationは$V\colon B_\Sigma\to \{0,1\}$ に適当な意味で一意に延長する。$\vee,\ \wedge,\ \to,\ \neg$ のtruth table を用いて再帰的に定義する。
    - proposition $\varphi \in B_\Sigma$ が、atomic propositionの真理値（つまりvaluation $V\colon \Sigma\to \{0,1\}$ ）に依らず常にtrueであるとき、 $\varphi$ を**トートロジー**と呼び、 $\vDash\varphi$ とかく。
    - logicに関する定理と、logicの内部の定理を区別する。
    - propositional logicでは、stating axiom からスタートし、deduction rulesに従って演繹して得られるpropositionを**theorem**と呼ぶ。
    - したがって、axiomはtheoremである。
    - propositionが $\varphi$ がtheoremであるとき、 $\vdash\varphi$ とかく。
    - theoremの定義から、 $\vdash\varphi$ であるかどうかという問題は純粋にsyntacticであり、 $\varphi$ に含まれるatomic propositionの真理値に依存しない。
    - しかし、axiomsとdeduction rulesには次のようなconsistency requirementがある。それは、 $\varphi$ に含まれるatomic propositionの真理値をどうとっても $\varphi$ が真であるというものである。すなわち、 $\vdash\varphi$ ならば $\vDash\varphi$ であるということである。これを、**soudness** conditionと呼ぶ。日本語では健全性という。
    - 逆に、 $\vDash\varphi$ ならば $\vdash\varphi$ となることを、**completeness** conditionと呼ぶ。おそらく、日本語でいう意味論的完全性のことである。
    - soundかつcompleteになるようなaxiomとdeduction rulesを定めることが目標になる。
    - soundかつcompleteな異なる2つのaxiom/deduction rulesができる場合があるが、それらは同じ定理を導くすなわちトートロジーを定めるという意味で同値である。
    - axiomsとdeduction rulesをうまく選べば、soundかつcompleteにできる（とばした）。
    - $\psi$ から$\varphi$ が演繹できるとき、 $\psi\vdash\varphi$ とかく。
    - $B_\Sigma$ 上の同値関係を、 $\psi \sim\varphi\Leftrightarrow \psi\vdash$ かつ $\varphi\vdash\psi$ であると定め、 $L_\Sigma:=B_\Sigma /{\sim}$とおく。これを、**Lindenbaum(-Tarski) algebra**と呼ぶ。
  - 1.4（古典力学の命題論理）を読んだ。が、なんかモチベーションが良くわからないので後半は読みとばした。
  </details>

- 量子論の基礎の3.24まで読んだ。シュレディンガー方程式は一般のバナッハ空間における常微分方程式であるが、どれぐらい有限次元の場合と同じことができるかわからない。
</details>

# 2025/01/24
- バイトをした。ちょっと段取り悪かったせいで持ち場が終わるのが9:20になってしまった。もうちょっとイモ類とナスピーマンの陳列ルーティーンを考えないといけない。
- 量子論の基礎の3.24.4では無限次元空間での微分を行っているが、これが実際にできることを確かめた。Lang, Real and Functional Analysisにほとんど書いてある。 $\frac{d}{dt}\left\langle\psi(t)|\varphi(t)\right\rangle=\left\langle\frac{d}{dt}\psi(t)\middle|\varphi(t)\right\rangle+\left\langle\psi(t)\middle|\frac{d}{dt}\varphi(t)\right\rangle$ であることは自力で確かめた。
- 日記を個人ページに移動した。Github PagesはデフォでJekyllを使ってmarkdownをhtmlに変換して表示してくれるようになっているので、その利用方法を学んだ。mathjaxによる数式描画が上手くいかなかったがcssを抜いたら行けた。cssの追加は後々考える。
- 量子論の基礎の3章まで読んだ。閉じた系の時間発展、すなわちシュレディンガー方程式を満たすこと、また、測定時に状態が受ける反作用、つまり射影仮説について学んだ。
  - このことを紙のノートにメモすることにした。
- Weibelの2.7.6(balancing Ext)まで読んだ。augmentation mapの誘導する射が擬同型であるという証明だった。具体的に何が同型を与えるかわかるというのは超重要だが、spectral sequence proofも読みたいね。
  - ホモロジー代数のメモ用ノートも作った。
 
# 2025/01/25
- 量子論の基礎の正準量子化の所を少し読んだ。系の時間発展はラグランジアン/ハミルトニアンの停留点になるという事実は知っているが、もう少し解析力学を知っていた方が良いと思ったので解析力学もちゃんと勉強することにする。
- Weibelを読んだ。
  - 2.7.7はright balanced functorの定義(Cartan - Eilenbergにもある)だが、$\mathrm{Hom}(A\otimes B, C)$はright balancedでないと思う。
      - Mathstack Exchangeにも同様の主張があった。$A$が射影的で、$\mathrm{Hom}(A\otimes B, -)$が完全でない例を作ればよいが、$A=\mathbb{Z}$、$B=\mathbb{Z}/2\mathbb{Z}$とおけばそのそのテンソル積は$\mathbb{Z}/2\mathbb{Z}$に等しく、これはアーベル群として射影的でない。よってこれをdomainとするHom関手は完全でない。
  - 2.7.8 (TorのExternal prodtct)を見た。係数変更における積$(A\otimes R)\otimes_Z(A\otimes R)\to A\otimes_Z R$の拡張に見えるけど、なんにつかうん？

# 2025/01/26
- WeibelとSchreiber「Intro to Homological Alg...」を読んだ。
  - 平坦加群$M$は$-\otimes M$-acyclicなので、平坦加群についてまとめようとした。
  - 「$M$が$A$-平坦$\Leftrightarrow A$の任意の有限生成イデアル$I$について、$I\otimes M\to R\otimes M\cong M$が単射」という命題を示そうとしたが、間に合わなかった
  - 証明はStacks Projectにある。これの直感が全くわかない。

# 2025/01/27
- バイトの後寝てしまいなにもできなかった...

# 2025/01/28
- Stacks Projectにある証明を読んだ。直感を教えてくれ

# 2025/01/29
- SchreiberのIntro to Homological Algebraの3.113あたりを読んだ。
  - 3.114の証明にLazard's criterion必要なくね...（projectiveのcolimはprojectiveなので（間違ってる？））
    - proj.のcolimはprojになるとは限らないっぽい（簡単に証明できなかったので）。
  - projの(filtered) colimがprojになるとはかぎらないのかもしれない。
  - 環上の加群の圏に関しては、任意のオブジェクトのfree resolutionをとれるらしい（たしかに）。
  - それならそのfree res.のcolimはflatになっていいね！
- filtered colimit、ind-object、cofinal map(functor)あたりについてちゃんと学びたい（Kashiwara-Schapiraよめ）
- (co)limをシステマチックに使えるようになるために、Kan拡張も学ぶべき(Kashiwara-Schapiraよめ)
- Landsmanの2章の頭を読んだ。ヒルベルト空間の無限テンソル積を知らず終わりになった。

# 2025/01/30
- バイトだめ杉田。
  - カットサラダのAI発注（？）をやるらしく、決められたレイアウトで品出ししないといけないのに、適当に埋めちゃった。次いったら怒られっるかも
- Landsmanの2章を読むのに、有限次元ヒルベルト空間の勉強をする必要があるが、わからん
  - spectral theoremを理解するためにC*-代数のことも少し知っておく必要があるんだけども、そんなこと勉強していたら量子論勉強できないよ！
 
# 2025/01/31
- Landsmanを読んだ。
  - appendix Aの4節を読んだ。有限次元ヒルベルト空間の自己共役作用素$a$に対し、自然なC*-代数の同型$\mathbb{C}[a]\cong C^*(a)$があることをみた。
  - $C^*(a)$とは、$a$と$\mathrm{id}$で生成されるC*-algのことらしいが、生成されるとは何？定義がなくてわからなかった。読み飛ばした。
  - 2.1節の頭を読んだ。density operator $\rho$とrandom variable $a$とそこから定まる$\sigma(a)$上の確率分布$p_a$の定義をみたが、それらの関係が良くわからない。
