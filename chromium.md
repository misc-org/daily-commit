唐突に `"cmd"+"shift"+"left"` が使えなくなった  
VScodeのせいかと思ったら `chrome` でも使えない...  
これは MacOS のせいか!?またかよ、まったく...  
でも、`テキストエディット` と `safari` はできる...  

この共通点は...`chromium`!!!  

`chrome` は当然 `chromium`。  
`VScode` は Electron なので chromium が内包されている。  

ってことは...`discord` も `slack` も...!?  
=> 大正解!  
原因は分かったが、どうすれば...?  

ちなみに Tauri で作った自作アプリを試してみると...  
使える!!  
やっぱり Tauri はレンダリングエンジンを内包していないんだな...  
(まあ、DevTool見れば明らかなんだけど)
