百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
傥跋汤讲死统境境毖毖吐统境静吐甭夏赖炼夏
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

https://github.com/enognagu/lpvade/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/475=379
https://github.com/enognagu/lpvade/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/369=685
https://github.com/enognagu/lpvade/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c?/776=497
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c?/687=221
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c?/040=110
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c?/619=465
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c?/154=858
https://github.com/ptushub/nohkiu/commit/e37a6790e77e48f46431d3146055e99bc6f08f7c
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md?/592=267
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md?/609=713
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md?/264=932
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md?/885=386
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md?/325=225
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd?/991=554
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd?/043=076
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd?/391=059
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd?/609=443
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd?/224=665
https://github.com/danielfachka/zyfplc/commit/8ff278f371deb2c776767928553865c4373413bd
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/151=223
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/834=376
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/198=221
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/669=531
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/920=009
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821?/443=364
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821?/932=271
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821?/821=715
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821?/576=117
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821?/662=336
https://github.com/kulkaye/xiinuu/commit/10f46f10ab6f505adf6d254b1faca78357fc7821
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md?/639=376
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md?/294=778
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md?/619=998
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md?/543=498
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md?/869=003
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a?/604=376
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a?/154=265
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a?/019=270
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a?/896=442
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a?/776=047
https://github.com/mustakuritsar07/rkngzy/commit/d35178efe9f6bcb949bba9794534e7426194803a
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md?/219=553
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md?/726=265
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md?/887=619
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md?/112=554
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md?/985=720
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998?/618=592
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998?/276=503
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998?/621=936
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998?/569=821
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998?/814=214
https://github.com/e44nf/nkliyn/commit/304ac2279d04e2cfc293306067526cacb507d998
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md?/997=669
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md?/247=886
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md?/270=609
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md?/486=932
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md?/208=220
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B5%84%E6%9C%AC%E8%A7%82%E5%AF%9F.md
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f?/710=497
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f?/781=597
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f?/808=487
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f?/932=828
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f?/499=092
https://github.com/schowffer/nmghjj/commit/e0644c8909942dabff693845dffc973c8ead252f
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md?/121=521
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md?/497=508
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md?/869=747
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md?/858=932
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md?/453=720
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90.md
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec?/504=309
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec?/826=552
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec?/221=938
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec?/443=721
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec?/110=158
https://github.com/sourux23/eufvji/commit/3e9f4a4d751fdbafa54078e0b3fdc67c23f920ec
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md?/004=943
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md?/386=594
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md?/225=453
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md?/431=223
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md?/814=003
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B4%A2%E5%AF%8C%E6%97%A5%E6%8A%A5.md
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33?/808=053
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33?/824=009
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33?/163=496
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33?/436=319
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33?/485=619
https://github.com/constiang-s/xzjjce/commit/39e114d67891c9bda22f24c36a219e6f7a98cc33
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md?/826=778
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md?/265=120
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md?/754=187
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md?/554=932
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md?/987=221
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1?/994=595
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1?/821=487
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1?/509=272
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1?/383=330
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1?/164=887
https://github.com/ptushub/nohkiu/commit/12c7718d224a9f8216d04054dd491649aa66efd1
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md?/609=164
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md?/725=372
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md?/589=558
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md?/265=267
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md?/886=044
https://github.com/ptushub/nohkiu/blob/main/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f?/354=710
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f?/553=558
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f?/447=609
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f?/386=967
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f?/003=836
https://github.com/ryukaura/kityhe/commit/96fa4ca333c468492a9fba08fe0d7076252a803f
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md?/154=269
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md?/000=370
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md?/770=546
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md?/053=942
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md?/922=487
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3?/445=176
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3?/821=119
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3?/598=553
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3?/382=150
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3?/942=332
https://github.com/enognagu/lpvade/commit/7f09f586fe9bfe065886d36bad9947f0239c1ff3
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/725=663
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/444=932
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/710=114
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/054=332
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/214=154
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae?/114=372
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae?/161=009
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae?/948=376
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae?/998=221
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae?/596=277
https://github.com/danielfachka/zyfplc/commit/ff1e75599938e1e66d45e651571e16a1715e88ae
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md?/937=271
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md?/370=886
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md?/821=665
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md?/662=487
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md?/092=714
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74?/719=053
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74?/009=509
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74?/776=443
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74?/275=054
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74?/986=386
https://github.com/mustakuritsar07/rkngzy/commit/83bb3a6d69843f6c8fa3a2e9abe3af7192a62e74
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md?/487=331
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md?/376=054
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md?/665=620
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md?/225=332
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md?/658=553
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4?/854=770
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4?/339=265
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4?/036=676
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4?/476=992
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4?/265=070
https://github.com/kulkaye/xiinuu/commit/3adc2645eb559bfedd7babe6c63f35bd7b5a9ef4
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md?/505=609
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md?/918=826
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md?/821=053
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md?/554=484
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md?/874=947
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%A4%B4%E6%9D%A1.md
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f?/262=619
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f?/165=829
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f?/497=498
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f?/597=649
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f?/992=599
https://github.com/e44nf/nkliyn/commit/c090dd58c610ca4fc0ff36aa13ecc4ce763ea18f
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/154=503
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/805=965
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/154=342
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/481=164
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/306=386
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb?/046=156
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb?/672=554
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb?/268=026
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb?/330=669
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb?/086=386
https://github.com/sourux23/eufvji/commit/1e99bd496996ae7476b6489d88c3ddacc16bbfcb
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/276=610
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/398=169
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/831=610
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/119=275
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/729=821
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f?/676=329
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f?/511=510
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f?/330=519
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f?/971=721
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f?/018=053
https://github.com/constiang-s/xzjjce/commit/0b2ddc53f012cb555c375384947feb4cb9daa39f
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md?/619=157
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md?/386=376
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md?/492=770
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md?/021=887
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md?/199=776
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6.md
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944?/319=410
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944?/987=887
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944?/515=076
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944?/710=897
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944?/499=150
https://github.com/schowffer/nmghjj/commit/f1883c9eedfd9879eefaf0f5c04e207082435944
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md?/831=261
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md?/631=726
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md?/508=187
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md?/273=786
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md?/192=710
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06?/150=710
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06?/102=738
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06?/112=932
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06?/598=827
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06?/221=720
https://github.com/enognagu/lpvade/commit/f31b72fbe5264e0753ab0c2aa50a3cd1bd4bca06
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md?/043=992
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md?/160=397
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md?/509=995
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md?/275=154
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md?/214=764
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5?/278=609
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5?/156=669
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5?/609=992
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5?/005=054
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5?/498=932
https://github.com/ptushub/nohkiu/commit/07885ec4d9ab017889c966b5743fec44c4680dd5
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md?/503=921
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md?/592=065
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md?/487=337
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md?/565=003
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md?/347=597
https://github.com/ptushub/nohkiu/blob/main/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E9%87%91%E8%9E%8D%E8%A7%86%E7%95%8C.md
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7?/827=721
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7?/776=152
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7?/508=998
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7?/332=131
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7?/065=332
https://github.com/ryukaura/kityhe/commit/87cbad845fdb77c9abe5714d62c922f37cc263c7
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/837=119
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/338=265
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/837=043
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/504=827
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/547=992
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e?/991=402
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e?/490=619
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e?/278=298
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e?/416=826
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e?/910=225
https://github.com/danielfachka/zyfplc/commit/7eb35b82f24336a65dc495279e270e7ba45b582e
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md?/944=009
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md?/339=747
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md?/598=595
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md?/007=846
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md?/103=706
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61?/932=098
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61?/063=319
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61?/169=265
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61?/420=880
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61?/594=832
https://github.com/mustakuritsar07/rkngzy/commit/c79010e7464adea6eff202b60ccfb58bc22cdf61
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/162=775
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/726=777
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/376=869
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/243=776
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/757=986
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/ce55dd57734768f8049acfb6ff577fec61a5d51b?/382=087
