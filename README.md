# Git
* [Git](Git.md) : 코드 버전 관리 프로그램 
![gitgithub](https://user-images.githubusercontent.com/53849793/112778449-8ade4180-907f-11eb-9d75-9d6df5984de9.png)

# 왜? git
## git 사용하게 된 이유
* **트랜드** : 
 - 오픈소스
* **협업 관리 도구**
* **버전 관리 용이**





> 개발자들에게 필수라는 Git을 사용하는 이유가 뭘까
> <br>
이유를 알고 사용하는 것과 모르고 사용하는 것에는 분명한 차이가 있습니다.
<br>
개발을 하다 보면 어떤 기능을 빼고 더하고 등 수정하는 과정은 필수입니다.
<br>
하지만 이전의 기능을 다시 되돌리고 싶을 때도 있고 만들어둔 기능이 없던 전 버전으로
되돌리고 싶을 때도 분명 있을 겁니다.
<br>
기능의 추가와 같이 save는 필수라는 겁니다. 나중에 어떤 기능이 필요하고 또 필요 없을지 모르는 거니까요.
<br>

![스크린샷, 2021-01-17 09-47-45](https://user-images.githubusercontent.com/53849793/112794747-59c33880-90a2-11eb-8efa-340709221176.png)

## 저장소 위치
* **원격 저장소(Remote Repository)** : 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유
* **로컬 저장소(Local Repository)** : 내 PC에 파일이 저장되는 개인 전용 저장소
 
## Staging Area

![image](https://user-images.githubusercontent.com/53849793/112796455-f2f34e80-90a4-11eb-9a47-4b1417652189.png)

## 스냅샷

Git은 데이터를 파일 시스템 스냅샷의 연속으로 취급하고 크기가 아주 작다. Git은 프로젝트의 상태를 저장할 때마다 파일이 존재하는 그 순간을 중요하게 여긴다.

<img src="https://git-scm.com/book/en/v2/images/snapshots.png">

> 시간순으로 프로젝트의 스냅샷을 저장.

## Branch

개발을 하다 보면 코드를 여러 개로 복사해야 하는 일이 자주 생긴다. 코드를 통째로 복사하고 나서 원래 코드와는 상관없이 독립적으로 개발을 진행할 수 있는데, 이렇게 독립적으로 개발하는 것이 브랜치다
