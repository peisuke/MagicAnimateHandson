# MagicAnimateHandson

## データの準備

<img width="327" alt="image" src="https://github.com/peisuke/MagicAnimateHandson/assets/14243883/5f9a0f79-b79b-469c-a4e0-15cde70c1d40">

## DensePoseで姿勢推定
ここのソースコードをコピーして使うと良い。ちなみに、DumpActionをimportするとavが足りないと言われる。インストールしてあるのに。怒られてから、もっかいpip installすると動くみたい。

https://github.com/peisuke/MagicAnimateHandson/assets/14243883/1f7e8e31-ce81-4f6a-b822-875c9cacbb22

## MagicAnimateで動画の作成

上で作成した動画と画像を使って、動画を作成してみよう。configs/prompts/animation.yamlに、入力データを指定するところがあるので、先程の動画のファイル名と好きなキャラの画像ファイル名を入れて実行する。samplesだったかどっかのディレクトリに出力される。

https://github.com/peisuke/MagicAnimateHandson/assets/14243883/dedfc143-c8b2-4187-bb49-8802ec14d76b
