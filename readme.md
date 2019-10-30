<h1 align="center">
AWS Lambda + Github Action
</h1>

> 위 두가지 스택을 이용하여 간단한 이미지 업로드 / 리사이징 프로토타입 서버를 만드는 것을 목표로 합니다.

## 사용 기술 스택
- [Node.js](https://nodejs.org/)
- [AWS](https://aws.amazon.com/ko/)
    - Lambda & Api Gateway
    - Cognito
    - S3
    - DynamoDB
- [Serverless](https://serverless.com/?gclid=Cj0KCQjwzozsBRCNARIsAEM9kBPZJI685tdxiuakzBZnCztcthuOP6C8mtFB_6jalFNkdUbrZf0Y14YaAtvGEALw_wcB)
- [Github Action](https://github.com/features/actions)

## 공부 목록 :bulb:

0. AWS 계정을 생성합니다.
1. AWS Lambda, Cognito, DynamoDB, S3에 대한 개념 이해 & 이용해보기
   - [서버리스 스택](https://serverless-stack.com) 사이트의 예제를 따라해보며 학습합니다.
2. Github Action과 S3를 이용하여 간단히 프론트 엔드 서버를 배포해봅니다.
3. Github Action에서 자주 이용하는 기능을 공식 도큐먼트에서 공부 / 번역하여 공유합니다.
4. 그동안 배운 기능을 활용하여 간단한 이미지 리사이징 서버를 구축합니다.

## 이미지 리사이징 서버 구축 참고 사이트

- [Lambda 한개로 만드는 On-demand Image Resizing](https://engineering.huiseoul.com/lambda-%ED%95%9C%EA%B0%9C%EB%A1%9C-%EB%A7%8C%EB%93%9C%EB%8A%94-on-demand-image-resizing-d48167cc1c31)
- [당근마켓 AWS Lambda를 이용한 이미지 썸네일 생성 개발 후기](https://medium.com/daangn/aws-lambda%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%8D%B8%EB%84%A4%EC%9D%BC-%EC%83%9D%EC%84%B1-%EA%B0%9C%EB%B0%9C-%ED%9B%84%EA%B8%B0-acc278d49980)
- [하루만에 서버리스 온디맨드 이미지 리사이징 서비스 구축하기](https://todait.github.io/image-resizing-service)
- [VCNC 서버 비용을 70%나 줄인 온디맨드 리사이징 이야기](http://engineering.vcnc.co.kr/2016/05/ondemand-image-resizing/)
