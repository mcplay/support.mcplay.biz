# はじめに
サバイバルサーバーの土地を「クレーム」することで、建築物を他プレイヤーから守ることができます。
クレームされた土地は、他プレイヤーによるブロック設置、破壊、動物の殺害、チェストを開くなどを拒否します。

土地をクレームするにはいくつかアイテムが必要です。木のスコップと棒です。これらのアイテムは自分で作ることができます。スコップはクレームの作成、修正に利用され、棒はクレーム情報を表示するために使用されます。

チュートリアル動画があります。こちらもご確認ください。

[How to Claim Land with the Grief Prevention Minecraft Server Plugin - YouTube](https://youtu.be/VDsjXB-BaE0)

# クレームの作成
自分が主張したい土地に他の人の主張が存在するかどうかを確認するには、木の棒を手に持ってブロックに向かって右クリックします。`シフト＋右クリック`すると、周辺のすべてのクレームが表示されます。

他の人の主張がないことを確認したら、手に持った木のシャベルを持ち、保護したい土地の対角線上で右クリックする必要があります。

# クレームのサイズ変更
木のシャベルを使えば、クレームのサイズを変更することができます。これはクレームを作成するのと似ています。

初めに木の棒でクレームの場所を確認します。このときクレームの境界線が表示されるので角が何処にあるかを確認します。

クレームのサイズを変更するときには、移動したい角を`右クリック`します。その後、新しい角を`右クリック`します。

# クレームの細分化
クレームを細分化することで、プレイヤーにクレームの一部のみへアクセス権を与えることができます。

細分化の考えは簡単です。メインのクレームの中に小さなクレームを作成し、その中で権限をプレイヤーに与えられるようにできます。細分化クレームが作成されると、プレイヤーに対し権限を与えられます。細分化クレーム内でtrustコマンドを使用する事でプレイヤーに権限を与えることができます。

細分化クレームを作成するには、細分化モードになる必要があります。このモードになるには、`/subdivideclaims`コマンドを使用します。このモードになると、クレームを作成するのと同じように、細分化クレームを作成できます。細分化クレームは白い境界線で表示されます。通常モードに戻るには、`/basicclaims`コマンドを使用してください。

# 許可
他プレイヤーに対してクレームの権限を様々なレベルに分けて与えることができます。サーバー上の全てのプレイヤーを信頼するには`<player>`を`all`に置き換えてください。
- クレームの全てをアクセスできるようにするには（破壊、設置、チェストアクセス、その他）: `/trust <player>`
- チェストへアクセスできるようにするには（建築はできない）: `/containertrust <player>`
- レバーやドアへアクセスできるようにするには（ドアを開く、ボタン押す、その他）: `/accessstrust <player>`
- クレームを管理できるようにするには（他プレイヤーをtrustできる）: `/permissiontrust <player>`

# コマンド
- `/unclaim` - 保護を削除する。
- `/claimslist` - 保護の一覧を表示する。
- `/containertrust <player>` - クレームの中でチェストへのアクセス権を与える。
- `/permissiontrust <player>` - クレームで他人を信頼、信頼しない権限を与える。
- `/accesstrust <player>` - クレームの中でドアやトラップドアを使用できるようにする。
- `/subdivide` - クレームの中に、サブクレームを作成する。
- `/restrictsubclaim` - サブクレームが親クレームの権限を継承しないように設定する。
- `/trust <player>` - クレームの中でチェストを設置、使用することを許可する。
- `/trustlist` - クレームで信用されている人を表示する。
- `/untrust <player>` - クレームの信用からプレイヤーを削除する。