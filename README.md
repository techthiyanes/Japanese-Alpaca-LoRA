<img src="https://github.com/kunishou/Japanese-Alpaca-LoRA/blob/main/image/top.png" alt="alpaca">
  
# 🦙🌲🤏🌸 Japanese-Alpaca-LoRA 🌸
日本語に翻訳したStanford Alpacaのデータセットを用いてLLaMAをファインチューニングし作成したLow-Rank AdapterのリンクとGenerateサンプルコード

### Japanese-Alpaca-LoRA-7b DEMOページ (期間限定公開)  
※ パワーの弱いGPUをレンタルしているためアクセスが集中すると動作が遅くなる可能性があります（以下のColabでも実行可能です）

https://huggingface.co/spaces/kunishou/Japanese-Alpaca-LoRA-7b-DEMO

Instruct : 指示を入力  
Input : 付属情報を入力  
Temparature : 生成する回答の多様性度合い    
Beams : 生成する回答の候補数  
Max_tokens : 生成する回答の長さ  

入力例：  
instruct : 次の文章を要約して下さい。  
input : ディープラーニングまたは深層学習とは、対象の全体像から細部までの各々の粒度の概念を階層構造として関連させて学習する手法のことである。コーセラの共同創業者であるアンドリュー・ンによれば、「人工知能への第一歩」という認識は正しいのだという。

### Try the pretrained model using google colab
Google Colabで実行したい場合は以下より（30Bなどの大きいモデルはProプラン以上でA100を使わないと動かないかも）

※ 30BモデルはMax_tokensを128にしないとエラーが出ることがあります。  
※ 13BモデルがUI上で指示を出すとエラーが出ます（現在、原因を確認中）。  

<a href="https://colab.research.google.com/github/kunishou/Japanese-Alpaca-LoRA/blob/main/generate_colab.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### LoRA on Hugging Face
Japanese-Alpaca-LoRA 7b, 13B, 30B, 65B
https://huggingface.co/kunishou

### 参考
Stanford Alpaca  
https://github.com/tatsu-lab/stanford_alpaca  
Alpaca-LoRA  
https://github.com/tloen/alpaca-lora  
