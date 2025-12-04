# NFT スマートコントラクト デモ

## 概要
イーサリアムのスマートコントラクトを使用したNFT発行・移転のデモンストレーションです。

## デモサイト
🌐 **[https://[your-username].github.io/nft-demo/](https://[your-username].github.io/nft-demo/)**

## 使用技術
- **ブロックチェーン**: Ethereum Sepolia Testnet
- **スマートコントラクト**: Solidity (OpenZeppelin ERC721)
- **フロントエンド**: HTML5 + JavaScript (ethers.js)
- **ウォレット**: MetaMask / WalletConnect

## セットアップ手順

### 1. スマートコントラクトのデプロイ
1. [Remix IDE](https://remix.ethereum.org/) を開く
2. `contracts/SimpleNFT.sol` をコピー
3. Sepoliaテストネットにデプロイ
4. コントラクトアドレスをメモ

### 2. デモサイトの利用
1. 上記URLにアクセス
2. MetaMaskでSepoliaネットワークに接続
3. コントラクトアドレスを入力
4. NFT発行・移転を実行

## 必要なもの
- Sepoliaテストネット用ETH ([Faucet](https://sepoliafaucet.com/))
- MetaMaskウォレット
- 画像ファイル（NFT化するコンテンツ）

## デモ内容
- **仕様1**: 画像ファイルをNFTとして発行
- **仕様2**: NFTの所有権を他のアドレスに移転

## 注意事項
- テストネット環境での実証実験です
- ガス代（手数料）が必要です（テスト用ETH）
- 実際の本番環境では画像をIPFS等に保存します
