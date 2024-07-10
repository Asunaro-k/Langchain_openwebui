# Langchain_openwebuiapi

## Table of Contents

- [はじめに](#はじめに)
- [インストール](#インストール)
- [使い方](#使い方)
- [参考サイト](#参考サイト)

## はじめに

Langchainを触ってみたかったが、Openaiのapikeyにお金を出すのが嫌でopenwebuiのapiを使ってやれないかと思い作成。ゼミのレクチャー用。このリポジトリには、LangChain を使って Formosa Foundation API と統合したカスタム言語モデルがあります。このモデルは、Formosa Foundationの言語モデルの機能を活用することで、与えられたプロンプトに基づいてテキストを生成することができます。これを使用することでlangchainでいろいろやりやすくなる。apiを使用せずローカルLLMの場合はfrom langchain_community.llms import Ollamaでサポートされているのでそちらを使用してください。


## インストール

1. **Clone the repository**

    ```bash
    git clone https://github.com/Asunaro-k/Langchain_openwebui.git
    cd Langchain_openwebui
    ```

2. **Create a conda**

    ```bash
    conda create -n Langchain python==3.12
    conda activate Langchain
    ```

3. **Install dependencies**

    ipynb内に記載。後々requirements.txt作るから許して

## 使い方

1. **Set up your api**

    openwebuiの設定→アカウントからAPIを発行
   APIとopenwebuiのurlをコードに追加

3. **Run the script**

    ipynbをそのまま実行で行けます。情報として追加するURLは好きなサイトを追加してください。



## 参考サイト
    https://hackmd.io/@BrookWu/HkQ96FPBn 
    https://qiita.com/t_kamiya78/items/659d156c4a88e6a37de9
