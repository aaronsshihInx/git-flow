# Git-flow 分享 by Ben Xie

## flow

![img](https://raw.githubusercontent.com/aaronsshihInx/git-flow/main/flow.jpg)

## OverView

根據您提供的信息，您似乎在討論軟體開發流程中的一些問題，包括在 Alpha 和 Beta 版本之間的差異、版本控制、分支管理、合併流程以及測試策略。這些問題可能會導致功能性整合、版本控制、合併衝突等方面的困擾。讓我們逐一分析並提出解決方案。

1. Alpha 和 Beta 版本之間的差異
   您提到在 Alpha 版本修正的問題在 Beta 版本中仍存在，這可能是由於版本控制或合併流程中的問題所導致。建議您檢查在 Alpha 版本修正的問題是否已經合併到 Beta 版本中，並確保版本控制系統中的合併記錄正確。

2. 版本控制和分支管理
   您描述了開發線、主要分支（Main）、Epic 和 Story 等概念。這些都是版本控制和分支管理中常見的術語。建議您確保在合併和發布時，所有的功能變更都按照正確的流程進行，並且在版本控制系統中有清晰的記錄。

3. 合併流程和測試策略
   您提到了合併流程中的依賴問題，以及在開發線和 Production 線之間的合併。建議您確保在合併時解決依賴問題，並且在合併後進行全面的測試，以確保新功能的穩定性和相容性。

4. 版本命名和標記
   您提到了版本命名和標記的問題，包括 Alpha、Beta 和 Production 版本的命名方式。建議您確保版本命名清晰明確，以便於識別和追蹤不同版本之間的差異。

5. 開發團隊的合作方式
   最後，您提到了多人開發時的合作方式和分工。建議您確保團隊成員之間的溝通暢通，並且在版本控制和合併流程中遵循統一的標準和流程。

總的來說，版本控制、分支管理、合併流程和測試策略是軟體開發中非常重要的環節，需要確保每個步驟都嚴謹執行，以確保軟體的品質和穩定性。

## Convert to timestamp

<details>
  <summary>Click me</summary>

1
00:00:00,000 --> 00:00:01,720
待會講一個非常關鍵的話

2
00:00:01,720 --> 00:00:03,720
為什麼在上方 Alpha 的東西

3
00:00:03,720 --> 00:00:05,720
在 Beta 上居然沒有

4
00:00:06,720 --> 00:00:07,220
OK

5
00:00:07,220 --> 00:00:08,840
或者是在 Alpha 修正的問題

6
00:00:08,840 --> 00:00:10,080
為什麼在 Beta 上有

7
00:00:10,080 --> 00:00:11,580
明明我們就有推到 Beta

8
00:00:11,580 --> 00:00:13,580
那為什麼 Beta 還是存在

9
00:00:13,580 --> 00:00:14,080
OK

10
00:00:14,080 --> 00:00:16,920
那這個東西其實是因為我們發版流程所導致

11
00:00:16,920 --> 00:00:18,120
那我們發版流程

12
00:00:18,120 --> 00:00:20,620
我們先可以看一下左邊這個線型發版流程

13
00:00:20,620 --> 00:00:22,940
我們現在的開發線主要是 MEM

14
00:00:22,940 --> 00:00:25,180
然後我們會在每一個地方做 Commit

15
00:00:25,180 --> 00:00:27,879
就是做一個功能做一個功能做一個功能

16
00:00:27,879 --> 00:00:30,520
然後我們通常開發劃碼師

17
00:00:30,520 --> 00:00:32,119
我們會先擺一條功能線

18
00:00:32,119 --> 00:00:33,720
然後做好之後把它 Replace 回去

19
00:00:33,720 --> 00:00:35,400
也就是說我這邊開發了三個點

20
00:00:35,400 --> 00:00:36,639
它就要回去三個點

21
00:00:36,639 --> 00:00:38,119
然後我們拉過去做了四個點

22
00:00:38,119 --> 00:00:39,200
我就要回去四個點

23
00:00:39,200 --> 00:00:42,200
然後到時候你的開發線就會充滿著像 MEM

24
00:00:42,200 --> 00:00:45,080
它每一個東西我們一個小小的開發的

25
00:00:45,080 --> 00:00:46,599
一個記錄一個記錄記錄

26
00:00:46,599 --> 00:00:48,520
那我們今天如果要發版的話

27
00:00:48,520 --> 00:00:50,160
我們有三條常駐線

28
00:00:50,160 --> 00:00:53,000
就是有 Alpha 線跟 Beta 線還有 Beta 曲線

29
00:00:53,000 --> 00:00:55,520
這三個線是常駐存在的

30
00:00:55,520 --> 00:00:56,080
OK

31
00:00:56,080 --> 00:00:57,680
那我們如果今天要發版的時候

32
00:00:57,680 --> 00:00:58,799
我們會怎麼做呢

33
00:00:58,799 --> 00:01:01,080
我們可能就會挑我們有做的點

34
00:01:01,080 --> 00:01:02,040
然後把它拉過去

35
00:01:02,040 --> 00:01:03,959
比方說我們今天要上到 Alpha

36
00:01:03,959 --> 00:01:05,639
那我今天要把三角

37
00:01:05,639 --> 00:01:09,879
我今天要把紅圈跟紅三角上到 Alpha

38
00:01:09,879 --> 00:01:12,199
我就會把這七個點挑到 Alpha 線上

39
00:01:12,199 --> 00:01:13,959
就如各位所看到對吧

40
00:01:13,959 --> 00:01:15,360
那這樣上上去之後

41
00:01:15,360 --> 00:01:16,519
接著我們會打版號

42
00:01:16,519 --> 00:01:17,959
比方說我拉了三個圈

43
00:01:17,959 --> 00:01:20,400
要打 1.0.0 對吧

44
00:01:20,400 --> 00:01:22,519
然後我們就會上這版打 Alpha

45
00:01:22,519 --> 00:01:24,959
然後接著我們如果再把三角形加上去

46
00:01:24,959 --> 00:01:27,120
我們就再打個版號 1.0.1

47
00:01:27,239 --> 00:01:27,720
對不對

48
00:01:27,720 --> 00:01:28,919
然後再上上去

49
00:01:28,919 --> 00:01:31,199
順利的話這部分是沒有問題的

50
00:01:31,199 --> 00:01:33,559
可是如果不順利的話

51
00:01:33,559 --> 00:01:34,839
當我們在拉三個點的時候

52
00:01:34,839 --> 00:01:37,519
它有可能會依賴人

53
00:01:37,519 --> 00:01:39,599
這就是寶哥之所以說

54
00:01:39,599 --> 00:01:42,320
為什麼沒有一個空的背景的原因

55
00:01:42,320 --> 00:01:46,000
因為我們是用 Triplic 就直接抓過去

56
00:01:46,000 --> 00:01:47,120
你直接抓的話

57
00:01:47,120 --> 00:01:50,559
就像這個三角形它是依賴於這個圈

58
00:01:50,559 --> 00:01:52,040
其實我只是覺得很奇怪

59
00:01:52,040 --> 00:01:54,360
當初為什麼 Alpha、Beta、Production

60
00:01:54,360 --> 00:01:55,919
都用 Triplic

61
00:01:55,919 --> 00:01:57,320
我也不知道

62
00:01:57,320 --> 00:01:59,839
我覺得原因在這個 Row 很奇怪

63
00:01:59,839 --> 00:02:02,000
對對對它應該有一個緣由

64
00:02:02,000 --> 00:02:03,800
對好但是我先解釋一下

65
00:02:03,800 --> 00:02:04,959
因為現在遇到的狀況是這樣

66
00:02:04,959 --> 00:02:06,559
所以我們每次上版的時候

67
00:02:06,559 --> 00:02:08,000
其實是用挑的

68
00:02:08,000 --> 00:02:09,080
那用挑的就會有依賴問題

69
00:02:09,080 --> 00:02:10,119
對這非常奇怪

70
00:02:10,119 --> 00:02:11,360
我們不用談這個了

71
00:02:11,360 --> 00:02:12,679
直接談新的

72
00:02:12,679 --> 00:02:13,679
這個一定有問題

73
00:02:13,679 --> 00:02:14,639
對對對

74
00:02:14,639 --> 00:02:15,399
對一定 Row 嘛

75
00:02:15,399 --> 00:02:16,720
所以我們很常 Row

76
00:02:16,720 --> 00:02:18,080
所以寶哥才會有疑問

77
00:02:18,080 --> 00:02:19,559
為什麼我們上到 Alpha 的東西

78
00:02:19,559 --> 00:02:21,399
Beta 還會重現

79
00:02:21,399 --> 00:02:22,399
那 Beta 會怎樣

80
00:02:22,399 --> 00:02:24,119
我相信 Production

81
00:02:24,119 --> 00:02:24,759
對吧

82
00:02:24,800 --> 00:02:26,240
那 Production 就不好看

83
00:02:26,240 --> 00:02:27,600
對我也覺得很奇怪

84
00:02:27,600 --> 00:02:29,479
因為我用 Control 就很奇怪

85
00:02:29,479 --> 00:02:30,320
對好

86
00:02:30,320 --> 00:02:32,919
那我們講一下未來的開發流程

87
00:02:32,919 --> 00:02:33,919
那未來我們開發流程

88
00:02:33,919 --> 00:02:36,199
我們主要會先從開發線

89
00:02:36,199 --> 00:02:37,679
那在我們公司看到 Main

90
00:02:37,679 --> 00:02:39,320
然後我們先從 Main 裡面

91
00:02:39,320 --> 00:02:40,240
我們在開單的時候

92
00:02:40,240 --> 00:02:42,960
會開一個叫 Epic 的單

93
00:02:42,960 --> 00:02:46,639
然後 Epic 下面可能會有數個 Story 單

94
00:02:46,639 --> 00:02:47,960
那我在這邊

95
00:02:47,960 --> 00:02:49,440
就是我這邊有兩條線

96
00:02:49,440 --> 00:02:51,600
一個叫 Epic 一個叫 Story

97
00:02:51,600 --> 00:02:56,800
那我從 Main 開一個 Epic 之後

98
00:02:56,800 --> 00:02:58,720
我會從這邊開數個 Story

99
00:02:58,720 --> 00:03:01,679
因為一個 Epic 裡面有很多個 Story

100
00:03:01,679 --> 00:03:02,880
比方說我們這次要做的東西

101
00:03:02,880 --> 00:03:04,119
叫 Revolutionary Center

102
00:03:04,119 --> 00:03:05,119
它雖然是一個 Epic

103
00:03:05,119 --> 00:03:07,039
可是它裡面有很多個 Story

104
00:03:07,039 --> 00:03:09,360
所以我就會從 Epic 裡面開很多個 Story

105
00:03:09,360 --> 00:03:10,720
然後它做完的時候

106
00:03:10,720 --> 00:03:11,800
它就會 Replace 回去

107
00:03:11,800 --> 00:03:13,240
就是我這邊做了三個點

108
00:03:13,240 --> 00:03:14,679
它這邊會回復三個點

109
00:03:14,679 --> 00:03:17,600
那經過幾個禮拜或是幾個月做完之後

110
00:03:17,600 --> 00:03:20,679
我們最終會把這個東西拉出去

111
00:03:20,679 --> 00:03:22,919
拉到一個叫做 Release 的分支線

112
00:03:22,919 --> 00:03:25,759
也就是你們看到的 Story 右邊的那一條

113
00:03:25,759 --> 00:03:27,000
拉出去的這個動作

114
00:03:27,000 --> 00:03:28,559
我們要 Merge 來做

115
00:03:28,559 --> 00:03:29,679
這是跟之前不太一樣

116
00:03:29,679 --> 00:03:30,839
我們之前都是用 Replace

117
00:03:30,839 --> 00:03:32,800
就是你這邊當初做了幾個點

118
00:03:32,800 --> 00:03:35,119
你在開發線只有幾個點

119
00:03:35,119 --> 00:03:36,759
那這樣的好處是

120
00:03:36,759 --> 00:03:39,679
你可以一覽無遺看到全部的點在這邊

121
00:03:39,679 --> 00:03:40,679
可是它的缺點就是

122
00:03:40,679 --> 00:03:42,679
如果我們抓的時候就有可能漏抓

123
00:03:42,679 --> 00:03:44,639
比方說你漏抓了一個單角

124
00:03:44,639 --> 00:03:45,160
對吧

125
00:03:45,160 --> 00:03:46,320
可是如果你是 Merge 的話

126
00:03:46,320 --> 00:03:49,000
你等於是把三個點折成一個點

127
00:03:49,000 --> 00:03:50,279
所以你只要移動這個點

128
00:03:50,279 --> 00:03:52,039
那過門都會有一點點

129
00:03:52,039 --> 00:03:52,720
這是重點

130
00:03:52,720 --> 00:03:53,119
對

131
00:03:53,119 --> 00:03:53,479
好

132
00:03:53,479 --> 00:03:54,320
那這是重點

133
00:03:54,320 --> 00:03:55,759
那我們 Merge 過去之後

134
00:03:55,759 --> 00:03:57,199
我們就馬上打一個版號

135
00:03:57,199 --> 00:04:01,479
那那個版號它叫做 1.0.0A1

136
00:04:01,479 --> 00:04:03,720
那 1.0.0 就是我們這次要上的版號

137
00:04:03,720 --> 00:04:08,440
那 A1 的意思就是 Alpha 的第一版

138
00:04:08,440 --> 00:04:09,399
Alpha 的第一版

139
00:04:09,399 --> 00:04:10,479
那想當然了

140
00:04:10,479 --> 00:04:13,240
上 Alpha 第一版一定不可能完全沒問題

141
00:04:13,240 --> 00:04:14,240
所以我們還會再修

142
00:04:14,240 --> 00:04:15,800
那我們旁邊還會再拉一條線

143
00:04:15,800 --> 00:04:16,839
就是修正線

144
00:04:16,839 --> 00:04:18,119
那這個修正線我們就修修修

145
00:04:18,119 --> 00:04:20,600
修完之後我們會再合併回去

146
00:04:20,600 --> 00:04:21,880
然後會再發一個版號

147
00:04:21,880 --> 00:04:24,119
這叫做 1.0.0A2

148
00:04:24,119 --> 00:04:26,799
那顧名思義它是 Alpha 的第二版

149
00:04:26,799 --> 00:04:27,160
好

150
00:04:27,160 --> 00:04:29,880
以此類推可能會到 A3、A4、A5

151
00:04:29,880 --> 00:04:30,799
經過幾輪之後

152
00:04:30,799 --> 00:04:31,799
我們終於要上 Beta

153
00:04:31,799 --> 00:04:32,279
對吧

154
00:04:32,279 --> 00:04:34,239
我們就在同一條鋁製線

155
00:04:34,239 --> 00:04:37,359
開一條 1.0.0B1

156
00:04:37,359 --> 00:04:40,160
意思就是在 Beta 上的第一版

157
00:04:40,160 --> 00:04:41,160
然後以此類推

158
00:04:41,160 --> 00:04:42,200
如果有需要修正

159
00:04:42,200 --> 00:04:42,760
再繼續修正

160
00:04:42,760 --> 00:04:43,640
繼續打版號

161
00:04:43,640 --> 00:04:45,720
1.0.0B2

162
00:04:45,720 --> 00:04:46,359
OK

163
00:04:46,399 --> 00:04:48,920
然後最終我們在 Beta 也都修正了

164
00:04:48,920 --> 00:04:49,920
完全沒有問題了

165
00:04:49,920 --> 00:04:51,160
我們這時候要發版

166
00:04:51,160 --> 00:04:52,000
發到 Production

167
00:04:52,000 --> 00:04:54,640
然後這個時候我們就拉出去一條

168
00:04:54,640 --> 00:04:55,600
叫 Production 線

169
00:04:55,600 --> 00:04:58,720
應該說把它合併到 Production 線

170
00:04:58,720 --> 00:05:00,000
大家有注意到

171
00:05:00,000 --> 00:05:02,839
在未來的發版流程裡面

172
00:05:02,839 --> 00:05:04,920
只有 Main 跟 Production 是黑色的線

173
00:05:04,920 --> 00:05:06,600
也就是這兩條是常駐線

174
00:05:06,600 --> 00:05:08,839
其他東西右腕擠丟

175
00:05:08,839 --> 00:05:12,279
就是如果我今天 merge 到 Production 線之後

176
00:05:12,279 --> 00:05:14,559
那我就會把我的 reset 給砍掉

177
00:05:14,559 --> 00:05:15,320
這條線給砍掉

178
00:05:15,320 --> 00:05:16,600
因為它已經發版了

179
00:05:16,600 --> 00:05:18,679
那我在 merge 到 Production 的時候

180
00:05:18,679 --> 00:05:20,720
我同時也會把做好的東西

181
00:05:20,720 --> 00:05:23,000
把它合回去把模型處理

182
00:05:23,000 --> 00:05:24,279
對啊 我想說怎麼合回去

183
00:05:24,279 --> 00:05:26,880
對 它應該是到 Main 才對

184
00:05:26,880 --> 00:05:30,279
所以它應該會到一個

185
00:05:30,279 --> 00:05:31,640
Production 才到 Main

186
00:05:31,640 --> 00:05:32,200
沒錯

187
00:05:32,200 --> 00:05:33,640
太擠了

188
00:05:33,640 --> 00:05:36,359
這個等一下我解釋

189
00:05:36,359 --> 00:05:37,480
好 謝謝

190
00:05:37,480 --> 00:05:38,480
好

191
00:05:38,480 --> 00:05:39,600
這個這樣做是有原因的

192
00:05:39,600 --> 00:05:40,959
是因為

193
00:05:43,799 --> 00:05:44,320
好

194
00:05:44,359 --> 00:05:46,880
然後我先接著先繼續講完

195
00:05:46,880 --> 00:05:48,959
然後接著我們上到 Production 之後

196
00:05:48,959 --> 00:05:51,040
然後會把它再合回開發線

197
00:05:51,040 --> 00:05:52,959
然後當然中間如果有問題

198
00:05:52,959 --> 00:05:54,239
我們會開發之前

199
00:05:54,239 --> 00:05:55,839
然後再把它合到 Production

200
00:05:55,839 --> 00:05:57,920
那只要合到 Production

201
00:05:57,920 --> 00:06:00,799
它就要順便再合回開發線

202
00:06:00,799 --> 00:06:01,279
對

203
00:06:01,279 --> 00:06:02,880
那至於剛剛 Emily 提到說

204
00:06:02,880 --> 00:06:04,760
太久的問題就是因為我們做的東西

205
00:06:04,760 --> 00:06:05,839
因為它是一個完整的功能

206
00:06:05,839 --> 00:06:07,440
所以它原本就會出去比較久

207
00:06:07,440 --> 00:06:09,279
如果除非有個情況是

208
00:06:09,279 --> 00:06:11,200
你接下來要做的東西

209
00:06:11,200 --> 00:06:16,640
你要依賴你即將發版的東西的話

210
00:06:16,640 --> 00:06:20,160
那我們可能還會拖得比較快

211
00:06:20,160 --> 00:06:21,279
好 我先講

212
00:06:21,279 --> 00:06:23,679
這個東西還有一個可能遇到的問題是

213
00:06:23,679 --> 00:06:25,200
如果同時有多個 EPIC 在

214
00:06:25,200 --> 00:06:26,640
沒錯 是的

215
00:06:26,640 --> 00:06:29,279
所以這一條我是用一個 EPIC 來講

216
00:06:29,279 --> 00:06:30,239
所以大家去想像

217
00:06:30,239 --> 00:06:31,760
如果多個 EPIC

218
00:06:31,760 --> 00:06:32,880
它其實是多維

219
00:06:32,880 --> 00:06:34,000
它同時進行

220
00:06:34,000 --> 00:06:36,320
對 然後到時候 Merge 就會很痛苦

221
00:06:36,320 --> 00:06:36,959
不會痛苦

222
00:06:36,959 --> 00:06:38,559
因為我是用 Merge

223
00:06:38,559 --> 00:06:39,359
我不是用 Epic

224
00:06:39,359 --> 00:06:41,359
那是因為你們中間的 Code

225
00:06:41,359 --> 00:06:43,119
Config 很少的時候

226
00:06:43,119 --> 00:06:44,480
我是不知道你們

227
00:06:44,480 --> 00:06:45,279
舉例來講

228
00:06:45,279 --> 00:06:46,399
以我們 Backend 的狀況

229
00:06:46,399 --> 00:06:49,279
我們一定會有多個的同時改動的檔案

230
00:06:49,279 --> 00:06:50,959
那這樣就會痛苦

231
00:06:50,959 --> 00:06:54,239
對 可是因為我之所以強調用 Merge 的原因

232
00:06:54,239 --> 00:06:54,799
就是因為

233
00:06:54,799 --> 00:06:56,720
我們要至少同一個檔案都要修一次

234
00:06:56,720 --> 00:06:57,920
對 沒有錯

235
00:06:57,920 --> 00:06:58,880
你用 Rebase

236
00:06:58,880 --> 00:06:59,920
我不知道修到多久

237
00:06:59,920 --> 00:07:01,440
所以我先講一下

238
00:07:01,440 --> 00:07:03,040
我們那次採用的做法是

239
00:07:03,040 --> 00:07:06,239
都一直進 Map

240
00:07:06,239 --> 00:07:09,040
然後只是這樣當然會遇到一個問題

241
00:07:09,040 --> 00:07:10,640
就是反向的

242
00:07:10,640 --> 00:07:12,640
我同時在做一個 Feature

243
00:07:12,640 --> 00:07:14,320
ABCD 在做四個 Feature

244
00:07:14,320 --> 00:07:15,679
都跑在 Map 上面

245
00:07:15,679 --> 00:07:18,399
然後這個時候可能只有 A 先做好了

246
00:07:18,399 --> 00:07:19,519
A 要先 Release

247
00:07:19,519 --> 00:07:22,320
結果 BCD 還沒做好

248
00:07:22,320 --> 00:07:24,720
那這個時候就要確保說

249
00:07:24,720 --> 00:07:26,880
這個東西 BCD 做到一半的東西

250
00:07:26,880 --> 00:07:30,559
不會影響到正常的 Release 的東西

251
00:07:30,559 --> 00:07:31,839
那所以以 Backend 來講

252
00:07:31,839 --> 00:07:32,959
我們是這樣做的

253
00:07:32,959 --> 00:07:35,040
或者是如果真的需要的話

254
00:07:35,040 --> 00:07:37,040
就是用個 Feature Tagger

255
00:07:37,040 --> 00:07:37,519
沒錯

256
00:07:37,519 --> 00:07:39,920
然後就是看什麼時候再去把它打開

257
00:07:39,920 --> 00:07:41,920
那全部都一直合為 Map

258
00:07:41,920 --> 00:07:43,920
然後大家就是邊開發邊 Merge

259
00:07:43,920 --> 00:07:45,519
然後大家都一起去做

260
00:07:45,519 --> 00:07:47,040
其實這邊有個關鍵點

261
00:07:47,040 --> 00:07:49,679
就是在於你何時開這些 Feature

262
00:07:49,679 --> 00:07:53,040
大家有看到未來發版流程裡面有個 APIC 線嗎

263
00:07:53,040 --> 00:07:56,320
這個 APIC 線你可以發現它其實有很多 APIC

264
00:07:56,320 --> 00:07:57,519
那我們做好之後

265
00:07:57,519 --> 00:07:58,239
如果你要合

266
00:07:58,239 --> 00:07:59,279
你可以不要合

267
00:07:59,279 --> 00:08:00,480
就放在這裡

268
00:08:00,480 --> 00:08:01,920
你需要合的時候

269
00:08:01,920 --> 00:08:04,959
那你再把它合到對應的 Release

270
00:08:04,959 --> 00:08:07,200
這樣子我們就可以完全控制說

271
00:08:07,200 --> 00:08:09,440
今天哪個檔案我們要上

272
00:08:09,440 --> 00:08:11,760
我覺得看你們

273
00:08:11,760 --> 00:08:14,320
那我說以我們 Backend 的例子來講

274
00:08:14,320 --> 00:08:17,600
因為我們會有非常多開發同的檔案的狀況

275
00:08:17,600 --> 00:08:19,040
或者是在做

276
00:08:19,040 --> 00:08:19,679
舉例來講

277
00:08:19,679 --> 00:08:22,559
我們還可能做一些 Structure 的 Refactor

278
00:08:22,559 --> 00:08:26,000
那那種東西絕對是會有很多 Conflict 產生

279
00:08:26,000 --> 00:08:28,000
所以如果可以 Merge

280
00:08:28,000 --> 00:08:30,160
為 Main 的速度比較快的話

281
00:08:30,160 --> 00:08:36,320
會好處就是會減少到時候 Merge 時候的那些困擾

282
00:08:36,320 --> 00:08:38,000
就是它會比較早快

283
00:08:38,000 --> 00:08:38,880
比較快發生

284
00:08:38,880 --> 00:08:39,919
然後比較快

285
00:08:39,919 --> 00:08:42,799
就是小部分小部分小部分就已經 Merge 了

286
00:08:42,799 --> 00:08:45,039
就不會到時候一大波很可怕

287
00:08:45,039 --> 00:08:46,400
類似像這種狀況

288
00:08:46,400 --> 00:08:47,679
那以我們 Backend 來講

289
00:08:47,679 --> 00:08:48,799
我們的生態是這樣

290
00:08:48,799 --> 00:08:51,840
所以我們會採用那樣子的一個開發流程

291
00:08:51,840 --> 00:08:53,200
那我就

292
00:08:53,200 --> 00:08:54,479
所以我是說

293
00:08:54,479 --> 00:08:57,280
看你們 Frontend 的開發流程是怎麼樣

294
00:08:57,280 --> 00:08:59,280
其實如果是像你說像這種的話

295
00:08:59,280 --> 00:09:01,039
你其實在 Release 的時候

296
00:09:01,039 --> 00:09:02,400
Release 就可以合

297
00:09:02,400 --> 00:09:04,960
比如說我下一個版本一定是會進 APAC

298
00:09:05,679 --> 00:09:07,359
或者是 Alpha

299
00:09:07,359 --> 00:09:09,039
Alpha 就合

300
00:09:09,039 --> 00:09:10,880
可是你們的 Alpha 就合

301
00:09:10,880 --> 00:09:13,440
當然是前提是 Alpha 不要太久

302
00:09:13,440 --> 00:09:16,080
那我們可能光是一個 AlphaStoring

303
00:09:16,080 --> 00:09:17,919
每個 Storing 都會不停 Conflict

304
00:09:17,919 --> 00:09:20,080
所以我們其實不一定等到 Alpha 再合

305
00:09:20,080 --> 00:09:21,679
所以我們採用的就是

306
00:09:21,679 --> 00:09:24,159
每一個 PR 就不停的進 Main

307
00:09:24,159 --> 00:09:25,919
我們的做法是這樣

308
00:09:25,919 --> 00:09:27,520
那可是就是確保說

309
00:09:27,520 --> 00:09:30,799
Partial Release 的時候不會有問題就好了

310
00:09:30,799 --> 00:09:33,440
這就是另外一層要去顧慮的地方

311
00:09:33,520 --> 00:09:36,479
那你們這樣的做法當然就是 Conflict 的時候

312
00:09:36,479 --> 00:09:37,359
可能比較多

313
00:09:37,359 --> 00:09:39,039
那就是看你們選擇

314
00:09:39,039 --> 00:09:40,559
不是給你們自己去決定

315
00:09:40,559 --> 00:09:43,599
我覺得主要要解決的問題是功能性的整合

316
00:09:43,599 --> 00:09:45,760
就是你在發版的時候

317
00:09:45,760 --> 00:09:46,719
我們的所有功能

318
00:09:46,719 --> 00:09:49,359
就是屬於這個功能的所有 Conflict

319
00:09:49,359 --> 00:09:51,200
都必須在發版的那個點

320
00:09:51,200 --> 00:09:52,559
今天要解決的問題

321
00:09:52,559 --> 00:09:53,679
然後還有另外一個問題就是

322
00:09:53,679 --> 00:09:54,640
我做好之後

323
00:09:54,640 --> 00:09:56,559
我有沒有選擇的方式

324
00:09:56,559 --> 00:09:58,000
要選擇哪些功能要上

325
00:09:58,000 --> 00:09:59,119
哪些功能不要上

326
00:09:59,119 --> 00:10:00,960
那因為我們之前是有這種方式

327
00:10:00,960 --> 00:10:02,960
所以等於是你要挑功能的時候

328
00:10:02,960 --> 00:10:04,000
我覺得那個很奇怪

329
00:10:04,000 --> 00:10:04,479
我不要講

330
00:10:04,479 --> 00:10:04,880
對對對

331
00:10:04,880 --> 00:10:06,960
所以那既然

332
00:10:06,960 --> 00:10:08,239
就是因為它的特色就是

333
00:10:08,239 --> 00:10:09,599
因為它折合會比較久

334
00:10:09,599 --> 00:10:11,679
所以我們在挑點的時候就很好挑

335
00:10:11,679 --> 00:10:13,359
比方說我們發版

336
00:10:13,359 --> 00:10:15,119
這個東西它有一整包功能

337
00:10:15,119 --> 00:10:17,359
所以你今天要把它上到哪個地方去挑

338
00:10:17,359 --> 00:10:19,359
我建議最好是

339
00:10:19,359 --> 00:10:20,400
我會傾向

340
00:10:20,400 --> 00:10:21,679
如果你們覺得這樣 OK

341
00:10:21,679 --> 00:10:24,880
我也是會覺得 Alpha 就合是比較好的

342
00:10:24,880 --> 00:10:26,719
你說到 Release 就合

343
00:10:26,719 --> 00:10:28,080
Release 到 Alpha

344
00:10:28,080 --> 00:10:29,359
就是 Alpha Release 就合

345
00:10:29,359 --> 00:10:29,840
你的意思是說

346
00:10:29,840 --> 00:10:31,039
它只要每次有 Peg 就合

347
00:10:31,039 --> 00:10:31,919
對對對

348
00:10:32,000 --> 00:10:34,799
就是當你要給 QA 的時候

349
00:10:34,799 --> 00:10:35,840
你就先給 QA 回去

350
00:10:35,840 --> 00:10:36,400
可以啊

351
00:10:36,400 --> 00:10:37,440
可以啊

352
00:10:37,440 --> 00:10:39,919
就不要等到 Product 才合

353
00:10:39,919 --> 00:10:40,640
我另外問的

354
00:10:40,640 --> 00:10:43,440
如果你們整個測試在 DEV 的時候

355
00:10:43,440 --> 00:10:44,479
你們是顧哪一條

356
00:10:46,479 --> 00:10:47,919
每個人顧自己的

357
00:10:47,919 --> 00:10:49,200
自己的

358
00:10:49,200 --> 00:10:50,559
自己的 APIC

359
00:10:50,559 --> 00:10:51,919
那就會有 N 條

360
00:10:51,919 --> 00:10:53,679
其實對會有個 N 條

361
00:10:53,679 --> 00:10:55,919
就是主要是這條 APIC 線

362
00:10:55,919 --> 00:10:56,960
那 APIC 線會做不到

363
00:10:56,960 --> 00:10:58,159
假設我做 A 功能

364
00:10:58,159 --> 00:10:59,679
那 DEV 現在是只有 A 功能

365
00:10:59,679 --> 00:11:00,799
那如果你做 B 功能

366
00:11:01,039 --> 00:11:02,559
我的意思是

367
00:11:02,559 --> 00:11:03,520
在 CIC 的時候

368
00:11:03,520 --> 00:11:05,280
部屬是顧哪一個 Branch

369
00:11:07,119 --> 00:11:07,919
如果是

370
00:11:07,919 --> 00:11:09,520
現在的話是顧 Main

371
00:11:09,520 --> 00:11:10,960
但是之後的話

372
00:11:10,960 --> 00:11:12,000
應該就是顧 Main

373
00:11:14,000 --> 00:11:14,880
顧這個

374
00:11:14,880 --> 00:11:16,159
好多個 APIC

375
00:11:16,159 --> 00:11:16,559
對啊

376
00:11:16,559 --> 00:11:17,280
所以就是

377
00:11:17,280 --> 00:11:18,799
所以就是如果我說 A 功能

378
00:11:18,799 --> 00:11:20,400
那今天 DEV 就只有這樣

379
00:11:20,400 --> 00:11:20,960
我講一下

380
00:11:20,960 --> 00:11:21,599
我認知是

381
00:11:21,599 --> 00:11:23,679
這邊可能會再開一個 DEV 的分支

382
00:11:23,679 --> 00:11:25,119
我今天要驗哪個功能

383
00:11:25,119 --> 00:11:26,799
我就可以從 Release 直接就過來

384
00:11:26,799 --> 00:11:28,239
然後這 DEV 隨時可以砍掉

385
00:11:29,200 --> 00:11:31,200
我的想法會是這樣

386
00:11:31,200 --> 00:11:33,280
那這樣跟我說的也沒有什麼差別

387
00:11:33,280 --> 00:11:33,760
差不多

388
00:11:33,760 --> 00:11:34,479
也沒有差別

389
00:11:34,479 --> 00:11:36,159
就是你今天什麼東西上到 APIC

390
00:11:36,159 --> 00:11:37,039
可是我要講的是

391
00:11:37,039 --> 00:11:38,640
跟後端整合的時候

392
00:11:38,640 --> 00:11:40,400
的環境

393
00:11:40,400 --> 00:11:41,200
你說 DEV

394
00:11:41,200 --> 00:11:41,679
對

395
00:11:44,479 --> 00:11:46,479
那所以就是我們在開 APIC 的時候

396
00:11:46,479 --> 00:11:47,679
我們必須把

397
00:11:47,679 --> 00:11:50,239
一個 APIC 裡面就是整到非常不可能的東西

398
00:11:50,239 --> 00:11:51,440
不可以從中間拉出

399
00:11:51,440 --> 00:11:52,799
中間往下上往下不上

400
00:11:52,799 --> 00:11:53,280
對不對

401
00:11:53,280 --> 00:11:54,080
我們就盡量

402
00:11:54,080 --> 00:11:57,679
你訂好的 APIC 跟 Story

403
00:11:57,679 --> 00:11:59,119
就是那些東西

404
00:11:59,119 --> 00:12:00,479
所以正常來講

405
00:12:00,479 --> 00:12:03,599
New Feature 不應該突然從一個 APIC 拉出來

406
00:12:03,599 --> 00:12:04,799
那個就是另外一個 APIC

407
00:12:04,799 --> 00:12:05,440
因為是

408
00:12:05,440 --> 00:12:07,440
我想到一個狀況是像

409
00:12:07,440 --> 00:12:08,640
Redmi 7 當然沒有問題

410
00:12:08,640 --> 00:12:10,239
我們訂好的 APIC 就是這個

411
00:12:10,239 --> 00:12:11,440
可是同時進版的時候

412
00:12:11,440 --> 00:12:13,760
還會有會拉一些官方的 Ticket

413
00:12:13,760 --> 00:12:15,679
或是 Captain 的 Ticket

414
00:12:15,679 --> 00:12:18,400
那這 Ticket 假設來不及上

415
00:12:18,400 --> 00:12:20,960
或者是假設他們急著要上

416
00:12:20,960 --> 00:12:21,440
那可能會

417
00:12:21,440 --> 00:12:26,000
理論上我覺得 Ticket 跟 APIC 應該開開啦

418
00:12:26,000 --> 00:12:27,359
或者是你覺得它上不了

419
00:12:27,359 --> 00:12:28,880
你把它移到另外一個 APIC

420
00:12:28,880 --> 00:12:31,520
所以我現在其實是拆開不同的 APIC

421
00:12:31,520 --> 00:12:32,159
對對對

422
00:12:32,159 --> 00:12:32,719
這個甚至

423
00:12:32,719 --> 00:12:34,239
因為每個 Ticket 上的時間不一樣

424
00:12:34,239 --> 00:12:36,960
我只好把每一個 Ticket 拆成不同的 APIC

425
00:12:36,960 --> 00:12:39,119
因為有時候他們的文化圓滿

426
00:12:39,119 --> 00:12:40,000
剛好這一邊

427
00:12:40,000 --> 00:12:41,599
所以我現在

428
00:12:41,599 --> 00:12:43,359
所以我的 APIC 這邊其實不會開個

429
00:12:43,359 --> 00:12:44,159
去往下

430
00:12:44,159 --> 00:12:45,280
有可能進版的時候

431
00:12:45,280 --> 00:12:46,159
APIC 會有問題

432
00:12:46,159 --> 00:12:46,960
對對對

433
00:12:46,960 --> 00:12:48,159
那既然

434
00:12:48,159 --> 00:12:50,080
反正我們做好一個 APIC 了之後

435
00:12:50,080 --> 00:12:53,119
我們本來就可以決定它要上

436
00:12:53,119 --> 00:12:54,960
那我會建議你可能

437
00:12:54,960 --> 00:12:55,760
針對 Ticket

438
00:12:55,760 --> 00:12:58,000
你可以叫做用 Spring

439
00:12:58,000 --> 00:12:59,280
譬如說 Phase 1

440
00:12:59,280 --> 00:13:01,760
就是譬如說叫做 Regression Phase 1

441
00:13:01,760 --> 00:13:03,760
那這裡面就是

442
00:13:03,760 --> 00:13:05,440
假設本來 10 個 Ticket

443
00:13:05,440 --> 00:13:07,440
然後你只是拉掉 5 個

444
00:13:07,440 --> 00:13:08,880
變成只有 5 個一起上

445
00:13:08,880 --> 00:13:11,039
那它至少還是同一次 Release

446
00:13:11,039 --> 00:13:12,880
會 Cover 到的還是一個 Ticket

447
00:13:12,880 --> 00:13:16,000
不用到一個 Ticket 一個 APIC 太累了

448
00:13:16,000 --> 00:13:17,440
對

449
00:13:17,440 --> 00:13:18,880
那中央開一個 APIC

450
00:13:18,880 --> 00:13:20,960
然後我可能一個 Bypass

451
00:13:20,960 --> 00:13:22,159
然後還有 Phase 4

452
00:13:22,159 --> 00:13:24,479
就是按照 Release 的 Tempo

453
00:13:24,479 --> 00:13:25,840
去開 APIC

454
00:13:25,840 --> 00:13:27,200
好

455
00:13:27,200 --> 00:13:29,119
然後因為我們過去的版號

456
00:13:29,119 --> 00:13:32,320
都是什麼 1.1.32

457
00:13:32,320 --> 00:13:35,039
那我想把未來的版號把它改成

458
00:13:35,039 --> 00:13:36,080
因為加 A 跟 B

459
00:13:36,080 --> 00:13:37,280
就是讓大家清楚

460
00:13:37,280 --> 00:13:38,559
它就是 Alpha 第幾版

461
00:13:38,559 --> 00:13:39,520
Beta 第幾版

462
00:13:39,520 --> 00:13:40,479
因為我們現有的

463
00:13:40,479 --> 00:13:41,840
我們 1.32.

464
00:13:41,840 --> 00:13:44,000
我哪知道它代表什麼意思

465
00:13:44,000 --> 00:13:46,000
你知道它是版號的推進

466
00:13:46,000 --> 00:13:48,479
可是你看不出它其實是在哪一個環境

467
00:13:48,479 --> 00:13:49,679
然後多少版本

468
00:13:49,679 --> 00:13:51,679
那所以

469
00:13:51,679 --> 00:13:53,440
大家可以看到最右邊有個主版號

470
00:13:53,440 --> 00:13:55,440
然後還有功能版號跟修正版號

471
00:13:55,440 --> 00:13:56,479
那基本上主版號

472
00:13:56,479 --> 00:13:57,599
可是我會希望說

473
00:13:57,599 --> 00:13:59,599
我是不知道你的 A1、A2

474
00:13:59,599 --> 00:14:01,599
如果你單純是要分

475
00:14:01,599 --> 00:14:03,599
A、B、C 的話

476
00:14:03,599 --> 00:14:05,119
只有 A 跟 B

477
00:14:05,119 --> 00:14:06,159
好,A 跟 B 的話

478
00:14:06,159 --> 00:14:07,679
我的想法是

479
00:14:07,679 --> 00:14:09,119
如果是同一個卡密

480
00:14:09,119 --> 00:14:10,719
譬如說來的你應該

481
00:14:10,719 --> 00:14:13,280
譬如說就是 1.0.1A

482
00:14:13,280 --> 00:14:16,000
跟 1.0.1B

483
00:14:16,000 --> 00:14:17,280
前面的數字

484
00:14:17,280 --> 00:14:18,799
如果是同一個卡密的話

485
00:14:18,799 --> 00:14:20,320
它的數字應該要一樣

486
00:14:20,320 --> 00:14:21,359
這樣確保說

487
00:14:21,359 --> 00:14:23,359
你知道它們的版本是 match 的

488
00:14:23,359 --> 00:14:25,359
它是一樣 1.0.1

489
00:14:25,359 --> 00:14:27,359
是看我的 branch 名稱

490
00:14:27,359 --> 00:14:29,359
我的 branch 名稱跟 release 是 1.0.1

491
00:14:29,359 --> 00:14:31,359
所以在這條程式上

492
00:14:31,359 --> 00:14:33,359
不會有 1.0.1

493
00:14:33,359 --> 00:14:35,359
可是這樣我怎麼會知道說它的

494
00:14:35,359 --> 00:14:37,359
就是那可能

495
00:14:37,359 --> 00:14:39,359
後面有個卡

496
00:14:39,359 --> 00:14:41,359
就是看有沒有什麼 number

497
00:14:41,359 --> 00:14:43,359
它是 unique 的

498
00:14:43,359 --> 00:14:44,400
可以讓我知道

499
00:14:44,400 --> 00:14:45,359
要不然我的意思是說

500
00:14:45,359 --> 00:14:47,359
你這邊

501
00:14:47,359 --> 00:14:49,359
B1、B2 是什麼意思

502
00:14:49,359 --> 00:14:51,359
Beta 的 B

503
00:14:51,359 --> 00:14:53,359
那我想要知道的是

504
00:14:53,359 --> 00:14:55,359
那 B1 可不可以跟 A1 打在同個頁上

505
00:14:55,359 --> 00:14:57,359
因為我想要確認說

506
00:14:57,359 --> 00:14:59,359
這個 A1 跟 B1 是同個

507
00:14:59,359 --> 00:15:01,359
它們是同分

508
00:15:01,359 --> 00:15:03,359
好,我這樣講好了

509
00:15:03,359 --> 00:15:05,359
其實中間這個版號可以當成

510
00:15:05,359 --> 00:15:07,359
我如果進 Beta 我就進個版號

511
00:15:07,359 --> 00:15:09,359
譬如說我下禮拜

512
00:15:09,359 --> 00:15:11,359
給空量的 Beta

513
00:15:11,359 --> 00:15:13,359
我就 1.1.0

514
00:15:13,359 --> 00:15:15,359
那如果我在 Alpha 的話

515
00:15:15,359 --> 00:15:17,359
我就是 1.1.X

516
00:15:17,359 --> 00:15:19,359
是基於這個 Beta

517
00:15:19,359 --> 00:15:21,359
可是上了 Alpha 的東西

518
00:15:21,359 --> 00:15:23,359
上了 Beta 的東西

519
00:15:23,359 --> 00:15:25,359
你們還會再上 Alpha 嗎

520
00:15:25,359 --> 00:15:27,359
不會啊

521
00:15:27,359 --> 00:15:29,359
可是我要知道 Alpha 的有沒有上 Beta

522
00:15:29,359 --> 00:15:31,359
這個如果是走我這個流程的話

523
00:15:31,359 --> 00:15:33,359
你只要進了 Beta 就是一種 Beta

524
00:15:33,359 --> 00:15:35,359
可是 A2 跟 B1

525
00:15:35,359 --> 00:15:37,359
舉例來講

526
00:15:37,359 --> 00:15:39,359
它可能還有

527
00:15:39,359 --> 00:15:41,359
不一定耶

528
00:15:41,359 --> 00:15:43,359
為什麼上了 Alpha 影響 Beta

529
00:15:43,359 --> 00:15:45,359
我的意思是說

530
00:15:45,359 --> 00:15:47,359
你上了 Beta

531
00:15:47,359 --> 00:15:49,359
如果你上 Beta 才發現的問題

532
00:15:49,359 --> 00:15:51,359
你要修

533
00:15:51,359 --> 00:15:53,359
你是不是也要修在 Alpha 跟 Beta 上面

534
00:15:53,359 --> 00:15:55,359
那這時候你的版號長什麼樣

535
00:15:55,359 --> 00:15:57,359
那它就會叫 B3

536
00:15:57,359 --> 00:15:59,359
然後放在 Beta 跟 Alpha

537
00:15:59,359 --> 00:16:01,359
所以 Alpha 的版號

538
00:16:01,359 --> 00:16:03,359
也是 B3

539
00:16:03,359 --> 00:16:05,359
我有沒有 Console 上面

540
00:16:05,359 --> 00:16:07,359
可以看得到一個地方

541
00:16:07,359 --> 00:16:09,359
它是 B3 這樣

542
00:16:09,359 --> 00:16:11,359
我們的 GitHub 上在每一個 Server 上面

543
00:16:11,359 --> 00:16:13,359
有寫它現在的這個 Server

544
00:16:13,359 --> 00:16:15,359
是哪一個版號

545
00:16:15,359 --> 00:16:17,359
那我就沒有問題

546
00:16:17,359 --> 00:16:19,359
因為我只要確保它們兩個

547
00:16:19,359 --> 00:16:21,359
可以讓我知道它們兩個是同一個版號

548
00:16:21,359 --> 00:16:23,359
我知道

549
00:16:23,359 --> 00:16:25,359
因為你在 Beta 上修這個東西

550
00:16:25,359 --> 00:16:27,359
你修 Alpha 也沒問題

551
00:16:27,359 --> 00:16:29,359
可是我

552
00:16:29,359 --> 00:16:31,359
好

553
00:16:31,359 --> 00:16:33,359
沒問題

554
00:16:33,359 --> 00:16:35,359
還在測試

555
00:16:35,359 --> 00:16:37,359
這個可以

556
00:16:37,359 --> 00:16:39,359
反正你打了 Tag

557
00:16:39,359 --> 00:16:41,359
你要打到你的環境

558
00:16:41,359 --> 00:16:43,359
好

559
00:16:43,359 --> 00:16:45,359
好

560
00:16:45,359 --> 00:16:47,359
所以

561
00:16:47,359 --> 00:16:49,359
反正我們走這個流程的話

562
00:16:49,359 --> 00:16:51,359
那之後你做的東西

563
00:16:51,359 --> 00:16:53,359
如果你不記得上

564
00:16:53,359 --> 00:16:55,359
當你有需要

565
00:16:55,359 --> 00:16:57,359
你待會會知道

566
00:16:57,359 --> 00:16:59,359
是

567
00:16:59,359 --> 00:17:01,359
可是 Release 的情形

568
00:17:01,359 --> 00:17:03,359
有時候會這樣

569
00:17:03,359 --> 00:17:05,359
後端可以

570
00:17:05,359 --> 00:17:07,359
前端不行嗎

571
00:17:07,359 --> 00:17:09,359
前端也可以

572
00:17:09,359 --> 00:17:11,359
就看我們到時候

573
00:17:11,359 --> 00:17:13,359
如果我們到時候急著想要開發線

574
00:17:13,359 --> 00:17:15,359
也有不同的

575
00:17:15,359 --> 00:17:17,359
我舉個例子來講

576
00:17:17,359 --> 00:17:19,359
我想要這次的 Release 有兩個 Epic

577
00:17:19,359 --> 00:17:21,359
那基本上就是

578
00:17:21,359 --> 00:17:23,359
回到 Mate 一起 View Release

579
00:17:23,359 --> 00:17:25,359
所以我會覺得 Release 都是從 Mate 拉出去

580
00:17:25,359 --> 00:17:27,359
Release 有時候

581
00:17:27,359 --> 00:17:29,359
上

582
00:17:29,359 --> 00:17:31,359
可以

583
00:17:31,359 --> 00:17:33,359
這樣

584
00:17:33,359 --> 00:17:35,359
好

585
00:17:35,359 --> 00:17:37,359
結束

586
00:17:37,359 --> 00:17:39,359
你一定會先上可搭選

587
00:17:39,359 --> 00:17:41,359
你在可搭選發生問題一定是他發生問題

588
00:17:41,359 --> 00:17:43,359
所以你從這邊拉是沒有問題的

589
00:17:43,359 --> 00:17:45,359
不一定

590
00:17:45,359 --> 00:17:47,359
就是你從那邊拉的時候

591
00:17:47,359 --> 00:17:49,359
應該是說你 Mate 已經修復了

592
00:17:49,359 --> 00:17:51,359
你

593
00:17:51,359 --> 00:17:53,359
對

594
00:17:53,359 --> 00:17:55,359
那你

595
00:17:55,359 --> 00:17:57,359
如果你會發生這個問題

596
00:17:57,359 --> 00:17:59,359
你中間一定是錯的

597
00:17:59,359 --> 00:18:01,359
可是有可能你在這個底用錯

598
00:18:01,359 --> 00:18:03,359
可是不管怎麼樣

599
00:18:03,359 --> 00:18:05,359
都一定是在可搭選出錯

600
00:18:05,359 --> 00:18:07,359
你說這個點出錯

601
00:18:07,359 --> 00:18:09,359
可是你這邊本來就會

602
00:18:09,359 --> 00:18:11,359
發一個

603
00:18:11,359 --> 00:18:13,359
下一個版本上會進可搭選

604
00:18:13,359 --> 00:18:15,359
我的意思是你在這邊做了這個點

605
00:18:15,359 --> 00:18:17,359
然後你以為做對可是其實你做錯你沒發現

606
00:18:17,359 --> 00:18:19,359
然後你上可搭選你才發現

607
00:18:19,359 --> 00:18:21,359
做錯

608
00:18:21,359 --> 00:18:23,359
就是你做了這兩個點

609
00:18:23,359 --> 00:18:25,359
但是其實你弄錯

610
00:18:25,359 --> 00:18:27,359
那他的問題還是出在這一條線

611
00:18:27,359 --> 00:18:29,359
可是你不會發現

612
00:18:29,359 --> 00:18:31,359
你是上的時候你才發現

613
00:18:31,359 --> 00:18:33,359
當你上的時候

614
00:18:33,359 --> 00:18:35,359
所以你才需要

615
00:18:35,359 --> 00:18:37,359
從這邊拉

616
00:18:37,359 --> 00:18:39,359
是這樣

617
00:18:39,359 --> 00:18:41,359
你這上去他也會回去

618
00:18:41,359 --> 00:18:43,359
對可是問題是

619
00:18:43,359 --> 00:18:45,359
在這邊還沒有修正

620
00:18:45,359 --> 00:18:47,359
而且這條線已經被我砍掉

621
00:18:47,359 --> 00:18:49,359
他會上去你在砍掉之前他還是會回 Mate

622
00:18:49,359 --> 00:18:51,359
所以你在這邊下一個修正

623
00:18:51,359 --> 00:18:53,359
他的問題是從這邊拉出來沒有問題

624
00:18:53,359 --> 00:18:55,359
可是問題是你拉回 Mate 的時候

625
00:18:55,359 --> 00:18:57,359
這個時候問題還沒有解決

626
00:18:57,359 --> 00:18:59,359
對但是你會在可搭選被發現

627
00:18:59,359 --> 00:19:01,359
同時你的 Mate 也有包含這個

628
00:19:01,359 --> 00:19:03,359
所以從這邊拉是沒有問題的

629
00:19:03,359 --> 00:19:05,359
我剛剛講這樣子

630
00:19:05,359 --> 00:19:07,359
從這邊拉然後合併回去

631
00:19:07,359 --> 00:19:09,359
這個也很難講

632
00:19:09,359 --> 00:19:11,359
因為你的 Mate

633
00:19:11,359 --> 00:19:13,359
理論上可搭選有問題

634
00:19:13,359 --> 00:19:15,359
Mate 如果跟可搭選是一樣的東西

635
00:19:15,359 --> 00:19:17,359
當然就一樣都會發現問題

636
00:19:17,359 --> 00:19:19,359
可是有可能 Mate

637
00:19:19,359 --> 00:19:21,359
持續會有其他的 API 或 Story 去

638
00:19:21,359 --> 00:19:23,359
改所以他可能已經看不到

639
00:19:23,359 --> 00:19:25,359
那問題了可是這問題只有在

640
00:19:25,359 --> 00:19:27,359
可搭選才會看到

641
00:19:27,359 --> 00:19:29,359
都有可能啦

642
00:19:29,359 --> 00:19:31,359
不是你只有這件事情發辦的時候

643
00:19:31,359 --> 00:19:33,359
你才會合併 MateMate 才會被改變

644
00:19:33,359 --> 00:19:35,359
你不會任何行為

645
00:19:35,359 --> 00:19:37,359
直接去改到 Mate

646
00:19:37,359 --> 00:19:39,359
有啊你改那個 API

647
00:19:39,359 --> 00:19:41,359
你這個流程就不會有這個問題

648
00:19:41,359 --> 00:19:43,359
你有可能 Release 就回去

649
00:19:43,359 --> 00:19:45,359
Release 是回去沒有錯

650
00:19:45,359 --> 00:19:47,359
所以誰改 Mate

651
00:19:47,359 --> 00:19:49,359
誰就把手剁掉

652
00:19:49,359 --> 00:19:51,359
到時候工程師都沒手

653
00:19:51,359 --> 00:19:53,359
什麼什麼你說什麼

654
00:19:53,359 --> 00:19:55,359
你說不能在 Mate 上面修嗎

655
00:19:55,359 --> 00:19:57,359
對啊當然不行啊

656
00:19:57,359 --> 00:19:59,359
理論上不行

657
00:19:59,359 --> 00:20:01,359
你走這個流程就理論上不行

658
00:20:01,359 --> 00:20:03,359
你一定要開一個 Release 分支出來

659
00:20:03,359 --> 00:20:05,359
我們的行為是這樣

660
00:20:05,359 --> 00:20:07,359
就是沒有我們的行為是

661
00:20:07,359 --> 00:20:09,359
APIC 做完

662
00:20:09,359 --> 00:20:11,359
其實我們在 APIC 做完就

663
00:20:11,359 --> 00:20:13,359
順便取回來

664
00:20:13,359 --> 00:20:15,359
跟這個一樣

665
00:20:15,359 --> 00:20:17,359
不一樣

666
00:20:17,359 --> 00:20:19,359
可是我們 Release 一定是從這裡到這裡去

667
00:20:19,359 --> 00:20:21,359
不會 Pick

668
00:20:21,359 --> 00:20:23,359
他們現在這個問題是要解掉

669
00:20:23,359 --> 00:20:25,359
說有些要上有些不上

670
00:20:25,359 --> 00:20:27,359
我就是全拉

671
00:20:27,359 --> 00:20:29,359
還有漏抓的

672
00:20:29,359 --> 00:20:31,359
我就是全拉所以不會漏抓

673
00:20:31,359 --> 00:20:33,359
你全拉走左邊沒問題

674
00:20:33,359 --> 00:20:35,359
現在就是

675
00:20:35,359 --> 00:20:37,359
有一些東西是部分上部分不上

676
00:20:37,359 --> 00:20:39,359
所以才要用那種方式

677
00:20:47,359 --> 00:20:49,359
只要回到 Mate

678
00:20:49,359 --> 00:20:51,359
如果你是確定要 Release 的東西

679
00:20:51,359 --> 00:20:53,359
才會回到 Mate

680
00:20:53,359 --> 00:20:55,359
一定是要 Release 的東西才會回到 Mate

681
00:20:55,359 --> 00:20:57,359
然後你就都一起回到 Mate 之後再拉出來

682
00:20:57,359 --> 00:20:59,359
可是問題是

683
00:20:59,359 --> 00:21:01,359
如果是這樣子的話

684
00:21:01,359 --> 00:21:03,359
你就變成是我拉出去的東西

685
00:21:03,359 --> 00:21:05,359
不是只有我 APIC 的東西

686
00:21:05,359 --> 00:21:07,359
對啊

687
00:21:07,359 --> 00:21:09,359
因為我這次 Release 我就是 ABC

688
00:21:09,359 --> 00:21:11,359
但是我就是要避免

689
00:21:11,359 --> 00:21:13,359
不行啊

690
00:21:13,359 --> 00:21:15,359
QA 測我要同一包一起測啊

691
00:21:15,359 --> 00:21:17,359
你要同一包一起測

692
00:21:17,359 --> 00:21:19,359
那你那些 APIC 全部都要上

693
00:21:19,359 --> 00:21:21,359
對啊

694
00:21:21,359 --> 00:21:23,359
你會有很多 APIC

695
00:21:23,359 --> 00:21:25,359
比方說

696
00:21:25,359 --> 00:21:27,359
可是我說你可以先回到 Mate

697
00:21:27,359 --> 00:21:29,359
然後再拉出 Release

698
00:21:29,359 --> 00:21:31,359
可是你回到 Mate 的話

699
00:21:31,359 --> 00:21:33,359
你就會有一個空間

700
00:21:33,359 --> 00:21:35,359
不是我是說

701
00:21:35,359 --> 00:21:37,359
確定要 Release 的時候

702
00:21:37,359 --> 00:21:39,359
在那個時間點一起回到 Mate

703
00:21:39,359 --> 00:21:41,359
那是一樣意思

704
00:21:41,359 --> 00:21:43,359
你如果能確定這件事情

705
00:21:43,359 --> 00:21:45,359
是沒問題

706
00:21:45,359 --> 00:21:47,359
因為你現在不是也是確定要 Release 的才拉到 Release

707
00:21:47,359 --> 00:21:49,359
我覺得這一條可能要放在這邊

708
00:21:49,359 --> 00:21:51,359
對啊我的意思是這樣

709
00:21:51,359 --> 00:21:53,359
這條放在這邊

710
00:21:53,359 --> 00:21:55,359
這兩個點是從這個 Release 拉出來的

711
00:21:55,359 --> 00:21:57,359
對啊

712
00:21:57,359 --> 00:21:59,359
其實也是一樣的

713
00:21:59,359 --> 00:22:01,359
總之就是做這件事情

714
00:22:01,359 --> 00:22:03,359
就是為了要關注

715
00:22:03,359 --> 00:22:05,359
它的功能就是那個功能

716
00:22:05,359 --> 00:22:07,359
它沒有其他的

717
00:22:07,359 --> 00:22:09,359
有我們都是很多功能一起玩

718
00:22:09,359 --> 00:22:11,359
那如果有需要的功能

719
00:22:11,359 --> 00:22:13,359
你再把所有需要的 APIC 再把它拉到 Release

720
00:22:13,359 --> 00:22:15,359
在我的流程裡面是 Release

721
00:22:15,359 --> 00:22:17,359
在你的流程裡面可能是 Mate

722
00:22:17,359 --> 00:22:19,359
你要給我一條 Release 啊

723
00:22:19,359 --> 00:22:21,359
沒有啊

724
00:22:21,359 --> 00:22:23,359
就是這條

725
00:22:23,359 --> 00:22:25,359
你要把上的 APIC

726
00:22:25,359 --> 00:22:27,359
可是以後就會有很多 Release 的線

727
00:22:27,359 --> 00:22:29,359
而且你做完之後

728
00:22:29,359 --> 00:22:31,359
我們之前有想到

729
00:22:31,359 --> 00:22:33,359
我們這邊是會

730
00:22:33,359 --> 00:22:35,359
好像會比較傾向像 feature toggle 的方式

731
00:22:35,359 --> 00:22:37,359
用東西去改變

732
00:22:37,359 --> 00:22:39,359
對啊

733
00:22:39,359 --> 00:22:41,359
因為這樣就可以快速的 Merge

734
00:22:41,359 --> 00:22:43,359
回 Mate 這是最好的

735
00:22:43,359 --> 00:22:45,359
那你現在

736
00:22:45,359 --> 00:22:47,359
右邊這個

737
00:22:47,359 --> 00:22:49,359
我可以避免這件事情

738
00:22:49,359 --> 00:22:51,359
可是右邊這個

739
00:22:51,359 --> 00:22:53,359
會導致的問題

740
00:22:53,359 --> 00:22:55,359
就是 Merge 的時候辛苦

741
00:22:55,359 --> 00:22:57,359
因為都比較大包

742
00:22:57,359 --> 00:22:59,359
你會有很恐怖的 config

743
00:22:59,359 --> 00:23:01,359
都比較大包

744
00:23:01,359 --> 00:23:03,359
才會 Merge

745
00:23:03,359 --> 00:23:05,359
當然如果你們現在都沒有遇過這種困擾

746
00:23:05,359 --> 00:23:07,359
你們可能不知道

747
00:23:07,359 --> 00:23:09,359
可能沒有遇過

748
00:23:09,359 --> 00:23:11,359
那個問題是指說

749
00:23:11,359 --> 00:23:13,359
這邊這個 Release 是基於它來開發的

750
00:23:13,359 --> 00:23:15,359
才會有這種困擾

751
00:23:15,359 --> 00:23:17,359
不是

752
00:23:17,359 --> 00:23:19,359
你說的大包問題是在和魂 Man 的時候

753
00:23:19,359 --> 00:23:21,359
對 和魂 Man 那一包很恐怖

754
00:23:21,359 --> 00:23:23,359
那一包會超恐怖

755
00:23:23,359 --> 00:23:25,359
所以我們才會選擇一直和魂 Man

756
00:23:25,359 --> 00:23:27,359
就是這樣

757
00:23:27,359 --> 00:23:29,359
config 會比較少

758
00:23:29,359 --> 00:23:31,359
所以你可以在 Release 的時候和這個沒有

759
00:23:31,359 --> 00:23:33,359
而且你就比較快去配取到別人做了什麼事情

760
00:23:33,359 --> 00:23:35,359
我覺得沒關係

761
00:23:35,359 --> 00:23:37,359
大家都獨立作業

762
00:23:37,359 --> 00:23:39,359
做做做可能有一些重複的

763
00:23:39,359 --> 00:23:41,359
我覺得這就流派而已啊

764
00:23:41,359 --> 00:23:43,359
那你們現在會遇到問題嗎

765
00:23:43,359 --> 00:23:45,359
信仰之聲

766
00:23:47,359 --> 00:23:49,359
我覺得其實還蠻 OK 的

767
00:23:49,359 --> 00:23:51,359
我會遇到的問題

768
00:23:51,359 --> 00:23:53,359
是很多東西要 refresh

769
00:23:53,359 --> 00:23:55,359
剛剛

770
00:23:55,359 --> 00:23:57,359
這是不一樣的事情

771
00:23:59,359 --> 00:24:01,359
我們現在是用 Github

772
00:24:01,359 --> 00:24:03,359
剛剛那個 Emily 提到的問題

773
00:24:03,359 --> 00:24:05,359
就是因為我們現在有

774
00:24:05,359 --> 00:24:07,359
就是這些主機

775
00:24:07,359 --> 00:24:09,359
我們在 Github 上我們有把現在主機的版號放上來

776
00:24:09,359 --> 00:24:11,359
比方說我們現在看到的可能是

777
00:24:11,359 --> 00:24:13,359
Alpha 就是 100A2

778
00:24:13,359 --> 00:24:15,359
然後 Beta 你看到 100B1

779
00:24:15,359 --> 00:24:17,359
然後你說你在 Beta 上修正的時候

780
00:24:17,359 --> 00:24:19,359
它可能就是叫 B2

781
00:24:19,359 --> 00:24:21,359
對不對 那這個時候我也可以把

782
00:24:21,359 --> 00:24:23,359
這東西變成 100B2

783
00:24:23,359 --> 00:24:25,359
這樣子你就知道說

784
00:24:25,359 --> 00:24:27,359
這個沒有問題 這個我知道

785
00:24:27,359 --> 00:24:29,359
我剛剛說的是另外一個問題

786
00:24:29,359 --> 00:24:31,359
我知道我知道

787
00:24:31,359 --> 00:24:33,359
可以啊

788
00:24:33,359 --> 00:24:35,359
可以在 Release 合群

789
00:24:35,359 --> 00:24:37,359
蛤

790
00:24:37,359 --> 00:24:39,359
我只是要說

791
00:24:39,359 --> 00:24:41,359
越早回去理論上

792
00:24:41,359 --> 00:24:43,359
多人開發的話

793
00:24:43,359 --> 00:24:45,359
困擾會比較少

794
00:24:45,359 --> 00:24:47,359
就這樣

795
00:24:49,359 --> 00:24:51,359
這個就各自專案各自處理

796
00:24:51,359 --> 00:24:53,359
就這樣

797
00:24:53,359 --> 00:24:55,359
就這樣

798
00:24:57,359 --> 00:24:59,359
因為就是左邊跳的問題

799
00:24:59,359 --> 00:25:01,359
所以我猜

800
00:25:01,359 --> 00:25:03,359
對

801
00:25:05,359 --> 00:25:07,359
這個就是看哪一個開發團隊

802
00:25:07,359 --> 00:25:09,359
你們選用你們自己相對

803
00:25:09,359 --> 00:25:11,359
操作的方式

804
00:25:11,359 --> 00:25:13,359
就這樣

</details>
