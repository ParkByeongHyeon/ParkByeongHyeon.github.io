---
title: "Denoising Diffusion Probabilistic Models (DDPM) paper review"
date: 2026-09-23 10:14:00 +0900
categories: [Paper review]
tags: [Diffusion, DDPM, Generative Model]
---
## Denoising Diffusion Probabilistic Models (DDPM) paper review
NeurIPS 2020. [[Paper]](https://arxiv.org/abs/2006.11239) [[GitHub]](https://github.com/hojonathanho/diffusion.git)  
Jonathan Ho, Ajay Jain, Pieter Abbeel  

## Motivation
인공지능을 공부하다 보면, '딥러닝 낄낄 패거리들'이 Diffusion 어쩌고, DDPM 어쩌고 하는 글이나 영상을 많이 본 적이 있을 것이다. 대충 뭐 노이즈를 더하고, 빼고 하면 이미지가 짜잔! 하고 나온다는데 댓글 등의 반응이 아~ 그래서 그렇구나~ 하는데 엄청 고수 같고 뭔가 나만 이해 못하는 것 같다는 생각이 든 적이 몇번 있다. 그래서 한번 공부하려고 논문을 펴봤는데 수식에 정신이 아득해져 나만 어렵나 하면서 생활관에서 울면서 공부했던 기억이 있다. ChatGPT도 없던 시절이라 머리 깨지면서 공부했는데 갑자기 추억이다. (Shout out to 5군단 특임대!)
여튼 그런데 막상 주위에 Diffusion에 대해 물어보면 제대로 대답하는 사람을 한번도 보지 못했다. 약간 마블 시리즈, 공상과학 영화에서 대충 설명하기 힘든 내용이면 양자역학임ㅇㅇ, 암튼 그럼, 뭐 어쩌라고, 이런 느낌의 개념이 되어버린 듯 하다.
그래서 혹시나 Diffusion을 처음 공부하거나, 아는 척하고 싶은 사람을 위해 최대한 수식의 의미와 직관을 전달하는 느낌의 Paper review를 해보고자 한다.
