百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
及删示示痪士吐毙靶塘靶吐吐心心丛丛从酶酶
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

https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20925969.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20213419.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20421813.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20585243.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20070297.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20658186.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20432520.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20325415.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20366302.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20092569.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20147419.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20243419.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20541308.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20851923.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20287707.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20141564.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20030892.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20486921.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20870525.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20830292.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20396107.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20275802.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20347969.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20198961.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20925245.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20512914.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20696418.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20253185.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20983636.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20492858.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20420292.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20816589.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20430852.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20485647.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20043709.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20092029.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20692070.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20197904.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20463974.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20947486.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20308569.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20836708.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20819241.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20729818.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20581963.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20581207.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20587468.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20036796.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20592087.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20445870.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20409814.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20554764.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20679588.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20809647.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20313625.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20558753.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20247025.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20114325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20760369.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20008658.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20208170.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20981254.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20410202.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20554766.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20625095.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20920257.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20232894.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20110321.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20320251.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20692473.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20424347.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20661421.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20990247.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20432589.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20093927.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20014213.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20754095.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20703984.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20191439.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20338147.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20937069.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20692169.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20508325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20447654.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20531766.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20781803.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20982547.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20110325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20329285.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20803984.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20202732.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20908636.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20036254.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20192541.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20212862.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20943647.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20363581.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20669769.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20258570.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20717096.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20150876.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20104703.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20631879.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20521751.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20709181.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20721475.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20721245.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20987074.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20850296.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20720925.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20369029.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20447036.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20965685.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20540369.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20845207.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20536364.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20870363.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20043258.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20164769.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20643164.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20262698.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20275827.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20601090.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20660381.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20603254.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20760325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20481036.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20754325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20440958.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20598708.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20261090.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20546473.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20872558.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20559474.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20814365.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20483629.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20095869.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20209547.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20053698.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20536936.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20327081.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20938147.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20869253.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20829584.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20430364.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20954369.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20542543.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20374706.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20749258.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20758058.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20032547.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20876458.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20275870.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20976921.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20043870.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20716969.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20386581.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20204736.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20215769.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20163292.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20976925.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20864703.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20270386.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20159470.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20376141.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20716648.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20165825.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20379978.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20543008.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20226925.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20548759.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20158690.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20659213.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20307083.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20036925.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20321693.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20983036.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20760365.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20670325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20750392.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20876970.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20602036.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20108725.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20647364.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20582576.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20504039.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20326981.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20227381.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20609205.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20609203.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20981036.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20649698.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20042581.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20559281.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20653256.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20865814.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20218103.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20096903.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20054147.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20521950.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20493692.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20389854.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20998603.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20008470.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20209810.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20005887.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20327038.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20520847.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20143647.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20058658.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20092903.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20546453.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20231325.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20610847.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20659258.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20058770.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20097814.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20483925.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20365870.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20618864.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20316920.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20389843.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20654269.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20605085.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20098654.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20271429.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20750319.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20521425.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20763252.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20376521.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20659364.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20609254.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20219436.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20092187.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20316936.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20503658.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20043097.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20929205.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20250361.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20820392.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20875470.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20469825.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20296415.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20795146.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20925741.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20048769.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20543085.md
https://gitlab.com/carlclarkcsy1e/jdallxh/-/blob/main/20242876.md
