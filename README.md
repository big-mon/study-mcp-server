# Model Context Protocol Server

Model Context Protocol (MCP) サーバーの実装プロジェクトです。

## 概要

このプロジェクトは [Model Context Protocol](https://modelcontextprotocol.io/) のクイックスタートチュートリアルを実装したものです。

本リポジトリは[Windows 環境で Model Context Protocol (MCP) サーバーを立ち上げるチュートリアルをやった](https://zenn.dev/bigmon/articles/451afc685e856a)にて経緯を説明しています。

## 機能

- MCP サーバーの基本的な実装
- モデルコンテキストの管理

## セットアップ

1. 依存関係をインストール:

   ```bash
   npm install
   ```

2. プロジェクトをビルド:

   ```bash
   npm run build
   ```

3. サーバーを起動:
   ```bash
   node build/index.js
   ```

## 依存関係

- @modelcontextprotocol/sdk
- zod

## ライセンス

ISC
