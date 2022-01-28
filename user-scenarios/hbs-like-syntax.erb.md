---
title: HBS Like syntax
---

# This file contains HBS Like syntax and it should not be processed by HBS converter
```
=# SELECT gptext.analyzer('demo.wikipedia.articles', 'index', 'text_intl',
'Chopin takes a wayward sidestep into a delicious series of upward flying scales');
analyzer

----------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------
(WorldLexerTokenizer,"{{""Chopin""},

{""takes""},{""a""},{""wayward""},{""sidestep""},{""into""},{""a""},{""delicious""},{""series""},{""of""}
,{""upward""},{""flying""},{""scales""}}")
(CJKWidthFilter,"{{""Chopin""},{""takes""}
,

{""a""},{""wayward""},{""sidestep""},{""into""},{""a""}
,

{""delicious""},{""series""},{""of""},{""u pward""},{""flying""},{""scales""}}")
(LowerCaseFilter,"{{""chopin""},{""takes""},{""a""},{""wayward""},{""sidestep""},{""into""},{""a""},{""delicious""}
,

{""series""},{""of""},{"" upward""},{""flying""},{""scales""}}")
(WorldLexerBigramFilter,"{{""chopin""},{""takes""},{""a""},{""wayward""},{""sidestep""},{""into""},{""a""},{""delicious""},{""series""}
,

{""of ""}
,

{""upward""},{""flying""},{""scales""}}")
(StopFilter,"{{""chopin""},{""takes""},{},{""wayward""},{""sidestep""},{},{},{""delicious""},{""series""},{},{""upward""}
,

{""flying""}
,{""sca
les""}}")
(SetKeywordMarkerFilter,"{{""chopin""},

{""takes""},{},{""wayward""},{""sidestep""},{},{},{""delicious""},{""series""},{},{""upward""},{""flyi ng""},{""scales""}}")
(PorterStemFilter,"{{""chopin""},{""take""},{},{""wayward""},{""sidestep""},{},{},{""delici""},{""seri""},{},{""upward""},{""fly""},{""scale"
"}}")
(7 rows)
```


VS_DOTNET_REFERENCES "System;${ <%=vars.product_name%>Native_DOTNET_LIBRARY }")