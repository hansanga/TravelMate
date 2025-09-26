# ✈️ 장소가 아닌 일정에서 시작하는 여행 공유 플랫폼, TravelMate

<img width="1215" height="810" alt="Group 167" src="https://github.com/user-attachments/assets/1b2d2b1c-6268-41a6-b0c5-88e68085c84a" />

- 배포 URL : [TravelMate](https://clinquant-kangaroo-7d97f3.netlify.app/)
<br/>

## 프로젝트 소개

‘TravelMate’는 여행자의 일정(여행 기간)에 따라 맞춤형 정보를 제공하는 일정 중심 여행 공유 플랫폼입니다.
기존 여행 커뮤니티가 장소를 먼저 정해야 정보를 탐색할 수 있었다면, TravelMate는 “며칠 갈 수 있는지”에서 시작하는 새로운 여행 접근 방식을 제공합니다.

- 여행자는 1박 2일부터 한 달 살기까지 여행 기간별 채널에서 일정을 탐색하고 공유할 수 있습니다.
- 예산, 장소, 테마 필터를 통해 내 일정에 꼭 맞는 여행 계획을 쉽게 찾고, 다른 여행자들과 소통할 수 있습니다.
- 장소 기반이 아닌 ‘기간 기반 여행 탐색’이라는 차별화된 접근을 통해, 여행자들이 일정에 꼭 맞는 여행을 손쉽게 찾고 공유할 수 있도록 돕는 것을 목표로 합니다.

## 개발 기간
- 2025 4/25 ~ 5/19

## 개발환경
#### Languages
<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">

#### Frameworks/Libraries
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">

#### Data Fetching & State
<div class="flex flex-wrap items-center gap-2">
   <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
   <img src="https://img.shields.io/badge/zustand-4D2B1A?style=for-the-badge&logo=zustand&logoColor=white">

#### Styling
<img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">

#### Version Control & Collaboration
<div class="flex flex-wrap items-center gap-2">
   <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
   <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
   <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">


#### Design
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">

<br/><br/>

## 팀원 구성
| 남윤서 | 김태연A | 이예빈 | 한상아 | 심유진 |
|:------:|:------:|:------:|:------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/158164219?v=4" alt="남윤서" width="150"> | <img src="https://avatars.githubusercontent.com/u/89635061?v=4" alt="김태연A" width="150"> | <img src="https://avatars.githubusercontent.com/u/105144795?v=4" alt="이예빈" width="150"> | <img src="https://avatars.githubusercontent.com/u/89959007?v=4" alt="한상아" width="150"> | <img src="https://avatars.githubusercontent.com/u/204798087?v=4" alt="심유진" width="150"> |
| FE | FE | FE | FE | FE |
| [@ysnam0123](https://github.com/ysnam0123) | [@TYss00](https://github.com/TYss00) | [@llyybbb](https://github.com/llyybbb) | [@hansanga](https://github.com/hansanga) | [@youjin430](https://github.com/youjin430) |
<br/>

## 팀원 역할

<img width="1440" height="1024" alt="Frame 647" src="https://github.com/user-attachments/assets/9853f608-650d-4b25-a270-462b97568ad0" />

<br/>

## 디렉토리 구조
```
🗂️ 디렉토리 구조
📦public                  
📦src
 ┣ 📂api
 ┣ 📂assets
 ┃ ┣ 📂achievementIcons
 ┃ ┣ 📂icons
 ┃ ┗ 📂images
 ┣ 📂cloudinary
 ┣ 📂components
 ┃ ┣ 📂channel
 ┃ ┣ 📂routers
 ┃ ┣ 📜Input.tsx
 ┃ ┣ 📜Loading.tsx
 ┃ ┣ 📜NoticePanel.tsx
 ┃ ┣ 📜PaswordInput.tsx
 ┃ ┣ 📜PostModal.tsx
 ┃ ┣ 📜SearchPanel.tsx
 ┃ ┣ 📜Tag.tsx
 ┃ ┣ 📜WriteInfo.tsx
 ┃ ┣ 📜WriteInfoMenu.tsx
 ┃ ┗ 📜button.tsx
 ┣ 📂css
 ┣ 📂hook
 ┣ 📂layout
 ┣ 📂pages
 ┃ ┣ 📜Home.tsx
 ┃ ┣ 📜Login.tsx
 ┃ ┣ 📜MyProfile.tsx
 ┃ ┣ 📜NotFound.tsx
 ┃ ┣ 📜ProfileEdit.tsx
 ┃ ┣ 📜Register.tsx
 ┃ ┣ 📜SuperAdmin.tsx
 ┃ ┣ 📜UserList.tsx
 ┃ ┣ 📜UserProfile.tsx
 ┃ ┗ 📜Write.tsx
 ┣ 📂stores
 ┣ 📂types
 ┣ 📜App.tsx
 ┣ 📜main.tsx
 ┗ 📜vite-env.d.ts
```

## 주요기능

### [온보딩]
- 페이지를 새로고침할 때마다 다채로운 배경 화면을 제공합니다.
  
| 온보딩                                                                                 |
| ----------------------------------------------------------------------------------------- |
| ![1-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/eb2d5506-78ca-4f42-9f15-d54ce6993912)|

<br/>

### [비로그인]
- 온보딩 화면에서 여행 이야기를 눌러 홈화면에 접근할 수 있습니다.
- 비로그인 시에도 채널필터와 검색기능을 사용할 수 있습니다.
- 비로그인 상태에서 사용자 프로필에 접근 가능하며, 팔로우를 누르면 로그인 화면으로 돌아갑니다.

| 채널 필터                                                                              |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/196fc89c-dbc2-4898-b053-69fe845ec6cc) |


| 게시글 검색 & 사용자 검색                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (2)](https://github.com/user-attachments/assets/e3677cf3-59ba-49b9-9d07-43490e24b197) |

---

### [회원가입 페이지]

- 닉네임, 이메일, 비밀번호, 비밀번호 확인을 입력받습니다.
- 이메일, 비밀번호 확인은 조건에 충족해야 옆에 아이콘이 활성화됩니다.
- 아이디 중복 또는 다른 빈칸이 존재할 경우 toast로 에러안내 문구를 띄워줍니다.

| 회원가입                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (15)](https://github.com/user-attachments/assets/6b3d78aa-c56b-422d-ba76-534f0ad1a2d1) |

<br/>

### [로그인 페이지]

- 이메일, 비밀번호를 입력하며, 비밀번호는 눈 아이콘을 누르면 비밀번호 확인이 가능합니다.
- 로그인이 완료되면 홈화면으로 이동됩니다.
  
| 로그인                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-optimize](https://github.com/user-attachments/assets/834b8b8a-7031-4c3c-91aa-73287762c43c) |

---

### [메인 페이지]

**게시글**

- 장소, 비용에 따른 게시글 필터링이 가능합니다.
- 현재 채널의 필터링 된 게시글만 확인할 수 있습니다.
- 다크모드 버튼을 눌러 다크모드를 활성화할 수 있습니다.

| 장소 필터링                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed](https://github.com/user-attachments/assets/a0877a33-e514-4ffe-9880-8b7b4c200058) |

| 비용 필터링                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed (1)](https://github.com/user-attachments/assets/97de102e-b9e2-44cf-9ec5-09581f71982e) |

| 다크모드                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed (2)](https://github.com/user-attachments/assets/dd3061ce-7811-4b49-976c-c1cf152130ee) |

<br/>

**댓글 및 좋아요**

- 좋아요와 댓글은 실시간으로 반영됩니다.
- 댓글 달기/좋아요 클릭 시 게시글 작성자에게 알림이 전송됩니다.

| 댓글 & 좋아요                                                                               |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed (3)](https://github.com/user-attachments/assets/dfe11c6a-509f-4aaa-aa4a-320bf7be597a) |

<br/>

**사용자 온라인유무 확인**

- 사용자의 온라인 유무를 아이콘색으로 확인 가능합니다.
- 사용자가 페이지에 접속하여 로그인하면 온라인상태가 되며, 사용자목록 최상단으로 올라옵니다.

| 사용자 온라인유무                                                                             |
| ----------------------------------------------------------------------------------------- |
| ![사용자 온라인](https://github.com/user-attachments/assets/03356705-bcae-4eee-be91-54ce54a8f4b8) |

<br/>

**알림**

- 사용자의 게시글에 좋아요를 누르면 알림이 전송되며, '모두 읽음' 버튼 클릭 시 모든 알림이 읽음처리 됩니다.

| 알림                                                                             |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed (4)](https://github.com/user-attachments/assets/5d630ce5-3467-46a0-89cf-3cfd2038a2cb) |

<br/>

---

### [게시글 작성 페이지]

- '여행 나누기' 버튼을 통해 게시글을 작성할 수 있습니다.
- 제목, 태그, 장소, 비용, 내용을 적어야 등록이 가능합니다.
- 비용에는 숫자만 작성 가능합니다.
- 태그 및 장소는 여러개 작성 가능하며 삭제도 가능합니다.
- 이미지는 여러장 첨부 가능합니다.

| 게시글 작성                                                                            |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (12)](https://github.com/user-attachments/assets/5e3a9977-0aff-4a89-9cda-9691f71d43b6) |

---

### [마이페이지]

**프로필 수정**

- 프로필 사진 및 닉네임, 비밀번호, 칭호, 소개를 수정할 수 있습니다.
- 비밀번호 변경 시 새로운 비밀번호와 비밀번호 확인이 일치해야 변경됩니다.

| 프로필 수정                                                                            |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (16)](https://github.com/user-attachments/assets/5e9a86eb-0546-4899-a642-9c82624a2fd8) |

<br/>

**게시글 수정**

- 내 게시글 피드에서 게시글을 클릭해 게시글 수정 버튼을 누르면 게시물 수정이 가능합니다.
- 기존에 작성된 제목, 내용, 첨부한 이미지를 확인할 수 있고, 수정 후 저장 버튼을 누르면 수정이 완료됩니다.

| 게시글 수정                                                                            |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-speed (5)](https://github.com/user-attachments/assets/eb9d43f7-061d-4503-8453-6668c0902884) |

<br/>

**게시글 삭제**

- 내 게시글 피드에서 게시글을 클릭해 게시글 삭제 버튼을 누르면 게시물 삭제가 가능합니다.

| 게시글 삭제                                                                           |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (17)](https://github.com/user-attachments/assets/3a3c0a26-24c1-4695-bc88-12e430f6f35d) |

---

### [관리자 페이지]

**채널 생성**

- 관리자는 채널 생성이 가능하며, 생성 후 바로 유저페이지에서 확인 가능합니다.

| 채널 생성                                                                           |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (18)](https://github.com/user-attachments/assets/a6e142ec-f11e-4bef-8bad-839e964ab155) |

<br/>

**채널 삭제**

- 관리자는 채널을 삭제할 수 있으며, 삭제 후 바로 유저페이지에서 확인 가능합니다.

| 채널 삭제                                                                           |
| ----------------------------------------------------------------------------------------- |
| ![ezgif com-video-to-gif-converter (19)](https://github.com/user-attachments/assets/99eaf78c-8c6f-48b4-ba1c-7ecb83ff9b0b) |

---

### [404 페이지]

- 존재하지 않는 주소로 이동 시 404페이지가 뜨며 홈버튼을 눌러 다시 메인페이지로 돌아갈 수 있습니다.

| 404 페이지                                                                          |
| ----------------------------------------------------------------------------------------- |
| ![404-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/fdfd4907-f63e-4647-8a06-71b3eb698cc6) |


---

## 트러블슈팅

**이미지 복수 장 업로드 문제**<br/>
제공된 API의 image 필드에는 한 장의 파일만을 허용하고 있어 서비스 취지에 꼭 필요한 이미지 복수 장의 업로드가 불가능한 상황이었으나, cloudinary 서비스로 정적 url을 생성하여 title 필드에 string으로 넣는 방법으로 해결.
<br/>

**팔로우/언팔로우 구현 문제**<br/>
유저의 팔로잉/언팔로잉을 구현할 때 팔로우 상태임에도 다시 팔로우되고, 팔로잉이 되어있어도 언팔로우에서 실패하는 현상이 발생함. 문제의 원인은 단순히 userId로 비교했다는 점이었고,
로그인 유저의 following 목록의 id값과 상대 유저의 followers 목록의 id값을 교차 비교해서 
공통의 id값이 있는지 확인해 공통의 id값을 추가/삭제하는 방식으로 수정해 해결.


