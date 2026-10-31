모바일 청첩장 템플릿 사용법 (초보자용)

1) 압축을 풀면 index.html 파일이 있습니다.
2) index.html을 메모장으로 열어 내용을 수정하세요.
   - 이름, 날짜, 시간, 예식장 주소
   - 부모님 성함, 계좌번호
   - 예식장 지도 링크(네이버 지도 공유 URL로 교체)
3) 사진은 index.html과 같은 폴더에 아래 이름으로 저장하세요.
   - 대표 사진: wedding.jpg
   - 갤러리 사진: gallery1.jpg, gallery2.jpg, gallery3.jpg, gallery4.jpg
   사진이 없으면 해당 사진 영역은 자동으로 숨겨집니다.
4) GitHub에 올릴 때 index.html과 사진 파일을 함께 업로드하세요.
   계좌번호 등 개인정보가 포함된 사이트는 공개되므로, 공개해도 괜찮은 정보만 넣으세요.

GitHub Pages 공개하기
A. github.com에 로그인 → 오른쪽 위 + → New repository
B. Repository name에 예: wedding-invitation 입력
C. Public 선택 → Create repository
D. Add file → Upload files → index.html과 사진 파일을 끌어다 놓기 → Commit changes
E. 저장소 Settings → Pages
F. Build and deployment의 Source를 Deploy from a branch로 선택
G. Branch는 main, 폴더는 /(root) 선택 → Save
H. 잠시 기다린 뒤 Pages 화면에 표시되는 사이트 주소를 열어 확인하세요.
   보통 주소 형식은 https://사용자이름.github.io/wedding-invitation/ 입니다.

참고: GitHub Pages는 정적 파일을 웹사이트로 공개하는 기능입니다.
공개 저장소의 파일과 웹사이트는 인터넷에 공개될 수 있으니 개인정보는 신중히 입력하세요.
공식 가이드: https://docs.github.com/en/pages/quickstart
