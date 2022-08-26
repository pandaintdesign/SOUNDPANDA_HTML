# 필독!
이곳은 "원격저장소"로 **White의 컴퓨터 폴더(로컬저장소)** 와 연동 되어있습니다! 로컬저장소 폴더 삭제엄금!   

```
 1. 새로운 제품군을 생성할 때에는 "basic폴더"를 Copy하여 생성합니다.
 2. 영상의 경우 아래 영상 픽셀값 표를 체크하여 이미지의 가로폭과 근사치의 px 값을 입력하여 적용합니다.
```

## 업로드 방법

**폴더명 : ##SOUNDPAND_**

**[유실을 대비한 공용폴더 백업과 코드 백업방법 영상]**
[SOUNDPANDA_code](https://drive.google.com/drive/folders/1YXS5nTr0FRrZiL20rfLOcKGP6cGa8Dwo?usp=sharing, "SOUNDPANDA_code")


**[깃허브 명령어 정리]**   

깃허브 내 명령어는 무궁무진하지만 업로드와 다운로드에 관련된 명령어만 추가하겠습니다.
자세한 항목은 깃 공식 영어전문과 한국어로 정리되어 있는 게시물 링크 첨부합니다.

```
# 현재 directory(로컬저장소)의 모든 파일을 Staging Area(원격저장소)로 이동
git add .

# file들의 tracking 상태 보기 -> 업로드가 되었는지, 누락된게 있는지
git status

# Staging 의 파일들 commit 하기 -> 수정내역 추적할 때 이 메시지로 구분
git commit -m "messsage"

# 저장소에 commit 반영하기 -> 로컬저장소에서 원격저장소로 업로드
git push

# 저장소에서 commit 가지고 오기 -> 원격저장소에서 로컬저장소로 다운로드
git pull

```

- [깃허브 명령어](https://wecandev.tistory.com/152, "깃허브 명령어")
- [git origin(원문)](https://git-scm.com/docs, "git origin")

## 영상 픽셀값 (근사치, px단위)

|가로값|세로값|
|:--:|:--:|
|640|360|
|720|405|
|752|423|
|768|432|
|784|441|
|800|450|
|832|468|
|864|486|
|880|495|
|928|522|
|944|531|
|960|540|
|1008|567|
|1040|585|
|1440|810|



이 필독서는 "마크다운 언어"로 만들어졌습니다.
수정 시에는 마크다운 "언어 문법"을 참고해주세요.
