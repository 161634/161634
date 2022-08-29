
--[[

免费开源写法 且行且珍惜
所有写法 + 优化改善 + 设计来自夏轲
新写法思路 拒绝垃圾模板
禁止二改倒卖 禁止二改换作者
全网第一人写出 好东西多分享
像我这样的人不多了

]]--

function Main() 
XK = gg.multiChoice({
"『使用方法』\n➩点我查看如何使用和说明",
"[🇲🇾] ➩𝐒𝐚𝐬𝐬𝐲𝐛𝐲𝐩𝐚𝐬𝐬",
"[🇲🇾] ➩Bypass [Lobby]",
"[🇲🇾] ➩Lobby [ For H vs H ]",
"『退出脚本』"
},nil,(os.date([[
🕰️『%H点:%M分:%S秒』🕰️
♛▪× ᴘᴏᴡᴇʀ ʙʏ ᴍᴜʟᴛɪᴄʜᴏɪᴄᴇ ᴜɪ ×▪♛
→ ᴀʟʟ ʙʏ ᴄᴀᴛᴡɪʟʟ夏轲 ←

使用前请阅读好来使用方法
以下列表都是已经破解好的文件哟
如何使用看使用方法
云更新 不定时更新破解文件
好用多转发 谢谢❤️

]])))
if XK == nil then
gg.toast("『已缩小』")
else
if XK[1] == true then A1() end
if XK[2] == true then A2() end
if XK[3] == true then A3() end
if XK[4] == true then A4() end
if XK[5] == true then Exit() end
end
CatWill = -1 
end


function A1()
gg.alert([[

[ 使用方法 ]

选择你要的文件然后确定
会弹出要生成源码文件还是直接执行
这里根据自行选择
生成的源码文件会生产在 /storage/emulated/0/#➩ 破解文件列表

请勿用于非法用途
禁止倒卖
本脚本采用云更新
会不定时云更新破解文件
更新了会在电报Telegram频道通知

复制电报链接方便获取最新消息
不强迫你进频道 不进频道是你的损失不是我的损失
我是无所谓 反正是你获取不到最新消息而已
复制了链接就粘贴在游览器打开然后加入即可

作者 : [ 夏轲 ]

]],"复制进群链接")
gg.copyText("https://t.me/LearnLuaScript")
end

function A2()
alert = gg.alert("请选择你要源码文件还是直接在这里执行？","生成源码文件","直接执行")
if alert == nil then A2() end
if alert == 1 then
gg.newFolder = function (s)
    local s = s
    if s:sub(#s) ~= "/" then s = s .. "/" end
    s = s .. ".new"
    gg.saveList(s)
    os.remove(s)
    end

gg.newFolder("/storage/emulated/0/#➩ 破解文件列表")
io.open("/storage/emulated/0/#➩ 破解文件列表/[×𝐃𝐄𝐂×] 𝐒𝐚𝐬𝐬𝐲𝐛𝐲𝐩𝐚𝐬𝐬.lua","w"):write([==[

--[[

丑的人还在沉睡~~~
           　　 ⊂⌒／ヽ-、＿_
           　／⊂_/＿＿＿＿ ／
           　￣￣￣￣￣￣￣
           帅的人已经醒来~~~ 
　　　∩∩
　　（´･ω･）
　  ＿|　⊃／(＿＿_
　／ └-(＿＿＿_／

破解By夏轲
购买工具/技术私聊 @LuaScript_Programmer
破解技术吊打全网加密 无视防御

Dec By CatWill
Buy Dec Tutorial Or Tool Dm @LuaScript_Programmer
Dec Tutorial Can Dec All Script

]]
gg.toast("ᴋ ʀ ᴀ _ ᴋ ᴇ ɴ 💞")
gg.toast("✔️ GİRİŞ BAŞARILI")
gg.alert("𝐒𝐭𝐚𝐫𝐭 𝐛𝐲𝐩𝐚𝐬𝐬..↪️")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("635530605756416;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7133701809754865664;2305843009213693952", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("6989586621679009792;8574853690513424384", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1936483328;1936221025", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("177331434350968832;7091317848412258304", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1936681076;1936285535", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("3458764513820540928;720575940379279360", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("196864;16842753", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.refineNumber(196864, gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1179403647;1936026977", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7998392938210000896;4179340454199820288", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber(1987339635, gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7349874591868649472;3963167672086036480", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7566047373982433280;8214565720323784704", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;262403", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("4107282860161892352;3891110078048108544", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("133378;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("3242591731706757120;8286623314361712640", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("8502796096475496448;3530822107858468864", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.alert("𝐃𝐨𝐧𝐞🛡️")
gg.toast("𝐒𝐚𝐬𝐬𝐲𝐜𝐨𝐝𝐞♦️")
]==])
gg.alert("生成成功！\n生成路径为 ➩ /storage/emulated/0/#➩ 破解文件列表/")
end
if alert == 2 then
gg.toast("ᴋ ʀ ᴀ _ ᴋ ᴇ ɴ 💞")
gg.toast("✔️ GİRİŞ BAŞARILI")
gg.alert("𝐒𝐭𝐚𝐫𝐭 𝐛𝐲𝐩𝐚𝐬𝐬..↪️")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("635530605756416;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7133701809754865664;2305843009213693952", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("6989586621679009792;8574853690513424384", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1936483328;1936221025", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("177331434350968832;7091317848412258304", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1936681076;1936285535", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("3458764513820540928;720575940379279360", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("196864;16842753", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.refineNumber(196864, gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1179403647;1936026977", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7998392938210000896;4179340454199820288", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber(1987339635, gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("h00000000", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7349874591868649472;3963167672086036480", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("7566047373982433280;8214565720323784704", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;262403", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("4107282860161892352;3891110078048108544", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("133378;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("3242591731706757120;8286623314361712640", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("8502796096475496448;3530822107858468864", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.alert("𝐃𝐨𝐧𝐞🛡️")
gg.toast("𝐒𝐚𝐬𝐬𝐲𝐜𝐨𝐝𝐞♦️")
end
end

function A3()
alert = gg.alert("请选择你要源码文件还是直接在这里执行？","生成源码文件","直接执行")
if alert == nil then A2() end
if alert == 1 then
gg.newFolder = function (s)
    local s = s
    if s:sub(#s) ~= "/" then s = s .. "/" end
    s = s .. ".new"
    gg.saveList(s)
    os.remove(s)
    end

gg.newFolder("/storage/emulated/0/#➩ 破解文件列表")
io.open("/storage/emulated/0/#➩ 破解文件列表/[×𝐃𝐄𝐂×] Bypass [Lobby].lua","w"):write([==[

--[[

丑的人还在沉睡~~~
           　　 ⊂⌒／ヽ-、＿_
           　／⊂_/＿＿＿＿ ／
           　￣￣￣￣￣￣￣
           帅的人已经醒来~~~ 
　　　∩∩
　　（´･ω･）
　  ＿|　⊃／(＿＿_
　／ └-(＿＿＿_／

破解By夏轲
购买工具/技术私聊 @LuaScript_Programmer
破解技术吊打全网加密 无视防御

Dec By CatWill
Buy Dec Tutorial Or Tool Dm @LuaScript_Programmer
Dec Tutorial Can Dec All Script

]]

gg.alert("𝐁𝐮𝐲 𝐕𝐢𝐩 𝐆𝐆 𝐩𝐫𝐢𝐯𝐚𝐭𝐞 𝐀𝐧𝐭𝐢-𝐁𝐚𝐧: @𝐆𝐨𝐝_𝐙𝐮𝐞𝐬 𝐉𝐨𝐢𝐧 𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦: @𝐅𝐥𝐚𝐬𝐡𝐒𝐜𝐫𝐢𝐩𝐭 ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(":com.tencent.mobileqqa", gg.TYPE_BYTE)
gg.searchNumber(":com.tencent.mobileqqq", gg.TYPE_BYTE)
gg.searchNumber(":com.tencent.mobileqqu", gg.TYPE_BYTE)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1953391971", gg.TYPE_DWORD)
gg.refineNumber("1953391971", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("1953789044", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1818716462", gg.TYPE_DWORD)
gg.refineNumber("1818716462", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("1953789044", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("579451217772544;572854148005888", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("572854148005888;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("565157566611456;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("564058054983680;582749752655872", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;67109377", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("135682;134658", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134658;133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;131330", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("4096;135682", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("131330;134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Remaining", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";GOD", gg.TYPE_WORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Elimination", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";ZUES", gg.TYPE_WORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Finished", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";ZUES", gg.TYPE_WORD)
gg.clearResults()
gg.alert("Lobby Bypass Active Join: @FlashScript For More Updates")
gg.alert("Give Feedback ✔")

]==])
gg.alert("生成成功！\n生成路径为 ➩ /storage/emulated/0/#➩ 破解文件列表/")
end
if alert == 2 then

--[[

丑的人还在沉睡~~~
           　　 ⊂⌒／ヽ-、＿_
           　／⊂_/＿＿＿＿ ／
           　￣￣￣￣￣￣￣
           帅的人已经醒来~~~ 
　　　∩∩
　　（´･ω･）
　  ＿|　⊃／(＿＿_
　／ └-(＿＿＿_／

破解By夏轲
购买工具/技术私聊 @LuaScript_Programmer
破解技术吊打全网加密 无视防御

Dec By CatWill
Buy Dec Tutorial Or Tool Dm @LuaScript_Programmer
Dec Tutorial Can Dec All Script

]]

gg.alert("𝐁𝐮𝐲 𝐕𝐢𝐩 𝐆𝐆 𝐩𝐫𝐢𝐯𝐚𝐭𝐞 𝐀𝐧𝐭𝐢-𝐁𝐚𝐧: @𝐆𝐨𝐝_𝐙𝐮𝐞𝐬 𝐉𝐨𝐢𝐧 𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦: @𝐅𝐥𝐚𝐬𝐡𝐒𝐜𝐫𝐢𝐩𝐭 ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(":com.tencent.mobileqqa", gg.TYPE_BYTE)
gg.searchNumber(":com.tencent.mobileqqq", gg.TYPE_BYTE)
gg.searchNumber(":com.tencent.mobileqqu", gg.TYPE_BYTE)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1953391971", gg.TYPE_DWORD)
gg.refineNumber("1953391971", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("1953789044", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1818716462", gg.TYPE_DWORD)
gg.refineNumber("1818716462", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("1953789044", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("579451217772544;572854148005888", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("572854148005888;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("565157566611456;564058054983680", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("564058054983680;582749752655872", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;67109377", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("135682;134658", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134658;133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;131330", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("4096;135682", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("131330;134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("84149249", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Remaining", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";GOD", gg.TYPE_WORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Elimination", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";ZUES", gg.TYPE_WORD)
gg.clearResults()
gg.toast("Protection By: @God_Zues Dm For Vip Speed Flash Support Hacks ")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(";Finished", gg.TYPE_WORD)
gg.getResults(500)
gg.editAll(";ZUES", gg.TYPE_WORD)
gg.clearResults()
gg.alert("Lobby Bypass Active Join: @FlashScript For More Updates")
gg.alert("Give Feedback ✔")

end
end

function A4()
alert = gg.alert("请选择你要源码文件还是直接在这里执行？","生成源码文件","直接执行")
if alert == nil then A2() end
if alert == 1 then
gg.newFolder = function (s)
    local s = s
    if s:sub(#s) ~= "/" then s = s .. "/" end
    s = s .. ".new"
    gg.saveList(s)
    os.remove(s)
    end

gg.newFolder("/storage/emulated/0/#➩ 破解文件列表")
io.open("/storage/emulated/0/#➩ 破解文件列表/[×𝐃𝐄𝐂×] Lobby [ For H vs H ].lua","w"):write([==[

--[[

丑的人还在沉睡~~~
           　　 ⊂⌒／ヽ-、＿_
           　／⊂_/＿＿＿＿ ／
           　￣￣￣￣￣￣￣
           帅的人已经醒来~~~ 
　　　∩∩
　　（´･ω･）
　  ＿|　⊃／(＿＿_
　／ └-(＿＿＿_／

破解By夏轲
购买工具/技术私聊 @LuaScript_Programmer
破解技术吊打全网加密 无视防御

Dec By CatWill
Buy Dec Tutorial Or Tool Dm @LuaScript_Programmer
Dec Tutorial Can Dec All Script

]]

gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288232579469934592", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("572854148005888;582749752655872", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("579451217772544;564058054983680", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("303473799200768;282587373240320", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("648523848194457600;288233678981562368", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288232579469934592", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("131842;133634", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109377", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134914;133378", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("133890", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134146;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("135682", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1701147238", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1869438821", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1601593600", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1684171615", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1597518385", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1601466991", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1868719460", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711301733", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1818582883", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711301996", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1717960813", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711305833", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1701076854", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1953062772", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("134350848", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("134218114", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134914;133378", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("133890", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134146;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("135682", gg.TYPE_DWORD)
gg.clearResults()
gg.alert("done")
]==])
gg.alert("生成成功！\n生成路径为 ➩ /storage/emulated/0/#➩ 破解文件列表/")
end
if alert == 2 then

--[[

丑的人还在沉睡~~~
           　　 ⊂⌒／ヽ-、＿_
           　／⊂_/＿＿＿＿ ／
           　￣￣￣￣￣￣￣
           帅的人已经醒来~~~ 
　　　∩∩
　　（´･ω･）
　  ＿|　⊃／(＿＿_
　／ └-(＿＿＿_／

破解By夏轲
购买工具/技术私聊 @LuaScript_Programmer
破解技术吊打全网加密 无视防御

Dec By CatWill
Buy Dec Tutorial Or Tool Dm @LuaScript_Programmer
Dec Tutorial Can Dec All Script

]]

gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("620137442967552;564058054983680", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288232579469934592", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("572854148005888;582749752655872", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("579451217772544;564058054983680", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("303473799200768;282587373240320", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("648523848194457600;288233678981562368", gg.TYPE_QWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("288232579469934592", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("131842;133634", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109377", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134914;133378", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("133890", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134146;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("135682", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1701147238", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1869438821", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1601593600", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1684171615", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1597518385", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1601466991", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1868719460", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711301733", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1818582883", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711301996", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1717960813", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1711305833", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1701076854", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1953062772", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("134350848", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("134218114", gg.TYPE_DWORD)
gg.getResults(80000)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134658;144387", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134914;133378", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("133890", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_OTHER)
gg.searchNumber("134146;131330", gg.TYPE_DWORD, nil, nil, nil, nil)
gg.getResults(50000)
gg.editAll("135682", gg.TYPE_DWORD)
gg.clearResults()
gg.alert("done")
end
end

function Exit()
while true do
print([[
🕰️『%H点:%M分:%S秒』🕰️
♛▪× ᴘᴏᴡᴇʀ ʙʏ ᴄʜᴏɪᴄᴇ ᴜɪ ×▪♛
→ ᴀʟʟ ʙʏ ᴄᴀᴛᴡɪʟʟ夏轲 ←
]]) 
os.exit() 
end 
end


while true do 
if gg.isVisible(true) then
CatWill = 1
gg.setVisible(false)
end
if CatWill == 1 then
Main() 
end
end
