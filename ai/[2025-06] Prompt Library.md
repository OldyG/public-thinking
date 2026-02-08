# 프롬프트 라이브러리 공유하기 꿈

vscode를 사용중
한 프로젝트에 지침문서들이 10개 20개 100개 쌓이는 것이 비효율적이라고 생각함

아애 별도 git 프로젝트를 생성하고

```
prompty-library/
  naonsoft/    // 회사명
    {projectName1}/
      code-rule-front-end/
      code-rule-back-end/
      db/
      infra/
      ...
  work-style/
    // 내 개인적인 프롬프트 저장공간
    // 반말 선호,
    // powershell 힌트 들
    // playwright사용하여 AI에게 눈 달아주기
```

이렇게 개인과 회사를 구분하여 디렉토리를 구성 후
프로젝트 별로 프롬프트를 관리하면 어떨까?

그리고, 팀원들과 이 git 프로젝트를 공유하면 어떨까?
