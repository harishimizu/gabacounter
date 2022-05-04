# これ is 何？　
  
同一IP・同一端末からの多重アクセスをもカウントする（ここ重要）、  
昔のウェブサイトによくあったアクセスカウンターです。  
  

# 使い方
  
counter.htmlとcounter.datを権限606だか604だかのディレクトリに放り込んでください。  
counter.datは権限606、counter.htmlは権限604にしてください。    
アクセスカウンターを表示したい文章位置に、  
  
<!-- アクセスカウンター -->  
<script type="type/javascript" src="./counter/counter.html"></sctipt>  
<!-- アクセスカウンター終わり -->  
  
以上のHTMLタグを記述すると、counter.datに記載された数字に対し、counter.htmlが呼び出される度にアクセス毎に+1した数字を表示します。  