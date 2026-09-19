百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
裁毖毖毖毙甭温掠信梅路路秤夏哑墩墩嫡哑哑
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

https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832?/609=495
https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832?/710=164
https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832?/373=342
https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832?/009=370
https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832?/321=528
https://github.com/danielfachka/zyfplc/commit/a7fbb11e2dc0ee56ba5d4bd71aafd5ff6befa832
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md?/932=110
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md?/498=225
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md?/338=610
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md?/821=269
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md?/603=945
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%99%BE%E7%A7%91.md
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666?/611=603
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666?/832=598
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666?/508=158
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666?/870=903
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666?/592=947
https://github.com/ryukaura/kityhe/commit/0db0d1534bc1b77cca207be1f7e2db8d9182e666
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md?/658=603
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md?/767=830
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md?/879=773
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md?/055=492
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md?/725=151
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE.md
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7?/964=932
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7?/221=653
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7?/354=053
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7?/663=832
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7?/325=954
https://github.com/sourux23/eufvji/commit/324fd22d1f4e8b55d2a6c3268f01151a3a12b6c7
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/561=276
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/241=664
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/056=492
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/231=043
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/425=821
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d?/932=508
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d?/443=609
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d?/609=484
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d?/003=531
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d?/265=965
https://github.com/constiang-s/xzjjce/commit/927c479f0c3edcac665cc42b93b2df23ca92726d
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md?/932=609
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md?/334=597
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md?/836=262
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md?/714=119
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md?/877=775
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E4%BA%AC%E4%B8%9C.md
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7?/271=487
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7?/381=509
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7?/423=821
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7?/662=508
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7?/998=376
https://github.com/e44nf/nkliyn/commit/e3fce001162aa42bdb84ceec2a115f3f881c9ad7
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/153=598
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/043=765
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/932=221
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/832=447
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md?/092=558
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238?/747=009
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238?/047=610
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238?/265=405
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238?/828=475
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238?/165=331
https://github.com/schowffer/nmghjj/commit/63eaed413dca8f7a7c88a0b651b598d2e82da238
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md?/270=714
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md?/881=375
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md?/040=442
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md?/729=369
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md?/343=114
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8.md
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2?/943=709
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2?/043=886
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2?/198=497
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2?/714=603
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2?/554=592
https://github.com/ptushub/nohkiu/commit/dad11b2a9e7e3f9fd2a764cfdc8bc6fc024d60d2
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md?/277=765
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md?/710=381
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md?/043=775
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md?/270=009
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md?/257=825
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%85%BE%E8%AE%AF.md
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2?/278=897
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2?/510=654
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2?/675=936
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2?/332=265
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2?/376=341
https://github.com/enognagu/lpvade/commit/b9d3092671eb4ce2125dd3dc83e60049a9f835b2
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/504=158
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/164=487
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/331=297
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/550=826
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md?/199=598
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E6%8A%95%E8%B5%84%E8%A7%86%E7%95%8C.md
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f?/992=225
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f?/386=803
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f?/497=276
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f?/154=114
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f?/510=831
https://github.com/mustakuritsar07/rkngzy/commit/fd208b2608121edde32ffafd6cfdef3ab8f1fc3f
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md?/770=786
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md?/843=370
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md?/481=720
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md?/043=776
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md?/414=110
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b?/992=854
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b?/821=162
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b?/740=992
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b?/064=187
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b?/110=447
https://github.com/danielfachka/zyfplc/commit/dfe3025d8423c288c9cf14b51f275d855fe4af6b
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/525=887
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/887=609
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/553=609
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/615=825
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/062=821
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0?/602=417
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0?/997=497
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0?/792=521
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0?/386=854
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0?/932=154
https://github.com/kulkaye/xiinuu/commit/a693e8b7f1a826f298b8bd8230e5b8d57b9d58e0
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md?/831=596
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md?/098=788
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md?/821=652
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md?/003=828
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md?/810=181
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8F%82%E8%80%83%E6%B6%88%E6%81%AF.md
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213?/470=043
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213?/505=386
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213?/191=016
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213?/047=119
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213?/276=475
https://github.com/ryukaura/kityhe/commit/97611f1d06b3847bfbb504e55c7b049099a4e213
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/558=509
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/043=503
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/892=049
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/521=910
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/329=492
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82?/154=053
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82?/386=998
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82?/399=725
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82?/487=447
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82?/824=054
https://github.com/sourux23/eufvji/commit/b11be04e2244d210a2db2a6fdd771444b34d5e82
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md?/598=710
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md?/943=832
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md?/832=881
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md?/770=047
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md?/214=497
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd?/668=497
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd?/043=883
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd?/099=054
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd?/743=599
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd?/714=261
https://github.com/constiang-s/xzjjce/commit/c4b3c7d209a4f7a1b26ae17d025313800349f3dd
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/310=229
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/225=710
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/619=831
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/375=632
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/983=947
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9?/236=602
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9?/836=942
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9?/225=040
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9?/162=041
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9?/774=225
https://github.com/enognagu/lpvade/commit/2779a94b5e9938ef8bf18c0eba1b372660deddc9
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md?/157=934
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md?/392=662
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md?/032=797
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md?/823=881
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md?/322=708
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA.md
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246?/543=652
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246?/376=265
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246?/508=043
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246?/710=825
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246?/609=712
https://github.com/ptushub/nohkiu/commit/ff8e6d35f736e8ea39efdb6ca44e47c9b81b7246
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md?/663=120
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md?/385=887
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md?/065=558
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md?/830=267
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md?/470=831
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%89%BE%E5%9B%9E%E5%AF%86%E7%A0%81.md
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0?/604=009
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0?/381=880
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0?/376=376
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0?/001=164
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0?/710=598
https://github.com/mustakuritsar07/rkngzy/commit/b0399fc14e5bf577cef6d4ea93aadaea1943b4b0
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/716=643
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/049=297
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/225=942
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/947=591
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md?/541=831
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E5%A4%A7%E7%A5%9E%E4%BA%91%E9%9B%86%E9%A2%84%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0?/154=487
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0?/992=003
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0?/276=710
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0?/619=160
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0?/009=220
https://github.com/schowffer/nmghjj/commit/c42d487abd0a5af4066d31941047e8cbe89e6ac0
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/710=497
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/618=165
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/320=825
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/158=053
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/470=823
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5?/942=487
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5?/507=830
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5?/002=830
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5?/825=721
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5?/831=934
https://github.com/e44nf/nkliyn/commit/c11996e1d65639a91c169ccb9dfeb26f3aeb0ef5
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/265=881
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/210=003
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/726=164
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/443=265
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/107=053
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4?/594=559
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4?/856=665
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4?/335=884
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4?/970=291
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4?/228=376
https://github.com/danielfachka/zyfplc/commit/287b1adc1f3030b4a7aa4ec2ee7e698a1d62ceb4
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md?/413=962
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md?/346=162
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md?/824=990
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md?/824=687
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md?/499=990
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E6%97%B6%E4%BB%A3%E7%BB%8F%E6%B5%8E.md
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76?/769=629
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76?/432=376
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76?/014=270
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76?/381=481
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76?/669=876
https://github.com/kulkaye/xiinuu/commit/628980f48879007d02b7a608e0a0c58bd4378a76
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/430=821
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/976=763
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/567=647
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/368=046
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/763=903
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9?/612=714
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9?/571=379
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9?/370=883
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9?/969=269
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9?/270=509
https://github.com/ryukaura/kityhe/commit/4192df32efe4c6f226cc655f838a8414e8da3cb9
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md?/264=609
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md?/942=421
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md?/265=932
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md?/497=569
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md?/047=164
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9?/898=554
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9?/598=098
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9?/776=798
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9?/043=432
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9?/354=821
https://github.com/sourux23/eufvji/commit/f6015cb2c352d7f1aa83a770fd2d7aa3991c6db9
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md?/365=954
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md?/345=939
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md?/553=236
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md?/886=821
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md?/192=009
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/enognagu/lpvade/commit/5d7741e580c542c3830c7ff85efcb3e14d0c1db8?/776=609
https://github.com/enognagu/lpvade/commit/5d7741e580c542c3830c7ff85efcb3e14d0c1db8?/932=710
https://github.com/enognagu/lpvade/commit/5d7741e580c542c3830c7ff85efcb3e14d0c1db8?/154=554
https://github.com/enognagu/lpvade/commit/5d7741e580c542c3830c7ff85efcb3e14d0c1db8?/686=497
