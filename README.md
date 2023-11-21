# Pytorch Distributed Data Parallel
## Pytorch DDP tutorial

+ 대용량 파일 학습을 위해 Pytorch에서 제공하는 Data Distributed Parallel 클래스에 대한 튜토리얼을 진행함

+ Pytorch Documentation에서 제공하는 Tutorial을 참고하여 작성함

-----
### 용어정리

1. node = GPU가 있는 machine의 수
2. rank = process id
   
   2-1. global_rank = 전체 node에서의 rank

   2-2. local_rank = 각 node내에서의 rank
   
3. world_size = process의 수
   
   3-1. global_world_size = 모든 node에서 실행되는 process의 수
   
   3-2. local_world_size = 각 node에서 실행되는 process의 수

------
Reference
1. https://pytorch.org/tutorials/intermediate/ddp_tutorial.html
2. https://pytorch.org/docs/stable/distributed.html
3. https://csm-kr.tistory.com/47
