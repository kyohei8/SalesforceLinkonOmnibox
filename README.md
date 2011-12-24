## Salesforce Link on Chrome Omnibox (Chrome Extensions) ##

表示しているSalesforce組織のリンクをOmniboxから指定、遷移することができます。<br />
IDの入力も可能です<br />
<br />
sf [キーワード,ID]　→　通用のSalesforceのLinkを検索、IDの場合はそのレコードの詳細ページおよび編集ページ<br />
sf apex:[キーワード]　→　ApexのReferenceを検索し、ページの候補を表示<br />
sf vf:[キーワード]　→　VisualforceのReferenceを検索し、ページの候補を表示<br />
sf api:[キーワード]　→　APIのReferenceを検索し、ページの候補を表示<br />
sf meta:[キーワード]　→　MetadataのReferenceを検索し、ページの候補を表示<br />

<br />
インストール方法
-----------
* 以下のリンクをGoogle Chromeで開き"続行"を選択します

https://github.com/downloads/kyohei8/SalesforceLinkonOmnibox/SalesforceLinkonOmnibox_v1_1.crx

Reference
-----------
Wiki参照
https://github.com/kyohei8/SalesforceLinkonOmnibox/wiki/Reference

<br />
更新履歴
----------
v1.1 <span style="color:#DDD"> #2011/12/25</span><br />
・Referenceの検索に対応
v1 <span style="color:#DDD"> #2011/12/19</span><br />
・公開<br />


<br />
注意事項
----------
Referenceの検索に<a href="http://code.google.com/intl/ja/apis/websearch/docs/" target="_blank">Google検索API(しかも古い方)</a>を使用しているのでリクエストの数に制限があります <br/>
