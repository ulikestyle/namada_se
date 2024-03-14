# CREW S CLASS ASTEROIDS

**Category:**  
Operating IBC/ Interoperability infrastructure - Operate a Shielded Expedition-compatible Osmosis testnet relayer

**Description:**  
We deploy a fullnode for namada SE .  
We also deploy another fullnode for osmo-test-5, namada CLI and Hermes. All operations below are based on this server.

Hermes memo_prefix: tnam1qq4njwzlfktljfrrjk2eyxckwr4t43agdsunx6w2

Below is the IBC relayer channel we created for namada and osmosis.

```
Namada (shielded-expedition.88f17d1d14):
   channel_id:    channel-608
   client_id:     07-tendermint-185
   connection_id: connection-73
   port_id:       transfer
Creation address: tnam1qqh2q00z5r9ry8qaau9xjwpvuedz3eu0qyw5vcae
```
```

Osmosis (osmo-test-5): 
   channel_id:    channel-6120
   client_id:     07-tendermint-1978
   connection_id: connection-1929
   port_id:       transfer
Creation address: osmo1a6fzjsj0ug5pe64ycj9465ql8mgqu4ue4h84p2
```

Below is the Trade address we created for namada and osmosis.

```
Creation address: tnam1qq4njwzlfktljfrrjk2eyxckwr4t43agdsunx6w2
Creation address: osmo19ay6zvcq7ut6kll5hqr227leypm6n9lgl3rwkj
```

**`ibc test and Relayer address transactions:`**

**IN OSMOSIS**   
https://www.mintscan.io/osmosis-testnet/tx/FC05ABE9CA5BB35B40E77486B21CAB91A42890FBEC6BEE6DC4059B7AF6836B6E?height=5990272

**OUT FROM OSMOSIS**  
https://www.mintscan.io/osmosis-testnet/tx/DC5D5AE2C3256527C298B6D0FE9508980AF9A052C14F303470D19FEA88C608A1?height=5990310

**`Public RPC:`**

**Namada:** https://namada-rpc.equinoxdao.xyz   
**Osmosis:** http://65.109.84.19:26004
