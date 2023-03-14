# TheEconomist
储存经济学人中英文对照的文章
文章的翻译都是通过彩云小译实现的, 就是复制粘贴复制粘贴,
首先翻译中国相关的文章, 然后有时间再翻译其他的文章, 每一期一个文件夹

杂志原文来源:https://github.com/hehonghui/awesome-english-ebooks 

在目录下以bilingual结尾的是翻译好的中英文双语对照版书籍，如TheEconomist_bilingual.epub
整本的翻译使用的工具是一个chatgpt api工具 https://github.com/yihong0618/bilingual_book_maker

命令： python3 make_book.py --book_name test_books/TheEconomist.2023.02.11.epub  --no_limit --language "Simplified Chinese"

TheEconomist.2023.02.18.epub是使用[chatgpt api工具](https://github.com/yihong0618/bilingual_book_maker)的彩云小译api接口翻译的, 使用彩云小译接口速度快很多,几分钟翻译一本书

命令:python3 make_book.py --book_name test_books/TheEconomist.2023.02.18.epub  --model caiyun

