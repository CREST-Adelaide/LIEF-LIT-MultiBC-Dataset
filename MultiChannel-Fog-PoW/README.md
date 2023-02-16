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
- Ch1: PoW-X64-ARMv7
- Ch2: PoW-X64-ARMv7
- Ch3: PoW-X64-ARMv7
- Evaluation: Ch1-Performance-ResourceConsumption
- Evaluation: Ch2-Performance-ResourceConsumption
- Evaluation: Ch3-Performance-ResourceConsumption

Experiment Plan:
1. Verifier(request)
2. DeplPoW_X64_ARM(Ch1)
3. DeplPoW_X64_ARM(Ch2)
4. DeplPoW_X64_ARM(Ch3)
5. EvalPerformanceEthereum(Ch1)
6. EvalPerformanceEthereum(Ch2)
7. EvalPerformanceEthereum(Ch3)