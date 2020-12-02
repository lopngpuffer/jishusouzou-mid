<!DOCTYPE html>
<html lang="ja">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>情報科学科お役立ちサイト</title>
</head>

<body>
  <header>
    <div class="head">
      <p>USEFUL<br><span class="website">WEBSITE</span></p>	
      <div class="name">INFORMATION SCIENCE</div>
  </header>
  <div id="menu-bar">
    <div>TOP</div>
    <div>ドイツ</div>
    <div>アイツ</div>
  </div>



  <div class="subject">
    <details>
      <summary>
        数学
        <span class="badge"><img src="images/math.png" alt="math" class="math"></span>
      </summary>

      <div class="container">
        <p>
          <a href="https://matrixcalc.org/ja/">行列計算機</a><br>
          行列に関連する様々な計算を行ってくれるサイトです。過程も含めて記述してくれます。<br>
          後述のWolframAlphaも便利ですが、行列に関してはこちらの方が使いやすいかと思います。<br>
          某講義で解答が配布されず困っている方も多いかと思いますが、これを使えば理解できるはずです。<br>
        </p>

        <p>
          <a href="https://ja.wolframalpha.com/">WolframAlpha</a><br>
          微積分や線形代数などの数学に関するものは勿論、物理や化学などの分野も含め世の中の様々な計算を行ってくれるサイトです。<br>
          過程の記述は有料版のみですが、検算には十分使えます。<br>
        </p>

        <p>
          <a href="https://www.geogebra.org/">GeoGebra</a><br>
          関数を入力するとグラフを描画してくれるサイトです。視覚的に捉えることで、より理解を深めることが出来ます。<br>
          極値や交点の値も計算してくれます。<br>
        </p>

        <p>
          <a href="https://mathematicspedia.com/index.php?Mathpedia">Mathpedia</a><br>
          大学数学全般に対して、基礎的な事項の解説がなされています。<br>
          内容は少し難しめで未完成の部分も多いのですが、大学数学の大まかな全体像を捉えるのには良いかと思います。<br>
        </p>

        <p>
          <a href="http://w3e.kanazawa-it.ac.jp/math/">KIT数学ナビゲーション</a><br>
          高校数学と学部1・2年レベルの大学数学範囲における、基礎的な用語や公式が見やすくまとめられています。<br>
          わからないことが出てきた時に辞書的な使い方をするのがオススメです。<br>
        </p>

        <p>
          <a href="https://mathtrain.jp/">高校数学の美しい物語</a><br>
          主に高校数学の範囲で、基本公式の確認から数学オリンピックレベルの問題の解説に至るまで、様々なトピックが独立した記事になっています。<br>
          勿論普段の学習にも使えますが、どちらかと言えば知的好奇心を満たしたい方向けのサイトです。<br>
        </p>
      </div>

    </details>

    <details>
      <summary>
        プログラミング
        <span class="badge"><img src="images/pro.jpeg" alt="programming" class="programming"></span>
      </summary>
      <div class="container">

        <p>
          <a href="https://www.processing.org/reference/">Processing公式リファレンス</a><br>
          Processingの公式リファレンスです。Processingの標準機能や公式のライブラリなどが掲載されています。<br>
          英語ですが、翻訳すれば活用できると思います。<br>
        </p>

        <p>
          <a href="https://typing.run/">typing.run</a><br>
          明治大学総合数理学部先端メディアサイエンス学科の春学期プログラミング演習1で使用されたサイトです。<br>
          Processingのコードを写経タイピングすることができます。タイピング速度やタイポ率が表示されます。<br>
          明大生ではないため、一部の機能に制限がありますが、寿司打のように楽しめると思います。<br>
        </p>

        <p>
          <a href="https://developer.mozilla.org/ja/">MDN web docs</a><br>
          このサイトは、Firefoxを開発したMozillaが公開している、開発者向けのサイトです。<br>
          web技術に関して調べたい場合は、まずこのサイトを参照することで正しい情報を得ることができます。<br>
        </p>

        <p>
          <a href="https://docs.python.org/ja/3/reference/index.html">Python言語リファレンス</a><br>
          Pythonの公式リファレンスです。<br>
          1年生の授業では、Pythonは学習しませんが、2年次以降はお世話になるかもしれません。<br>
        </p>

        <p>
          <a href="https://9cguide.appspot.com/">苦しんで覚えるC言語</a><br>
          実践プログラミングの参考書にも指定されているサイトです。体系的にC言語を学ぶことができます。<br>
        </p>

        <p>
          <a href="https://atcoder.jp/contests/APG4b">C++入門 AtCoder Programming Guide for beginners(APG4b)</a><br>
          競技プログラミングで有名なAtCoder社が提供している無料のプログラミング入門教材です。<br>
          AtCoderを始めたいけど何をしたらいいのかわからない！という人におすすめの教材です。<br>
          C++について深く学ぶというよりは、基礎プロで扱った内容+αをC++で学習するというのがイメージしやすいと思います。<br>
        </p>
      </div>
    </details>

    <details>
      <summary>
        英語
        <span class="badge"><img src="images/english.jpg" alt="english" class="english"></span>
      </summary>
      <div class="container">
        <p>
          <a href="https://www.deepl.com/ja/translator">Deepl</a><br>
          ディープラーニングを利用したテキスト翻訳サービスです。英語や日本語だけでなく、様々な言語間での翻訳が可能です。<br>
          翻訳の精度は類似サービスと比べて高く、非常に使い勝手が良いです。<br>
          しかし、まだまだ完璧ではなく頻繁に誤訳も発生するので、最終的には自分でチェックするのが肝心です。<br>
        </p>

        <p>
          <a href="https://www.ibm.com/watson/jp-ja/developercloud/speech-to-text.html#try-it-out">Speach to
            Text</a><br>
          入力された音声を認識し、それをテキストに書き起こしてくれるサービスです。<br>
          翻訳は勿論のこと、文書作成や発音練習などにも使えます。<br>
        </p>

        <p>
          <a href="https://www.grammarly.com/">Grammarly</a><br>
          英文の文法をチェックしてくれるツールです。<br>
          直接サイトにアクセスしての利用もできますが、ブラウザの拡張機能としてインストールしておくとテキスト入力時にリアルタイムでチェックを行ってくれます。
        </p>

        <p>
          <a href="https://tool.stabucky.com/word_counter.htm">英単語カウンター</a><br>
          英文の語数を数えてくれるツールです。<br>
          英作文の課題で最後に語数を記載しなければならない時などに便利だと思います。<br>
        </p>
      </div>

    </details>

    <details>
      <summary>
        情報処理入門
        <span class="badge"><img src="images/ono.jpg" alt="panda" class="onoue"></span>
      </summary>
      <div class="container">
        <p><a href="https://www.jitec.ipa.go.jp/">IPA公式サイト</a><br>
          基本情報技術者試験などを主催しているIPAの公式サイトです。<br>
          諸々の試験についての概要を確認したり、申し込みを行ったり出来ます。<br>
        </p>
        <p><a href="https://www.fe-siken.com/">基本情報技術者試験ドットコム</a><br>
          基本情報技術者試験の過去問がまとめられているサイトです。<br>
          参考書等で各分野の基礎事項を軽く頭に入れたあとは、ここでどんどん問題演習をこなすのが良いかと思います。<br>
        </p>
        <p><a href="https://online.osawa-lab.com/">OSAWA Lab</a>
          大澤先生が担当する講義の動画はこのサイトから配信されます。<br>
          他学年の講義も自由に見られる仕様になっているので、興味があれば覗いてみるのも良いでしょう。<br>
        </p>
      </div>
    </details>

    <details>
      <summary>
        レポート
        <span class="badge"><img src="images/report.png" alt="report" class="report"></span>
      </summary>
      <div class="container">
        <p><a href="https://plagiarism.strud.net/">剽窃チェッカー</a><br>
          入力された文章に対して、ウェブ上に同一の文字列がないかチェックするツールです。<br>
          偶然一致してしまうということもあり得ますし、せっかくの努力を無駄にしないためにもこれを使って確認しましょう。<br>
        </p>
        <p><a href="https://phonypianist.sakura.ne.jp/convenienttool/strcount.html">文字数カウント</a><br>
          テキストボックスに入力した文章の文字数をカウントしてくれるツールです。<br>
          リアルタイムでカウントしてくれる機能もついているので使い勝手がよく、字数制限のあるレポートなどの作成時に便利です。<br>
        </p>
        <p><a href="http://www.logicalskill.co.jp/jwriting.html">日本語ライティングの世界</a><br>
          主にライティングの技術についてまとめられているサイトです。<br>
          日本語ライティングだけでなく、英語ライティングやプレゼンテーションに関しても学ぶことが出来ます。<br>
        </p>
      </div>
    </details>

    <details>
      <summary>
        情報科学科
        <span class="badge"><img src="images/Internet.jpg" alt="infomation sciense" class="is"></span>
      </summary>
      <div class="container">
        <p>
          <a href="https://osawa-lab.com/">大澤研究室HP</a><br>
          大澤先生の研究室では、ドラえもんの開発はもちろんのこと、AI、ML(機械学習)をはじめとしたさまざまな分野を研究しています。<br>

        </p>

        <p>
          <a href="http://tozaki.is.chs.nihon-u.ac.jp/">尾崎研究室HP</a><br>
          尾崎先生の研究室では、「データマイニング手法の開発 & 応用領域の開拓」というテーマで研究を行っています。<br>
          データマイニングとは、大量のデータから、価値のある情報を発掘し、ビッグデータやデータサイエンス、機械学習、人口知能とも密接な関係にある分野です。<br>
        </p>

        <p>
          <a href="https://vdslab.jp/">尾上研究室HP</a><br>
          尾上先生の研究室では、情報可視化とデータサイエンスを中心に研究をしています。<br>

        </p>

        <p>
          <a href="http://www.is.chs.nihon-u.ac.jp/~kan/">韓研究室HP</a><br>

        </p>

        <p>
          <a href="http://www.kthrlab.jp/">北原研究室HP</a>
          <a href="http://www.kthrlab.jp/~kitahara/">個人HP</a><br>

        </p>

        <p>
          <a href="http://www.is.chs.nihon-u.ac.jp/~asaito/member/men_p.html">斎藤研究室HP</a><br>

        </p>

        <p>
          <a href="http://www.tani.cs.chs.nihon-u.ac.jp/g-thesis/">谷研究室HP</a><br>

        </p>

        <p>
          <a href="http://www.is.chs.nihon-u.ac.jp/~furuichi/">古市研究室HP</a><br>

        </p>

        <p>
          <a href="https://mytlab.org/">宮田研究室HP</a><br>

        </p>

        <p>
          <a href="http://www.is.chs.nihon-u.ac.jp/moriyama/">森山研究室HP</a><br>

        </p>

        <p>
          <a href="http://www.is.chs.nihon-u.ac.jp/">情報科学科公式HP</a><br>

        </p>

        <p>
          <a href="https://twitter.com/is_nuchs">情報科学科公式Twitter</a><br>

        </p>
      </div>

    </details>

  </div>
  <footer>チーム青い鳥</footer>
  <script src="main.js"></script>
</body>

</html>
