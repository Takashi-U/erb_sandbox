使用方法
========

    git clone https://github.com/Takashi-U/erb_sandbox.git
    cd erb_sandbox
    bundle install
    bundle exec guard

guardを利用して、保存される度に自動コンパイルを行います。
もう一つターミナルを立ち上げてerb_sandboxに移動し、次のコマンドを実行してください。

    bundle exec nanoc view

これでサーバーが立ち上がるので、localhost:3000をブラウザで見てください。
