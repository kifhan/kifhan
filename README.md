# Kihwan Lee / 이기환

[한국어](#한국어) | [English](#english)

- Email: [kifhan@gmail.com](mailto:kifhan@gmail.com)
- GitHub: [github.com/kifhan](https://github.com/kifhan)
- Portfolio site: [kifhan.github.io](https://kifhan.github.io)
- Korean PDF: [portfolio-ko.pdf](https://kifhan.github.io/portfolio-ko.pdf)
- English PDF: [portfolio-en.pdf](https://kifhan.github.io/portfolio-en.pdf)

---

## 한국어

### 현재 집중 분야

이기환은 온라인에서 @kifhan으로 활동하는 부산 기반 풀스택 개발자입니다. React, Node.js, Django, 클라우드 플랫폼을 활용해 반응형 웹 제품과 운영 시스템을 10년 이상 만들어 왔습니다. 웹 개발, 게임 개발, 인공지능, 로보틱스에 관심이 있고, 아이디어를 빠르게 구체적인 PoC로 전환하는 프로토타이핑에 강점이 있습니다.

현재는 백엔드 계약, 고객 웹, 운영자 CRM, 현장 POS, 클라우드 운영을 연결하는 제품 시스템에 집중하고 있습니다. 서로 다른 화면이 같은 주문, 예약, 결제, 권한, 사이트 단위 비즈니스 상태를 일관되게 공유하도록 만드는 일이 가장 강한 영역입니다.

### 제품 하이라이트

#### AmazingTicket

키즈파크/체험형 매장을 위한 멀티테넌트 예약 및 티켓 구매 솔루션입니다.

- 역할: Lead Developer (Fullstack)
- Backend/API: Django, Django REST Framework, PostgreSQL/PostGIS, Redis, Celery
- Frontend: React, TypeScript, Vite, TanStack Query, Zustand
- Operations: GCP, Cloud SQL, Cloud Storage, deployment scripts, targeted verification
- 제품 표면: 고객 예약 흐름, CRM 대시보드/매장 설정, 예약 상품/캘린더/목록, 마이페이지 구매/예약 상태
- Site: [amazingticket.site](https://www.amazingticket.site)

#### Amazing POS

현장 캐셔 판매, 테이블/주문 관리, 단말 결제 흐름, 디바이스 로컬 운영 설정을 다루는 standalone Expo POS 앱입니다.

- Expo, React Native, Expo Router, React Query
- 사이트 단위 세션 컨텍스트, 단말 식별, 로컬 디바이스 설정
- 현장 조작 속도를 우선하는 cashier-first interaction model
- 결제 대기 잠금과 복구 가능한 주문 상태 흐름

#### CRM Operations

예약 처리, 매출 통계, 결제 오류 지원, 사이트 권한, export, bulk action을 위한 운영자 워크플로우입니다.

- 반복 운영 업무를 위한 고밀도 UI
- 서버 페이지네이션, 필터, 상태 변경, CSV export
- 사이트 단위 permission gate와 action-level policy
- 대시보드와 통계 기준을 백엔드 계약과 정렬

### 전체 프로젝트 이력

#### Aling (2024)

소상공인을 위한 인플루언서 마케팅 및 매칭 솔루션입니다. Beta 단계에서 개발 중인 프로젝트입니다.

Role: Tech Lead & Frontend Developer

[View project](https://branding.aling.co.kr/)

Personal achievements:

- expo-router를 활용해 라우팅 구조를 효율화했습니다.
- 안전한 접근 제어를 위한 인증 제어를 구현했습니다.
- Supabase 기반 빠른 프로토타이핑으로 서버 개발자와의 커뮤니케이션 및 개발 속도를 높였습니다.

#### AmazingTicket (2023)

키즈파크를 위한 멀티테넌트 예약 및 티켓 구매 솔루션입니다.

Role: Lead Developer (Fullstack)

[View project](https://www.amazingticket.site)

Personal achievements:

- Django REST Framework queryset, serializer, Redis caching, indexing을 활용해 API 성능을 개선했습니다.
- AWS Auto Scaling Group, CloudFormation, RDS Aurora PostgreSQL 기반 load balancing을 구성했습니다.
- CloudFormation, Route53, CloudFront, S3 기반 React 웹 앱 배포를 자동화했습니다.
- Python script, SSH, AWS CLI 기반 백엔드 배포를 자동화했습니다.
- GeoDjango 기반 위치 쿼리로 정교한 위치 데이터를 다뤘습니다.
- React Native 기반 deep-linking과 app notification 같은 모바일 기능을 개발했습니다.

#### HappySaeaMap (2021)

사용자가 영상을 보면서 화면 속 장소를 지도에서 확인할 수 있는 웹 애플리케이션입니다.

Technologies: React, React-Router, React-strap, Chakra-UI, Google Maps, Firebase, YouTube API

[View project](https://happysaeamap.web.app/)

Personal achievements:

- 영상 재생과 지도 마커/컨트롤을 동기화했습니다.
- 영상과 지도 마커 간 데이터 관계를 안정적으로 구성했습니다.

#### Umtaijung.com Website for artist Um Taijung (2020)

React와 Chakra UI를 사용해 아티스트 소개, 갤러리, 문의 기능을 갖춘 반응형 웹사이트를 개발했습니다.

[View project](https://www.umtaijung.com)

#### Ummuseum.com Website for Ummuseum (2019 ~ 2021)

Gnuboard, jQuery, PHP, MySQL을 사용해 미술관 소개, 갤러리, 문의 기능을 갖춘 반응형 웹사이트를 개발했습니다.

[View project](http://www.ummuseum.com)

#### HappySaea : The game (2019)

Phaser 3로 만든 2D 게임 프로젝트입니다. 간단한 스토리, 맵, 환경 상호작용을 포함하며 unfinished project입니다.

[View project](https://kifhan.github.io/HappySaea/)

Personal achievements:

- Tile map, game state control, stage control을 구현했습니다.

#### GoWithRobo : Self-driving robot that cares your groceries (2019)

ROS, Python, Arduino, Raspberry Pi/Jetson Nano, SLAM, OpenCV, Deep Learning을 활용한 자율주행 장보기 보조 로봇 프로젝트입니다.

- Self-driving capabilities
- Map navigation
- Object detection and tracking
- Voice command system
- Video chat

Originally designed to assist visually impaired individuals.

[View video](https://youtu.be/MZVMW8I5pdE)

Personal achievements:

- Multi-threaded Python programming을 활용했습니다.
- ROS 1, SLAM, robot hardware, self-driving technology에 대한 경험을 쌓았습니다.

#### MultiHack : Real-Time Editor and Voice Chat. (2018)

HTML, JavaScript, Node.js, Express, Socket.io, WebRTC, LevelDB로 만든 실시간 협업 에디터와 음성/영상 채팅 프로젝트입니다.

[View project](https://github.com/multihack/multihack-web)

Personal achievements:

- CRDT, peer-to-peer network, collaborative interface concurrency에 대한 이해를 쌓았습니다.

#### KihwanNet : a visual interface for building neural networks (2018)

HTML과 JavaScript로 만든 시각적 신경망 구성 인터페이스입니다.

[View project](https://github.com/rellat/kihwannet)

Personal achievements:

- Multi-perceptron 이론을 학습하고 JavaScript로 구현했습니다.
- HTML Canvas 기반 GUI를 만들었습니다.

### 기술 스택

- HTML5, CSS3, JavaScript, TypeScript
- React
  - React-Router, React-strap, Styled-Components, Tailwind-css, Formik, Yup, React-Three-Fiber, Three.js, Axios, zustand, react-query, Recoil
- Next.js
- Node.js
  - Webpack, Babel, Express, NestJS, Mongoose, Sequelize, Prisma, RESTful API, JWT, OAuth, Socket.io, WebRTC, Nginx, AWS EC2, MongoDB, MySQL, PostgreSQL, Redis
- Python
  - Django, Django REST Framework, Django Channels, FastAPI, Flask
  - NumPy, pandas, matplotlib, scikit-learn, TensorFlow, Keras, PyTorch
- Vue
  - Vuex, Vue-Router
- Svelte
  - SvelteKit, Svelte-UI
- Firebase, Strapi
- React Native
  - Expo, React Navigation, react-native-paper, react-native-svg
- AWS S3, EC2, ELB, Auto Scaling Group, Route 53, etc.
- Google Cloud Compute, Cloud SQL, Storage, DNS, etc.
- Docker

### 연락처

- 이메일: [kifhan@gmail.com](mailto:kifhan@gmail.com)
- GitHub: [github.com/kifhan](https://github.com/kifhan)
- Portfolio site: [kifhan.github.io](https://kifhan.github.io)

---

## English

### Current Focus

I'm Kihwan Lee, also known online as @kifhan, a Busan-based full-stack developer with over 10 years of experience building responsive, user-friendly web products with modern technologies like React, Node.js, Django, and cloud platforms. My interests span web development, game development, artificial intelligence, and robotics, and I work best when rapid prototyping can turn an idea into a concrete proof of concept quickly.

Today I focus on product systems that connect backend contracts, customer-facing web, operator CRM, field POS, and cloud operations. My strongest work is connecting product surfaces that share the same order, reservation, payment, permission, and site-scoped business state.

### Product Highlights

#### AmazingTicket

Multi-tenant reservation and ticketing product for customer booking, CRM operations, payment handling, and on-site workflows.

- Role: Lead Developer (Fullstack)
- Backend/API: Django, Django REST Framework, PostgreSQL/PostGIS, Redis, Celery
- Frontend: React, TypeScript, Vite, TanStack Query, Zustand
- Operations: GCP, Cloud SQL, Cloud Storage, deployment scripts, targeted verification
- Product surfaces: customer reservation flow, CRM dashboard/settings, reservation product/calendar/list, my-page purchase and reservation status
- Site: [amazingticket.site](https://www.amazingticket.site)

#### Amazing POS

Standalone Expo POS app for cashier sales, table/order management, terminal payment flows, and device-local operational settings.

- Expo, React Native, Expo Router, React Query
- Site-scoped session context, terminal identity, local device settings
- Cashier-first interaction model for fast field operations
- Payment pending locks and recovery-oriented order state

#### CRM Operations

Operator workflows for reservation handling, sales statistics, payment-error support, site permissions, exports, and bulk actions.

- Dense operational UI for repeated admin work
- Server pagination, filters, status mutations, CSV exports
- Site-scoped permission gates and action-level policy checks
- Dashboard and statistics alignment with backend contracts

### Full Portfolio Archive

#### Aling (2024)

Influencer marketing & matching solution for small businesses. Beta (Currently in development)

Role: Tech Lead & Frontend Developer

[View project](https://branding.aling.co.kr/)

Personal achievements:

- Utilized expo-router for efficient routing.
- Implemented advanced authentication controls for secure access.
- Achieved rapid prototyping through Supabase. It helped communicate with server developer and accelerates the development process.

#### AmazingTicket (2023)

Multi-tenant Reservation and Ticket Purchase Solution for Kids Park.

Role: Lead Developer (Fullstack)

[View project](https://www.amazingticket.site)

Personal achievements:

- Optimized API performance using Django REST framework querysets, serializers, and database caching with Redis and indexing.
- Implemented load balancing with AWS Auto Scaling Group, CloudFormation, and RDS Aurora PostgreSQL.
- Automated React web app publishing with CloudFormation, Route53, CloudFront, and S3.
- Automated backend deployment with Python script, SSH, and AWS CLI.
- Leveraged location-based queries with GeoDjango for precise location data.
- Developed engaging mobile features like deep-linking and app notifications using React Native.

#### HappySaeaMap (2021)

Web application allowing users to watch videos and locate on-screen locations.

Technologies: React, React-Router, React-strap, Chakra-UI, Google Maps, Firebase, YouTube API

[View project](https://happysaeamap.web.app/)

Personal achievements:

- Implemented synchronized video playback with map marker and control.
- Established a robust data relationship between video and map markers.

#### Umtaijung.com Website for artist Um Taijung (2020)

For this project, I developed a responsive website using React and Chakra UI. The website features a gallery, artist info, and contact form.

[View project](https://www.umtaijung.com)

#### Ummuseum.com Website for Ummuseum (2019 ~ 2021)

In this project, I developed a responsive website using Gnuboard, jQuery, PHP, and MySQL. The website features a gallery, museum info, and contact form.

[View project](http://www.ummuseum.com)

#### HappySaea : The game (2019)

This is a 2D game that I developed using Phaser 3. The game features a simple story, a map, and interaction with the environment. Unfinished project.

[View project](https://kifhan.github.io/HappySaea/)

Personal achievements:

- Implemented tile map, game state control, and stage control.

#### GoWithRobo : Self-driving robot that cares your groceries (2019)

Project leveraging ROS, Python, Arduino, Raspberry Pi/Jetson Nano, SLAM, OpenCV, Deep Learning:

- Self-driving capabilities
- Map navigation
- Object detection and tracking
- Voice command system
- Video chat

Originally designed to assist visually impaired individuals.

[View video](https://youtu.be/MZVMW8I5pdE)

Personal achievements:

- Utilized multi-threaded Python programming.
- Acquired knowledge of ROS 1, SLAM, robot hardware, and self-driving technology.

#### MultiHack : Real-Time Editor and Voice Chat. (2018)

Realtime collaboration for programmers. This is a project that I developed using HTML, JavaScript, Node.js, Express, Socket.io, WebRTC, and LevelDB. The project features a real-time editor with collaboration, and a video chat.

[View project](https://github.com/multihack/multihack-web)

Personal achievements:

- Gained insights into CRDT, peer-to-peer (P2P) networks, and concurrency in collaborative interfaces.

#### KihwanNet : a visual interface for building neural networks (2018)

Creating a Neural Network with a visual interface. This is a project that I developed using HTML and JavaScript. The project features a visual interface for building neural networks.

[View project](https://github.com/rellat/kihwannet)

Personal achievements:

- Studied multi-perceptron theory and implemented it in JavaScript.
- Created an intuitive GUI using HTML Canvas.

### Skills

- HTML5, CSS3, JavaScript, TypeScript
- React
  - React-Router, React-strap, Styled-Components, Tailwind-css, Formik, Yup, React-Three-Fiber, Three.js, Axios, zustand, react-query, Recoil
- Next.js
- Node.js
  - Webpack, Babel, Express, NestJS, Mongoose, Sequelize, Prisma, RESTful API, JWT, OAuth, Socket.io, WebRTC, Nginx, AWS EC2, MongoDB, MySQL, PostgreSQL, Redis
- Python
  - Django, Django REST Framework, Django Channels, FastAPI, Flask
  - NumPy, pandas, matplotlib, scikit-learn, TensorFlow, Keras, PyTorch
- Vue
  - Vuex, Vue-Router
- Svelte
  - SvelteKit, Svelte-UI
- Firebase, Strapi
- React Native
  - Expo, React Navigation, react-native-paper, react-native-svg
- AWS S3, EC2, ELB, Auto Scaling Group, Route 53, etc.
- Google Cloud Compute, Cloud SQL, Storage, DNS, etc.
- Docker

### Contact Me

- Email: [kifhan@gmail.com](mailto:kifhan@gmail.com)
- GitHub: [github.com/kifhan](https://github.com/kifhan)
- Portfolio site: [kifhan.github.io](https://kifhan.github.io)
