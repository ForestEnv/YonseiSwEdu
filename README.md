## 22학년도 여름방학 장기집중교육 팀 프로젝트

## 👭팀 이름

### 🌲Forest

- 환경을 생각하는 사람들이 속해 있으며, 이메일 삭제를 통해 환경에 긍정적인 영향을 미칠 수 있다고 믿는 팀원들…

## 📄이번 프로젝트…

### ✉️간단한 이메일 분류 구현

- 추후에 진행 예정인 프로젝트집중교육의 주제와 이번 장기집중교육의 수업 내용을 연관맺어 다양한 모델을 사용한 이메일 분류를 구현…

## 🧑🏻‍🤝‍🧑🏼팀원 소개

| 🌲이현탁 | 나이브 제이즈 분류 모델로 스팸 메일 분류 |
| --- | --- |
| 🌳이현지 | 1D CNN으로 스팸 메일 분류 |
| 🌴홍윤걸 | RNN으로 스팸 메일 분류 |
| 🍃윤희열 | 데이터셋 전처리, 문서 정리 |

## 🖥️구현 모델
<details>
<summary><h3>RNN</h3></summary>
<div>

> RNN은 은닉층의 노드에서 활성화 함수를 통해 나온 결과값을 출력층 방향으로도 보내면서, 다시 은닉층 노드의 다음 계산의 입력으로 보내는 특징

</div>
</details>

<details>
<summary><h3>나이브 베이즈</h3></summary>
<div>

> [나이브 베이즈 분류 모델](https://bkshin.tistory.com/entry/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-1%EB%82%98%EC%9D%B4%EB%B8%8C-%EB%B2%A0%EC%9D%B4%EC%A6%88-%EB%B6%84%EB%A5%98-Naive-Bayes-Classification)은 스팸 메일 필터, 텍스트 분류, 감정 분석, 추천 시스템 등에 광범위하게 활용되는 분규 기법이다.<br>
Feature -> 광고성 단어 개수, 비속어 개수, 성적 용어 개수 등... (각각이 하나의 Feature이며, 하나의 분류 모델에는 여러 개의 Feature가 있음, 서로 독립(independent))<br>
Label -> 스팸 메일인 경우 Label = 1, 스팸 메일이 아닌 경우 Label = 0

> 나이브 베이즈 분류는 베이즈 정리에 기반한 통계적 분류 기법.<br>
나이브 베이즈 분류기는 빠르고, 정확하며, 정확성도 높고 대용량 데이터에 대해 속도도 빠르다.

</div>
</details>
<details>
<summary><h3>1D CNN</h3></summary>
<div>

> 본래 CNN은 이미지 처리를 하기 위해 만들어진 아키텍처이다.<br>
이미지 처리 당시 CNN의 필터(ex.9칸)가 이미지의 지역적인 정보를 추출하는 역할을 한다면, 텍스트 CNN의 필터는 텍스트의 지역적인 정보, 즉 단어 등장순서/문맥 정보를 보존할 수 있다.

</div>
</details>
<details>
<summary><h3>결론</h3></summary>
<div></div>
</details>
<details>
<summary>참고</summary>
   <div>
   <ul>
    <li>[RNN](https://wikidocs.net/22894)</li>
    <li>[나이브 베이즈](https://wikidocs.net/22892)</li>
    <li>[CNN](https://ratsgo.github.io/natural%20language%20processing/2017/03/19/CNN/)</li>
   </div>
</details>
