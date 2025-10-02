<h1 align="center">안녕하세요, 개발자 이미령입니다! 👋</h1>
<div align="center">아직 초심자입니다!</div>
<hr>

<div>
<h3>🔗 About Me</h3>
<table>
<tr><td>
<div>💡 매우 책임감 있고 실천 정신이 강하며, 직접 실행해 얻는 진정한 지식을 신봉합니다.</div>
<div>💡 항상 기본 원리를 이해해야만 적용할 수 있는 사람이라, 학습 과정에서도 항상 탄탄하게 배우려고 노력해왔습니다.</div>
<div>💡 팀워크를 중요하게 생각하며, 1+1>2라는 믿음을 가지고 있습니다.</div>
<div>💡 단순히 배우고 새로운 것에 접하는 것을 좋아하며, 마음이 열려 있고 발전적인 관점으로 문제를 바라봅니다.</div>
</td></tr>
</table>
</div>

<div>
<h3>📚 Tech Stack</h3>
<div>🍀 Frontend: HTML, CSS, Vue3</div>
<div>🍀 Backend: JAVA</div>
<div>🍀 Database: Oracle</div>
</div>

<h3>🔧 Projects</h3>

> **프론트엔드: 안전성과 편리성을 지향하며 주변 상품으로 확장된 신형 차(茶) 음료점 사용자 정보 관리 시스템** (ongoing)
> <br>
> Vue3 + HTML + Oracle

<h4>✅ 이미 구현한 기능:</h4>
<ul>
<li>기본 로그인 및 회원가입</li>
<li>구매 기록 및 가맹 등록 기능</li>
</ul>

<h4>🚧 추가 구현 예정 기능:</h4>
<ul>
<li>기본 가상 결제</li>
<li>매장 전환</li>
<li>비밀번호 변경</li>
<li>장바구니에 여러 상품 동시에 주문</li>
<li>알레르기나 기피 음식 등 원클릭 차단</li>
</ul>


<h4>📖 프로젝트 배경</h4>
<hr>
사람들이 음료점을 찾거나 음료를 주문하는 이유는 단순히 “마시기” 위해서라기보다는, 종종 특별히 할 일이 없기 때문입니다. 그러나 현재 시중의 많은 음료점들은 매우 단조롭고, 일부는 오히려 병 음료보다 새로움이 부족합니다.
또한 제품 인터랙션 디자인에는 성심이 부족합니다. 다양한 토핑과 재료안내는 제공하지만, 특정 식재료 알레르기가 있거나 당뇨 환자처럼 섭취 제한이 필요한 사람들에 대한 고려는 거의 없습니다.
대부분의 브랜드는 자신들을 일반 식품점처럼만 운영하고 있으며, 음료점이 제공할 수 있는 정신적 만족을 간과하고 있습니다.
이러한 문제의식을 바탕으로 이번 프로젝트를 간단히 설계해 보았습니다.
(물론 위에서 언급한 모든 부분이 실제로 하나도 이뤄지지는 못했지만.)

<h4>✅ 이미 구현한 기능:</h4>
<hr>

 기본 로그인 및 회원가입
 ---
 
>로그인 
<img width="940" height="867" alt="image" src="https://github.com/user-attachments/assets/d286b6ae-812d-4f5f-bf6d-6ff189ace152" />

 
로그인하면 직접 홈페이지로 돌아오고 위쪽에 자동적으로 프로파일 항목이 떠있음.
<img width="940" height="458" alt="image" src="https://github.com/user-attachments/assets/ffeb20c4-ddce-4e64-889a-2e30127f1f64" />

>회원가입
<br>
회원가입은 중복체크 기능이 있고 비밀번호를 설정할 때 다시 설정할 필요 없이 한눈에 보이도록 설계했음.
<img width="981" height="1371" alt="image" src="https://github.com/user-attachments/assets/048db2fd-05c2-4630-bdab-2d9833ef9c3f" />


프로파일
---
프로파일의 내용은 신분에 따라 다릅니다.

>일반 사용자
<br>
일반 사용자와 판매자에게는 가맹 신청과 내소식으로 구성되었습니다.

<img width="1104" height="922" alt="image" src="https://github.com/user-attachments/assets/a14d57c4-3258-464a-aeb2-d1a1e78ecd14" />


>관리자
<br>
관리자에게는 관리 위주로 설계하였습니다.

<img width="940" height="861" alt="image" src="https://github.com/user-attachments/assets/0f63c5e4-1944-4ee1-8bf9-c1c96837a084" />

>개인 정보 수정
<br>
수정 가능한 정보는 자유롭게 수정할 수 있습니다.
<img width="940" height="864" alt="image" src="https://github.com/user-attachments/assets/4692a222-2f5b-41db-a51d-0df89c254f58" />

 
가맹 등록 기능 
---
로그인 상태에서 만이 가맹 신청을 할 수 있는데 제출하면 관리자가 통과여부를 결정합니다.
<img width="940" height="443" alt="image" src="https://github.com/user-attachments/assets/379d515c-e5eb-40b9-8968-f55729bb55e7" />

 
신청자는 프로파일에서 신청 통과 여부를 확인할 수 있습니다.
<img width="1351" height="376" alt="image" src="https://github.com/user-attachments/assets/d4497ce4-06ce-4a37-8159-186287f91b44" />



구매 기록 
---

>주문
<br>
옵션 선택 화면:

<img width="940" height="787" alt="image" src="https://github.com/user-attachments/assets/1361ca90-624b-4370-ae8e-b45c72422d36" />

 
옵션 선택 시 가격 자동 계산

<img width="940" height="569" alt="image" src="https://github.com/user-attachments/assets/1d83fb6f-76c5-44bc-8d08-aa773d4a076f" />


>내역
<br>
주문완료 후 바로 내역 체크 가능:  
<img width="810" height="462" alt="image" src="https://github.com/user-attachments/assets/dbb56132-1112-4a7e-9484-ff1ef5d7ef79" />

주문한 후 내역에서 같은 내역에 따라 다시 주문 가능:
<img width="1614" height="910" alt="image" src="https://github.com/user-attachments/assets/6d8155f7-caaa-44a6-a0c3-a9459b95ae14" />

옵션을 저장하면 주문 내역에서 바로 가서 결제 가능:
<img width="904" height="463" alt="image" src="https://github.com/user-attachments/assets/3d6e2042-141b-4ebf-8d9f-7a410088c4d7" />


<table>
<tr><td>
<h4>🚧 추가 구현 예정 기능:</h4>
<ul>
<li>기본 가상 결제</li>
<li>매장 전환</li>
<li>비밀번호 변경</li>
<li>장바구니에 여러 상품 동시에 주문</li>
<li>알레르기나 기피 음식 등 원클릭 차단</li>
<li>(필요)반품 기능을 설정(seller의 진도에 따라)</li>
<li>회원 적립</li>
 <li>블라인드 박스 형식의 음료 배송</li>
</ul>

<h4>문제점들</h4>
<ul>
<li>옵션 저장이 불필요한 기능임(“쇼핑 카트”와 “좋아요”로 대체 )</li>
<li>프로파일의 설계가 합리적이 못함</li>
</ul>
</td></tr>
</table>
</div>


<h3>📫 Contact</h3>
<div>📧 Email: 3228302551@qq.com</div>
