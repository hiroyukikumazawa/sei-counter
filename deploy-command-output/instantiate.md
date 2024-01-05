## Instantiate command
```bash
seid tx wasm instantiate $CONTRACT_ID '{"count": 0}' --chain-id $CHAIN_ID --from $ACCOUNT_NAME --gas=4000000 --fees=1000000usei --broadcast-mode=block --label $LABEL --no-admin --node $RPC_ENDPOINT
```

## Output
```output.txt
{"body":{"messages":[{"@type":"/cosmwasm.wasm.v1.MsgInstantiateContract","sender":"sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz","admin":"","code_id":"3777","label":"1","msg":{"count":0},"funds":[]}],"memo":"","timeout_height":"0","extension_options":[],"non_critical_extension_options":[]},"auth_info":{"signer_infos":[],"fee":{"amount":[{"denom":"usei","amount":"1000000"}],"gas_limit":"4000000","payer":"","granter":""}},"signatures":[]}

confirm transaction before signing and broadcasting [y/N]: y

code: 0
codespace: ""
data: 0A6C0A282F636F736D7761736D2E7761736D2E76312E4D7367496E7374616E7469617465436F6E747261637412400A3E736569317332376D64717A3730323734666E757477377774363438713632346665786E7465726B786E3267706837397A6E63653532676D71356470706364
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
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6LzY=
  type: tx
- attributes:
  - index: true
    key: c2lnbmF0dXJl
    value: STY0WWh2SFNFNHpTOVJOSjd4Qjh3a2VvbTVKQUlxYThGbG42TTdpRnk2WjJuVTZ4YzlQeHVTM2gyNTd3VGRzVjQ5UEpmcG9keUErRXdkeld4bUl5NEE9PQ==
  type: tx
- attributes:
  - index: true
    key: YWN0aW9u
    value: L2Nvc213YXNtLndhc20udjEuTXNnSW5zdGFudGlhdGVDb250cmFjdA==
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
    key: X2NvbnRyYWN0X2FkZHJlc3M=
    value: c2VpMXMyN21kcXo3MDI3NGZudXR3N3d0NjQ4cTYyNGZleG50ZXJreG4yZ3BoNzl6bmNlNTJnbXE1ZHBwY2Q=
  - index: true
    key: Y29kZV9pZA==
    value: Mzc3Nw==
  type: instantiate
- attributes:
  - index: true
    key: X2NvbnRyYWN0X2FkZHJlc3M=
    value: c2VpMXMyN21kcXo3MDI3NGZudXR3N3d0NjQ4cTYyNGZleG50ZXJreG4yZ3BoNzl6bmNlNTJnbXE1ZHBwY2Q=
  - index: true
    key: bWV0aG9k
    value: aW5zdGFudGlhdGU=
  - index: true
    key: b3duZXI=
    value: c2VpMW5ncjdsc3d6eGpqNnk2enRnOGMwdnY4MzY2azA2NDVtdTRzenN6
  - index: true
    key: Y291bnQ=
    value: MA==
  type: wasm
gas_used: "169081"
gas_wanted: "4000000"
height: "59292970"
info: ""
logs:
- events:
  - attributes:
    - key: _contract_address
      value: sei1s27mdqz70274fnutw7wt648q624fexnterkxn2gph79znce52gmq5dppcd
    - key: code_id
      value: "3777"
    type: instantiate
  - attributes:
    - key: action
      value: /cosmwasm.wasm.v1.MsgInstantiateContract
    - key: module
      value: wasm
    - key: sender
      value: sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz
    type: message
  - attributes:
    - key: _contract_address
      value: sei1s27mdqz70274fnutw7wt648q624fexnterkxn2gph79znce52gmq5dppcd
    - key: method
      value: instantiate
    - key: owner
      value: sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz
    - key: count
      value: "0"
    type: wasm
  log: ""
  msg_index: 0
raw_log: '[{"events":[{"type":"instantiate","attributes":[{"key":"_contract_address","value":"sei1s27mdqz70274fnutw7wt648q624fexnterkxn2gph79znce52gmq5dppcd"},{"key":"code_id","value":"3777"}]},{"type":"message","attributes":[{"key":"action","value":"/cosmwasm.wasm.v1.MsgInstantiateContract"},{"key":"module","value":"wasm"},{"key":"sender","value":"sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz"}]},{"type":"wasm","attributes":[{"key":"_contract_address","value":"sei1s27mdqz70274fnutw7wt648q624fexnterkxn2gph79znce52gmq5dppcd"},{"key":"method","value":"instantiate"},{"key":"owner","value":"sei1ngr7lswzxjj6y6ztg8c0vv8366k0645mu4szsz"},{"key":"count","value":"0"}]}]}]'
timestamp: ""
tx: null
txhash: 3F4698602D887AF59FA8847EF38D175766085507D0E24B793AD810164F37E24A
```
