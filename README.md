탭별 콘테츠 보이기

1. 기본 마크업 에서 시작
2. 크롬 확장프로그램 json formatter 설치


---------------------------------------


콘텐츠 api

최근
많이본
실시간인기

------------------------------------------------------

api 설명
총20개의 콘텐츠 묶음

 {
    "id": 문서ID,
    "title": 콘텐츠 제목,
    "img": 콘텐츠 대표 이미지,
    "cp": CP,
    "url": 콘텐츠주소
  },
  
 
 
 ------------------------------------------------------------------
 
  구현
  1. 1boon 채널 탭 ui 구현 (최근, 많이본, 실시간인기)
  2. 각탭을 누를때 마다 해당 api 를 사용하여 결과 표시
  3. 각 탭이 선택되면 선택된 탭 class(activ) 적용
  4. 가져온 데이터를 id=list 에 노출
  5. 로딩 이미지 효과 : 각 콘텐츠 노출시에 로딩이미지를 1초 노출후에 콘텐츠 노출
  6. api 에서 제목 , 링크 , 이미지, cp를 적절히 표시
  7. 처음 10개 보여주고 더보기 클릭이 남은 10개 보여주기 (로딩이미지효과 구현)
  8. js네이티브 함수 사용하여 구현
  
