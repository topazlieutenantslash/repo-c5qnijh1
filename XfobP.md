百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
墓嫡哑墩嫡忧坪肛陨啡纷尤尤旨羌腔官关羌肛
状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%80%E7%82%B9%E8%B5%84%E8%AE%AF.md?/569=743
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%80%E7%82%B9%E8%B5%84%E8%AE%AF.md?/652=047
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%80%E7%82%B9%E8%B5%84%E8%AE%AF.md?/541=692
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%80%E7%82%B9%E8%B5%84%E8%AE%AF.md
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8?/443=110
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8?/554=275
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8?/443=497
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8?/710=498
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8?/470=275
https://github.com/danielfachka/zyfplc/commit/449255b74a3ab6d860e8b22762f6f981cb07cbc8
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/053=265
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/453=047
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/887=453
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/609=710
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/436=885
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0?/498=498
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0?/125=913
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0?/110=615
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0?/610=832
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0?/886=043
https://github.com/schowffer/nmghjj/commit/360860eab896607dc0bc944ffaa5590f300dd4d0
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md?/718=163
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md?/231=825
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md?/831=432
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md?/990=609
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md?/038=716
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F.md
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c?/598=043
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c?/336=265
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c?/770=831
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c?/003=389
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c?/770=114
https://github.com/mustakuritsar07/rkngzy/commit/533f2e48f8b3fb9fb0a1b843587284ce9702e37c
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md?/154=336
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md?/154=598
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md?/998=775
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md?/598=487
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md?/870=386
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9?/720=884
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9?/483=591
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9?/076=609
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9?/006=110
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9?/376=022
https://github.com/ryukaura/kityhe/commit/502c197869001d4f7fab5058721f0466ae53fde9
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md?/710=900
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md?/087=564
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md?/935=376
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md?/265=225
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md?/971=663
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043?/609=498
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043?/932=373
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043?/164=480
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043?/710=935
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043?/803=508
https://github.com/sourux23/eufvji/commit/7464dfdad21b0827df3ff1bfea8bb46dd46ad043
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md?/602=008
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md?/055=821
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md?/293=834
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md?/447=053
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md?/092=878
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B5%84%E6%9C%AC%E5%89%8D%E6%B2%BF.md
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d?/370=492
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d?/558=003
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d?/819=481
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d?/870=276
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d?/381=884
https://github.com/e44nf/nkliyn/commit/66496accb7f9be6a53715e96d8f9e6b33418961d
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md?/836=009
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md?/598=570
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md?/714=712
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md?/697=218
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md?/975=413
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%83%E4%BA%BF%E7%90%83%E5%8F%8B%E4%BC%9A.md
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211?/009=886
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211?/497=672
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211?/271=665
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211?/043=357
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211?/508=669
https://github.com/constiang-s/xzjjce/commit/759d9ce4b3950ca4b12a1c032a9bdf7e76aa1211
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/908=261
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/239=268
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/019=659
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/269=053
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/426=336
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6?/832=998
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6?/334=108
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6?/975=598
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6?/220=421
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6?/526=965
https://github.com/ptushub/nohkiu/commit/c6f929fb86e5881c2c84338cd7d3b40560cca0c6
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/490=941
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/302=331
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/220=290
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/781=887
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/574=268
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b?/834=003
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b?/495=554
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b?/509=710
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b?/508=265
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b?/897=717
https://github.com/enognagu/lpvade/commit/b42813ac0df84b8ef475d553361ca8c8beb5292b
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md?/495=932
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md?/728=932
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md?/336=839
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md?/964=721
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md?/403=432
https://github.com/enognagu/lpvade/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%96%B0%E8%93%9D%E7%BD%91.md
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c?/932=775
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c?/221=609
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c?/669=932
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c?/261=770
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c?/619=386
https://github.com/danielfachka/zyfplc/commit/fad4415ceab86594e8618befc034bf5ec226c44c
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md?/943=608
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md?/712=497
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md?/854=332
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md?/609=542
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md?/618=669
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E6%8A%96%E9%9F%B3.md
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488?/043=995
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488?/376=298
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488?/165=826
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488?/943=505
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488?/265=991
https://github.com/kulkaye/xiinuu/commit/84576c4b3e34e13ed046078c4078be002a4d3488
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md?/119=056
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md?/776=373
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md?/882=591
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md?/154=339
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md?/218=789
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b?/169=006
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b?/443=221
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b?/669=159
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b?/824=098
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b?/265=009
https://github.com/schowffer/nmghjj/commit/491de8f39c66f42c819c1885a2d80d22e1a2a89b
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md?/887=111
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md?/664=786
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md?/710=554
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md?/884=417
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md?/325=710
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49?/908=443
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49?/601=553
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49?/254=887
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49?/345=221
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49?/776=897
https://github.com/mustakuritsar07/rkngzy/commit/796828b40b7e84c8a25ba817a967e4b69a5c4d49
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/825=554
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/564=008
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/326=006
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/908=710
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/709=055
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e?/932=654
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e?/159=764
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e?/609=225
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e?/265=597
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e?/925=710
https://github.com/ryukaura/kityhe/commit/873f958d1258efc038796a75453a09b941f8449e
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/508=642
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/858=154
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/614=169
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/461=379
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/319=225
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc?/167=376
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc?/221=966
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc?/009=776
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc?/154=498
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc?/710=603
https://github.com/sourux23/eufvji/commit/9bae053740c4811900e058dce3abc3dcf38a64fc
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/821=720
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/831=669
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/381=154
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/005=154
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/539=821
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb?/831=420
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb?/556=484
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb?/389=501
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb?/389=113
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb?/119=308
https://github.com/e44nf/nkliyn/commit/763a28a912044eed809f1d8232a86ef0638db1fb
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md?/553=099
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md?/663=487
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md?/009=110
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md?/312=021
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md?/531=330
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4?/154=875
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4?/487=458
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4?/665=008
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4?/888=275
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4?/754=832
https://github.com/constiang-s/xzjjce/commit/c03fcacd4bb902cc75a7e9770c35bc35a9038fb4
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md?/332=509
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md?/943=521
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md?/932=710
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md?/998=501
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md?/047=110
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%A4%A9%E8%B5%9A50.md
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c?/059=991
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c?/443=261
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c?/890=723
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c?/132=989
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c?/154=043
https://github.com/enognagu/lpvade/commit/fb4d1110d0e977309840222421ba36ec9d81244c
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/090=243
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/167=770
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/897=778
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/335=379
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/544=314
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9?/008=378
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9?/540=821
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9?/821=942
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9?/332=710
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9?/611=508
https://github.com/danielfachka/zyfplc/commit/ae41159900dfeaaf18a2f66405a66344984b6aa9
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/127=447
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/336=487
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/897=881
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/271=827
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/541=947
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659?/162=565
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659?/047=046
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659?/554=269
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659?/987=832
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659?/714=271
https://github.com/ptushub/nohkiu/commit/15c1052112e19f27cf52858dbd9414d5b4d1c659
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md?/710=275
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md?/221=998
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md?/415=857
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md?/332=339
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md?/758=748
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%99%BE%E5%BA%A6.md
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b?/509=054
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b?/056=551
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b?/609=043
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b?/487=934
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b?/932=449
https://github.com/kulkaye/xiinuu/commit/ae7dbfe7aa33f0cd706d28ab596016d54ea4778b
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/609=581
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/865=142
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/487=881
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/487=236
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/528=236
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae?/721=942
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae?/661=009
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae?/937=565
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae?/997=110
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae?/595=047
https://github.com/schowffer/nmghjj/commit/3c3514b14d660f020ef89f0ecb2d0e0ce4c566ae
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/831=055
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/421=998
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/840=553
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/575=965
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/214=554
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2?/097=386
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2?/665=154
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2?/374=370
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2?/231=661
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2?/665=008
https://github.com/mustakuritsar07/rkngzy/commit/a861fa356230330339fbad7e3439aedba558b8b2
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md?/403=154
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md?/332=485
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md?/051=054
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md?/443=936
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md?/834=376
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F.md
