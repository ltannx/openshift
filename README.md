
<h1 align="center"> 免责声明 </h1>

# v2ray 部署在 openshift starter

环境变量： CONFIG_JSON（配置）、

{
  "log": {
    "loglevel": "warning"
  },
  "inbound": {
    "protocol": "vmess",
    "port": 8080,
    "settings": {
      "clients": [
        {
          "id": "e5c2697d-8d2e-4353-b663-3b0e50e23991",
          "alterId": 64,
          "security": "aes-128-gcm"
        }
      ]
    },
    "streamSettings": {
      "network": "ws"
    }
  },
  "inboundDetour": [],
  "outbound": {
    "protocol": "freedom",
   "settings": {}
  }
}
