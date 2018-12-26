{"meta":"<h2 id=\"api\">API<a href=\"#api\" class=\"anchor\">#</a></h2>","api":"<h3 id=\"virtuallist\">VirtualList<a href=\"#virtuallist\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>&#x53C2;&#x6570;</th>\n<th>&#x8BF4;&#x660E;</th>\n<th>&#x7C7B;&#x578B;</th>\n<th>&#x9ED8;&#x8BA4;&#x503C;</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>children</td>\n<td>&#x6E32;&#x67D3;&#x7684;&#x5B50;&#x8282;&#x70B9;</td>\n<td>any</td>\n<td>-</td>\n</tr>\n<tr>\n<td>minSize</td>\n<td>&#x6700;&#x5C0F;&#x52A0;&#x8F7D;&#x6570;&#x91CF;</td>\n<td>Number</td>\n<td>1</td>\n</tr>\n<tr>\n<td>pageSize</td>\n<td>&#x4E00;&#x5C4F;&#x6570;&#x91CF;</td>\n<td>Number</td>\n<td>10</td>\n</tr>\n<tr>\n<td>itemsRenderer</td>\n<td>&#x7236;&#x6E32;&#x67D3;&#x51FD;&#x6570;&#xFF0C;&#x9ED8;&#x8BA4;&#x4E3A; (items, ref) =&gt; <ul ref=\"{ref}\">{items}</ul><br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function() =&gt; void</td>\n<td>Function</td>\n<td>(items, ref) =&gt; &lt;ul ref={ref}&gt;{items}&lt;/ul&gt;</td>\n</tr>\n<tr>\n<td>threshold</td>\n<td>&#x7F13;&#x51B2;&#x533A;&#x9AD8;&#x5EA6;</td>\n<td>Number</td>\n<td>100</td>\n</tr>\n<tr>\n<td>itemSizeGetter</td>\n<td>&#x83B7;&#x53D6;item&#x9AD8;&#x5EA6;&#x7684;&#x51FD;&#x6570;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function() =&gt; void</td>\n<td>Function</td>\n<td>-</td>\n</tr>\n<tr>\n<td>jumpIndex</td>\n<td>&#x8BBE;&#x7F6E;&#x8DF3;&#x8F6C;&#x4F4D;&#x7F6E;&#xFF0C;&#x9700;&#x8981;&#x8BBE;&#x7F6E; itemSizeGetter &#x624D;&#x80FD;&#x751F;&#x6548;, &#x4E0D;&#x8BBE;&#x7F6E;&#x8BA4;&#x4E3A;&#x5143;&#x7D20;&#x7B49;&#x9AD8;&#x5E76;&#x53D6;&#x7B2C;&#x4E00;&#x4E2A;&#x5143;&#x7D20;&#x9AD8;&#x5EA6;&#x4F5C;&#x4E3A;&#x9ED8;&#x8BA4;&#x9AD8;</td>\n<td>Number</td>\n<td>0</td>\n</tr>\n</tbody>\n</table>\n"}