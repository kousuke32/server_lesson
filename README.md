- ls(LiSt)
	- ディレクトリ内に存在するディレクトリやファイルを一覧表示するコマンド
	- オプション
		- -a は不可視ファイルも表示
		- -l はタイプや権限、所有者や所有グループなどの詳細情報を表示
		- /はルートを意味し、ディレクトリやファイルの根源のことをいう

- pwd(Print Working Directory)
	- 現在自分が位置しているディレクトリ（ワーキングディレクトリ）がどこであるかを出力する

-cd(Change Directory)
	- ワーキングディレクトリを指定したディレクトリに変更するコマンド
	- 指定方法
		- ~ ホームディレクトリ
		- / ルートディレクトリ
		- - 移動前に位置していたディレクトリ
		- . ワーキングディレクトリ
		- .. ワーキングディレクトリの一階層上のディレクトリ
		- ../../ ワーキングディレクトリの二階層上のディレクトリ

- mkdir(MaKe DIRectory)
	- ディレクトリを作成するコマンド

- touch
	- ファイルを作成するコマンド

- &&
	- AND演算子（左辺の実行が成功すれば、右辺を実行する）

- cp(CoPy)
	- cpはファイルあるいはディレクトリのコピーを行うコマンド(cp コピー元　コピー先)
	- オプション
		- -r でディレクトリの複製を行うことができる

-mv(MoVe)
	- ファイルやディレクトリの移動を行うコマンド（mv 変更元　変更先）

- rm(ReMove)
	- ファイルやディレクトリの削除を行うコマンド（rm　削除するファイル、ディレクトリ）

- ワイルドカード
	- * 0文字以上の任意の文字
	- ? 任意の一文字を表す記号

- cat(CATnate)
	- ファイルの内容をターミナル上に出力するコマンド

- >
	- 左辺の実行結果の出力を右辺で指定したファイルに書き込む記号

->>
	- 左辺の実行出力結果を右辺で指定したファイルの末尾に書き込む記号

- vi
	- ターミナル上で即時起動できるエディタ
	- ノーマルモード（escキー）
		- ノーマルモード時は編集を行うことができない
		- 移動や保存、検索や削除などの操作をキーで行うことができる
		- オプション
			- j 下に移動
			- k 上に移動
			- h 左に移動
			- l 右に移動
			- :w 保存
			- :wq 保存して終了
			- :q! 保存せずに強制終了
			- u 変更内容を一つもとに戻す
			- Ctrl + r 変更内容を一つ前にすすめる
	- インサートモード（i）
		- ファイル編集モード
		- 入力したキーがそのままファイルに反映される
