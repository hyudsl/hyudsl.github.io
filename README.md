# DSLAB (Hanyang University)

### https://dsl.hanyang.ac.kr/

## 세미나 포스트 추가 방법

1. 파일 생성 \
_posts 폴더에 파일을 생성합니다. \
파일명의 날짜는 세미나 날짜입니다. \
파일명 형식: YYYY-MM-DD-title.md

2. 파일에 다음을 추가합니다. (--- 빼먹으면 안 돼요.)
```
---
layout: seminar-post
title: 'UniIR: Training and Benchmarking Universal Multimodal'
subtitle: ''
categories:
    - "Computer Vision"
tags: [Multimodal, VLM]
date: 2023-12-02
pdf_url: 'https://drive.google.com/file/d/1T3F_624bpfymQQxLJ_dqO4TNSjJTjEME/preview'
---
```

수정이 필요한 항목들

* title: 홈페이지에 표시할 제목

* categroies: 논문의 카테고리 (NLP, LLM, Computer Vision, Multi-Modal AI 중 하나) \
  꼭 따옴표로 묶어주세요.

* tags: 논문에 관련된 주제들, 최대 2개까지

* date: 세미나 날짜, 파일명에 쓰인 날짜와 동일하게

* __pdf_url__ \
구글 드라이브에서 pdf 파일의 공유 링크를 복사하여 붙여넣습니다. (공유 권한을 '링크가 있는 모든 사용자' 로 바꾸고 해주세요.) \
그 뒤 꼭 경로 마지막을 preview로 바꿔줍니다. (홈페이지에 제대로 표시가 안 될 수 있습니다.) \
ex. \
https://drive.google.com/file/d/1T3F_624bpfymQQxLJ_dqO4TNSjJTjEME/view?usp=drive_link \
→ https://drive.google.com/file/d/1T3F_624bpfymQQxLJ_dqO4TNSjJTjEME/preview

포스트에 넣고 싶은 내용이 있는 경우, 위 내용 아래에 추가하면 홈페이지에서 pdf 뷰어 아래에 추가됩니다.


## People 추가 방법
추가할 사람들의 학위 과정에 맞게 _data 폴더에서 아래 파일 중 하나를 수정합니다.
* people_phd.yml
* people_master.yml
* people_undergraduate.yml
* people_aumni.yml 

사진은 images/people에 추가합니다.

## Publication 추가 방법
_data/publications.yml에 추가합니다. \
International, domestic과 연도 구분 잘 확인하고 추가해주세요. \
논문 링크가 없는 경우에는 생략해도 괜찮습니다. \
__연구실 인원들 이름에는 '\<strong\>' 태그 달아주세요!__

## 페이지 별 대표 파일
* home → _layout/home.html
    * Title 및 sub title → _data/defaults.yml
    * 상단 왼쪽 로고 → _config.yaml 내 title
    * research interests → _data/research_interests.yml
* people → peoples.html
* seminar → _layout/seminar.html
    * seminar 별 포스트 → _layout/seminar-post.html
* publications → _layout/publications.html
