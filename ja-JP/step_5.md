## ステップ3： いろいろな答え方

入力によって、チャットボットがちがう答え方をするようにプログラムすることができます。

+ チャットボットが「元気？」と聞くと、入力が「はい」の時**だけ**「それはよかった！」と答えるようにできますか?
    
    新しいコードをきちんとテストするためには、**2回**テストします。答えが「はい」の時と、「いいえ」の時です。
    
    チャットボットは入力が「はい」の時は「それはよかった!」と答え、「いいえ」の時は何も言いません。
    
    ![チャットボットの答え](images/chatbot-if-test.png)

\--- hints \--- \--- hint \--- チャットボットが「やあ」と言うと、 「元気？」と**聞きます**。 チャットボットは答えが**「はい」**の時は、「それはよかった！」と**言います**。 \--- /hint \--- \--- hint \--- 新しく使うブロックはこちらです。 ![Blocks for a chatbot reply](images/chatbot-if-blocks.png) \--- /hint \--- \--- hint \--- コードの見本はこちらです。 ![Code for a chatbot reply](images/chatbot-if-code.png) \--- /hint \--- \--- /hints \---

+ 今の所、チャットボットは入力が「いいえ」の時は何も言ってくれません。答えが「いいえ」の時に、チャットボットが「それはこまったね・・・。」と言うようにできますか？
    
    テストして保存しましょう。 チャットボットは答えが「いいえ」の時は「それはこまったね・・・。」と言います。 「いいえ」だけでなく、入力が「はい」以外の時、チャットボットは「それはこまったね・・・。」と答えます。
    
    ![「はい」または「いいえ」と入力した時の答え](images/chatbot-if-else-test.png)

\--- hints \--- \--- hint \--- 入力が**「はい」**の時、チャットボットは「それはよかった！」と答えますが、 「はい」**以外**の時は「それはこまったね・・・。」と答えます。 \--- /hint \--- \--- hint \--- 使うブロックはこちらです。 ![Blocks for a yes/no reply](images/chatbot-if-else-blocks.png) \--- /hint \--- \--- hint \--- コードの見本はこちらです。 ![Code for a yes/no reply](images/chatbot-if-else-code.png) \--- /hint \--- \--- /hints \---

+ `もし…なら／でなければ`のブロックには、チャットボットの言葉だけではなく、いろいろなコードを入れることができます。 チャットボットの**コスチューム**を見てみると、いくつかあるのがわかると思います。
    
    ![チャットボットのコスチューム](images/chatbot-costume-view.png)

+ 答えに合わせてチャットボットのコスチュームをかえることができますか?？
    
    テストして保存しましょう。答えによってチャットボットの顔がかわります。
    
    ![コスチュームをかえる](images/chatbot-costume-test.png)

\--- hints \--- \--- hint \--- 答えによってチャットボットのが**コスチューム**がかわります。 \--- /hint \--- \--- hint \--- 使うブロックはこちらです。 ![Blocks for a changing costume](images/chatbot-costume-blocks.png) \--- /hint \--- \--- hint \--- コードの見本はこちらです。 ![Code for a changing costume](images/chatbot-costume-code.png) \--- /hint \--- \--- /hints \---

+ チャットボットのコスチュームが、最後に話しかけた時と同じままであることに気づきましたか？ 直せますか？
    
    ![コスチュームのバグ](images/chatbot-costume-bug-test.png)
    
    テストして保存しましょう。コードをテストして「いいえ」と入力すると、チャットボットは怒った顔になります。もう一度テストすると、名前を聞く前に、笑った顔に戻ります。
    
    ![コスチュームを直す](images/chatbot-costume-fix-test.png)

\--- hints \--- \--- hint \--- チャットボットが**クリックされた時**、**コスチューム** が笑った顔にかわります。 \--- /hint \--- \--- hint \--- 足すブロックはこちらです。 ![Blocks for a costume fix](images/chatbot-costume-fix-blocks.png) \--- /hint \--- \--- hint \--- コードの見本はこちらです。 ![Code for a costume fix](images/chatbot-costume-fix-code.png) \--- /hint \--- \--- /hints \---

\--- challenge \---

## チャレンジ：もっといろいろな答え

チャットボットが他のことも聞くようにプログラムしてみましょう。「はい」か「いいえ」で答えられるようにしましょう。あなたのチャットボットはきちんと答えられるでしょうか？

![スクリーンショット](images/chatbot-joke.png) \--- /challenge \---