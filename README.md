[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/petehunt/langchain-github-bot)

## Getting started

```bash
$ pip install -r requirements.txt
$ export OPENAI_API_KEY=sk-...

# インデックスの作成
$ python3 -c'from langchain_bot import source_docs; from langchain_bot import search_index; search_index(source_docs())'

# 質問の投げ方
$ python3 -c'from langchain_bot import print_answer; print_answer("暗黙のanyをコンパイルエラーにする方法を 教えて")'
 TypeScript にて `noImplicitAny: true` を設定することで、TypeScriptが型をany型と推測した場合にエラーが発生するようになります。
SOURCES: https://github.com/yytypescript/book/blob/3662ce0e69026cba3c2fc12587a261ddee1fa2fa/docs/reference/values-types-variables/any.md, https://github.com/yytypescript/book/blob/3662ce0e69026cba3c2fc12587a261ddee1fa2fa/docs/reference/tsconfig/noimplicitany.md

$ dagit -f langchain_bot.py
```
