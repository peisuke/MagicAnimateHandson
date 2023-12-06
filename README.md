# MagicAnimateHandson

## データの準備

<img width="327" alt="image" src="https://github.com/peisuke/MagicAnimateHandson/assets/14243883/5f9a0f79-b79b-469c-a4e0-15cde70c1d40">

## DensePoseで姿勢推定
01_pose_estimation_for_magic_animate.ipynbを上から順に実行する。ちなみに、DumpActionをimportするとavが足りないと言われる。インストールしてあるのに。怒られてから、もっかいpip installすると動くみたい。

<img width="487" alt="image" src="https://github.com/peisuke/MagicAnimateHandson/assets/14243883/98b55145-e499-4352-be8d-90a0bdfd5650">

## MagicAnimateで動画の作成

02_magic_animate_generate.ipynbを使い、上で作成した動画と画像を使って、動画を作成してみよう。configs/prompts/animation.yamlに、入力データを指定するところがあるので、先程の動画のファイル名と好きなキャラの画像ファイル名を入れて実行する。samplesだったかどっかのディレクトリに出力される。

https://github.com/peisuke/MagicAnimateHandson/assets/14243883/dedfc143-c8b2-4187-bb49-8802ec14d76b

## OpenPoseで姿勢推定

03_openpose_for_magic_animate.ipynbを上から順に実行する。OpenPoseのモデルは指定したGoogle Driveからダウンロードしてくることにする。

<img width="495" alt="image" src="https://github.com/peisuke/MagicAnimateHandson/assets/14243883/018679f7-0119-49b1-9693-6d63d4e2aa77">

## MagicAnimateで動画の作成

TBD
