# 選挙候補者評価フレームワーク

`選挙候補者評価フレームワーク` は、各種LLMの **Research** や **Deep Research** モードを活用する前提で作成された、  
選挙候補者の評価を行うためのフレームワークです。このフレームワークは、選挙候補者の情報を収集し、評価するための一連の手順を提供します。

## 詳細な評価フレームワーク

[選挙候補者評価フレームワーク.md](./選挙候補者評価フレームワーク.md)  をプロンプト本文に含めてください。

## 使用方法

1. 上記の詳細フレームワークをプロンプトに含めます
2. 選挙名と行われる年、評価したい候補者名と所属する政党をプロンプトに含めます
3. LLMの**Research**モードまたは**Deep Research**モードを使用して、候補者の情報を収集します
4. フレームワークに従って、体系的に候補者を評価します

> [!warning]
> **Research**モードは非常に大量のトークンを消費します。
