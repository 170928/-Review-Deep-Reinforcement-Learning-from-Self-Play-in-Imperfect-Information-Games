# -Review-Deep-Reinforcement-Learning-from-Self-Play-in-Imperfect-Information-Games
[Review and Implementation]

### Abstract
많은 실생활 어플리케이션들은 "imperfect information"을 기반으로 하는 "large-scale game"으로 표현할 수 있습니다.  
비완전 정보 기반은 게임들을 다루기 위해서 이전의 연구들은 "Nash equalibria (내쉬 균형)"을 handcrafted abstraction 기반으로 계산하는데 집중해왔습니다.   
이 논문에서는 domain 에 대한 사전 지식 없이 Nash equalibrai (내쉬 균형)을 근사할 수 있는 "확장 가능한 end to end 접근법"을 제시합니다.  
제시되는 방법은 허구의 self-play 를 deep reinforcement learning과 결합합니다.  
Leduc poker에 이 알고리즘이 적용되었을 때, Neural Fictitious Self-Play (NFSP)는 내쉬 균형에 도달하는 모습을 보였습니다.

### Introduction 
 
