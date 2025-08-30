# Minecraft1.21.9更新

'''1.21.9'''是'''[[铜器时代]]'''的正式版，也是{{el|je}}即将到来的一次次要更新，发布时间待定，加入了[[铜箱子]]、[[铜傀儡]]、[[铜傀儡像]]、[[铜粒]]、{{pa|Shelf|}}以及铜[[盔甲]]和铜质[[工具]]，并修复了一些漏洞。<ref>{{snap|25w31a|Jul 29, 2025}}</ref>

== 新内容 ==
=== 方块 ===
; [[铜箱子]]
* [[箱子]]的铜质变种，有斑驳、锈蚀、氧化以及对应的涂蜡变种。
* 可由8个[[铜锭]]和1个箱子合成。
* 能够氧化，也可以被涂蜡、除蜡或除锈。

; [[铜傀儡像]]
* 新的装饰性方块，有斑驳、锈蚀、氧化以及对应的涂蜡变种。
* 对未涂蜡且未氧化的铜傀儡像使用[[斧]]会生成[[铜傀儡]]。
* 能够[[氧化]]，也可以被涂蜡、除蜡或除锈。
* 与其交互可改变其姿势。
* 与[[红石比较器]]连接时会根据当前姿势发出红石信号。
* 被[[活塞]]推动时会被破坏并掉落对应物品。

; [[避雷针]]
* 加入了斑驳、锈蚀、氧化以及对应的涂蜡变种，以与铜傀儡头顶的避雷针保持一致。
  ** 现在避雷针能够氧化，也可以被涂蜡、除蜡或除锈。

; [[铜火把]]
* [[火把]]的铜质变种。
* 由[[铜粒]]、[[煤炭]]和[[木棍]]合成。

; [[铜栏杆]]
* [[铁栏杆]]的铜质变种。
* 由6个[[铜锭]]合成。
* 能够氧化、被涂蜡、除蜡或除锈。

; [[铜链]]
* {{pa|Iron Chain}}的铜质变种。
* 由2个铜粒和1个铜锭合成。
* 能够氧化、被涂蜡、除蜡或除锈。

; [[铜灯笼]]
* [[灯笼]]的铜质变种。
* 由8个铜粒和1个铜火把合成。
* 能够氧化、被涂蜡、除蜡或除锈。
  ** 氧化程度仅会改变外观，不会影响发光。

; {{pa|Shelf|}}
* 新的装饰性方块，有12种木质变种。
* 可用6个相同的[[去皮原木]]、[[去皮菌柄]]或[[去皮竹块]]合成6个，合成时需要将3×3合成方格的顶行和底行填满。
* 正面有3个槽位，可存放最多3组物品。
  ** 与任意槽位交互时，玩家的主手物品会与所交互槽位的物品交换。
  ** 类似于[[物品展示框]]，{{pa|Shelf}}会在正面展示其包含的所有物品。
* 被红石信号充能时，{{pa|Shelf}}的正面纹理会随之改变；充能的同种{{pa|Shelf}}可以相连接，最多可以连接3个。
  ** 与单个{{pa|Shelf}}交互时，其包含的所有物品会与玩家快捷栏最右侧的3个物品交换。
  ** 与两个相连接的{{pa|Shelf}}交互时，其包含的所有物品会与玩家快捷栏最右侧的6个物品交换。
  ** 与三个相连接的{{pa|Shelf}}交互时，其包含的所有物品会与玩家快捷栏的所有物品交换。
* 与其相接的[[红石比较器]]会按照槽位中是否有物品输出红石信号。
  ** 类似于二进制，槽位内无物品视为0，而有物品视为1。个位数在最左侧的槽位，即信号等级=左+中&times;2+右&times;4，范围为{{range|000<sub>(2)</sub>|111<sub>(2)</sub>}}，即{{range|0|7}}。
  ** 与是否被红石信号充能无关。
* 加入了<code>align_items_to_bottom</code>方块状态，控制{{pa|Shelf}}中物品是否向底部对齐，默认为<code>false</code>。
  ** 为<code>false</code>时，物品会忽略<code>on_shelf</code>物品渲染变换的竖直平移而纵向居中。
  ** 为<code>true</code>时，物品会根据<code>on_shelf</code>物品渲染变换的从{{pa|Shelf}}底部向上的竖直平移渲染。

=== 物品 ===
; [[盔甲]]
* 加入了铜盔甲，即[[头盔]]、[[胸甲]]、[[护腿]]和[[靴子]]的铜质变种。
  ** 可由[[铜锭]]合成。
  ** 提供的[[护甲值]]高于皮革盔甲，但略低于金盔甲。
  ** [[耐久度]]高于皮革盔甲，但低于锁链盔甲和铁盔甲。
  ** [[附魔能力]]为8，低于铁盔甲。

; [[马铠]]
* 加入了铜马铠。
  ** 提供{{Armor|4}}护甲值。
  ** 会在包含铁马铠的战利品表中出现，且生成概率与铁马铠相同。

; [[工具]]
* 加入了铜质工具，即[[斧]]、[[锄]]、[[镐]]、[[锹]]和[[剑]]的铜质变种。
  ** 可由[[铜锭]]和[[木棍]]合成。
  ** 攻击伤害与石质工具相同，但耐久度高于石质工具。
  ** 挖掘速度快于石质工具，但慢于铁质工具。
  ** 附魔能力为13，高于钻石质工具，但略低于铁质工具。

; [[铜粒]]
* 可由[[铜锭]]分解而成，也可通过烧炼铜盔甲和铜质工具获得。
* 可重新合成为铜锭。

; [[刷怪蛋]]
* 加入了铜傀儡刷怪蛋。

=== 生物 ===
;[[铜傀儡]]
* 将[[雕刻南瓜]]或[[南瓜灯]]放置在[[铜块]]的任意一面即可生成对应氧化程度的铜傀儡。
  ** 铜傀儡会在放置雕刻南瓜或南瓜灯的位置上生成。
  ** 铜傀儡的[[氧化]]程度与铜块相同，并且这个铜块会转变为对应的[[铜箱子]]。
* 死亡后会掉落1-3个[[铜锭]]。
* 能够分类箱子中的物品。
  ** 未手持物品时，铜傀儡会尝试搜寻附近的铜箱子，从其中收集物品。
  *** 每次最多可以收集16个物品。
  *** 所有物品均可收集。
  ** 手持物品时，铜傀儡会尝试搜寻附近的[[箱子]]或[[陷阱箱]]，将手持的物品放入其中。
  *** 该容器必须是空的，或包含与铜傀儡手持物品种类相同的物品。
  ** 会按顺序与最多10个箱子（或陷阱箱）或铜箱子进行交互。
  ** 未能找到匹配的箱子时，铜傀儡会进入7秒的空闲状态，随后再次进行尝试。
  ** 搜寻范围为自身位置水平方向32格，垂直方向8格。
* 处于完全氧化状态时会转变为[[铜傀儡像]]。
  ** 转变后，铜傀儡会以随机姿势保持静止，并掉落手持物品。
  ** 会保留转变前通过[[命名牌]]获得的名字。
* 玩家空手与铜傀儡交互时，铜傀儡会掉落其手持物品。
* 头盔槽位的虞美人可用[[剪刀]]剪下。
* 穿戴的装备会在变为[[铜傀儡像]]时掉落。

=== 游戏内容 ===
; [[Java版粒子|粒子]]
* 加入了<code>copper_fire_flame</code>。

=== 命令格式 ===
; {{cmd|fetchprofile}}
* 用于获取玩家档案内容。
* 此命令会异步执行，期间游戏不会暂停。
* 只有当获取操作完成后，才会输出为一条包含结果的消息。
  ** 玩家可通过此消息复制已完全解析的<code>profile</code>组件的内容。
  ** 亦可执行包含上述组件的给予[[玩家的头]]的{{cmd|give @s minecraft:player_head}}命令。
* 由于执行时未知结果，此命令永远返回<code>1</code>。
* 语法：
  ** <code>fetchprofile name <player name></code>
  *** 由玩家名称解析档案，不区分大小写。
  ** <code>fetchprofile id <uuid></code>
  *** 由玩家[[UUID]]解析档案。

=== 世界生成 ===
; [[世界加载屏幕]]
* 加入了一个显示在世界加载时所有需加载区块的加载进度条，包括：
  ** {{cmd|forceload}}加载的区块。
  ** 传送门活动的区块。
  ** 单人游戏中，末影珍珠加载的区块。
  ** 单人游戏中，玩家周围的区块。
  ** 创建世界时，分配世界出生点所需的区块。

; {{pa|End Flash}}
* 出现于末地的天空，表现为不定时出现的紫色光芒。
  ** 出现时，维度的天空光照随之增长。
  ** 可通过“{{pa|Hide Sky Flashes}}”选项来禁用{{pa|End Flash}}改变世界的天空光照和亮度的功能。
  ** 此为即将到来的{{pa|Vibrant Visuals|}}的一部分特性。

; [[噪声设置]]
* 在噪声设置定义文件中加入了<code>preliminary_surface_level</code>字段以取代<code>initial_density_without_jaggedness</code>。
  ** 原字段<code>initial_density_without_jaggedness</code>是通过扫描密度函数值>0.390625的首个点确定近似地表高度的3D密度函数。
  ** 现字段<code>preliminary_surface_level</code>是直接生成近似地表Y坐标的2D密度函数。
  ** 可用<code>find_top_surface</code>密度函数复现原字段的扫描行为。

; [[密度函数]]
* 加入了<code>find_top_surface</code>密度函数，用于近似计算指定密度函数的顶层表面。
  ** 此函数会从上限扫描到下限来定位密度函数值由负转正的位置。
  ** 上限应尽可能接近实际地表以保证最佳性能，且不能低于实际地表高度。
  ** 格式如下：
<div class="treeview">
::* {{nbt|compound}} 根对象
::** {{nbt|string|type}}：<code>find_top_surface</code>。
::** {{nbt|string}}{{nbt|double}}{{nbt|compound|density}}：所计算表面的密度函数。
::** {{nbt|string}}{{nbt|double}}{{nbt|compound|upper_bound}}：提供最高有效Y值的2D密度函数。
::** {{nbt|int|lower_bound}}：最低有效Y值。
::** {{nbt|int|cell_height}}：（{{interval|left_open=0}}）所扫描网格的分辨率。
</div>
* 加入了<code>invert</code>密度函数，用于计算<code>1/argument</code>。
** 格式如下：
<div class="treeview">
::* {{nbt|compound}} 根对象
::** {{nbt|string|type}}：<code>invert</code>。
::** {{nbt|string}}{{nbt|double}}{{nbt|compound|argument}}：输入的密度函数。
</div>

=== 常规 ===
; [[调试屏幕]]
* 现在也可以在世界以外的屏幕中启用，且始终置于顶层。
* 现在默认会显示较少的信息，包括FPS、TPS、游戏版本、系统规格、内存使用、玩家位置、玩家区段坐标和3D准星。
* 加入了调试选项屏幕，使用{{key|F3+F5}}打开。
  ** 用于配置哪些调试信息需隐藏/仅在调试屏幕中显示/始终可见。
  ** 其他{{key|F3}}调试组合键也可通过此屏幕开关。
  ** 之前未向社区开放的调试功能（比如可视化区段八叉树）现在可通过此屏幕开关。
  ** 调试选项屏幕有以下预设配置。
  *** {{cd|Default}}：将所有选项重置为默认状态。
  *** {{cd|Performance}}：仅显示如FPS的简单性能指标。

; [[选项]]
* 在“{{tr|辅助功能设置|協助工具設定|無障礙功能設定}}”界面中加入了“{{tr|按键控制…|按鍵設定...|按鍵設定⋯⋯}}”按钮。
  ** 此界面中的“自动跳跃”、“潜行”和“疾跑”设定键已移除。
* 在“{{tr|按键控制|按鍵設定}}”界面中加入了用于调整“{{tr|攻击/摧毁|攻擊／破壞}}”及“{{tr|使用物品/放置方块|使用物品／放置方塊}}”按键绑定模式（“按住”或“切换”）的按钮。
* 在“{{tr|按键控制|按鍵設定}}”界面中加入了“{{pa|Sprint Window}}”滑动条，控制双击前进键疾跑时双击有效的窗口期，单位为刻，最大为10，为“关”时无法通过双击前进键以疾跑。
* 在“鼠标设置”界面中加入了“{{tr|反转鼠标X轴|反轉滑鼠 X 軸}}”按钮。
  ** 原来的“鼠标反转”已重命名为“{{tr|反转鼠标Y轴|反轉滑鼠 Y 軸}}”。
* 在“聊天设置”中加入了“{{tr|保存未发送的聊天消息|儲存未傳送的聊天訊息}}”选项。
  ** 启用时，未发送的消息会在玩家主动关闭聊天框时保存。

; {{pa|Server Code of Conduct}}屏幕
* 加入服务器时显示此屏幕。玩家只有同意此{{tr|准则|準則|守則}}，才能在此服务器上游玩。
* 屏幕中存在一个复选框，以允许在下一次加入此服务器且{{tr|准则|準則|守則}}未改变时跳过此屏幕。

; [[服务端配置文件格式]]
* 向{{filename|server.properties}}中加入了新布尔型字段<code>enable-code-of-conduct</code>。
  ** 设为<code>true</code>时，服务端会在{{filename|server.properties}}所在目录的{{filepath|codeofconduct}}子目录下寻找{{pa|Server Code of Conduct}}文件。
  ** 每个{{pa|Server Code of Conduct}}文件的格式应为{{filename|<-{}-语言代码>.txt}}。
* 向{{filename|server.properties}}中加入了新布尔型字段<code>management-server-enabled</code>。
  ** 设为<code>true</code>时，服务端会启用[[服务端管理协议]]。
* 向{{filename|server.properties}}中加入了新字符串型字段<code>management-server-host</code>。
  ** 设置[[服务端管理协议]]绑定的主机名（默认为<code>localhost</code>）。
* 向{{filename|server.properties}}中加入了新整数型字段<code>management-server-port</code>。
  ** 设置[[服务端管理协议]]绑定的端口（默认为<code>25585</code>）。
* 向{{filename|server.properties}}中加入了新整数型字段<code>status-heartbeat-interval</code>。
  ** 设置[[服务端管理协议]]中向已连接的客户端发送心跳通知的间隔，设置为<code>0</code>会禁用此功能。(默认为<code>0</code>)。

; [[盔甲材料]]
* 加入了铜质材料。

; [[工具材料]]
* 加入了铜质材料。

; [[标签]]
* 加入了下列方块标签：
  ** {{cd|#copper_chests}}
  ** {{cd|#copper}}
  ** {{cd|#incorrect_for_copper_tool}}：{{cd|d=pretty|#needs_diamond_tool|#needs_iron_tool}}
  ** {{cd|#copper_golem_statues}}
  ** {{cd|#lightning_rods}}
  ** {{cd|#wooden_shelves}}
  ** {{cd|#chains}}：{{cd|d=pretty|chain|copper_chain|waxed_copper_chain|exposed_copper_chain|waxed_exposed_copper_chain|weathered_copper_chain|waxed_weathered_copper_chain|oxidized_copper_chain|waxed_oxidized_copper_chain}}。
  ** {{cd|#lanterns}}：{{cd|d=pretty|lantern|soul_lantern|copper_lantern|waxed_copper_lantern|exposed_copper_lantern|waxed_exposed_copper_lantern|weathered_copper_lantern|waxed_weathered_copper_lantern|oxidized_copper_lantern|waxed_oxidized_copper_lantern}}。
  ** {{cd|#bars}}：{{cd|d=pretty|iron_bars|copper_bars|waxed_copper_bars|exposed_copper_bars|waxed_exposed_copper_bars|weathered_copper_bars|waxed_weathered_copper_bars|oxidized_copper_bars|waxed_oxidized_copper_bars}}。
* 加入了下列物品标签：
  ** {{cd|#copper_chests}}
  ** {{cd|#copper}}
  ** {{cd|#copper_tool_materials}}
  ** {{cd|#repairs_copper_armor}}
  ** {{cd|#copper_golem_statues}}
  ** {{cd|#lightning_rods}}
  ** {{cd|#wooden_shelves}}
  ** {{cd|#chains}}：{{cd|d=pretty|chain|copper_chain|waxed_copper_chain|exposed_copper_chain|waxed_exposed_copper_chain|weathered_copper_chain|waxed_weathered_copper_chain|oxidized_copper_chain|waxed_oxidized_copper_chain}}。
  ** {{cd|#lanterns}}：{{cd|d=pretty|lantern|soul_lantern|copper_lantern|waxed_copper_lantern|exposed_copper_lantern|waxed_exposed_copper_lantern|weathered_copper_lantern|waxed_weathered_copper_lantern|oxidized_copper_lantern|waxed_oxidized_copper_lantern}}。
  ** {{cd|#bars}}：{{cd|d=pretty|iron_bars|copper_bars|waxed_copper_bars|exposed_copper_bars|waxed_exposed_copper_bars|weathered_copper_bars|waxed_weathered_copper_bars|oxidized_copper_bars|waxed_oxidized_copper_bars}}。
* 向{{cd|#stronghold_biased_to}}生物群系标签中加入了{{cd|cherry_grove}}。
* 加入了下列实体类型标签：
  ** {{cd|#accepts_iron_golem_gift}}：{{cd|copper_golem}}。
  *** 会将铁傀儡的赠礼戴到头上的实体。
  ** {{cd|#candidate_for_iron_golem_gift}}：{{cd|d=pretty|villager|#accepts_iron_golem_gift}}。
  *** 会被铁傀儡赠予虞美人的实体。
  ** {{cd|#cannot_be_pushed_onto_boats}}：{{cd|d=pretty|player|guardian|elder_guardian|cod|pufferfish|salmon|tropical_fish|dolphin|squid|glow_squid|tadpole|creaking}}。
  *** 不会被推进[[船]]的实体。
* 加入了下列物品标签：
  ** {{cd|#shearable_from_copper_golem}}：{{cd|poppy}}。
  *** 可从铜傀儡头部剪下的物品。
* 向{{cd|#cluster_max_harvestables}}物品标签中加入了{{cd|copper_pickaxe}}。
* 向方块标签<code>#impermeable</code>中加入了<code>barrier</code>。

; [[魔咒定义格式#魔咒效果|魔咒效果]]
* 向<code>explode</code>魔咒效果中加入了{{nbt|list|block_particles}}<ref>更新日志中称为<code>block_effects</code>。</ref>字段，以指定爆炸时产生的每种方块粒子。
  ** 格式如下：
<div class="treeview">
::* {{nbt|list|block_particles}}
::** {{nbt|compound}}：一种方块粒子。
::*** {{nbt|int|weight|required=1}}：（{{interval|left_open=0}}）此项被随机选中的权重。
::*** {{nbt|compound|particle|required=1}}：要渲染的粒子。
::*** {{nbt|float|scaling}}：（默认为<code>1.0</code>）爆炸中心和方块位置间距离的乘数。
::*** {{nbt|float|speed}}：（默认为<code>1.0</code>）粒子的速度乘数。
</div>

; [[文本组件]]
* 加入了<code>object</code>文本组件类型。
  ** 用于以字符形式显示纹理图集中的一个精灵图。
  ** 精灵图总会显示为8&times;8像素的矩形。
  ** 格式：
<div class="treeview">
::* {{nbt|compound}} 复合标签格式根标签
::** {{nbt|string|type}}：<code>object</code>。
::** {{nbt|string|atlas}}：（默认为<code>minecraft:blocks</code>）纹理图集的命名空间ID。
::** {{nbt|string|sprite}}：图集中精灵图的命名空间ID。示例：<code>item/porkchop</code>。
</div>

; [[战利品表]]
* 加入了<code>harvest/sweet_berry_bush</code>战利品表，用于生成与[[甜浆果丛]]交互收获甜浆果的战利品。

; [[模型#渲染变换|模型渲染变换]]
* 加入了<code>on_shelf</code>渲染变换，用于模型在{{pa|Shelf}}上的变换。

; [[纹理]]
* 加入了纹理<code>environment/end_flash.png</code>。

; [[声音事件]]
* 加入了声音事件{{cd|d=pretty|entity.copper_golem.shear|weather.end_flash}}。

; [[服务器]]
* 加入了[[Minecraft服务器管理协议]]。
  ** 用于管理服务端而开放的API。
  ** 基于WebSocket和JSON-RPC 2.0协议进行双向通信。
  ** 由[[服务端配置文件]]中的{{code|management-server-enabled}}控制开启与关闭。
  **如果服务端启动时不能绑定指定的主机名和端口，服务端将启动失败。

== 更改 ==

=== 方块 ===
; [[箱子]]、[[陷阱箱]]和[[末影箱]]
* 现在音效音量更低。

; [[铜活板门]]
* 配方由6个[[铜锭]]更改为4个铜锭。

; [[龙蛋]]
* 现在不会传送至所在维度的建筑高度限制之外。

; {{pa|Iron Chain|}}
* 锁链（Chain）现在被重命名为{{pa|Iron Chain|showorigin=1}}。

=== 物品 ===
; [[染料]]
* 更新了染料的纹理。

; [[刷怪蛋]]
* 现在在[[和平]]难度中会出现提示框文本。
* 现在在和平难度中，怪物不会生成。

; [[附魔书]]
* 现在[[稀有度]]由“少见”更改为“稀有”。

=== 生物 ===
; [[铁傀儡]]
* 现在会将[[虞美人]]赠予附近的铜傀儡，接受的铜傀儡会将其戴到头上。

; [[快乐恶魂]]
* 现在成年快乐恶魂的音效可在64个方块内听到。

; [[蜜蜂]]
* 现在末地的蜜蜂不会再在[[主世界]]降雨时归巢。

; [[僵尸]]、[[骷髅]]及其变种
* 现在有概率装备铜盔甲。
  ** 铜盔甲的出现概率大于皮革盔甲和金盔甲。
  ** 受此影响，金盔甲的出现概率现在低于皮革盔甲。

; [[末影人]]
* 随末地天空光照变化更新了[[寻路]]AI，现在不会趋向移动到暗处。

=== 非生物实体 ===
; [[动力矿车]]
* 手中没有可作为燃料的物品或燃料充足时，按{{ctrl|使用}}键与其交互不再使动力矿车方向改变为玩家点击时的方向。

=== 游戏内容 ===
; [[爆炸]]
* 现在爆炸时会与[[Java版1.15-pre1|1.15-pre1]]前一样生成方块粒子。

=== 命令格式 ===
; {{cmd|test}}
* {{cmd|test pos [<var>]|link=none}}子命令：
  ** 搜索半径由200格更改为250格。
* {{cmd|test clearall [<radius>]|link=none}}子命令：
  ** {{cd|<radius>}}的默认值由200更改为250。

; {{cmd|summon}}
* 现在尝试在和平难度下召唤怪物会执行失败。

=== 世界生成 ===
; [[末地]]
* 现在具有天空光照和环境光照。
* 怪物生成位置的最大天空光照现在为15。
* 现在，末地的天空中会不定时地出现紫色光芒。
  ** 紫色光芒出现时，维度的天空光照随之增长。
  ** 紫色光芒出现时，被照到的方块会稍微变紫一点。

; [[生物群系]]
* 现在即使温度低于0.15，不[[降雨]]的生物群系也不会降雪。

; [[区块加载]]
* 与存在玩家活动或存在强制加载区块的维度相同，现在满足下方任一条件的维度也会被视为“活跃”并持续处理区块和实体。
  ** 存在活动的传送门。
  ** 存在飞行中的[[末影珍珠]]。

; [[出生点区块]]
* 移除了“出生点区块”的概念，但世界加载行为仍与之前相同。

; [[世界加载屏幕]]
* 现在显示玩家将进入的周围区块，而非围绕世界出生点加载的区块。

; [[结构定义格式#jigsaw|拼图结构定义格式]]
* {{nbt|int|max_distance_from_center}}字段现在可以指定垂直与水平轴不同的限制。
  ** 格式如下：
<div class="treeview">
::* {{nbt|compound|max_distance_from_center}}
::** {{nbt|int|horizontal|required=1}}：（{{interval|left=1|right=128}}）
::** {{nbt|int|vertical}}：（{{interval|left=1|right=4096}}，默认为4096）
</div>
:* 示例：<code>"max_distance_from_center": { "horizontal": 20, "vertical": 500 }</code>。

=== 游戏内容 ===
; [[游戏规则]]
* 移除了{{cd|[[游戏规则/spawnChunkRadius|spawnChunkRadius]]}}。

; [[创造模式物品栏]]
* 铜傀儡刷怪蛋现在自[[铁傀儡刷怪蛋]]后移动到[[鳕鱼刷怪蛋]]后。

=== 常规 ===
; [[聊天]]
* 现在可以在[[下界传送门]]中打开聊天。
* 玩家传送到其他维度后，之前打开的聊天仍会保持开启且保留内容。
* 聊天被强制（例如死亡或打开对话框时）而非主动关闭时，未发送的聊天内容现在会以聊天草稿形式保存。
  ** 下次聊天打开时，聊天草稿会被填入消息框。
  ** 草稿文本在完全恢复前呈灰色，通过如下任一交互可使草稿恢复为普通文本：
  *** 输入附加文本
  *** 使用方向键移动光标
  *** 点击文本
  *** 选取文本，使文本高亮
  ** 草稿恢复前，按下{{key|Enter}}可发送此消息。
  ** 草稿恢复前，按下{{key|Backspace}}会删除此消息。

; [[社交屏幕]]
* 现在在服务器中见过的玩家总会在社交屏幕中显示，即使他们处于离线状态。

; [[音乐]]
* 将音乐分类“{{tr|声音/语音|聲音／語音}}”重命名为“{{tr|复述功能/语音|朗讀功能／語音}}”。

; [[物品堆叠组件]]
* <code>block_attacks</code>：
  ** 不大于0的伤害现在不会触发抵挡行为，不会使具有<code>block_attacks</code>组件的物品进入冷却，也不会应用因抵挡而受到的击退。

; [[选项]]
* “显示字幕”选项已重命名为“{{pa|Closed Captions}}”，以更准确地描述它的作用。
* 将辅助功能选项“{{tr|隐藏闪电的闪烁效果|隱藏閃電效果|隱藏雷電閃光}}”重命名为了“{{pa|Hide Sky Flashes}}”以支持禁用{{pa|End Flash}}。

; [[全景图]]
* 更新了主菜单全景图以匹配[[铜器时代]]。

; [[统计信息]]
* 更改了标签页栏的样式。
  ** 现在使用新的标签页设计，取代了之前的按钮式标签页。
  ** 现在标签页在屏幕顶端对齐。

; [[数据包]]
<!--* 将数据包版本号更改为{{cd|84.0}}。-->
* 数据包版本号现在包含次要版本号。
  ** 次要版本号允许同一主要版本号下的数据包向后兼容。

; [[资源包]]
<!--* 将资源包版本号更改为{{cd|66.0}}。-->
* 资源包版本号现在包含次要版本号。
  ** 次要版本号允许同一主要版本号下的资源包向后兼容。

; {{filename|[[pack.mcmeta]]}}
* 更新了格式：
  ** 移除了{{nbt|int}}{{nbt|list}}{{nbt|compound|supported_formats}}。
  ** {{nbt|int|pack_format}}现在是可选的。
  ** 加入了必选字段{{nbt|int}}{{nbt|int-array|min_format}}和{{nbt|int}}{{nbt|int-array|max_format}}。
  *** 标准格式为包含两个整数的数组，如<code>[74, 1]</code>。
  *** 对于最低版本号，单个整数被视为次要版本号为0，比如{{cd|d=pretty|74|[74]|[74, 0]}}是等价的。
  *** 对于最高版本号，单个整数（也包括只有一个整数的数组）被视为<code>0x7fffffff</code>，即任何小版本号都接受。
  ** 在{{nbt|compound|overlays}}中的{{nbt|int}}{{nbt|list}}{{nbt|compound|formats}}也被移除，并同样被{{nbt|list|entries}}内的{{nbt|int}}{{nbt|int-array|min_format}}和{{nbt|int}}{{nbt|int-array|max_format}}取代。
* 支持的最低包版本号由{{cd|16}}降低至{{cd|15}}。

; [[标签]]
* 自实体类型标签<code>#cannot_be_pushed_onto_boats</code>中移除了<code>guardian</code>。

; [[战利品上下文]]
* 加入了战利品上下文参数集<code>entity_interact</code>，提供以下参数：
  ** <code>target_entity</code>：被交互的实体
  ** <code>interacting_entity</code>：（可选）与<code>target_entity</code>交互的实体
  ** <code>tool</code>：与<code>target_entity</code>交互所用的工具
* 加入了战利品上下文参数集<code>block_interact</code>，提供以下参数：
  ** <code>block_state</code>：被交互方块实体的方块状态
  ** <code>block_entity</code>：被交互的方块实体
  ** <code>interacting_entity</code>：（可选）与<code>block_state</code>交互的实体
  ** <code>tool</code>：与<code>block_state</code>交互所用的工具
* 加入了战利品上下文参数{{cd|d=pretty|target_entity|interacting_entity}}。

; [[战利品表]]
* 为实体被闪电苦力怕杀死时的掉落物加入了<code>charged_creeper/</code>战利品表。
  ** 根战利品表<code>charged_creeper/root</code>根据具体实体类型分配到下列子表：
  *** {{cd|d=list|list-level=***|charged_creeper/piglin|charged_creeper/creeper|charged_creeper/skeleton|charged_creeper/wither_skeleton|charged_creeper/zombie}}
* 加入了下列战利品表：
  ** <code>brush/armadillo</code>：刷扫犰狳
  ** <code>gameplay/turtle_grow</code>：幼年海龟成年
  ** <code>harvest/beehive</code>：用剪刀采集蜂箱/蜂巢
  ** <code>harvest/cave_vine</code>：采集洞穴藤蔓上的发光浆果
  ** <code>carve/pumpkin</code>：用剪刀雕刻-{}-南瓜

; [[文本组件]]
* <code>run_command</code>文本组件：
  ** 命令为{{cd|d=pretty|/say|/me|/msg|/tell|/w|/teammsg|/tm}}这类署名命令时，现在会显示一个窗口，以允许玩家将此命令输入到聊天窗口，或在无法打开聊天窗口时将此命令复制到剪贴板。
* 绘制精灵图时，粗体与斜体样式现在会被忽略。

; [[数据组件]]
* 更改了<code>profile</code>组件。
  ** 现在组件内容不再在游戏档案完全解析（即从Minecraft服务中下载）时改变，即解析值也不再会被储存。
  ** 此组件现在会有以下两种行为：
  *** '''静态'''：当此组件具有{{nbt|list}}{{nbt|compound|properties}}字段、同时具有{{nbt|string|name}}和{{nbt|int-array|id}}字段亦或上述两字段均无时。
  **** 此状态下，游戏档案会按原样渲染。
  **** 如果缺失{{nbt|list}}{{nbt|compound|properties}}字段，则与离线模式中一样使用根据{{nbt|int-array|id}}选择的默认皮肤。
  **** 这意味着所展示的皮肤会在此组件创建时冻结。
  **** 这一项更利于装饰用途。
  *** '''动态'''：{{nbt|string|name}}和{{nbt|int-array|id}}字段二者只有其一时。
  **** 包含此游戏档案的物品在客户端渲染时，此游戏档案会被解析为最近的数据。
  **** 即此物品总会展示目标玩家的当前皮肤。
  ***** 注：如果不重启客户端，玩家在游戏运行时更改的皮肤在客户端看不见。
  **** 解析会有延迟，期间会以默认皮肤显示。
  **** 若仅有{{nbt|string|name}}，则物品名称会被其替代。
  **** 此物品的物品提示框中会显示“{{tr|实时显示|動態}}”，以与静态游戏档案相区分。
  ** 旧版世界中未加载的生物头颅升级后通常会转换为动态游戏档案。

; [[着色器]]与后处理效果
* 移除了{{cd|d=pretty|core/blit_screen.vsh|post/blit.vsh|post/blur.vsh|post/invert.vsh|post/sobel.vsh|post/screenquad.vsh}}顶点着色器，现在由{{cd|core/screenquad.vsh}}替代。
* 用于后处理效果、亮度图生成和全屏位块传输的顶点着色器不再传递<code>Position</code>属性，而须通过<code>gl_VertexID</code>分配顶点坐标。

; 性能
* 改进了实体渲染顺序以提高性能。
* 改进了方块实体和物品的渲染性能。

== 修复 ==
{{fixes|fixedin=25w31a,25w32a,25w33a,25w34a,25w34b,25w35a|beforeVersion=25w31a|showdesc=1|new=1
|;old
|383|选择世界屏幕中，世界名称、版本和时间戳会从列表中溢出到右边。
|26334|死亡时，聊天界面被强制清空。
|36783|物品展示框/荧光物品展示框不会在包含地图时改变其判定箱。
|46503|在旁观实体时执行{{cmd|kill|link=none}}命令可保留实体着色器效果。
|46634|{{tr|雷鸣|雷聲|行雷聲}}音量不受“天气”音量设置影响。
|59413|水和熔岩能在屏障中产生滴粒子。
|69216|钓鱼时切换到旁观模式会保留鱼线。
|73881|在和平难度中生成怪物会使其出现1游戏刻。
|89142|将跳跃键绑定至{{key|Enter}}会使玩家在补全聊天消息时跳跃。
|94610|闪电苦力怕的生物头颅掉落物缺少战利品表项。
|98200|除了主音量外的所有音量滑动条都会被指定高音量的{{cmd|playsound|link=none}}忽略。
|98322|由旁观模式切换到创造模式后保持飞行。
|99785|能在旁观模式中牵引实体。
|119417|玩家上床并切换到旁观模式后卧床不起。
|147784|在旁观模式下右键制箭台时，工作台的GUI会闪烁约一秒。
|163218|“潜行”选项设为“切换”时，玩家能在游戏界面打开期间潜行。
|165991|自1.15-pre1起，TNT爆炸不再显示更多烟雾粒子。
|173730|持水桶对可含水方块{{key|Shift}}+右键单击不会在此方块旁边放置水。
|174759|龙蛋能传送到虚空之下的高度。
|183776|用{{key|F3+F4}}切换游戏模式后，需要通过连按两次{{key|F3}}来{{tr|开关|開啟及關閉}}调试屏幕。
|183784|缩放窗口后，游戏模式切换器调试菜单存在视觉漏洞。
|187850|若聊天被隐藏，成书中的<code>run_command</code>点击事件无效。
|191669|玩家向方块或普通障碍物疾跑时，将游戏模式切换到旁观模式会取消疾跑。
|192907|{{key|F3}}调试菜单不能在聊天打开时{{tr|开关|開啟及關閉}}。
|196443|<code>reducedDebugInfo</code>为<code>true</code>时，即使没有效果，按下{{key|F3+B}}和{{key|F3+G}}仍会在聊天中告诉玩家相应功能已开启或关闭。
|197247|使用{{key|F3+D}}清除待处理消息时，新消息会保留之前的延迟。
|203401|无法禁用或修改双击前进键的疾跑按键绑定。
|220842|在旁观具有着色器效果的生物时打开游戏模式切换器会{{tr|开关|開啟及關閉}}效果。
|232968|旁观模式与非旁观模式玩家同时查看箱子或木桶的内容能禁用其关闭动画。
|234479|能向已收到邀请或已经加入Realm中的玩家多次发送加入自己Realm的邀请。
|235780|鼠标指针悬停于信标GUI内的“完成”和“取消”按钮上时会错展示“信标”提示框。
|237016|即使游戏被暂停，聊天延迟功能也会继续输出消息。
|237843|观看终末之诗和鸣谢名单时的玩家能因处于空闲状态而被踢出。
|257540|绵羊吃草的频率只有21w39a之前的一半。
|238146|在睡觉期间切换到旁观模式后，夜晚永不跳过。
|259571|玩家死亡或游戏重载后，玩家上次的游戏模式不会被保存。
|259673|创建世界屏幕和统计信息屏幕中的标签选项卡效果不同。
|259692|在界面刚关闭时松开潜行/疾跑对应的输入按键会使这两种状态被不符预期地激活或切换。
|259935|生物群系的降水性为<code>NONE</code>时仍可以降雪。
|260591|{{cmd|execute on origin|link=none}}或{{cmd|execute on owner|link=none}}会失败于寻找处于不同维度中的目标实体。
|260822|信标GUI内的“完成”和“取消”按钮不再在鼠标指针悬停其上时展示提示框。
|260920|统计信息屏幕的列无法由键盘导航访问。
|261387|红树放置器中存在冗余的<code>block_predicate_filter</code>检查。
|262000|未使用的纹理：{{filename|misc/white.png}}。
|263597|末影龙重生噪音不能通过“敌对生物”音量滑动条降低。
|265290|使用{{key|Tab}}键时，命令方块界面内的元素未按顺序选中。
|269838|修剪南瓜的掉落物被硬编码为南瓜种子。
|269839|修剪蜂巢和蜂箱的掉落物被硬编码为蜜脾。
|270172|被勾住的玩家将游戏模式切换到旁观模式时，客户端与服务端失去同步。
|270190|在织布机界面中，在旗帜图案上悬停不会显示提示框。
|270669|翻译键<code>argument.block.property.novalue</code>中的参数顺序错误。
|270918|生物头颅的战利品表缺少包含<code>custom_name</code>的<code>copy_components</code>战利品表函数。
|272584|受到<code>Owner</code>为玩家的实体所造成爆炸而被改变方向的火球不再属于玩家。
|;1.21.1的漏洞
|275244|{{filename|configured_carver}}文件中的<code>width_smoothness</code>设置为0会导致游戏冻结或崩溃。
|275432|字幕在屏幕中难以观察。
|276431|龙蛋传送到建筑高度上限之上而使自己被删除。
|276568|游戏会生成盔甲纹饰图集的Mipmap版本。
|276629|洞穴藤蔓的掉落物似乎被硬编码为发光浆果。
|276931|附魔书的稀有度错误。
|277447|Minecraft会为箱子生成未使用的Mipmap纹理。
|277450|Minecraft会为潜影盒生成未使用的Mipmap纹理。
|277470|Minecraft会为床生成未使用的Mipmap纹理。
|277471|Minecraft会为告示牌生成未使用的Mipmap纹理。
|277473|Minecraft会为饰纹陶罐生成未使用的Mipmap纹理。
|277481|Minecraft会为旗帜生成未使用的Mipmap纹理。
|277483|Minecraft会为盾牌生成未使用的Mipmap纹理。
|277770|<code>block_age</code>处理器类型总是将台阶属性<code>type</code>改为<code>bottom</code>。
|;1.21.2的漏洞
|276759|刷扫犰狳的掉落物被硬编码为犰狳鳞甲。
|;1.21.3的漏洞
|278550|在创造模式或旁观模式中飞行时，水面会使玩家停止冲刺。
|;1.21.4的漏洞
|278965|樱花树林不属于<code>#stronghold_biased_to</code>标签。
|279793|驾驶马、驴、骡、僵尸马、骷髅马和骆驼不再强制玩家面向前方。
|289348|重新加载后，位于末地的末影珍珠不会在末地没有玩家时加载区块。
|;1.21.5的漏洞
|279548|TNT矿车在因摔落爆炸时不会记忆将其点燃的来源。
|295841|交互式碰撞检测路径已损坏。
|296054|非弹射物实体的高速正向移动可能无法触发起始位置周围方块的方块效果。
|296055|非弹射物实体的缓慢移动可能无法触发起始方块的方块效果。
|296057|非弹射物实体的侧向移动可能无法触发起始位置周围方块的方块效果。
|296372|自1.21.5起，展示实体位置与视线旋转的变化插值<code>teleport_duration</code>不可靠。
|296789|测试实例方块界面内的文本颜色与其他相似界面中的不一致。
|298274|某些无效命令会输出无附加信息的“{{tr|错误见下|錯誤如下}}”。
|298805|盾牌即使没有阻挡攻击也会被斧停用。
|;1.21.6的漏洞
|297126|升级25w15a或25w16a的世界时频繁出现“Failed to read field...”<!--日志文本不翻译-->错误。
|297496|Java版Realms信息框内的文本在被选中时完全消失。
|297593|从底部与炼药锅接触现在也会受到其中装有的物质影响。
|297898|进入对话框会暂时关闭聊天并清除玩家当前正在输入的内容。
|298605|创建“水世界”超平坦世界时，玩家在海底出生。
|298732|光标不再在非末行的行尾显示。
|298883|通过导航键{{key|Tab}}在Realms中选中可用的世界时，此栏未高亮。
|299067|多人游戏中，箭会因为玩家断开连接而丢失从属关系。
|299115|被反弹的箭会因为其主人离线而丢失<code>Owner</code>标签。
|;1.21.7的漏洞
|299314|以特定方式破坏唱片机不会使正在播放的音乐停下。
|299450|在书与笔界面中，不再能通过双击选取字符。
|299451|在书与笔中翻页时，页面不再自动聚焦。
|299548|若聊天被隐藏，<code>run_command</code>对话框行为不会生效。
|299566|书与笔界面中的光标距左侧过远。
|299627|高速弹射物实体插值非常不准确。

|299628|骑乘中的玩家或生物会在世界加载时触发幽匿感测体。
|299770|即使<code>enderPearlsVanishOnDeath</code>被设为<code>false</code>，由末影珍珠加载的区块仍会在玩家死亡后永远卸载。
|299782|在拼图结构中保存的僵尸村民会在世界生成后遗忘其生物群系变种和职业。
|;1.21.8的漏洞
|299823|Minecraft着色器引发C7050警告。
|299837|在同一游戏刻中执行两个及以上{{cmd|rotate|link=none}}命令只会应用最后一个命令的旋转。
|299872|被冰冻的玩家接触火时，冰冻遮罩闪烁。
|299873|对话框中纯文本消息的选择框会被切断。
|299896|能将已过期Realms的世界移至空槽位，但这会导致在没有有效Realms订阅时误导性产生创建世界提示。
|299913|“{{tr|你似乎还没有Realm…|你似乎還沒有 Realm…|你似乎並未擁有 Realm⋯⋯}}”可聚焦文本部件现在拥有黑色背景。
|300021|村民交易屏幕中的部分元素现在渲染于光标所持物品上方。
|300034|海豚会上船。
|300092|F3饼图中粒子子项缺少名称。
|300340|连续点击欢迎页面中的“继续”会重置按钮的消失动画进度。
|300457|{{cd|d=或|action|exit_action}}被设为<code>run_command</code>且设置了一条会产生署名的聊天消息的命令时无法退出对话框。
|300856|书署名屏幕中的I型光标的颜色错误。
}}

== 参考 ==
{{Reflist}}
