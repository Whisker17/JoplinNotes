id: 2f9f1dde81fe4f5ea1f2ddc4abe11464
parent_id: 6e2efcffeecc4db0a531b6e5e44e5f86
item_type: 1
item_id: a2dbec796db5403a84f915a41174ecb4
item_updated_time: 1620269241791
title_diff: 
body_diff: "@@ -4339,10 +4339,17 @@\\n RPC \\n-%E7%AB%AF%E7%82%B9\\n+Endpoint \\n %E4%BB%A5%E4%BB%8E S\\n@@ -4620,95 +4620,270 @@\\n %0D%0A- \\n-%E8%B5%84%E4%BA%A7%E7%B1%BB%E5%9E%8B%E8%A2%AB%E6%B7%BB%E5%8A%A0%E5%88%B0%E7%B1%BB%E5%9E%8B%E5%AE%9A%E4%B9%89%E4%B8%AD(#\\n+%E5%9C%A8%E7%B1%BB%E5%9E%8B%E5%AE%9A%E4%B9%89%E4%B8%AD%E5%8A%A0%E5%85%A5%E8%B5%84%E4%BA%A7%EF%BC%88Asset%EF%BC%89%E5%AE%9A%E4%B9%89%EF%BC%88%5B#29%5D(https://github.com/zeitgeistpm/tools/pull/\\n 29)\\n+%EF%BC%89\\n %0D%0A- %E5%9C%A8\\n+ \\n CLI\\n-%E4%B8%AD%E6%B7%BB%E5%8A%A0%E5%AE%A1%E6%89%B9%E6%BA%90%E5%87%BD%E6%95%B0(#\\n+ %E5%91%BD%E4%BB%A4%E8%A1%8C%E5%B7%A5%E5%85%B7%E4%B8%AD%E6%B7%BB%E5%8A%A0 %60ApprovalOrigin %60 %E5%87%BD%E6%95%B0%EF%BC%88%5B#30%5D(https://github.com/zeitgeistpm/tools/pull/\\n 30)\\n+%EF%BC%89\\n %0D%0A- %E6%B7%BB%E5%8A%A0\\n+ \\n joinPool\\n+ \\n %E5%92%8C%E5%85%B6%E4%BB%96\\n-%E5%A2%9E%E5%BC%BA%E5%8A%9F%E8%83%BD(#\\n+%E7%9B%B8%E5%85%B3%E5%8A%9F%E8%83%BD%E4%BC%98%E5%8C%96%EF%BC%88%5B#41%5D(https://github.com/zeitgeistpm/tools/pull/\\n 41)\\n+%EF%BC%89\\n %0D%0A- \\n-%E4%BB%A5%E5%8F%8A\\n %E5%90%84%E7%A7%8D%E5%90%84%E6%A0%B7%E7%9A%84\\n+ \\n bug\\n+ \\n %E4%BF%AE%E5%A4%8D%E5%92%8C\\n-%E8%BE%83%E5%B0%8F%E7%9A%84%E5%A2%9E%E5%BC%BA\\n+%E5%B0%8F%E4%BC%98%E5%8C%96\\n %0D%0A%0D%0A\\n@@ -4904,10 +4904,11 @@\\n %E7%94%A8%E7%9B%AE%E5%89%8D%E6%98%AF\\n-%E7%A7%81%E6%9C%89\\n+%E6%9C%AA%E5%BC%80%E6%BA%90\\n %E7%9A%84%EF%BC%8C%E6%88%91%E4%BB%AC\\n@@ -4918,16 +4918,18 @@\\n %E7%BB%AD%E5%BC%80%E5%8F%91%E5%92%8C%E5%86%85%E9%83%A8%E6%B5%8B%E8%AF%95\\n+%E9%98%B6%E6%AE%B5\\n %EF%BC%8C%E4%BD%86%E6%88%91%E4%BB%AC%E7%9A%84%E5%89%8D%E7%AB%AF%E5%BC%80\\n@@ -4931,22 +4931,24 @@\\n %E4%BB%AC%E7%9A%84%E5%89%8D%E7%AB%AF%E5%BC%80%E5%8F%91%E4%BA%BA%E5%91%98\\n+ \\n Tvrtko\\n+ \\n %E5%B7%B2%E7%BB%8F%E5%81%9A%E4%BA%86%E5%BE%88%E5%A4%9A%E4%BB%A4%E4%BA%BA\\n@@ -4962,24 +4962,18 @@\\n %E6%88%91%E4%BB%AC%E6%9C%80%E7%BB%88\\n-%E5%B0%86%E5%AD%98%E5%82%A8%E5%BA%93%E5%85%AC%E5%BC%80%E6%97%B6\\n+%E5%BC%80%E6%BA%90%E5%90%8E\\n %EF%BC%8C%E6%88%91%E4%BB%AC%E5%BE%88%E9%AB%98%E5%85%B4%E8%83%BD\\n-%E5%BE%88%E5%BF%AB\\n %E4%B8%8E%E6%82%A8%E5%88%86%E4%BA%AB\\n@@ -5003,16 +5003,21 @@\\n %E6%AD%A3%E5%9C%A8%E5%AF%B9%E8%87%AA%E5%8A%A8%E5%81%9A%E5%B8%82%E5%95%86\\n+%EF%BC%88AMM%EF%BC%89\\n %E8%BF%9B%E8%A1%8C%E7%A0%94%E7%A9%B6%EF%BC%8C%E7%89%B9%E5%88%AB%E5%85%B3\\n@@ -5028,14 +5028,10 @@\\n %E7%BB%8F%E6%B5%8E%E5%AD%A6%E5%AE%B6\\n-%E7%BD%97%E5%AE%BE%C2%B7%E6%B1%89%E6%A3%AE(\\n+ %5B\\n Robi\\n@@ -5042,16 +5042,63 @@\\n nsen\\n-)%E5%8F%91%E6%98%8E%E7%9A%84\\n+%5D(https://en.wikipedia.org/wiki/Robin_Hanson) %E6%8F%90%E5%87%BA%E7%9A%84 \\n LMSR\\n+ \\n %E5%B8%82%E5%9C%BA%E8%AF%84%E5%88%86\\n@@ -5128,49 +5128,172 @@\\n %E5%9F%BA%E6%9C%AC%E5%BB%BA%E6%A8%A1\\n-:\\n+%EF%BC%9A%5B\\n %E6%94%B6%E5%8F%96%E5%88%A9%E6%B6%A6%E7%9A%84\\n+ \\n AMM\\n-%E5%92%8C%E5%8A%A8%E6%80%81%E5%81%9A%E5%B8%82%E5%95%86%E3%80%82%E9%A2%84%E8%AE%A1%E6%9C%89%E5%85%B3%E6%96%B0%E4%B8%80%E4%BB%A3%E2%80%9C%E6%97%B6%E4%BB%A3%E7%B2%BE%E7%A5%9E%E2%80%9D%E5%81%9A%E5%B8%82%E5%95%86%E7%9A%84%E6%B6%88%E6%81%AF%E5%BE%88%E5%BF%AB%E5%B0%B1%E4%BC%9A%E5%85%AC%E5%B8%83\\n+%5D(https://github.com/zeitgeistpm/LMSR-zeitgeist) %E5%92%8C%5B%E5%8A%A8%E6%80%81%E5%81%9A%E5%B8%82%E5%95%86%5D(https://github.com/zeitgeistpm/Dynamic-Market-Maker-Zeitgeist)%E3%80%82%E9%A2%84%E8%AE%A1%E5%BE%88%E5%BF%AB%E6%88%91%E4%BB%AC%E5%B0%B1%E4%BC%9A%E9%92%88%E5%AF%B9 Zeitgeist %E6%96%B0%E7%9A%84%E5%81%9A%E5%B8%82%E5%95%86%E6%96%B9%E6%A1%88%E5%8F%91%E5%B8%83%E5%A3%B0%E6%98%8E\\n %E3%80%82%0D%0A%0D\\n@@ -5328,67 +5328,69 @@\\n %E4%BB%AC%E7%9A%84%E5%AE%98%E6%96%B9\\n+ \\n Telegram\\n-%E7%BB%84\\n+ %E7%BE%A4\\n %E7%9B%AE%E5%89%8D%E6%8B%A5%E6%9C%89\\n+ \\n 3500\\n+ \\n %E5%A4%9A%E4%BA%BA%E3%80%82\\n-%E6%88%91%E4%BB%AC%E4%B8%8E\\n+%E7%94%B1%E4%BA%8E%E9%9B%86%E6%88%90%E4%BA%86 \\n Combot\\n+ \\n %E8%87%AA%E5%8A%A8%E5%AE%A1%E6%A0%B8%E5%B7%A5%E5%85%B7\\n-%E7%9A%84%E9%9B%86%E6%88%90%E5%B8%AE%E5%8A%A9%E6%88%91%E4%BB%AC%E5%B0%86%E5%9E%83%E5%9C%BE%E9%82%AE%E4%BB%B6%E5%8F%91%E9%80%81%E8%80%85%E6%8B%92%E4%B9%8B%E9%97%A8%E5%A4%96\\n+%E4%BF%9D%E8%AF%81%E4%BA%86%E6%88%91%E4%BB%AC%E7%BE%A4%E7%BB%84%E6%88%90%E5%91%98%E7%9A%84%E8%B4%A8%E9%87%8F\\n %EF%BC%8C%E5%90%8C%E6%97%B6%E5%9B%B4%E7%BB%95\\n+ \\n Zeit\\n@@ -5398,19 +5398,19 @@\\n eist\\n+ \\n %E7%9A%84%E5%8F%91%E5%B1%95\\n-%E4%BF%9D%E6%8C%81%E4%BA%86%E5%81%A5%E5%BA%B7%E7%9A%84%E5%AF%B9%E8%AF%9D\\n+%E5%B1%95%E5%BC%80%E4%BA%86%E7%A7%AF%E6%9E%81%E8%AE%A8%E8%AE%BA\\n %E3%80%82%0D%0A%0D\\n@@ -5417,16 +5417,17 @@\\n %0ADiscord\\n+ \\n %E4%BB%8D%E7%84%B6%E6%98%AF%E4%B8%8E%E6%88%91%E4%BB%AC%E5%9B%A2%E9%98%9F\\n@@ -5441,24 +5441,27 @@\\n %E5%8A%A8%E7%9A%84%E5%A5%BD%E5%9C%B0%E6%96%B9%EF%BC%8C%E5%B9%B6%E4%B8%94\\n+ \\n Telegram\\n+ %E7%9A%84\\n %E9%9B%86%E6%88%90%E8%BF%98%E6%9C%89%E5%8A%A9%E4%BA%8E%E6%8F%90%E9%AB%98\\n@@ -5461,16 +5461,17 @@\\n %E6%88%90%E8%BF%98%E6%9C%89%E5%8A%A9%E4%BA%8E%E6%8F%90%E9%AB%98%E5%9C%A8\\n+ \\n Zeitgeis\\n@@ -5471,16 +5471,17 @@\\n eitgeist\\n+ \\n %E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84%E5%8F%82\\n@@ -5486,23 +5486,25 @@\\n %E7%9A%84%E5%8F%82%E4%B8%8E%E5%BA%A6%EF%BC%8C%E4%BB%8E%E8%80%8C%E4%BD%BF\\n+ \\n Discord\\n+ \\n %E5%A2%9E%E9%95%BF%E5%88%B0%E4%BA%86220%E5%A4%9A\\n@@ -5523,16 +5523,17 @@\\n %E5%9C%A8%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%AD%E9%9B%86%E6%88%90%E4%BA%86\\n+ \\n Zeitgeis\\n@@ -5538,24 +5538,17 @@\\n ist \\n-Testnet%E9%BE%99%E5%A4%B4%EF%BC%8C%E5%9C%A8%E8%BF%99%E9%87%8C%EF%BC%8C%E7%8B%82%E7%83%AD\\n+%E6%B5%8B%E8%AF%95%E7%BD%91%E6%B0%B4%E9%BE%99%E5%A4%B4%EF%BC%8C%E7%A7%AF%E6%9E%81\\n %E7%9A%84%E7%A4%BE%E5%8C%BA%E6%88%90\\n@@ -5559,33 +5559,37 @@\\n %E5%85%A5%E5%9F%BA%E6%9C%AC%E7%9A%84\\n-%EF%BC%81\\n+%60!\\n drip\\n+%60\\n %E5%91%BD%E4%BB%A4%E5%8D%B3%E5%8F%AF\\n-%E5%A2%9E%E5%8A%A0%E5%85%B6testnet%E4%BB%A4%E7%89%8C%E7%9A%84%E6%8C%81%E6%9C%89%E9%87%8F\\n+%E7%A9%BA%E6%8A%95%E5%85%B6%E6%B5%8B%E8%AF%95%E7%BD%91 token %E5%88%B0%E6%8C%87%E5%AE%9A%E5%9C%B0%E5%9D%80\\n %E3%80%82%0D%0A%0D\\n@@ -5599,16 +5599,17 @@\\n %E5%88%B0%E6%88%91%E4%BB%AC%E4%BB%8D%E5%A4%84%E4%BA%8E%E5%BB%BA%E7%AB%8B\\n+ \\n Zeitgeis\\n@@ -5609,16 +5609,17 @@\\n eitgeist\\n+ \\n %E7%9A%84%E6%97%A9%E6%9C%9F%E9%98%B6%E6%AE%B5%EF%BC%8C%E6%88%91%E4%BB%AC\\n@@ -5638,23 +5638,27 @@\\n %EF%BC%8C%E5%B9%B6%E6%84%9F%E8%B0%A2\\n+ \\n Polkadot\\n-%E5%92%8C\\n+ %E5%92%8C \\n Kusama\\n+ \\n %E7%A4%BE%E5%8C%BA%E7%9A%84%E6%94%AF\\n@@ -5669,28 +5669,22 @@\\n %E9%A1%BB%E7%89%B9%E5%88%AB%E5%90%91\\n-%E4%BA%9A%E5%8E%86%E5%85%8B%E6%96%AF%EF%BC%88Alex%EF%BC%89%E5%92%8C%E5%93%88%E5%A5%87%EF%BC%88\\n+ Alex %E5%92%8C \\n Hutch\\n-%EF%BC%89\\n+ \\n %E8%87%B4%E6%95%AC%EF%BC%8C%E4%BB%A5\\n@@ -5730,17 +5730,23 @@\\n %E5%9C%BA%E7%9A%84%E6%9E%A2%E7%BA%BD%0D%0A%0D%0A\\n-%E5%9C%A8\\n+%E6%88%91%E4%BB%AC%E7%83%AD%E8%A1%B7%E4%BA%8E%E5%9C%A8 \\n Zeitgeis\\n@@ -5750,30 +5750,29 @@\\n eist\\n-%EF%BC%8C%E6%88%91%E4%BB%AC%E7%83%AD%E8%A1%B7%E4%BA%8E\\n+ %E4%B8%8A\\n %E6%8E%A2%E7%B4%A2%E9%A2%84%E6%B5%8B%E5%B8%82%E5%9C%BA%E5%92%8C\\n+ \\n futarchy\\n-%E7%9A%84\\n+ %E7%9A%84%E5%B4%AD\\n %E6%96%B0%E7%94%9F%E6%80%81%E7%B3%BB\\n@@ -5791,11 +5791,8 @@\\n %E5%8A%A0%E5%85%A5%E6%88%91%E4%BB%AC\\n-%E7%9A%84%E6%97%85%E7%A8%8B\\n %E3%80%82%E6%9C%80%E5%A5%BD%E7%9A%84\\n@@ -5803,33 +5803,74 @@\\n %E9%98%85%E6%88%91%E4%BB%AC%E7%9A%84\\n+%5B\\n %E6%97%B6%E4%BA%8B%E9%80%9A%E8%AE%AF\\n+%5D(https://blog.zeitgeist.pm/#subscribe)\\n %EF%BC%8C%E5%8A%A0%E5%85%A5%E6%88%91%E4%BB%AC%E7%9A%84\\n+ \\n Discord\\n+ \\n %E6%9C%8D%E5%8A%A1%E5%99%A8%EF%BC%8C\\n-%E5%B9%B6%E4%B8%80%E5%AE%9A%E8%A6%81\\n+%E8%AF%B7%E6%8C%81%E7%BB%AD\\n %E5%85%B3%E6%B3%A8%E6%88%91%E4%BB%AC\\n@@ -5878,13 +5878,13 @@\\n %E5%B0%86%E5%8F%91%E5%B8%83%E7%9A%84\\n-%E6%BF%80%E5%8A%B1\\n %E6%B5%8B%E8%AF%95%E7%BD%91\\n+%E6%BF%80%E5%8A%B1\\n %E8%AE%A1%E5%88%92%E3%80%82%0D\\n@@ -5912,14 +5912,19 @@\\n %E4%BA%9B%E5%B8%8C%E6%9C%9B%E5%9C%A8\\n-%E6%97%B6%E4%BB%A3%E7%B2%BE%E7%A5%9E%E5%8D%8F%E8%AE%AE\\n+ Zeitgeist \\n %E4%B8%8A%E6%9E%84%E5%BB%BA%E4%BA%A7\\n@@ -5937,10 +5937,15 @@\\n %E4%B9%9F%E6%9C%89%E4%B8%80%E4%B8%AA\\n-%E8%B5%A0%E6%AC%BE\\n+ Grant \\n %E9%A1%B9%E7%9B%AE%E6%AD%A3%E5%9C%A8\\n@@ -5966,9 +5966,9 @@\\n %E6%96%B9%E7%9A%84%E7%A4%BE%E4%BA%A4\\n-%E9%A2%91\\n+%E6%B8%A0\\n %E9%81%93%E2%80%A6%E2%80%A6%0D\\n@@ -5976,17 +5976,17 @@\\n %0D%0A%E6%89%80%E6%9C%89%E7%A4%BE%E4%BA%A4%E9%93%BE%E6%8E%A5\\n-:\\n+%EF%BC%9A\\n http://l\\n@@ -6013,11 +6013,13 @@\\n %0D%0A%0D%0A\\n+%E5%AE%98%E6%96%B9\\n %E7%BD%91%E7%AB%99\\n-:\\n+%EF%BC%9A\\n http\\n@@ -6045,18 +6045,17 @@\\n %0ATwitter\\n-: \\n+%EF%BC%9A\\n https://\\n@@ -6085,11 +6085,13 @@\\n %0D%0A%0D%0A\\n+%E6%97%B6%E4%BA%8B\\n %E9%80%9A%E8%AE%AF\\n-:\\n+%EF%BC%9A\\n http\\n@@ -6116,17 +6116,30 @@\\n .pm/\\n-%E8%AE%A2%E9%98%85%0D%0A%0D%0A%E4%B8%8D%E5%92%8C:\\n+#subscribe%0D%0A%0D%0ADiscord%EF%BC%9A\\n http\\n@@ -6173,18 +6173,17 @@\\n %0D%0AGitHub\\n-: \\n+%EF%BC%9A\\n https://\\n@@ -6212,17 +6212,17 @@\\n %0D%0A%0D%0A%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6\\n-:\\n+%EF%BC%9A\\n contact@\\n"
metadata_diff: {"new":{},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2021-05-06T02:52:18.590Z
created_time: 2021-05-06T02:52:18.590Z
type_: 13