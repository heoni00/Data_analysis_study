## BIG Leader BM 개발 스터디 개인 프로젝트
### 배달의 민족 개인추천화 서비스 기획 및 알고리즘 연구

**팀원** : 김차헌, 이아리, 전성호, 이승희, 문호준  
**제작기간** : 2021.07.12 ~ 2021.07.16  

#### 프로젝트 동기 및 목표

🐣 동기 🐣   

본 프로젝트는 BIG LEADER AI 캠프 중 IT 비즈니스 서비스 개발에 관심이 있는 학우들이 모여 자발적으로 진행한 프로젝트입니다. 
스터디 진행 중 배달의 민족 서비스를 리뷰하게 되었고 개인 추천화 시스템의 부재를 알게 되었습니다. 

BM 이론 및 서비스 리뷰 등 스터디만으로는 한계가 있다 생각했습니다. 공부한 것들을 토대로 실제 IT 서비스를 구상하고 개발하면 역량 강화에 더 큰 도움이 될 것이라 생각했습니다.
무엇보다 ,, 저희가 구상한 아이디어가 정말 획기적이라 생각하였고 큰 가치가 있다 생각했습니다. 이렇게 좋은 아이디어를 그저 흘러가는 얘기로 넘기기엔 아까웠습니다.  

때문에 BM 이론 및 개인, 회사 서비스 리뷰 등의 학습을 토대로 **실제 배민 PM이 됐다 생각하고 개인 추천화 시스템 기획안 및 제안서를 만들어 보자!**라는 결심을 하게 되었습니다.  

🐤 목표 및 노력 🐤
  
- 단순히 BM 모델을 만드는 것에 그치지 않고 실제로 배민 서비스에 우리 아이디어를 관철시키고 싶었습니다.     
$\to$ 제안서를 만든 후 우아한 형제들 '홈페이지 제안 & 제휴', 기획팀 이메일 그리고 책자로 만들어 우편 전송했습니다.   

- 우아한 형제들 기업 문화에 맞게 **키치**하고 자유로운 형식의 제안서를 만들고 싶었습니다.    
$\to$ 기존 제안서 형식이 아닌 **배민트렌드 잡지**형식을 빌렸습니다. 또한, 배민 캐릭터가 스토리텔링하며 실제로 옆에서 얘기하는 듯한 제안서를 만들었습니다. 마치 배민 직원이 말하는 것처럼요.  

- 개인 추천화 서비스 알고리즘 구현 방식의 다양화.   
$\to$ 다양한 상황에 맞는 알고리즘 모델을 제시하고 각각의 장,단점을 작성했습니다.   

### OVERVIEW

#### 서비스 기획 동기

[![배달의 민족 개인화 추천 서비스 제안서_page-0001](https://user-images.githubusercontent.com/67791317/199926974-d1bc593a-9f9b-4f92-b8f0-82613c8cfdf3.jpg)](https://github.com/heoni00/2021-Sub_Project-Baemin/tree/main/7.%20제안서%20자료/1.%20배민%20불편사항%20코믹스#readme)

[배민 불편사항 코믹스 전편](https://github.com/heoni00/2021-Sub_Project-Baemin/tree/main/7.%20제안서%20자료/1.%20배민%20불편사항%20코믹스#readme)

본 팀이 만든 BM 제안서는 '우아한 형제들'에게 뜬금없는 제안서입니다. 본래 예정에 없고 신원이 불분명한 '어떤 팀'이 보낸 제안서입니다. 
따라서 우선은 읽고 싶은 제안서를 만들어야했습니다. 때문에 **강렬한 인상**과 함께 프로제트를 관통하는 **화두**를 제안서 서두에 남겨야 한다 생각했습니다.  

눈 앞에서 구상한 BM 서비스 제안 프레젠테이션을 할 수 없었지만 마치 옆에서 들려주는 듯한 인상을 보이기 위해 **코믹스** 형식으로 개인 추천화 시스템이 필요한 상황과 이유(불편사항)을 배민 캐릭터로 연출하여 풀어냈습니다. "너희 이렇게 가다간 ,, 금방 따라잡힌다?!" 라는 식으로 도발하면서요. 

#### 목차 

![슬라이드1](https://user-images.githubusercontent.com/67791317/199927061-280f9800-7076-4ef2-ba43-4dcc67aea2dd.JPG)

#### 서비스 분석 

**1. 문제점**

![슬라이드2](https://user-images.githubusercontent.com/67791317/199927172-ea1b9c73-3835-44bb-a7df-ba339382c52d.JPG)
![슬라이드3](https://user-images.githubusercontent.com/67791317/199927184-2dfa12cc-d1e8-4e6f-a6b4-ecc0ad6262b5.JPG)
![슬라이드4](https://user-images.githubusercontent.com/67791317/199927185-55276726-ff4b-4cd4-9993-066edb4014e8.JPG)

실제 소비자 역할에서 발견한 문제점에서 파생한 '밈(**배민맛**)을 활용하여 제언한다.  
배달음식에 대한 불만은 업계 모두가 짊어진 문제점이지만 '배달의 민족' 서비스가 대표 사례가 되는 문화를 꼬집으며 문제 시급성을 환기한다.  

**2. 문제 원인 분석**

![슬라이드6](https://user-images.githubusercontent.com/67791317/199927250-d54f8ead-3562-4d01-91ba-fa26776abfbf.JPG)

문제 원인 분석에 있어 정량적 지표가 필요하지만 일종의 문화 현상을 문제 근거로 삼았기 때문에 정확한 지표를 구할 수 없는게 한계점이라 생각한다. 

**3. 해결방안 제시** 

![슬라이드7](https://user-images.githubusercontent.com/67791317/199927321-f92576e8-f8cf-426f-aa11-b6f4b03bccb3.JPG)

- 사용자가 배달할 음식과 가게를 선정할 기준의 지표가 부족한 점. 
- 사용자의 기호(음식 취향)를 파악하여 좋아하는 음식을 제시하는 것이 아닌 음식과 가게의 양을 나열한점.  

위의 문제점을 해결하기 위해선 **양보다 질**, **새로운 가이드**를 만들어야한다 설득했습니다. 

#### 새로운 서비스 제시 

**1. 새로운 슬로건**

![슬라이드8](https://user-images.githubusercontent.com/67791317/199927376-b87ae133-cc75-4d80-9e75-094312d52f98.JPG)

기존 '좋은음식을 먹고싶은 곳에서'라는 슬로건이 아닌 '**좋아하는**은식을 먹고싶은 곳에서'라는 슬로건을 제시합니다. 

결국 앞으로 배민이 가야할 방향은 더이상 배달 플랫폼 선점 및 가게수 확보가 아닌 사용자가 좋아할만한 음식, 취향에 맞는 가게를 추천하여 더 만족스럽고 피로를 덜어주는 것입니다.   

미디어 산업에서는 이미 이러한 서비스를 아주 잘 실천하고 있습니다. 넷플릭스, 유튜브 처럼요!

**2. UI**

![슬라이드9](https://user-images.githubusercontent.com/67791317/199927418-f5e0454e-73ea-412c-8d37-adf275b55037.JPG)

개인 추천화 시스템은 총 4가지 종류의 추천탭을 활용할 예정이며 그에 맞는 UI를 구성했습니다. 

**3. 알고리즘**

<details>
<summary>알고리즘에 대한 설명 </summary>

![슬라이드10](https://user-images.githubusercontent.com/67791317/199927609-3dc5e680-63cc-4df3-a881-3ecb3dc3698d.JPG)
![슬라이드11](https://user-images.githubusercontent.com/67791317/199927611-1446733e-9149-4246-8b65-80291487b0b2.JPG)
![슬라이드12](https://user-images.githubusercontent.com/67791317/199927613-97c6b82a-2fdf-4a8a-9260-efe03a02493d.JPG)
![슬라이드13](https://user-images.githubusercontent.com/67791317/199927616-313810bb-00dd-48b0-a006-72ee471d4495.JPG)
![슬라이드14](https://user-images.githubusercontent.com/67791317/199927618-11bf98e7-0f0e-4b66-91ae-8ccf36be5370.JPG)

</div>
</details>

[알고리즘 page](https://github.com/heoni00/2021-Sub_Project-Baemin/tree/main/3.%20알고리즘)

#### 서비스 채택

**1. 기대효과** 

![슬라이드17](https://user-images.githubusercontent.com/67791317/199927733-0fb4ae54-56c1-4897-90be-61b2dd370a62.JPG)

BM 즉 비즈니스와 관련한 기획이라면 정성적 발전 이외에 정량적 기대효과를 제시해야하는데 이번 프로젝트에서는 그 부분이 매우 부족했음을 알아 아쉬운 부분이다. 당연스럽게 우리 서비스를 채택하면 사용자가 만족할 것! 이라고 제창하는 한계가 여실히 느껴진다. 

**2. 리스크헷지** 

![슬라이드18](https://user-images.githubusercontent.com/67791317/199927756-9f738ce9-d251-4e9d-917f-0ea5e35fe064.JPG)

개인적으로 만족했던 부분은 모든 서비스 기획안에는 예상리스크(리스크헷지)를 꼭 첨부하고 이를 인지할 수 있어야 하는 부분이다. 개인 추천화 시스템에 대한 논문 및 여러 한계점에 대해 서칭하여 위와 같은 예상 문제점을 첨부했다. 

#### 레퍼런스 

![슬라이드22](https://user-images.githubusercontent.com/67791317/199928162-28b523d4-85b8-478e-863c-ab53b0f03304.jpg)

### 마지막으로 ,,

🐥 배운점 🐥

- 몰입한 경험, 살면서 스스로 가치있는 일을 찾아 될 수 있을거란 확신을 갖고 모든 역량을 부어 작업한 정말 몇 안되는 값진 경험. 
- 협업의 방식, 동아리 운영 경험 및 주전공을 토대로 각기 다른 능력을 갖은 팀원과 의견을 개진하고 훌륭한 성과를 협업하여 만든 경험.
- 창의적인 사고, 트렌디한 기획안을 직접 제작하며 나의 생각을 표현하는 전략적이고 효과적인 수단을 얻었다. 
- 새로운 서비스 개발 경험, 공공서비스 개발이 아닌 비즈니스서비스 개발을 경험하여 한계점 및 고려할 점 등을 생각할 기회를 가졌다. 

💀 한계 💀 

- 정성적 문제점과 기대효과에만 치중하고 정량적 지표를 제시하지 못한점. 
- 창의적인 결과물에 비해 제안서 전달 방법은 너무 무모했다고 생각한다. 더 효과적으로 제안서를 전달하는 방법을 연구했어야한다. 
- 제안서 치곤 ,, 너무 길었다는 생각도 든다. 
