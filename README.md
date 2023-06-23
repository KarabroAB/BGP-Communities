# AS51519 BGP Communities

| Prefix type                                       | Community             | Large Community                  |
| ------------------------------------------------- | --------------------- | -------------------------------- |
| Prefix learned from Transit                       | 51519:200             | 51519:200:Transit ASN            |
| Prefix learned from Public Peer                   | 51519:300             | 51519:300:Perring DB IXP ID      |
| Prefix learned from IXP                           | 51519:310             | 51519:310:Perring DB IXP ID      |
| Prefix learned from Private Peer                  | 51519:350             | 51519:350:Peer ASN               |
| Prefix originated by 51519                        | 51519:100             | 51519:100 :0                     |
| Prefix originated by other Karabro controlled ASN | 51519:120             | 51519:120:Karabro controlled ASN |
| Prefix originated by Customer                     | 51519:400             | 51519:400:Customer ASN           |
| Prefix originated by Customer with BGP Access     | 51519:410             | 51519:410:BGP Access ASN         |
| Prefix originated by Customer with Private ASN    | 51519:420             | 51519:410:Random Unique ID       |
