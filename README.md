# Mission

version: c9 default

![이미지](https://s3-ap-northeast-2.amazonaws.com/dgulion/blog/IQXGEDBALFSTWPNKVHCR.png)

지금까지 만들었던 scaffold 게시판을 업그레이드 해보겠습니다.

1. 일단 유저`User`를 추가해보겠습니다. `User` 모델 추가
2. `Post`에 user_id 추가 (references, migration)
3. 댓글`Comment` 기능을 만들어보겠습니다.  `Comment`모델 추가
4. 댓글은 작성자와 원글이 필요합니다. (references)
5. 글에 좋아요 기능을 추가해보겠습니다. `Like` 모델 추가
6. 좋아요 기능은 좋아요한 사용자와 원글이 필요합니다.
7. 사용자들의 그룹이 필요합니다. `Group` 모델 추가
8. 한 사용자는 그룹을 여러 개 소속될 수 있고 그룹 안에는 여러 사용자가 포함될 수 있습니다. (m:n)

이러한 구조의 model을 만들어 봅시다.

이번 수업 시간에 배운 예제가 3개 추가되었습니다.
1. references
2. migration
3. m:n<br>

이를 사용해서 만들어주세요!