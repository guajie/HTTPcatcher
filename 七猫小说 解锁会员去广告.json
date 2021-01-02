{
  "rules" : [
    {
      "action" : "body",
      "matchField" : "",
      "field" : "",
      "value" : "is_vip\": \"1\"",
      "matchValue" : "is_vip\":\"0\"",
      "destiontion" : "response",
      "isRegex" : true
    },
    {
      "action" : "body",
      "matchField" : "",
      "field" : "",
      "value" : "adv_style\": \"0\"",
      "matchValue" : "adv_style\":\"\\d+\"",
      "destiontion" : "response",
      "isRegex" : true
    },
    {
      "action" : "body",
      "matchField" : "",
      "field" : "",
      "value" : " \"\"",
      "matchValue" : "\"广告是为了更多的免费内容\",\n      \"点击屏幕中央可以呼出菜单\",\n      \"菜单内可以切换夜间模式\",\n      \"菜单内可以调节亮度和字体大小\",\n      \"更多阅读设置里可以隐藏右上角金币\",\n      \"更多阅读设置里可以隐藏左上角设置\",\n      \"有问题可在我的-用户反馈里进行反馈\",\n      \"提醒:要求事先打钱汇款的是诈骗\",\n      \"提醒:网上汇款转账需警惕\",\n      \"提醒:花呗套现刷额度的是诈骗\",\n      \"提醒:请勿向他人泄露银行卡信息\",\n      \"提醒:请勿加陌生人微信或QQ\"",
      "destiontion" : "response",
      "isRegex" : false
    }
  ],
  "enabled" : false,
  "name" : "七猫小说 解锁会员去广告 A+",
  "description" : "七猫小说-看小说电子书的阅读神器 来自 Shanghai Seven-Cat Culture Media Co.,Ltd. https:\/\/apps.apple.com\/cn\/app\/%E4%B8%83%E7%8C%AB%E5%B0%8F%E8%AF%B4-%E7%9C%8B%E5%B0%8F%E8%AF%B4%E7%94%B5%E5%AD%90%E4%B9%A6%E7%9A%84%E9%98%85%E8%AF%BB%E7%A5%9E%E5%99%A8\/id1387717110\n\n提供未测试Qx规则\nhostname＝*\n\n#七猫小说 解锁会员去广告 A+\nhttps:\/\/(.+)\\.wtzw\\.com\/.+ url script-response-body qmxs_noad.js\n\nbody = $response.body.replace(\/is_vip\":\"0\"\/g, 'is_vip\":\"1\"').replace(\/adv_style\":\"\\d+\"\/g, 'adv_style\":\"0\"').replace(\/true\/g, 'false');\n$done({body});",
  "locations" : [
    {
      "method" : "GET",
      "scheme" : "https",
      "enabled" : true,
      "port" : 443,
      "query" : "",
      "host" : "xiaoshuo.wtzw.com",
      "path" : "\/api\/v1\/user\/get-user-info"
    },
    {
      "method" : "GET",
      "scheme" : "https",
      "enabled" : true,
      "port" : 443,
      "query" : "",
      "host" : "xiaoshuo.wtzw.com",
      "path" : "\/api\/v2\/user\/my-center"
    },
    {
      "method" : "GET",
      "scheme" : "https",
      "enabled" : true,
      "port" : 443,
      "query" : "*",
      "host" : "api-ks.wtzw.com",
      "path" : "\/api\/v1\/reader-adv"
    },
    {
      "method" : "GET",
      "scheme" : "https",
      "enabled" : true,
      "port" : 443,
      "query" : "",
      "host" : "cdn.wtzw.com",
      "path" : "\/bookimg\/free\/api\/v1\/reader\/reader-copy.json"
    }
  ]
}
