This is a 1+1+n design, meaning there is one channel used only by the cloud, one channel spanning clusters, and each cluster has its own blockchain channel. 

I used three x86 PC for this purpose, two serving as fog nodes while the remaining one serves as the cloud node. 

In the evaluation, I hit all four channels at the same time. 

Hardware infrastructure:

- CREST-NUC-1: 129.127.231.53
- CREST-Edge-1b: 129.127.230.61
- CREST-Edge-2b: 129.127.231.125
- CREST-Edge-3b: 129.127.231.162
- CREST-Edge-4b: 129.127.231.168
- CREST-NUC-3: 129.127.230.128
- CREST-Edge-1: 129.127.231.88
- CREST-Edge-2: 129.127.231.12
- CREST-Edge-3: 129.127.231.182
- CREST-Edge-4: 129.127.230.179

Request:
- Ch1: PoA-X64-ARMv7
- Ch2: PoA-X64-ARMv7
- Ch3: PoA-X64
- Ch4: PoA-X64
- Evaluation: Ch1-Performance-ResourceConsumption
- Evaluation: Ch2-Performance-ResourceConsumption
- Evaluation: Ch3-Performance-ResourceConsumption
- Evaluation: Ch4-Performance-ResourceConsumption

Experiment Plan:
1. Verifier(request)
2. DeplPoA_X64_ARM(Ch1)
3. DeplPoA_X64_ARM(Ch2)
4. DeplPoA(Ch3)
5. DeplPoA(Ch4)
6. EvalPerformanceEthereum(Ch1)
7. EvalPerformanceEthereum(Ch2)
8. EvalPerformanceEthereum(Ch3)
9. EvalPerformanceEthereum(Ch4)