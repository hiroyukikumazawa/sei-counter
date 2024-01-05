## Upload command
seid tx wasm store $CONTRACT_WASM_BINARY -y --from=$ACCOUNT_NAME --chain-id=$CHAIN_ID --node $ENDPOINT --gas=10000000 --fees=1000000usei --broadcas
t-mode=block

## output
```yml
code: 0
codespace: ""
data: 0A250A1E2F636F736D7761736D2E7761736D2E76312E4D736753746F7265436F6465120308C11D
events:
- attributes:
  - index: true
    key: c3BlbmRlcg==
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6
  - index: true
    key: YW1vdW50
    value: MTAwMDAwMHVzZWk=
  type: coin_spent
- attributes:
  - index: true
    key: ZmVl
    value: MTAwMDAwMHVzZWk=
  - index: true
    key: ZmVlX3BheWVy
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6
  type: tx
- attributes:
  - index: true
    key: YWNjX3NlcQ==
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6LzE=
  type: tx
- attributes:
  - index: true
    key: c2lnbmF0dXJl
    value: NWpFSnRQdTlPYmpyTUY3aHB5Ukg0ZVR0TjNpSkR6dzdtSVZTeDVOY0RvUUttMVlnM2NxMDhUV0hzSGpBWndKdlpzRUltRFNBOFI2d250WS9rdUhzbUE9PQ==
  type: tx
- attributes:
  - index: true
    key: YWN0aW9u
    value: L2Nvc213YXNtLndhc20udjEuTXNnU3RvcmVDb2Rl
  type: message
- attributes:
  - index: true
    key: bW9kdWxl
    value: d2FzbQ==
  - index: true
    key: c2VuZGVy
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6
  type: message
- attributes:
  - index: true
    key: Y29kZV9pZA==
    value: Mzc3Nw==
  type: store_code
gas_used: "986737"
gas_wanted: "10000000"
height: "59227391"
info: ""
logs:
- events:
  - attributes:
    - key: action
      value: /cosmwasm.wasm.v1.MsgStoreCode
    - key: module
      value: wasm
    - key: sender
      value: sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz
    type: message
  - attributes:
    - key: code_id
      value: "3777"
    type: store_code
  log: ""
  msg_index: 0
raw_log: '[{"events":[{"type":"message","attributes":[{"key":"action","value":"/cosmwasm.wasm.v1.MsgStoreCode"},{"key":"module","value":"wasm"},{"key":"sender","value":"sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz"}]},{"type":"store_code","attributes":[{"key":"code_id","value":"3777"}]}]}]'
timestamp: ""
tx: null
txhash: 8E3190140BD96DFC140FCB8632DEE07E8AA8B2F5E81A0EFEFF7C26BAAE3643F8
```