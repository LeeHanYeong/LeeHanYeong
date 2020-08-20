## 소개

### 이한영  

Django를 좋아하는 웹 개발자입니다.

✉️ dev@lhy.kr  
💾 [github.com/leehanyeong](https://github.com/leehanyeong)  
🏠 [lhy.kr](https://lhy.kr/)



## 경력

- [티페이](https://www.tpay.co.kr/) (2019.01 ~ 재직중)
  - DRF를 사용한 백엔드 개발
  - Vue.js를 사용한 프론트엔드 개발
- 패스트캠퍼스 (2016.09 ~ 2018.12)
  - Django기반의 웹 개발 교육 강사
- [타운컴퍼니](https://townus.co.kr/) (2015.09 ~ 2016.09)
  - DRF를 사용한 백엔드 및 Django 관리자 페이지 개발
  - AngularJS 1.x를 사용한 프론트엔드 개발
- [텐핑거스](https://10fingers.datepop.co.kr/) (2014.10 ~ 2015.01)
  - DRF를 사용한 백엔드 개발
  - Google App Engine을 사용한 배포
  - AngularJS 1.x를 사용한 관리자 페이지 개발



## 프로젝트

### [django-quill-editor](https://github.com/LeeHanYeong/django-quill-editor)

> 오픈소스 프로젝트 (2020.05 ~ )

JS기반의 오픈소스 WYSIWYG에디터인 [Quill.js](https://quilljs.com/)를 Django에서 쉽게 쓸 수 있게 도와주는 라이브러리입니다. 

django-ckeditor, django-summernote와 같은 기존의 WYSIWYG에디터는 이미지를 첨부할 때, 정해진 경로로 먼저 이미지를 업로드 한 후 에디터에 붙여넣어야 하는 불편한 과정이 있습니다.

### [django-secrets-manager](https://github.com/LeeHanYeong/django-secrets-manager)

> 오픈소스 프로젝트 (2019.09 ~ )

AWS의 [SecretsManager](https://aws.amazon.com/ko/secrets-manager/)서비스를 사용해서 Django의 각종 비밀값들을 쉽게 가져올 수 있도록 도와주는 라이브러리입니다.

### tBoard

> 티페이 (2019.01 ~ )

티페이의 사내 ERP인 tBoard의 백엔드 및 프론트엔드 개발과 배포를 맡았습니다. 기존 레거시 코드의 문제점을 해결하고, 문서화와 배포 자동화 등 개발 문화 개선 작업을 진행했습니다.

#### 레거시 개선

- Python2.x, Django1.x의 버전업 (Python 3.x, Django 2.x)
- JsonResponse로 직접 처리되던 API들을 DRF방식으로 변환
- pre-commit을 사용한 커밋 전 Code Lint, 컨벤션 적용
- Raw SQL로 처리되던 로직의 ORM화 및 Slow query개선

#### 개발

- Django와 DRF 확장기능들을 사용, 생산성 향상
  - django-mptt  
    재귀적으로 사용되는 모델의 트리 구조화
  - drf-yasg  
    DRF 구조를 기반으로 한 문서 자동화
  - 



## 경력 외 활동

- 소프트웨어 마에스트로 4기 멘티 (2013.07 ~ 2014.06)

