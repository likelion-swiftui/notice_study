# 10월 11일 실습

날씨 정보 뷰 만들기
- 책: ~105p 기초다지기
- 참고 링크: https://tttap.tistory.com/122 <br><br>
<a href='https://ifh.cc/v-JyQFWV' target='_blank'><img src='https://ifh.cc/g/JyQFWV.png' border='0'></a>
<br><br><br>

## 날씨 아이콘은 어떻게 구현하나요? <br>
아래와 같이 이미 구현돼있는 SF Symbol을 사용하면 된다.
```
 Image(systemName: "sun.max.fill")
 ```
systemName에 들어갈 수 있는 값은 매우매우 많기 때문에 전부 외울 수 없다. 그렇다면 아래와 같은 값을 어떻게 찾을 수 있을까?
```
 "sun.max.fill"
 ```
 <a href='https://ifh.cc/v-1VyHJF' target='_blank'><img src='https://ifh.cc/g/1VyHJF.jpg' border='0'></a>
 <a href='https://ifh.cc/v-rlfyHt' target='_blank'><img src='https://ifh.cc/g/rlfyHt.png' border='0'></a>
 <br><br><br>

 빨간 박스로 표시해놓은 버튼을 따라 이동해보자. 원하는 아이콘을 더블클릭하면 값을 자동 완성해준다. 
 <a href='https://ifh.cc/v-GXj2th' target='_blank'><img src='https://ifh.cc/g/GXj2th.png' border='0'></a>
 
 
 <a href='https://ifh.cc/v-8Dp2A9' target='_blank'><img src='https://ifh.cc/g/8Dp2A9.png' border='0'></a> 
이런 식으로 아이콘에 색을 여러 개를 입혀야 할 때 아래와 같은 코드를 적용하면 된다.
```
.renderingMode(.original)
```
