# chapter 18. SRE Engagement Model

SRE teamのsite reliabilityの向上のための戦略として，Production readiness reaviews (PRRs)，継続的改善などがある．

SREの目的は，プロダクトのreliabilityを保ちながらも開発速度を最大化することである．
しかし，SREチームにできることは限られていて，ドメインが大きすぎたり，過度に複雑だと，効果的でなくなる．
近年のmicroserviceの動向は，これを加速させており，一つのSREチームでは対処しかねる．
SREチームは何に集中するべきか決める必要がある．

この章ではプロダクトチームや，サービス自体についてどうやって関わるべきかについて考える．
さらにはサービス自体ではなく，プロダクトチームの狙いを理解し，それに対する正しい付き合い方を考える．

## The service lifecycle
